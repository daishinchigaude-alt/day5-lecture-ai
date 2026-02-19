# 講義音声ノートAI (Lecture Note AI)

音声ファイルをアップロードするだけで、AI（Gemini API）が文字起こし、要約、要点の抽出を自動で行うWebアプリです。

## 🚀 使い方
1. [https://daishinchigaude-alt.github.io/day5-lecture-ai/] にアクセスします。
2. Google AI Studioで取得した **Gemini APIキー** を入力します。
3. 録音した音声ファイル（.m4a, .mp3, .wavなど）を選択します。
4. 「AI解析を実行する」ボタンを押し、結果が表示されるまで待ちます（約30秒〜1分）。

## ✨ 主な機能
- **文字起こし**: 音声内容を詳細に全文テキスト化します。
- **3行要約**: 忙しい時でも内容がすぐわかる要約を生成します。
- **重要ポイント**: 講義や会議の要点を箇条書きで抽出します。
- **コピー機能**: 解析結果をワンクリックでクリップボードにコピーできます。

## 🛠️ 技術スタック
- **Frontend**: HTML5 / JavaScript (Vanilla JS)
- **Design**: Tailwind CSS (CDN経由)
- **AI Engine**: Gemini 1.5 Flash API
- **Deployment**: GitHub Pages

## 💡 開発の記録
今回の開発では、APIのバージョン管理（v1/v1beta）やモデル名の指定による404エラーの解決、およびブラウザでのMIMEタイプ（.m4a）の適切な処理に注力しました。

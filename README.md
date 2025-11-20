# Gen AI Class Submit 2025

## リポジトリの作成

このテンプレートリポジトリから自分のアカウントにリポジトリを作成します。

1. このリポジトリのGitHubページを開く
2. 右上の「Use this template」ボタンをクリック
3. 「Create a new repository」を選択
4. リポジトリの設定を入力：
   - **Repository name**: 任意の名前（例: `gen_ai_class_submit_2025`）
   - **Description**: リポジトリの説明（任意）
   - **Public** を選択
5. 「Create repository」ボタンをクリック
6. 作成されたリポジトリをローカルにクローン：
   ```bash
   git clone https://github.com/あなたのユーザー名/リポジトリ名.git
   cd リポジトリ名
   ```

## セットアップ

### 環境変数の設定

このプロジェクトでは、Gemini APIを使用するために環境変数 `GEMINI_API_KEY` の設定が必要です。

#### Linux/Mac の場合

ターミナルで以下のコマンドを実行してください：

```bash
export GEMINI_API_KEY="your_api_key_here"
```

恒久的に設定する場合は、`~/.bashrc` または `~/.zshrc` に追加してください：

```bash
echo 'export GEMINI_API_KEY="your_api_key_here"' >> ~/.bashrc
source ~/.bashrc
```

## APIキーの取得方法

Gemini APIキーは [Google AI Studio](https://aistudio.google.com/app/api-keys) から取得できます。

#### 新しいライブラリを追加する場合

1. `requirements.txt` に追加するライブラリ名を記述
   ```bash
   echo "ライブラリ名" >> requirements.txt
   ```

2. requirements.txtからインストール
   ```bash
   pip install -r requirements.txt
   ```

## 参考リンク

- [Gemini API ドキュメント](https://ai.google.dev/gemini-api/docs) - Gemini APIの公式ドキュメント
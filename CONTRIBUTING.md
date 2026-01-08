# 貢献ガイドライン (Contributing Guidelines)

GoogleAntigravityプロジェクトへようこそ！
ここでは、このレポジトリへの参加方法やファイルを更新する手順（プルリクエストの送り方）について解説します。

## 🔰 参加の基本ルール

1. **誰でも歓迎**: アイデアひとつ、誤字修正ひとつからでも大歓迎です。
2. **安全第一**: `main` ブランチへの直接書き込みはできません。必ず新しいブランチを作って作業し、プルリクエストを送ってください。
3. **日本語OK**: コミットメッセージやプルリクエストの説明は日本語で構いません。

## 📝 参加ステップ (Pull Requestの流れ)

Git/GitHubに慣れていない方は、以下の手順を参考にしてください。

### Step 1: 準備 (Clone & Branch)

まず、レポジトリを手元のパソコンにコピー（クローン）し、作業用の新しいブランチを作成します。

```bash
# レポジトリをクローン（最初の1回だけ）
git clone git@github.com:School-Agent-Inc/gd_antigravity.git
cd gd_antigravity

# 最新の状態にする
git checkout main
git pull origin main

# 作業用ブランチを作成（名前はわかりやすく。例: feature/add-new-idea）
git checkout -b feature/your-branch-name
```

### Step 2: 作業 (Edit & Commit)

自由にファイルを作成・編集してください。
完了したら、変更を保存（コミット）します。

```bash
# 変更したファイルを追加
git add .

# 変更内容を保存（メッセージは具体的に）
git commit -m "アイデアのメモを追加"
```

### Step 3: 提出 (Push & Pull Request)

変更をGitHub上の自分のブランチに送信（プッシュ）し、マージ依頼（プルリクエスト）を出します。

```bash
# GitHubへ送信
git push origin feature/your-branch-name
```

GitHubのレポジトリページを開くと、「Commits pushed...」という表示が出ているので、**「Compare & pull request」** ボタンを押します。
内容を確認して、**「Create pull request」** をクリックすれば完了です！

## 📂 どこに何を入れる？

- 具体的なプロジェクトのファイル → `projects/`
- ふと思いついたアイデア → `ideas/`
- 共有したい資料 → `resources/`

迷ったら `ideas/` に入れておけばOKです！

---
困ったことがあれば、GeminiDiveのチャットで気軽に質問してください。
Let's build something great together!

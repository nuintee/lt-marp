---
marp: true
theme: uncover
class: invert
paginate: true
---
# 社内LTをやり過ごす方法 (Marp) 👻
@nuintee

---

# こんな悩みはありませんか？
1. 💭 LTに参加したいけど**アイデアが浮かばない**

2. ⏰ LTのスライドを準備する**時間が無い**

---

# 🤔 それ...Marpで解決できます

---

# Marpとは?
### Markdownから**プレゼンテーションスライドを生成**してくれるツール

---

# Marpの特徴
1. 🐆 **すぐに使える**  
- Markdownが書ければ、そのままスライドが作れます
2. 👨‍🎨 **スタイル調整不要**  
  - 「uncover」「gaia」など、おしゃれなテーマが標準装備
---

# 😹 難しい事は不要！
速く、綺麗に、簡単に

---

# 🏃‍♂️ Marpの始め方

---

### 🏃‍♂️ Marpの始め方 #1
## ✍️ [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)を導入
VSCode・Cursor以外の人はすみません

---

### 🏃‍♂️ Marpの始め方 #2
## マークダウンファイルを作成
`index.md` や `slide.md`など

---

### 🏃‍♂️ Marpの始め方 #3
## Marpを有効化

![w:700](./images/marp-true.png)

<small>💡マークダウンの先頭に `marp: true`を追加</small>

---

### 🏃‍♂️ Marpの始め方 #4
## マークダウンファイルを書く

詳しい記述は[こちら](https://qiita.com/tomo_makes/items/aafae4021986553ae1d8)が参考になります

---

#### 🏃‍♂️ Marpの始め方 #5
### プレビューを確認
![bg right w:400](./images/preview.png)

<small>💡 コマンドパレット検索: `Markdown: Open Preview`</small>

---

### 🏃‍♂️ Marpの始め方 #6
## pptxとしてエクスポート
![w:700](./images/export-slide.png)

<small>💡 コマンドパレット検索: `Marp: Export Slide Deck`</small>

---

# 以上！

---

# 👨‍💻 ちょっと技術的な話

---

### 🌐 オンラインで公開するなら
# Github Pages + actions
git管理との相性・情報の多さ

---

### 🛠️ 使用したaction
1. **MarpをHTML出力:**
  - [KoharaKazuya/marp-cli-action@v4](https://github.com/KoharaKazuya/marp-cli-action)

2. **生成したHTMLのアップロード**
  - [actions/upload-pages-artifact@v3](https://github.com/actions/upload-pages-artifact)

3. **Github Pagesへのデプロイ**
  - [actions/deploy-pages@v4](https://github.com/actions/deploy-pages)
---

# 🌀 公開で少しハマったところ
1. [permission](https://zenn.dev/not75743/scraps/926f2693809744)の設定が分からない
2. [Workflowの権限不足](https://docs.github.com/ja/actions/security-for-github-actions/security-guides/automatic-token-authentication#using-the-github_token-in-a-workflow)
3. デプロイ後に絵文字が表示されない

---

# 👍 調べたらすぐ情報出た
ちなみに絵文字は action のバージョンが原因

---

### ⏰ 少し詰まったけど...
## Marp x actionsは便利

---

# 本題へ

---

### 冒頭の質問
# こんな悩みはありませんか？
1. 💭 LTに参加したいけど**アイデアが浮かばない**

2. ⏰ LTのスライドを準備する**時間が無い**

---


## ⚡️ 社内LTをやり過ごすテクニック 

---

### ⚡️ 社内LTをやり過ごすテクニック #1
# スライド作り自体の話をする
これでアイデアは考えなくてOK 

---

### ⚡️ 社内LTをやり過ごすテクニック #2
# 小洒落たテーマを使用する
スタイル調整の時間削減

---

### ⚡️ 社内LTをやり過ごすテクニック #3
# 絵文字をふんだんに使用する
やった感を出しましょう

---

### ⚡️ 社内LTをやり過ごすテクニック #4
# 時間稼ぎ
発表時にたくさん寄り道しましょう

---

### 🚨 LTをやり過ごす際の注意点
# メタなので1回しか使えない

---

# 終わりに
~ なんとかなっていますかね？ ~

---

<!-- 終了スライド -->
# ご清聴ありがとうございました 👋

~ 📚 本スライドの[リポジトリ](https://github.com/nuintee/lt-marp)も公開中です〜
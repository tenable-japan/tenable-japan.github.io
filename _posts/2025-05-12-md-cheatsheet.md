---
layout: post
title:  "Markdown cheetcheet"
date:   2025-05-12 17:00 +0900
categories: jekyll update cheetsheet
---

# 📘 Markdown Cheat Sheet for Jekyll & GitHub Pages

> このチートシートは、GitHub Pages 上の Jekyll サイトで使える Markdown 構文の一覧です。

---

## 📌 見出し（Headings）

```markdown
# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6
```

---

## 📌 テキスト装飾（Text Formatting）

```markdown
**太字**
*斜体*
~~取り消し線~~

`インラインコード`
```

---

## 📌 リスト（Lists）

### 順序なしリスト
```markdown
- アイテム1
- アイテム2
  - ネストされたアイテム
```

### 番号付きリスト
```markdown
1. 手順1
2. 手順2
   1. サブ手順
```

---

## 📌 リンク（Links）

```markdown
[GitHub](https://github.com)
```

---

## 📌 画像（Images）

```markdown
![代替テキスト](https://via.placeholder.com/150)
```

---

## 📌 引用（Blockquotes）

```markdown
> これは引用です。
>> ネストした引用
```

---

## 📌 コードブロック（Code Blocks）

<details>
<summary>クリックして表示</summary>

### JavaScript の例：

<pre><code>```js
function greet() {
  console.log("Hello, world!");
}
```</code></pre>

### シェルの例：

<pre><code>```bash
$ echo "Hello"
```</code></pre>

</details>

---

## 📌 テーブル（Tables）

```markdown
| 名前   | 年齢 | 所属       |
|--------|------|------------|
| 田中   | 29   | セキュリティ部 |
| 鈴木   | 34   | 開発部     |
```

---

## 📌 チェックリスト（To-do Lists）

```markdown
- [x] タスク1 完了
- [ ] タスク2 未完了
```

---

## 📌 HTMLタグ（Jekyllでも使える）

```html
<details>
<summary>クリックして展開</summary>
<p>ここに詳細が表示されます。</p>
</details>
```

---

## 📌 YAML フロントマター（Jekyll用）

```yaml
---
title: "Markdown チートシート"
layout: default
---
```

---

> 🔚 おわり！このチートシートを `README.md` や任意のページに貼り付けて使えます。

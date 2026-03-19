# 立体パズル GitHub / Jimdo 用

## ファイル
- index.html
- style.css
- app.js
- assets/（6面画像）

## GitHub Pages に出す方法
1. このフォルダの中身をそのまま GitHub のリポジトリに入れる
2. リポジトリ名は自由
3. Settings → Pages → Branch を `main` / `/root` にする
4. 数分待つ
5. 公開URLが出る

## Jimdo に載せる方法
Jimdo では iframe 埋め込みが安定です。

```html
<iframe
  src="ここにGitHub PagesのURL"
  width="100%"
  height="900"
  style="border:0;"
  loading="lazy"
  allowfullscreen>
</iframe>
```

## メモ
- 画像は assets フォルダに分かれています
- 立体レビュー付き版です

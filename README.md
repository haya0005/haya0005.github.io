# haya0005.github.io

八木 颯斗（Hayato Yagi）の個人ページ（仮内容）。

## ローカル確認

ブラウザで `index.html` を開くか、簡易サーバを起動します。

```bash
python3 -m http.server 8000
```

`http://localhost:8000` で確認できます。

## 公開（GitHub Pages）

1. 変更を `main` に push
2. GitHub リポジトリ → **Settings** → **Pages**
3. Source を **Deploy from a branch**、Branch を `main` / `/ (root)` に設定
4. 数分後に https://haya0005.github.io/ で公開

## 差し替えポイント

| 項目 | ファイル |
|------|----------|
| プロフィール文・経歴・受賞・論文・連絡先 | `index.html` |
| 顔写真 | `assets/profile.jpg` などを追加し、`index.html` の `img` の `src` を変更 |
| 見た目 | `styles.css` |

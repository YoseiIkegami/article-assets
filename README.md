# article-assets

Qiita / note など記事用の画像を置く公開リポジトリです。

docs-ikegami は private のため、Qiita から raw URL で画像を読めません。
記事に載せる画像はここに置き、絶対 URL で参照します。

## URL 形式

```
https://raw.githubusercontent.com/YoseiIkegami/article-assets/main/<記事スラッグ>/<ファイル名>
```

## 使い方

1. 記事ごとのフォルダを切る（例: `jev-tagging/`）
2. 画像を置く
3. 記事 Markdown では上記の raw URL を使う
4. 差し替え後にキャッシュが残る場合は `?v=2` を付ける

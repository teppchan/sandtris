# sandtris
練習でcodexに作らせてるゲーム

## Play

https://teppchan.github.io/sandtris/

## Prototype

ブラウザで `index.html` を開くとプレイできます。ビルド不要の1ファイルHTMLプロトタイプです。
Supabaseの `scores` テーブルを使って共有ランキングを表示・投稿します。

### Controls

- Enter / Space / クリック: 開始
- ← / →: 移動
- ↑: 回転
- ↓: 加速
- Space: 即落下
- P: 一時停止

## Development

`node_modules/` はリポジトリに含めません。必要な場合は `npm install` で復元します。

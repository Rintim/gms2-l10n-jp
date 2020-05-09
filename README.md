# (unofficial) Japanese l10n of GameMaker Studio 2 IDE

GameMaker Studio 2 本体の日本語化ファイルです。作業中。  
GMS2 インストール場所の `Languages` フォルダーへ `japanese.csv` をコピーしてください。

なお、デフォルトの状態ではフォントが大きすぎて正しく表示されない箇所が多いです。

IDE のフォントを変更するには、GMS2 インストール場所の `./defaults/default_macros.json` を編集します。  
編集するのは `default_font`、`default_style`、`default_font_size` の3つです。

実際の作業で使用しているのは次の設定です。

```json
    "default_font" : "MS Gothic",
    "default_style" : "Regular",
    "default_font_size" : "8"
```

これで、ほとんどの箇所は正しく表示されるようになります。一部はまだハミ出てしまいますが。  
また、めちゃくちゃ小さいので見にくいかもしれません。MS ゴシックで漢字がそこそこキレイに表示される最小サイズです。  
環境設定 -> 全般 から DPI を上げることで多少解決できそうですが、動作は保証しません。

マニュアルの翻訳を [こちら](https://trackiss.github.io/gms2manual-jp-public/) で行っております。  
今は作業中のプライベート リポジトリからデータを移行している最中で、しかも最近は IDE の翻訳に注力しているので更新は遅めです。

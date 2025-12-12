# co_tesou00

手相鑑定サイトのサンプル (index.html と style1〜4.html) を収録しています。

## 画像について

レビューツールで「バイナリ ファイルはサポートされません」と表示される問題に対応するため、/assets/kansei.jpg をデータURI化し、`assets/image-data.js` に埋め込んで参照しています。各ページの `<img>` タグには `data-kansei-img` 属性を付けており、スクリプト読み込み後に画像が差し込まれます。

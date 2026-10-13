# article-images

Qiita などの記事で使う画像置き場。

## フォルダ
資格ごとに分ける（ワークスペースの `記事/` と同じ名前）。

- `common/` … 資格をまたいで使う画像
- `iot-basic/` `iot-intermediate/` `mobile2/` `mobile-basic/` `smartphone-mobile/` `agile1/`

ファイル名は、ワークスペースの `記事/<フォルダ>/img/` と同じ（日本語のまま。例: `見出し_予想問題.jpg`）。

## 画像の URL
```
https://raw.githubusercontent.com/mochikoici/article-images/main/<フォルダ>/<ファイル名>
```
日本語の部分はパーセントエンコードする。

## 決まり
- 一度記事で使った画像は、名前を変えたり消したりしない（公開済みの記事の画像が出なくなる）。差し替えるときは別の名前で足す。
- すべて公開される。公開前の記事の画像は、記事を公開するときに置く。
- 他社の著作物（公式テキストの表紙など）は置かない。

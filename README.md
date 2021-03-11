# article_19113_kushimoto_rocket_visible_area

日本発の衛星データプラットフォーム Tellus のオウンドメディア「宙畑」の記事、https://sorabatake.jp/19113 で利用しているコードです。

以下を指定して発射場から打ち上げられたロケットが見えるエリアを判定します。

- ロケット発射場の緯度経度
- ロケット打ち上げ時の高さ
- 見通しエリアの半径
- 見通しエリアの同心円の数
- 見通し計算の精度

## 構成
- los-check.ipynb
  - 見通しを判定するコード。
- example.pbf
  - 対象の範囲を指定するサンプルデータ。OpenStreetMapから取得。


## ライセンス、利用規約
ソースコードのライセンスは CC0-1.0（Creative Commons Zero v1.0 Universal）ライセンスです。  
今回コード内で ASTER GDEM2 データを用いております。利用ポリシーは以下をご参考下さい。
https://www.tellusxdp.com/market/tool_detail/tellus-default/60

## 貢献方法
プルリクエストや Issue はいつでも歓迎します。

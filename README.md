# vector-style-performance
スタイルのパフォーマンスを調べる実験

## 結果メモ
### Point vs LineString (test2)
* 同じ地物を10000レイヤ分描画すると、Point（`type` : `circle`）のほうが、LineString（`type` : `line`）より描画完了が早い。


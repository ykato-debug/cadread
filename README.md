# cadread — 図面ビューア（JWW・DXF・DWG）

iPhone向けのCAD図面ビューア。`index.html` 1ファイルで動作します（外部通信なし）。

https://ykato-debug.github.io/cadread/

- 対応形式：JWW / JWC、DXF、DWG（〜2018形式）、SXF（SFC・P21）
- 拡大縮小・移動（ピンチ／ダブルタップ）
- 寸法計測：距離・連続距離・面積（端点・中点・線上に吸着、JWWはレイヤグループ縮尺で実寸換算）
- レイヤの表示／非表示
- PDF出力（ベクター／画像、A4〜A1、カラー／白黒）

TFS（Tfas）・BCD（FILDER CEED）は仕様非公開のため非対応。元CADでDWG/DXF/JWWに書き出してから開いてください。

図面の読み込みに [zumen](https://github.com/zumenjs/zumen)（MIT License）を使用しています。

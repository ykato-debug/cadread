# cadread — 図面ビューア（JWW・DXF・DWG）

iPhone向けのCAD図面ビューア。`index.html` 1ファイルで動作します（外部通信なし）。

https://ykato-debug.github.io/cadread/

- 対応形式：JWW / JWC、DXF、DWG（〜2018形式）、SXF（SFC・P21）
- 拡大縮小・移動（ピンチ／ダブルタップ）
- 寸法計測：距離・連続距離・面積（端点・中点・線上に吸着、JWWはレイヤグループ縮尺で実寸換算）
- 計測結果は画面に残り、一覧から個別削除・全削除・コピーが可能
- 距離計測は寸法線として表示し、ラベルをドラッグすると引出線付きで寸法線を引き出せる
- 縮尺の手動補正：縮尺（1/N）を入力するか、長さの分かる2点を指定して実寸を入力
- レイヤの表示／非表示
- PDF出力（ベクター／画像、A4〜A1、カラー／白黒）。ベクターPDFの文字は輪郭線で出力するため、どのビューア・プリンタでも消えない

TFS（Tfas）・BCD（FILDER CEED）は仕様非公開のため非対応。元CADでDWG/DXF/JWWに書き出してから開いてください。

図面の読み込みに [zumen](https://github.com/zumenjs/zumen)（MIT License）、PDFの文字出力に [opentype.js](https://github.com/opentypejs/opentype.js)（MIT License）と Noto Sans CJK JP のサブセット（SIL Open Font License 1.1）を使用しています。

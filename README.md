# kifuwarabe-gtm-uec12

第12回UEC杯コンピュータ囲碁大会 きふわらべ 思考部（＾～＾）

Computer go.  

Base: [https://github.com/bleu48/GoGo](https://github.com/bleu48/GoGo)  

## Documents

[Goのインストール](https://github.com/muzudho/hello-golang/blob/main/doc/installation/install.md)  

* Set up
  * [on Windows](./doc/set-up-app-on-windows.md)
* Run
  * [on Windows](./doc/run-app-on-windows.md)

## Dependent

* [gtp-engine-to-nngs](https://github.com/muzudho/gtp-engine-to-nngs)

## 感想

* adminmatch を使う場合でも、手番の色はちゃんと指定する必要がある
* 400手の時点で　勝敗表示が欲しい。パスパスのとき使う（なければ審判判断）
  * あれば自分から見た勝敗
  * あれば勝率
  * あればコミを入れた目数差
  * 残り時間を 何分何秒で表示して欲しい。
* 対局が終わるごとに、ログファイルを 退避してバックアップさせたい
* adminmatch であっても、選手側で B, W をちゃんと指定する必要がある。
  * だから 1対局ごとにログアウトして、 B, W を指定する必要がある。サーバー側で指定するだけではだめ。

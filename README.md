# PiNode
## 概要
- [概要とシステム構成](https://www.minelab.jp/public_data/pinode.pdf)

Raspberry Pi Zero WとP920センサノードを基にしたカメラ付き無線センサノードであるPiNodeの製作手順とPiNodeを最大4台収容する無線LANルーターであるPiNode-WRTの製作手順を記載する.
Raspberry Piは耐熱性に優れており,施設園芸環境下で安定したデータ収集を実現できる.

なお,Raspberry Pi自体は汎用的な装置であるため,接続するセンサを変更することでCO2といった他のデータも容易に収集できる.
無線LANルーターであるPiNode-WRTは必要に応じて別の無線LANルーターやアクセスポイントに変更しても良い.

## PiNode
- [PiNode-ハードウェア組立手順書](https://www.minelab.jp/public_data/pinode-hardware.pdf)
    - [PiNode-ケースファイル](https://www.minelab.jp/public_data/pinode-case.zip)
    - [PiNode-基板ガーバファイル](https://www.minelab.jp/public_data/pinode-pcb_1.1.zip)
    - ※電源として5Vでセンタープラスの[ACアダプタ](http://akizukidenshi.com/catalog/g/gM-07770/)が必要．
- [PiNode-ソフトウェア設定手順書](https://www.minelab.jp/public_data/pinode-software.pdf)
    - [OSイメージ(Raspbian Stretch Lite)](https://www.minelab.jp/public_data/2018-11-13-raspbian-stretch-lite.img)
    - [PiNodeソフトウェア](https://www.minelab.jp/public_data/pinode-v1.0.2.tar.gz)

### 部品表
|品名|数量|備考|
|:--|---:|:---|
|Raspberry Pi Zero WH|1||
|カメラモジュール|1|NoIRのものは不可|
|P920センサノード|1|[パスコン株式会社](http://www.passcon.co.jp/)製|
|microSD|1|SanDisk Extreme PRO推奨|
|ピンヘッダ(2.54mm 40ピン)|1|1台制作するのに26ピン必要|
|2.1mm標準DCジャック⇔スクリュー端子台 |1||
|12W級ACアダプター5V2A　LTE10UW-S1-BS01|1||
|片面ガラスコンポジット・ユニバーサル基板　Ｃタイプ|1|1枚で5台分|
|ケーブル用コネクタ|28||
|コネクタ用ハウジング 7P|1||
|コネクタ用ハウジング 6P|1||
|コネクタ用ハウジング 5P|2||
|コネクタ用ハウジング 4P|1||
|コネクタ用ハウジング 1P|1||
|ターミナルブロック 2P 小 青|1||
|ラズパイ用スタッキングコネクタ|1|1個で3台分|
|基板|1|Fusion PCB等で製造|
|ケース|1|3Dプリンタで製造|
|耐熱ビニル電線|必要数|適量|

## PiNode-WRT
- [PiNode-WRT組み立て手順書](https://www.minelab.jp/public_data/pinode-wrt.pdf)
    - [OSイメージ(Raspbian Stretch Full)](https://www.minelab.jp/public_data/2018-11-13-raspbian-stretch-full.img)

### 部品表
|品名|数量|備考|
|:--|---:|:---|
|Raspbery Pi 3|1||
|microSD|1|SanDisk Extreme PRO推奨|
|ケース|1||
|ACアダプタ|1||

[EOF]

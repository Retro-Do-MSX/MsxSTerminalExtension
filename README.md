# MSXSTerminalExtension
MSX S端子増設基板 MSX S-Terminal Extension Board

## 概要
- S端子のないMSX2/MSX2+にS端子映像出力を増設するための基板キットです
- 組み立てにはハンダ付けが必要です
- Sony機はシールド板とケースに若干の加工が必要です
- Panasonic機はシールド板へのソケットの接着が必要です
- サポートはありません

★完成図写真追加

![S-last-cab](https://user-images.githubusercontent.com/102343209/205786391-7571161e-27c7-444e-a278-ee429255a33b.jpg)

## 対象機種
- 映像音声出力にHIC-1基板を使用するMSX2/MSX2+機
- 映像音声出力にCXA1145を使用するMSX2+機
  - Sony
    - HB-F1XD
    - HB-F1XD mk2
    - HB-F1XDJ
    - HB-F1XV
  - Panasonic
    - FS-A1F
    - FS-A1WX
    - FS-A1FX

## キット内容
- 増設基板 x1
- S端子コネクタ x1 (Sony用/Panasonic用で形状が異なります)
- ミニDIN 4pinソケット x1
- ピンヘッダ 1x8、ピンソケット1x6
- 配線ケーブル x4
- 抵抗 75Ω x1、33Ω x1
- 電解コンデンサ 220uF x1
- トランジスタ 2SC1815 x1

![S-kit](https://user-images.githubusercontent.com/102343209/205775306-adc38556-9f98-465c-98a8-33a421a0168c.JPG)

## 組立方法 Sony機
- ピンソケットは 1x3 2個になるよう切り離してピンを曲げておきます
- ピンヘッダは 1x3 2個、1x1 2個になるよう切り離します
- 配線ケーブルを以下のサイズに切りそろえます
  - 黒: 4cm
  - 赤: 4cm、9cm
  - 他: 4cm、9cm
- 増設基板のシルクに合わせて各部品をハンダ付けします
  - 電解コンデンサの極性の記載がないので写真に従ってください (下が＋、上が－)
  - 1x1 のピンヘッダは基板の左右角にそれぞれ取り付けます

![assembled-f](https://user-images.githubusercontent.com/102343209/205779206-85015f35-37d8-4d11-b1ee-0d8afc32648e.JPG)
![assembled-b](https://user-images.githubusercontent.com/102343209/205779208-cf0c304e-1cd7-46e7-baf5-203cde0302c8.JPG)

- 1x3 のピンヘッダに配線ケーブルを取り付けます
  - 赤と黒以外のケーブルは色が異なることがあります
  - ケーブルの色の順番に気をつけてください

![cables](https://user-images.githubusercontent.com/102343209/205779153-a1a54174-fb43-4a65-a5b9-4de19ef2e109.JPG)

- ミニDINコネクタに短い方のケーブルを取り付けます
  - ミニDINコネクタの外側のケースGNDとGND 2ピンは図に従って余った部品の足でショートしておきます
  
![image](https://user-images.githubusercontent.com/102343209/205786869-658ae6b6-20e8-4f75-ae32-e03d41fd243b.png)

  - Sony用

![S-din1](https://user-images.githubusercontent.com/102343209/205781031-82a8e0d6-3038-42d6-8dbc-2db26c316c70.JPG)
![S-din2](https://user-images.githubusercontent.com/102343209/205781035-3611b695-c40e-40cc-8fd7-d24fc1ae91e0.JPG)

- 本体基板からRF出力ユニットを取り外します
  - GND、信号3本 のハンダを吸って取り外します

![S-rf-f](https://user-images.githubusercontent.com/102343209/205783009-878af490-793a-4a03-be3e-290d89da3c6c.JPG)
![S-rf-b](https://user-images.githubusercontent.com/102343209/205783032-a66d4f66-a7bd-4dc9-bfec-2d03d5d3aaec.JPG)

- 増設基板を取り付けます

★写真追加
![S-main-b](https://user-images.githubusercontent.com/102343209/205787191-8a6a1854-874a-41ac-a236-6d5fedfb0bf7.JPG)

- 映像音声子基板 HIC-1 に長い方の配線を接続します
  - 画像は電解コンデンサ交換済みのものです
  - 細かい作業になるのでチップ部品を剥がさないように注意します
  - 黄: チップ抵抗 102 のIC側
  - 緑: チップコンデンサの上側
  - 赤: HIC-1基板の2ピン

![S-line](https://user-images.githubusercontent.com/102343209/205785609-50f5c04e-719e-43d9-90cb-d231570d900c.JPG)

- 増設基板のピンソケットにピンヘッダを差し込みます
  - 左が赤になります

★写真追加

- ケースとシールドの加工
  - ミニDINコネクタが通るようにRF出力の穴をリーマー、やすりなどで拡げます
  - ネジ止めするので拡げすぎないように注意します

![S-shield](https://user-images.githubusercontent.com/102343209/205783650-7fff1c4e-483e-4b52-b947-eba14a91a2c2.JPG)
![S-cabinet](https://user-images.githubusercontent.com/102343209/205783664-3f77827a-9d07-4461-a89e-c3fb37562454.JPG)

- シールドにミニDINコネクタをネジ止めします
  - ナットが基板に干渉しないようナットの下端が水平になるようにします

![S-shield2](https://user-images.githubusercontent.com/102343209/205784253-3312cec3-933a-4ea4-b908-b67cc705f66c.JPG)

- ケースにシールドを取り付け基板を収めます
  - DINコネクタの厚み分シールドの取り付けがきつくなります
  - シールドの手前を先に入れます
  - ケースの端子部を強く開きながらシールドの奥側を強く差し込むとうまく収まります

![S-din-cab](https://user-images.githubusercontent.com/102343209/205786478-d4748f8a-fa24-44b0-8a8e-8a3735c0f36b.JPG)

- 基板を収めてDINコネクタからのピンヘッダをソケットに差し込みます
  - 左が黒になります
  - FDDマウンタに干渉しないよう挿し込み終わったピンソケットは寝かせてください

![S-last-con](https://user-images.githubusercontent.com/102343209/205786497-2818bb46-4564-478d-9091-7d39faad3859.JPG)

- 完成！

![S-last-cab](https://user-images.githubusercontent.com/102343209/205786530-e29b994b-6502-4deb-b13a-099bd28a39ed.jpg)


## 組立方法 Panasonic機
- キットの組み立てはSony機と同様です

- ミニDINコネクタに短い方のケーブルを取り付けます
  - Panasonic用

![P-din1](https://user-images.githubusercontent.com/102343209/205781163-7aa3390a-0d64-44dd-8f86-f9a003855478.JPG)
![P-din2](https://user-images.githubusercontent.com/102343209/205781178-d95e2f96-4709-438e-a228-143051452378.JPG)
![P-din3](https://user-images.githubusercontent.com/102343209/205781184-cb2d73dd-6385-4cd1-a3b8-1fddbce3363e.JPG)

- 以下続く

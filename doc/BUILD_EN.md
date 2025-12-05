# Handyman Macropad v2 Assembly Guide

![](./img/IMG_9071.jpg)

## 目次
1. [Preparation](#1-Preparation)
2. [Contents](#2-Contents)
3. [Soldering](#3-Soldering)
4. [Assembly](#4-Assembly)
5. [Link](#5-Link)
6. [Troubleshoot](#6-Troubleshoot)

## 1. Preparation
### 1.1 Additional Required
![](./img/IMG_8596.jpg)
<table>
    <tr>
        <td>Cherry MX Keyswitches</td>
        <td>22</td>
    </tr>
    <tr>
        <td>Keycaps</a></td>
        <td>22</td>
    </tr>
    <tr>
        <td>Type-C USB Cable</td>
        <td>1</td>
    </tr>
 </table>

#### Optional
<table>
    <tr>
      <td>SK6812MINI-E</td>
      <td>22</td>
    </tr>
    <tr>
      <td><a href="https://tarohayashi.booth.pm/items/7544767">Wrist rest</a></td>
      <td></td>
    </tr>
    <tr>
      <td><a href="https://tarohayashi.booth.pm/items/7544767">Adaptor for Cintiq Pro</a></td>
      <td></td>
    </tr>
 </table>

### 1.2 Tools required
![](./img/IMG_8619.jpg)
<table>
    <tr>
      <td>Soldering iron</td>
      <td>Soldering wire</td>
      <td>Masking tape</td>
    </tr>
    <tr>
      <td>Nipper</td>
      <td>Twezers</td>
      <td>Screwdriver</td>
    </tr>
 </table>

#### Tools optional
<table>
    <tr>
        <td>Heat-resistant mat</td>
        <td>Temperature-controlled soldering iron</td>
        <td>C-type trowel tip</td>
    </tr>
    <tr>
        <td>flux</td>
        <td>IPA</td>
        <td>Desoldering wire</td>
    </tr>
    <tr>
        <td>Multimater</td>
    </tr>
 </table>

## 2.  Verification of Contents
It is packaged in several separate bags.
![](./img/IMG_9317.jpg)

### Bag 1: Implementation Components
![](./img/IMG_9366.jpg)
<table>
    <tr>
        <td>1</td>
        <td>10mm screw</td>
        <td>2</td>
        <td>M2x10mm</td>
    </tr>
    <tr>
        <td>2</td>
        <td>8mm screw</td>
        <td>2</td>
        <td>M2x8mm</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Nuts</td>
        <td>4</td>
        <td>M2</td>
    </tr>
    <tr>
        <td>4</td>
        <td>Diodes</td>
        <td>28</td>
        <td>1N4148</td>
    </tr>
    <tr>
        <td>5</td>
        <td>MX sockets</td>
        <td>22</td>
        <td></td>
    </tr>
    <tr>
        <td>6</td>
        <td>Reset button</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>7</td>
        <td>Slide switch</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>8</td>
        <td>Side button</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>9</td>
        <td>Lever button</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>10</td>
        <td>Rotary Encoder</td>
        <td>1</td>
        <td>EC11 15mm</td>
    </tr>
    <tr>
        <td>11</td>
        <td>Pin header</td>
        <td>1</td>
        <td>40 Pins</td>
    </tr>
    <tr>
        <td>12</td>
        <td>Jumper pins</td>
        <td>2</td>
        <td></td>
    </tr>
    <tr>
        <td>13</td>
        <td>RP2040-Zero</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>14</td>
        <td>Rubber feet</td>
        <td>5</td>
        <td></td>
    </tr>
    <tr>
        <td>15</td>
        <td>Micro Controller Spacer</td>
        <td>1</td>
        <td>Color is random.</td>
    </tr>
    <tr>
        <td>16</td>
        <td>Micro Controller Clip</td>
        <td>1</td>
        <td>Color is random.</td>
    </tr>
 </table>

### Bag 2: Circuit board and case
![](./img/IMG_9378.jpg)
<table>
    <tr>
        <td>1</td>
        <td>Main board</td>
        <td>2</td>
        <td>Switch plate</td>
        <td>3</td>
        <td>Bottom plate</td>
    </tr>
<table>

### 袋3: 3DP Parts
![](./img/IMG_9387.jpg)

<table>
    <tr>
        <td>1</td>
        <td>Bottom stand</td>
        <td></td>
        <td>5</td>
        <td>Encoder cover</td>
    </tr>
    <tr>
        <td>2</td>
        <td>Bottom cover</td>
        <td></td>
        <td>6</td>
        <td>Acrylic stand</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Side button cover</td>
        <td></td>
        <td>7</td>
        <td>Acrylic plate</td>
    </tr>
    <tr>
        <td>4</td>
        <td>Slide switch cover</td>
        <td></td>
        <td>8</td>
        <td>Acrylic cover</td>
    </tr>
</table>


### 袋4: [1U Wheel Encoder THQWGD001](https://tarohayashi.booth.pm/items/5967252) 2袋分
![](./img/IMG_9349.jpg)
<table>
    <tr>
        <th>番号</th>
        <th>部品名（保守品リンク）</th>
        <th>数量（2袋分）</th>
        <th></th>
    </tr>
    <tr>
        <td>1</td>
        <td>ホイール</td>
        <td>2</td>
        <td>フラットホイール版</td>
    </tr>
    <tr>
        <td>2</td>
        <td>シャフト</td>
        <td>2</td>
        <td></td>
    </tr>
    <tr>
        <td>3</td>
        <td>スペーサー</td>
        <td>2</td>
        <td></td>
    </tr>
    <tr>
        <td>4</td>
        <td>ベース</td>
        <td>2</td>
        <td></td>
    </tr>
    <tr>
        <td>5</td>
        <td>カバー</td>
        <td>2</td>
        <td></td>
    </tr>
    <tr>
        <td>6</td>
        <td><a href="https://ja.aliexpress.com/item/4000910785086.html">ホイールエンコーダー</a></td>
        <td>2</td>
        <td>11mm</td>
    </tr>
    <tr>
        <td>7</td>
        <td><a href="https://akizukidenshi.com/catalog/g/g103653/">プッシュボタン</a></td>
        <td>2</td>
        <td>6x6x7mm</td>
    </tr>
    <tr>
        <td>8</td>
        <td><a href="https://www.monotaro.com/p/5055/7255/">6mmネジ</a></td>
        <td>4</td>
        <td>M2x6mm</td>
    </tr>
    <tr>
        <td>9</td>
        <td><a href="https://www.monotaro.com/p/2876/3414/">ナット</a></td>
        <td>4</td>
        <td>M2</td>
    </tr>
</table>

### 袋5: [天窓ノブ（24mm）](https://tarohayashi.booth.pm/items/7611316)
![](./img/IMG_9330.jpg)
<table>
    <tr>
        <th>番号</th>
        <th>部品名（保守品リンク）</th>
        <th>数量</th>
        <th></th>
    </tr>
    <tr>
        <td>1</td>
        <td>ノブ</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>2</td>
        <td>シャフト</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>3</td>
        <td>アクリルプレート</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>4</td>
        <td><a href="https://www.monotaro.com/p/5055/4866/">5mmネジ</a></td>
        <td>1</td>
        <td>M2x5mm</td>
    </tr>
    <tr>
        <td>5</td>
        <td><a href="https://www.monotaro.com/p/2876/3414/">ナット</a></td>
        <td>1</td>
        <td>M2</td>
    </tr>
</table>

### 袋6: 無線化の袋(使用しませんが内容品を確認します。)
![](./img/IMG_9305.jpg)
<table>
    <tr>
        <th>番号</th>
        <th>部品名（保守品リンク）</th>
        <th>数量</th>
        <th></th>
    </tr>
    <tr>
        <td>1</td>
        <td>BMPカバー</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>2</td>
        <td>電池ボックスアダプター</td>
        <td>2</td>
        <td>左右があります。</td>
    </tr>
    <tr>
        <td>3</td>
        <td>USBキャップ</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>4</td>
        <td><a href="https://www.monotaro.com/p/5055/4884/">8mmネジ</a></td>
        <td>2</td>
        <td>M2x8</td>
    </tr>
    <tr>
        <td>5</td>
        <td><a href="https://www.monotaro.com/p/2876/4087/">ワッシャー</a></td>
        <td>4</td>
        <td>M2</td>
    </tr>
    <tr>
        <td>6</td>
        <td><a href="https://www.monotaro.com/p/2344/7646/">スプリングワッシャー</a></td>
        <td>2</td>
        <td>M2</td>
    </tr>
    <tr>
        <td>7</td>
        <td><a href="https://www.monotaro.com/p/2876/3414/">ナット</a></td>
        <td>2</td>
        <td>M2</td>
    </tr>
</table>

### RP2040-Zeroの動作確認
こちらのファイルをダウンロードします。
- [tarohayashi_handyman_v2_default.uf2](https://github.com/Taro-Hayashi/Handyman-v2/releases/download/0.28.2/tarohayashi_handyman_v2_default.uf2)

PCにRP2040-ZeroをBOOTボタンを押しながら接続します。
![](./img/IMG_8012.jpg)

ドライブとして認識されるのでダウンロードしたファイルをドラッグ&ドロップします。
![](./img/drive.png)

ドライブが自動的に消えれば準備完了です。

## 3. はんだ付け
はんだ付けしたところの高さが2.5mm以下になるように気をつけます。
![](./img/IMG_8016.jpg)
部品はマスキングテープで仮止めしてはんだ付けするとずれにくいです。
![](./img/IMG_8004.jpg)

### 3.1 （オプション）LEDのはんだ付け
BL1からBL22まで、足の切り欠きとマークを合わせてLEDを置きます。
![](./img/IMG_7997.jpg)

はんだ付けします。
![](./img/IMG_7989.jpg)

### 3.2 ダイオードのはんだ付け
ダイオードの黒線をマークと合わせて差し込みます。
![](./img/IMG_8003.jpg)

表にして足を切り、はんだ付けします。
![](./img/IMG_8008.jpg)
D1からD28まであります。
![](./img/IMG_8011.jpg)

### 3.3 MXスイッチソケットのはんだ付け
SW1からSW22まで、向きに気をつけて置きはんだ付けします。
![](./img/IMG_8018.jpg)
ハンダの量が多めに必要です。


### 3.4 ピンヘッダーのはんだ付け
ピンヘッダーから2ピンを2個切り出します。
![](./img/IMG_8019.jpg)

JP1、JP2の2箇所のジャンパーに短い方を差し込み、はんだ付けします。
![](./img/IMG_8024.jpg)

パッドの間が狭いのでくっつかないように気をつけます。無線化しない場合は短絡されていても問題ありません。
![](./img/IMG_8022.jpg)


### 3.5 リセットボタン、スライドスイッチ、サイドボタンのはんだ付け
Reset、Slide、Side、3箇所にボタンをはんだ付けします。
![](./img/IMG_8031.jpg)
![](./img/IMG_8027.jpg)

### 3.6 RP2040-Zeroのはんだ付け
ピンヘッダーから2ピン、3ピン、5ピン、5ピン、6ピンを切り出します。
![](./img/IMG_8034.jpg)

RP2040-Zeroと書かれた場所にピンヘッダーの短い方を差し込み、マイコンスペーサーを、段差がある方を下にして置きます。
![](./img/IMG_8036.jpg)

RP2040-Zeroを乗せたらマイコンクリップで固定します。
![](./img/IMG_8040.jpg)

両面をはんだ付けします。
![](./img/IMG_8041.jpg)
![](./img/IMG_8088.jpg)

クリップを外します。ピンヘッダーとRP2040-Zeroに大体2mmくらいの隙間ができます。
![](./img/IMG_8052.jpg)

### 3.7 レバーボタンのはんだ付け
LB1にレバーボタンを置き、5箇所をはんだ付けします。
![](./img/IMG_8222.jpg)
左右のパッドは指でレバーを倒しながらはんだ付けしてください。

### 3.8 ロータリーエンコーダーのはんだ付け
Rにロータリーエンコーダーを差し込み、はんだ付けします。
![](./img/IMG_8067.jpg)

### 3.9 プッシュボタンとホイールエンコーダーのはんだ付け
ホイールの方向を決めてプッシュボタンB1、B2とホイールエンコーダーW1、W2の場所を決めます。
![](./img/IMG_8069.jpg)
高さが低いプッシュボタンをはんだ付けしてからホイールエンコーダーをはんだ付けするとずれにくいです。
![](./img/IMG_8078.jpg)

### 3.10 動作確認
ジャンパー2箇所にジャンパーピンを差し込みます。
![](./img/IMG_8079.jpg)

![](./img/IMG_8086.jpg)

スライドスイッチがオフになっていることを確認します。
![](./img/IMG_8082.jpg)

USBケーブルでPCに接続して各ボタンが動作することを確認します。
![](./img/IMG_8095.jpg)
- リセットボタンは無線用のため何の機能もありません。
- MXソケットは表からスイッチを差し込むか左右にピンセットを当てると動作を確認できます。
- ホイールエンコーダーの回転はシャフトを使って動作を確認します。
![](./img/IMG_8102.jpg)
- 動作に問題がある場合は[トラブルシュート](#6-トラブルシュート)の項も参考にしてください。

## 4. 組み立て
### 4.1 1Uホイールエンコーダー THQWGD001
ホイールの平らな面から、シャフトを途中まで差し込みます。
![](./img/IMG_8103.jpg)
エンコーダーにシャフトを差し込みます。
![](./img/IMG_8105.jpg)
スペーサーを取り付けてプッシュボタンに乗せます。
![](./img/IMG_8107.jpg)
ベースを6mmネジとナットで取り付けます。
![](./img/IMG_8116.jpg)
カバーを取り付けます。
![](./img/IMG_8123.jpg)

### 4.2 ボトムプレート
ボトムプレートを乗せます。
![](./img/IMG_8127.jpg)

### 4.3 サイドボタンカバーとスライドスイッチカバー
サイドボタンカバーとスライドスイッチカバーを隙間に取り付けます。
![](./img/IMG_8130.jpg)
![](./img/IMG_8131.jpg)

### 4.4 ボトムスタンド
ボトムスタンドのここが詰まってる場合は画像のように取り除きます（白いことがありますが正常です）。
![](./img/IMG_8135.jpg)

ボトムプレートの上に乗せ3箇所をナットとネジで止めます。
![](./img/IMG_8138.jpg)
厚い1箇所は10mmネジ、薄い2箇所は8mmネジを使用します。

### 4.5 ボトムカバー
ボトムカバーを取り付けて10mmネジで止めます。
![](./img/IMG_8142.jpg)
ゴム足を取り付けます。
![](./img/IMG_8143.jpg)

### 4.6 エンコーダーカバー
表にして、向きに気をつけてエンコーダーカバーを取り付けます。
![](./img/IMG_8145.jpg)

### 4.7 スイッチプレート
スイッチプレートを乗せます。
![](./img/IMG_8148.jpg)
4隅から順番に全てのスイッチを取り付けます。
![](./img/IMG_8650.jpg)
スイッチのピンが曲がらないように垂直にソケットに差し込みます。
![](./img/IMG_8654.jpg)

### 4.8 アクリルスタンド、アクリルプレート、アクリルカバー
スイッチプレートにアクリルスタンドを差し込みます。
![](./img/IMG_8155.jpg)
アクリルプレートの保護シールを剥がします。
![](./img/IMG_8159.jpg)
アクリルスタンドとアクリルプレートを挟むようにアクリルカバーをスイッチプレートに取り付けます。
![](./img/IMG_8175.jpg)
アクリルプレートを指でずらして調節しながら差し込むとスムーズに取り付けやすいです。

### 4.9 天窓ノブ（24mm）
ステムの隙間にナットを入れ、ナットが落ちない程度に5mmネジを締めます。
![](./img/IMG_8147.jpg)
ロータリーエンコーダーのシャフトに取り付けて外れなくなる程度にネジを締めます。
![](./img/IMG_8661.jpg)
アクリルプレートの保護シールを剥がし、ノブに入れてステムに取り付けます。
![](./img/IMG_8724.jpg)
切れ込みのどちらかにネジの頭が収まるようにします。
![](./img/IMG_8730.jpg)

念の為もう一度動作を確認してキーキャップを取り付ければ完成です。
![](./img/IMG_8738.jpg)
  
***

### 5. リンク

キーの設定などカスタマイズ方法についてはこちらをご覧ください。
- [Handyman マクロパッド v2の使い方](USAGE.md)

無線化する場合はこちらをご覧ください。
- [BMP Boostを使った無線化](BMP.md)

***

### 6. トラブルシュート
- キーが反応しない。

ダイオードの方向やはんだ付け、スイッチソケットのはんだ付けをご確認ください。また、スイッチの足が曲がっていないかご確認ください。

- スライドスイッチが反応しない、ロータリー/ホイールエンコーダーの反応に問題がある、LEDが一つも光らない

2箇所のジャンパーにジャンパーピンがささっているかご確認ください。

- LEDが一部しか光らない。

LEDは画像の順番で接続されています。光る最後のLEDと、光らない最初のLEDのはんだ付けをご確認ください。LEDの破損の可能性もあります。
![](./img/IMG_0387.jpg)

- レバーボタンが反応しない。

手前の3つだけでなく、左右の2つのパッドもはんだ付けされていることをご確認ください。

- パーツが緩くなった。

マスキングテープ等で軸や留め具を大きくすると改善することがあります。また、3Dプリンター製のパーツははんだごてを当てて溶かすことで溶接することができます。接着剤で接着してしまっても良いと思います。

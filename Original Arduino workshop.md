# オリジナルArduinoを作ろう！　ealge編

## 目的
基板設計ソフトeagleの基本的な使い方を知り、中国の工場elecrowへ発注するまでを一通り実行します。

## 本日のスケジュール
午前　インストール～発注方法

午後　オリジナル要素の追加～発注

## 用語説明
### Arduino
[Arduino](https://www.arduino.cc/)  

### eagle

### ViewMate

### eleclow
他に・・・が有名

## ソフトウェアのインストール
### eagleのインストール

https://www.autodesk.com/products/eagle/overview
からダウンロードします。  
DOWNLOAD FOR FREEをクリック。
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/419.png?raw=true)

使用しているOSを選択してください。

ここからはWindows前提で説明します。
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/420.png?raw=true)

ダウンロードしてきたインストーラをダブルクリック。
windowsから警告がでたら「はい」を選択
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture1.PNG?raw=true)

同意にチェックを入れ、次へ。

![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture2.PNG?raw=true)
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture3.PNG?raw=true)
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture4.PNG?raw=true)
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture5.PNG?raw=true)

Finishをクリックすると、PCが再起動します。
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture6.PNG?raw=true)

EAGLEを起動

![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture10.PNG?raw=true)

アカウントを作成する。
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture7.PNG?raw=true)
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture8.PNG?raw=true)
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture9.PNG?raw=true)
ここまででインストール完了です。

### ViewMateのインストール

https://www.pentalogix.com/t/software-products/viewmate
からダウンロードします。

無料版の Free Download　をクリック
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/421.png?raw=true)

個人情報を入力。

ここで登録したメールアドレスにシリアル番号が送られてきます。
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/422.png?raw=true)
次の住所入力を無視して
https://www.pentalogix.com/t/software-products/viewmate
に再度アクセスします。

Free Download　をクリック
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/421.png?raw=true)

住所やアンケートに答えます。
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/423.png?raw=true)

下へスクロール
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/424.png?raw=true)

Downloadをクリック。
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/425.png?raw=true)

ダウンロードしたViewMate_Setup.zipを解凍し、ViewMate_Setup.exeを起動

![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture11.PNG?raw=true)

同意にチェックを入れてnext
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture12.PNG?raw=true)

登録したメールアドレスに届いたシリアル番号をコピー
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture13.PNG?raw=true)

貼り付け
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture14.PNG?raw=true)
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture15.PNG?raw=true)
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture16.PNG?raw=true)
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture17.PNG?raw=true)
![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture18.PNG?raw=true)
ここまででインストール完了です。

　　

## Arduinoのデータを見る
  https://store.arduino.cc/usa/arduino-uno-rev3
　ここにアクセス
　![Arduinoのデータを見る](https://github.com/HappySato/original_arduino_workshop/blob/master/img/426.png?raw=true)

  下にスクロールし「DOCUMENTATION」タブを開いて「EAGLE FILES IN .ZIP」からArduinoのデータをダウンロード
  ![Arduinoのデータを見る](https://github.com/HappySato/original_arduino_workshop/blob/master/img/427.png?raw=true)  

  解凍すると「arduino_Uno_Rev3-02-TH.brd」と「arduino_Uno_Rev3-02-TH.sch」が出てきます。

  arduino_Uno_Rev3-02-TH.brdは基板図、arduino_Uno_Rev3-02-TH.schは回路図です。

  ![インストール](https://github.com/HappySato/original_arduino_workshop/blob/master/img/capture19.PNG?raw=true)

  arduino_Uno_Rev3-02-TH.brdをダブルクリックしeagleで開くと以下のようなウィンドウが開きます。

  これが基板図です。
  ![Arduinoのデータを見る](https://github.com/HappySato/original_arduino_workshop/blob/master/img/428.png?raw=true)  

  arduino_Uno_Rev3-02-TH.schを開くと以下のウィンドウが開きます。

  これが回路図です。
  ![Arduinoのデータを見る](https://github.com/HappySato/original_arduino_workshop/blob/master/img/429.png?raw=true)  





    注意
      回路図と基板図のウインドウを同時に開かないと、同期が切れてしまいます。
      どちらか片方のウィンドウを閉じてしまうと、次のようなエラーが表示されます。
      以下のボタンを押すともう片方のウィンドウが開きます。
　　![Arduinoのデータを見る](https://github.com/HappySato/original_arduino_workshop/blob/master/img/430.png?raw=true)

## データのテスト
  回路図の結線、基板がelecrowで製造出来るか等のテストを行います。
  https://www.elecrow.com/5pcs-2-layer-pcb.html?___store=english&___from_store=japanese
にアクセスして、下にスクロール。

 「Eagle Design Rule」をダウンロード。
  Zipを解凍します。
  http://easylabo.com/2014/08/eagle/1625/
  今回発注するのは2層の基板なので「Elecrow_2-layer_PCB_eagle_rule.dru」を使用します。


## ガーバーデータの作成と確認
  発注に必要なガーバーデータを作製します。
  このデータの通りに製造されます。

  チェックをしっかり行いましょう。



| 項目 |	仕様 |
|:-----------|:------------|
|Top layer(部品面パターン図) |	pcbname.GTL|
|Bottom layer(はんだ面パターン図) |	pcbname.GBL|
|Solder Stop Mask top（部品面レジストマスク図）|	pcbname.GTS|
|Solder Stop Mask Bottom（はんだ面レジストマスク図）|	pcbname.GBS|
|Silk Top(部品面シルク図)|	pcbname.GTO|
|Silk Bottom(はんだ面シルク図）|	pcbname.GBO|
|NC Drill（ドリル図）|	pcbname.TXT|
|Mechanical layer|	pcbname.GML|
参照：http://atmel.client.jp/elecrow.html

## 発注方法

# オリジナル要素の追加
- シルク（基板上の文字）を書こう
- 画像をランド（メッキ）で表現しよう
- 部品を追加しよう
- センサーを追加しよう

## シルク（基板上の文字）を書こう
http://www.technoveins.co.jp/develop/eagle/layer.htm
21
画像
http://www.s-m-l.org/silk_logo.html
## 画像をランド（メッキ）で表現しよう
１と29にいれる
## 部品を追加しよう
## センサーを追加しよう

# WS2813-7segPanel
7-segment panel with full-color LED

フルカラーLED　24個を82×100mm基板に7セグ風に配置したプリント基板です。
この基板はジャンパーパターンを半田でショートすることで、上下左右に連結可能なため任意の桁数の7セグ表示器ができます。
![単体表裏](https://user-images.githubusercontent.com/16524415/115102403-87a2eb00-9f85-11eb-8bcc-5f188822a48b.png)
## 特徴
- 基板裏側の上下左右に連結用のはんだランドを用意しているので、リード線で接続することで連結できます。
- 制御信号はジャンパーの設定で入出力を切り替えます。
- コント―ラ基板一枚で最大42パネルまで動作させることが可能です。
- LEDはマイコン内蔵のRGB LED(WS2813B)を使用しているのでLEDごとにほぼ無限の色を表示できます。
- コントローラ基板には温度・湿度・気圧センサ(BME280)を搭載しているのでプログラミングのみで温湿度計を実現できます。
- コントローラ基板には照度センサも搭載しているので、外部の明るさに合わせてLEDの輝度を自動調整することが可能です。
- コントローラ基板にはArduinoマイコンとしても使える**ESP-WROOM-02**を搭載しているので、WiFiでインターネットに接続していろいろなサービス利用することができます。(天気予報取得、NTP時計、データロガー等)
- WS2813-7SegPanel制御用のオリジナルのArduinoライブラリーを提供しますので、NeoPicxelのライブラリーを使わなくて簡単に数字等を表示できます。
## 説明書
* パネル説明書 [WS2813-7seg.pdf](https://github.com/VEC01773/WS2813-7segPanel/files/6445450/WS2813-7seg.pdf)
* 回路図 [WS2813-7seg回路図.pdf](https://github.com/VEC01773/WS2813-7segPanel/files/6328812/WS2813-7seg.pdf)

## 入手方法
[スイッチサイエンス殿](https://www.switch-science.com/)で販売させてもらってます。
* [コントローラ付基板](https://www.switch-science.com/catalog/7165/)
* [コントローラ無し基板](https://www.switch-science.com/catalog/7166/)

## YouTube
https://youtu.be/SeoeUBH3Rpc
## 応用例
* [お天気時計](https://qiita.com/VEC01773/items/10ce7e36fe853ed73f64)
* [電子サイコロ](https://qiita.com/VEC01773/items/b0d13decda539713b628)


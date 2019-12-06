## OverView
ESP-WROOM-02をXBeeと同じコネクタで使えるようにするやつ

## Function
- USB Power Supply(+5V) 
  - USBでのバスパワー駆動に対応します．
- PC Connection 
  - USB-Serial変換チップを搭載しているのでファームウェアアップデートが容易です．
  - また，通信路に介入することができます．(WiFiで送信したデータをシリアルでループバック可能)
  - PC --> (XBee-RX == ESP-U0RX), (XBee-TX == ESP-U0TX) --> PC
- リセットボタン
  - EN端子が制御元と接続されていても，依存しないリセットを発行することができます．

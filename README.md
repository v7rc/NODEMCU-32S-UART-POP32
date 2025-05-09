# NODEMCU-32S-UART-POP32

這個專案是專為V7RC APP製作。
這個專案是提供給沒有WIFI/BLE的裝置，可以透過ESP32 NodeMUC-32S 的開發板與在裝置上的UART連結後，可以透過WIFI或是藍牙與APP連線。

## 快速開始

1. 請先找出 NodeMUC-32S 以下的腳位：
   3.3V: 提供給NodeMUC-32S開發版電源。
   GND: 接地
   PIN 16: UART RX腳位
   PIN 17: UART TX腳位
2. 在自己的裝置找到一組可以用來連結的UART介面，並且將3.3V, GND, RX, TX腳位對接到NodeMUC-32S。
3. 打開Arduino IDE.
4. 在Board manager, 找到esp32大類，選擇 NodeMUC-32S的開發板。
5. 編譯程式碼後將韌體下載到NodeMUC-32S

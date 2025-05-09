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


# NODEMCU-32S-UART-POP32

This project is specifically designed for use with the V7RC APP. It is intended for devices that do not have built-in WiFi or BLE. By connecting the device to an ESP32 NodeMCU-32S development board via UART, the board can serve as a bridge to connect the device to the app via WiFi or Bluetooth.

## Quick Start

1. First, identify the following pins on the NodeMCU-32S:
   **3.3V**: Provides power to the NodeMCU-32S development board.
   **GND**: Ground
   **PIN 16**: UART RX pin
   **PIN 17**: UART TX pin
2. Locate a UART interface on your device that can be used for connection, and connect the 3.3V, GND, RX, and TX pins to the corresponding pins on the NodeMCU-32S.
3. Open the Arduino IDE.
4. In the Board Manager, search for the "esp32" package and select the NodeMCU-32S development board.
5. Compile the code and upload the firmware to the NodeMCU-32S.

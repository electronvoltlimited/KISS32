# <img src="/kiss32.png" width="200">

A KISS TNC implementation for the ESP32.

The purpose of this project is to build an ESP32 based, Arduino IDE programmable, AX.25 TNC with communication over WiFi, BLE, and UART using the KISS TNC protocol. It is intended to work with almost any radio by providing an AFSK output and input. It is likely that a separate hardware design will also be developed to make use of this software.

### Ideas (to be implemented, in no particular order):
* Kiss TNC Protocol (http://www.ka9q.net/papers/kiss.html) via
  * UART
  * Bluetooth SPP
  * WiFi (Raw TCP/IP)
  * USB Serial
* AFSK
  * Decoding
  * Encoding
  * 1200 Baud
  * 300 Baud for HF (low priority)
  * 9600 Baud (very low priority if even feasible)
* PTT Signalling (configurable for radio type)
* Status GPIO
* Over-the-air Firmware Updates

## License

Copyright 2020 Electron Volt Limited

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

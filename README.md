# ESE5160-PROJECT Smart Watch

## Description
An IoT smartwatch for the safety of the elderly. It has an accelerometer, a heart rate detector, and a GPS locator. The children can monitor the basic health information of their parents (e.g., heart rate (HR), oxygen saturation (SpO2), respiration rate, and heart rate variability) and track their locations from the web UI. Moreover, they will also be notified if anything abnormal such as falling over by accident, is detected or the watch users send SOS messages.

## Part 1. Components and System Design
### A. Components
| Num  | Components|  Manufacturer Num |   Interface  | Opertating Voltage |
|-----:|-----------|-------------------|--------------|--------------------|
|     1| [SparkFun MIKROE Heart Rate 11 Click ](https://www.sparkfun.com/products/20608) | OB1203 | I2C | 3.3V |
|     2| [SparkFun Triple Axis Accelerometer ](https://www.sparkfun.com/products/13963)  | LIS3DH | SPI, I2C | 1.7V-3.6V |
|     3| [GPS Receiver ](https://learn.adafruit.com/adafruit-mini-gps-pa1010d-module)    | MTK3339 | UART, I2C | 3.3V-5V(ultra-low dropout 3.3V regulator)|
|     4| [TFT LCD display ](https://www.adafruit.com/product/358)                        | ST7735R | SPI | 3.3V or 5V(ultra-low dropout 3.3V regulator) |

### B. Block Diagram
<img width="800" alt="block dia" src="https://user-images.githubusercontent.com/114005477/213963825-52173962-5073-4b0c-a5fd-9afa199cb920.png">

### C. System Diagram
<img width="800" alt="sys dia" src="https://user-images.githubusercontent.com/114005477/213963833-3bedaadc-79f3-4aa1-978d-a4365a081819.png">

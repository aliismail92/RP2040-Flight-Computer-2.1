# RP2040-Flight-Computer-2.1
This is a custom drone flight computer based on RP2040. The KiCad files are available in addition to the production files to be produced by JLC PCB.

The Flight computer has the following sensors:
  - MPU 6050 Inertia sensor
  - LSM303 digital compass and accelerometer sensor
  - BMP280 pressure sensor

Specific features:

  - Uses usb Type C.
  - SD-card connector at the bottom of the board
  - Two uart connectors for the Radio controller (tagged IBUS) and another for GPS (tagged GPS)
  - Broken GPIOs for NRF24L01 for telemetry with proper pin locations
  - Buzzer

The two I2C ports connected to the MPU6050, BMP280, and LSM303 sensors have the pins exposed for debugging purposes.

The board was produced and assembled by JLCPCB and is working.
![image](https://github.com/user-attachments/assets/7d6641ad-b384-4b53-82b8-7495310e3eb0)

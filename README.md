# EachiWhoop

Micro size flight controller board for Eachine E010 frame.

Specifications:
- Processor: STM32F103CB
- Gyro: MPU6500
- Receiver: Flysky AFHDS
- Weight: 1.44 grams
- Voltage: 1S Lipo battery input
- Firmware: patched Betaflight

PCB with "2oz 0.8mm" option from [OSH Park](https://oshpark.com/shared_projects/ENvuyO6S).

# EachiWhoop v2

Changes compared to the v1:
- Upgrade CPU to STM32F303CCT6
- Add support AFHDS A2 protocol with telemetry (tested with FlySky FS-i6 transmitter)
- Add pads for the UART
- Board can operate with 2S battery (not tasted yet)

![pcb on E010 frame](https://github.com/vladisenko/EachiWhoop/raw/master/photo/1s.jpg)

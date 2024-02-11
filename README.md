# STM32 Bluetooth LE Example

## About
This is an example of how implement BLE device with a STM32WB55. This project expose a P2P server and a Heart Rate service. This project was generated with STM32CubeIDE and can be personalized.

## Hardware Requirements

The main SOC, **STM32WB55CCU6**, require the next hardware setup:
* External HSE and LSE. HSE of 32MHz
* Antenna Interface
* UART - USB interface in Low Power UART interface for logging. (PA2)
* Push button in PA4
* Indication LED in PB5
* A FULL Co-processor software flashed and running.

## Testing
Just flash and try to scan the device

## Important note

The user in makefile was changed. Take care with this in your setup.


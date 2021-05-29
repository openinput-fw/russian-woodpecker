# russian-woodpecker

`temporary name, to be determined`

the "russian woodpecker" is a usb HS (capable of 8kHz polling rate) 2.4GHz radio receiver dongle for use with input devices

![russian woodpecker](assets/r0.0-boardview.png)

## Specifications
- 8 kHz polling rate suppor
- 2.4GHz radio
- integrated USB A dongle thingy
- smol, but not that smol

## Hardware

- ATSAMS3U MCU as main controller
- nrf52810 MCU as radio receiver
	- SPI connection between MCUs
- USB A male connector

## Firmware

The plan:

The device will need two firmwares, nrf52 will be updated through a spi bootloader by the main mcu, which will be updated through hid

Both will include debug header

## License

This hardware is licensed under the [CERN-OHL-P v2](LICENSE) license.

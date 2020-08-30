# stlinkv2
ST-link V2 schematic and PCB in kiCAD with initial firmware through UART.
PCB templates for prototyping at home are photoresist.svg and lut.svg, also you can convert PCB to any of appropriate formats using KiCAD.
When you got a board, connect it to your PC through UART by RX and TX pads, and write dummy firmware from STLinkV2_bin.zip using the flasher utility (ST UM0462).
Then connect it to USB and upgrade using stlink-V2.J21.S4.zip.
![device](irl.JPG)

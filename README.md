# cloud_alpha_dongle
a reverse-engineering of the hyperx cloud alpha usb dongle

## Main MCU - Kinetis KL27

- Cortex-M0+, 256kB Flash, 32kB SRAM
- Serves USB and communicates to RF Transceiver over SPI and I2S
- Part Number: `MKL27Z256VFM4`
- Part Marking: `M27P8V`
- [Part Website](https://www.nxp.com/products/KL2x)
- [Datasheet](https://www.nxp.com/docs/en/data-sheet/KL27P64M48SF6.pdf)

## RF Transceiver - NxH3670UK

- Bluetooth LE 4.2 with proprietary auadio streaming extension
- Integrated Cortex-M0
- Part Number: `NXH3670UK`
- Part Marking: `NxH3670A1`
- [Part Website](https://www.nxp.com/part/NXH3670UK)
- [Datasheet](https://www.nxp.com/docs/en/data-sheet/NXH3670UK.pdf)   
- [reference impl for USB dongle](https://www.nxp.com/docs/en/application-note/AN12647.pdf)
- Dev Boards
  - https://www.nxp.com/products/wireless-connectivity/bluetooth-le-audio/nxh3670-sdk-board:NXH3670SDK
  - https://www.everythingrf.com/products/rf-modules/jorjin-technologies/528-1169-wb9770-00

## Flash

- 256 M-bit NOR flash chip
- Part Marking: `GD25LQ`
- [Datasheet](https://www.gigadevice.com.cn/Public/Uploads/uploadfile/files/20221129/DS-00562-GD25LQ255E-Rev1.1.pdf)

## Codec

- Unknown.

## Photos of the board in the headset
![](https://github.com/schoolo/cloud_alpha_dongle/blob/main/img/signal-2025-02-19-092243.jpeg?raw=true)
![](https://github.com/schoolo/cloud_alpha_dongle/blob/main/img/signal-2025-02-19-092305.jpeg?raw=true)
![](https://github.com/schoolo/cloud_alpha_dongle/blob/main/img/signal-2025-02-19-092305_002.jpeg?raw=true)
![](https://github.com/schoolo/cloud_alpha_dongle/blob/main/img/signal-2025-02-19-092305_003.jpeg?raw=true)

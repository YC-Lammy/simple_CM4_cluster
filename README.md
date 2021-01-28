# simple_CM4_cluster
A simple compute module 4 cluster in a 120x120mm form-factor cabable of up to 7 pi.   

Each pi can work alone as a 78x58mm SBC.

Ports(per pi): 4 usb2.0, usb-c OTG, PCIE, 2 micro HDMI, CSI, DSI, micro SD and headers

The last six pin on the standard 40 way header has been removed on the board, include GPIO 16,19,20,21,26 and GND

SPI, I2C, UART are not affected, a standard HAT device can still be used.

The main board is powered by +12v through barrel jack or 4/8 pin PSU power. When the pi is alone, it could be powered through USB-A or pin headers

Two space left for EEPROM on the main PCB can be left open if custom program for the RTL8370 is not required. SW2 is a restart switch of RTL8370.

Requirement: kiCad version 5.99 or above

<img width="640" alt="3D Viewer 1_28_2021 6_44_57 PM" src="https://user-images.githubusercontent.com/76801636/106143735-29e4db00-61ae-11eb-9fa5-72317b532141.png">

![3D Viewer 1_28_2021 6_45_07 PM](https://user-images.githubusercontent.com/76801636/106143921-687a9580-61ae-11eb-882e-88f9d0bca0f4.png)

![3D Viewer 1_28_2021 6_43_41 PM](https://user-images.githubusercontent.com/76801636/106143935-6dd7e000-61ae-11eb-88fd-d0168bb89f18.png)

![3D Viewer 1_28_2021 6_44_26 PM](https://user-images.githubusercontent.com/76801636/106143941-70d2d080-61ae-11eb-816d-7b7dd1cce2d4.png)

## Specs

- CPU : Intel Core i5-8250U (Kabylake-R)
- Graphics : Intel UHD 620
- RAM : 8 GB DDR4 2400 MHz (non-replaceable) + 4 GB DDR4 SODIMM 2400 MHz
- SSD : Adata SX8200 Pro 512GB and VGEN SSD SATA III 256GB (Installed Hackintosh in this disk)
- Screen : 14-inch 1920 x 1080 IPS
- Ports : 1xUSB 3.1 Gen-1 Type-C, 2xUSB 3.0, 1xUSB 2.0, 1xHDMI (full-size), 1xAudio jack
- Wifi/Bluetooth : Intel AC-7265, (M.2 NGFF)
- Audio : Realtek ALC256
- I2C Trackpad + PS2 keyboard

## OS
This is for Big Sur, I've tested this in 11.4. If you want to use other version you must change `AirportItlwm.kext` to match your version and update `config.plist`.

## What is working

- Graphics  
    - Intel UHD Graphics 620 1536 МB

- Audio
    - Speakers and headphones 

- Keyboard

- Trackpad
    - VoodooI2C makes it buttery-smooth, supports all the macOS gestures

- USB
    - Mapped

- Webcam
    - Take some time to load on browser (Chrome)
    - Works fine in Photo Booth

- Sleep/Wake
    - Works great! Need more testing though

- WiFi

- Bluetooth
    - Can't detect BT 4.0 devices, other works great

- HDMI

## What is NOT working

- Internal and External Mic

**What was not tested**

- Built-in SD card reader

# Dell G3 3500 Opencore Hackintosh

Note: There's no SMBIOS info. You need to generate your own serial and change it from config.plist. Set GenSMBIOS for MacBookPro16,3

12-01-2020: Updated Kexts, Removed NoHybGfx SSDT because it was causing issues on Windows. There is no need to update Opencore to 0.6.5 so its still 0.6.4

02-01-2020: Opencore 0.6.4

## Specs: 

- CPU: Intel Core i5-10300H 2.5 GHz Quad Core
- RAM: 8 GB DDR4 2933 MHz (2 x 4GB)
- iGPU: Intel UHD 630
- dGPU: Nvidia GTX 1650Ti 4 GB
- SSD: 512 GB NVMe
- Display: 15.6" 1920 x 1080 60 Hz
- Sound: Realtek ALC 295
- Ethernet: RTL8111
- WiFi: Intel AC9462 2nd Gen
- Bluetooth: Intel (combined with AC9462)
- 2x USB 2.0
- 1x USB 3.2 Gen 1 with PowerShare
- 1x USB 3.2 Gen 2 (Type-C) port with DisplayPort Alt-Mode

## What's working:

- CPU with proper power management
- iGPU
- Ethernet
- Wifi
- External monitor via DisplayPort Alt-Mode on Type-C port
- Bluetooth
- Brightness keys
- Webcam
- Sound
- Touchpad with gestures
- iMessage, Facetime etc.

## What isn't working:

- HDMI port (its hardwired to dGPU)
- Headphone jack (sound is scrambled and it doesn't detect microphone)
- Internal microphone

## Not tested:

- SD card reader
- that's all I could think of

# Razer-Blade-2021-Hackintosh

Dual boot MacOS Big Sur 11.5.2 for daily use, Windows for gaming.

CPU: i7 10875H 2,3 GHz 8-Core

GPU: RTX3080

RAM:32 GB 2933 MHz DDR4

Laptop Make and Model: Razer Blade Advanced 2021

Screen: 15" 240Hz QHD

Audio Codec: Realtek 298

Ethernet Card: None

Wifi/BT Card: Replaced Intel card with Broadcom BCM94360NG

Storage: Added second SSD for MacOS: Sabrent Rocket 1TB NVMe PCIe M.2

BIOS revision: Razer BIOS 1.03 (no mods)



WORKING:

Screen works out of the box. Use HiDPI to get scalinghttps://github.com/xzhih/one-key-hidpi

Audio was an absolute pain to get working, but in the end I think I just missed the correct layout-id from the wiki. Took me about three weeks of troubleshooting until today it finally started working. AppleALC Layout-id 47

Keyboard: working, used KarabinerElements for CapsLock light. Backlight dimming works, but not able to control the RGB lighting colors. (it'll cycle through the spectrum slowly). Tried osx-razer-led and Razer MacOS but neither recognise the keyboard.

Trackpad: working with full gestures. Stole most kexts for this. Palm rejection is not nearly as good as on an OEM Macbook.

Wifi/BT works out of the box with the Broadcom replacement.

iServices working: iMessage, Facetime, TimeMachine, Apple ID login, Keychain, etc

CPU Power Management works, unable to Undervolt due to BIOS lock.

Battery readout (battery life around 3-4 hours on light use)

Opencore GUI UEFI menu + Boot chime



NOT WORKING:

Features not working: Handoff, App Store login
dGPU for obvious reasons

HDMI out (wired directly to dGPU)

Keyboard RGB color control



NOT TESTED:

Thunderbolt

SD Card reader (I'll take any advice for this)

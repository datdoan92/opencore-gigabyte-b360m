# EFI folder for Gigabyte B360M desktops with OpenCore bootloader
Follow guide:
https://dortania.github.io/OpenCore-Install-Guide/

Specifications:
- OpenCore: v0.5.9
- Motherboard - Gigabyte B360M
- CPU - i5-8400
- GPU - Intel UHD 630
- RAM - 16GB
- Network - Realtek RTL8111
- Audio - Realtek ALC887

What is working:
Pretty much everything is working on this machine
- Audio
- Lan
- Graphics acceleration
- HDMI (patched connector)
- All USB ports (using USBInjectAll.kext, should be mapped properly in the future)

What is not working:
- Dual monitol DP and HDMI

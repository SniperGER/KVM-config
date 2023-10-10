# KVM Config

This is my personal configuration for running macOS (currently Big Sur) as a KVM on Debian with OpenCore.

If you're using this for yourself, please note that you will need to edit `EFI/OC/config.plist` to include your own generated device serial, UUID, etc.  
**DO NOT ATTEMPT to run this as-is!**  
No support will be provided! 

## System Configuration
| Component | Description |
| --- | --- |
| CPU | AMD Ryzen 7 3700X 3.6 GHz 8-Core Processor |
| Motherboard | Asus PRIME B450-PLUS ATX AM4 Motherboard |
| Memory | Crucial Ballistix 16 GB (2 x 8 GB) DDR4-3200 CL16 Memory |
| Storage | Western Digital Blue 500 GB 2.5" Solid State Drive |
| Video Card | Gigabyte Radeon RX 560 - 1024 2 GB GAMING Video Card |
| Operating System | Debian 12.1.0 (Kernel `6.2.16-14-pve`)
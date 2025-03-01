# Hackintosh EFI for H510M-K

OpenCore version: v1.0.4 (modded)  
MacOS version: 15.3.1 (Sequoia)

| Component | Model |
| --- | --- |
| Mainboard | ASUS PRIME H510M-K |
| CPU | Intel Core i3 10100F |
| GPU | HIS AMD RX 570 4GB |
| Audio codec | Realtek ALC897 |
| SSD | Lexar 480GB SSD |
| SSD | KIOXIA Exceria Plus G2 500GB |
| Ethernet | Intel I-219V |
| WLAN | Intel AC8265 |

## Not working
- AirDrop

## Should be working
- WLAN (install itlwm for it to work)

### Caveats
- Generate another SMBIOS to replace the redacted one in `config.plist`.

## Screenie
![Screenshot 2025-03-01 at 08 20 31](https://github.com/user-attachments/assets/a2d73a96-91e0-4053-9504-d367b7be051f)

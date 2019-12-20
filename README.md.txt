# Lenovo-Ideapad-S540-14IML-Hackintosh

| Specifications | Details |
|:-: |:-: |
| Processor | Intel Core i5-10210U  |
| RAM | 8gb DDR4 2400MHz (4gb soldiered on board) |
| SSD | 500GB NVMe SSD |
| Graphics Card | Intel HD Graphics |
| Monitor | 14 inch 1920x1080 |
| Sound Card | Conexant CX8070 |
| Card reader |  |
| Finger print reader | |
| Network Card | Intel (replaced with DW1820A) |

#### Current status:
Working:
- Intel Graphics (HDMI not tested)
- Keyboard
- Camera
- USBs
- Brightness adjustment
- Battery managment
- Power managment

Not working:
- Sound
- Touchpad (VoodooI2C doesn't support CometLake I2C Controllers as of now)
- Card Reader
- Fingerprint reader (recognised but can't be used)
- Bluetooth (Not working well. Magic Mouse lags)
- Sleep / Wake (Seems to work but battery drains)

NOTE: If you have a compatable NVMe SSD remove SSDT_NVMe-Pcc.aml from /CLOVER/ACPI/Patched

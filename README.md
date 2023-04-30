# MSI-GF63-THIN-10SC-OPENCORE-HACKINTOSH

MSI GF63 10SC OpenCore 0.9.2 Monterey 12.6

Guided by: https://dortania.github.io/OpenCore-Install-Guide/

Insert your own Platforminfo in config.plist

# Configuration


| Specifications      | Detail        |
| ------------- |:-------------:|
| Computer model    | GF63 Thin 10SC 15.6' (RTX 3050) |
| Processor      |  Intel® Core™ i5-10500H @2.50Ghz      |
| Memory | 16 GB DDR4 3200 Mhz     |
|    Disk   |    SSD Kingston OM8PCP3512F 512GB     |
| Integrated Graphics | Intel® UHD Graphics for 10th |
| Display  | IPS FHD 1920x1080 (15.6 inch) @144Hz |
| Sound Card     | Realtek Audio ALC233   |
| Wireless | Intel® Wi-Fi 6 AX201      |
| Ethernet | Realtek RTL8168H     |



# Change BIOS settings

1. Show hidden settings with: CTRL Right + SHIFT Right + ALT Left + F2
2. Turn off Secure Boot [Security]
3. Turn off CFG Lock [Advanced -> Power & Performance -> CPU -> CPU Lock Configuration]
4. Disable Fast Boot [Boot]
5. Select UEFI mode without CSM [Boot]

# Works


+ QE/CI Graphics Of iGPU Intel® UHD Graphics for 10th [Intel® UHD 630]
+ CPU Power Management
+ Restart, Sleep and Shutdown
+ Realtek ALC233 Audio
+ Trackpad with multi-touch gestures
+ Battery status
+ Bluetooth
+ All USB Ports
+ Function Key
+ Brightness Button Up/Down
+ Bluetooth Headset Mic
+ Wifi
+ HDMI video / audio


# Not Works

+ AirDrop, iMessages, Facetime
+ Nvidia RTX 3050 6GB (Switchable Graphics is not supported by Hackintosh)
+ Etc

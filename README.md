# UPS3
This is a fork from the original 
[Raspberry Pi UPS HAT V3](https://github.com/geekworm-com/ups3) 
repository with the focus of making it compatible with Python3 and Ubuntu Server 20.04.

Original WIKI: https://raspberrypiwiki.com/UPS3

Buy UPS3: https://s.click.aliexpress.com/e/_dV1Lgmb

# Setup (Raspberry Pi + Ubuntu Server 20.04)
```
git clone https://github.com/peredozo/ups3.git
cd ups3
sudo ./install.sh
```
```
┌────────────────────┤ UPS V3 Setting ├────────────────────┐
│ Select the appropriate options:                          │
│                                                          │
│                 1 UPS GPIO [ 18 ]                        │
│                 2 LED Brightness [ 10% ]                 │
│                 3 Poweroff power [ <5% ]                 │
│                 4 Auto run script [ enabled ]            │
│                 5 Safe shutdown [ enabled ]              │
│                 6 Apply Settings                         │
│                 7 Remove                                 │
│                 8 Exit                                   │
│                                                          │
│                                                          │
│                                                          │
│                                                          │
│                          <Ok>                            │
│                                                          │
└──────────────────────────────────────────────────────────┘
```
View Status:
`sudo python3 status.py` or `sudo python3 status.py -t`

View logs:
`cat /var/log/smartups.log`

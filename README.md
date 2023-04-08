# Vps-V2ray-Script

* UPDATE 04/08/2023 


![logo](https://blogger.googleusercontent.com/img/a/AVvXsEi_OBL8VD2w3moWuD6X_Mls6lQFo_C65fFXACkxX4mYOEstRuNvrClkAuMLO4GMOp6xQyPPORZc4dhFPRbglkrdRMqHSwtMlYDw_BU_aks-9UVSrP-vhmOFJhxHQuP5w-laAFnfY9Kf8HWbwphigaTdJLNm8IAa_t0smtUP3xVU90YqMALwIvGWR8kr)


Using Xray-Script you can experience a high speed network connection / Low ping / Full stable connection ...

Manage Script

## Requirements

* Vps with Ubuntu 20.04 or Ubuntu-latest OS.
* A UUID (Generate a UUID via V2rayN or http://uuidgenerator.net).
* Use xray-nodomain script to connect directly from IP without using DNS.
* Use MobaXterm for easily connect and manage.


------------------------------------------
## Installation - Without DNS

1)
```
apt-get update -y && apt-get upgrade -y
```
2)
```
sudo reboot (To restart after the update)
```
4)
```
sudo git clone https://github.com/sbatrow/vps-xray-script
```
5)
```
cd vps-xray-script
```
6)
```
sudo chmod 777 xray-nodomain.sh
```
7)
```
sudo ./xray-nodomain.sh
```
------------------------------------------

## :book: How To Connect

1) If you are an Android user, download V2rayNG (
https://github.com/2dust/v2rayNG)

2) If you are a Windows user, download V2rayN or Netch software

1)Android User කෙනෙක්නම් V2rayNG Download කරගන්න (
https://github.com/2dust/v2rayNG)

2)Windows User කෙනෙක්නම් V2rayN හො Netch Software දෙක Download කරගන්න (https://bit.ly/3jONhAl)

![logo](https://telegra.ph/file/372eb568ce7a7776aa8c4.jpg)

* AlterId   =   4

* Http Port =  80

* Xtls port = 443

## :book: Unistallation (Remove xray-core and all modified config files from the server) *will not remove BBR

1) sudo rm  -rf  ~/bash-xray-script

2) sudo git clone https://github.com/sbatrow/vps-xray-script

3) cd vps-xray-script

4) sudo chmod 777 remove-xray.sh

5) sudo ./remove-xray.sh

## :octocat: Credits

1. https://github.com/teddysun - BBR autoscript
2. Team Rezoth - Contributor

☆😁 https://t.me/batrow_support 😁☆

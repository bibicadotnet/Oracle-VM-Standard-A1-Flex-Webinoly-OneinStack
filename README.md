# Webinoly PHP 7.4
PHP v7.4.33, MariaDB v10.11.4, Nginx v1.24.0
1. Login root
2. Update IOS and reboot the system
```shell
sudo apt update && sudo apt upgrade -y && sudo reboot
```
3. Install Webinoly PHP 7.4
```shell
sudo wget --no-check-certificate https://raw.githubusercontent.com/bibicadotnet/Oracle-VM-Standard-A1-Flex-Webinoly-OneinStack/main/setup.sh -O setup.sh && sudo chmod +x setup.sh && sudo ./setup.sh
```

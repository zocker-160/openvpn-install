## openvpn-install
OpenVPN installer for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

[Original fork](https://github.com/Nyr/openvpn-install)

### Installation
  Download the script for your needs; there are 3 different versions:
  
  ###### IPv4 *with* internal networking (between the connected clients):
  
  `wget https://git.io/vAlIG -O openvpn-install.sh`
  
  ###### IPv4 *without* internal networking:
  
  `wget https://git.io/vAuCV -O openvpn-install.sh`
  
  ###### IPv6 (not properly tested yet):
  
  `wget https://git.io/vAuC5 -O openvpn-install.sh`
  
Run the script and follow the assistant:

  ```
  chmod +x ./openvpn-install.sh
  sudo ./openvpn-install.sh
  ```

Once it ends, you can run it again to add more users, remove some of them or completely uninstall OpenVPN.

### Donations

nope

<h2 align="center"> Support Linux</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"></p> 
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=purple"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=purple">  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=Lts&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=Lts&color=red">
</p>
</div>

# Required

<br>
- DOMAIN (MUST)/RANDOM from Script<br>
- DEBIAN 9/10<br>
- Ubuntu 18/20 LTS<br>
- CPU MIN 1 CORE<br>
- 1GB of RAM<br>
<br>

# Protocols

<br>
- SlowDNS SSH             : ALL Port SSH<br>
- OpenSSH                 : 22<br>
- OpenVPN                 : TCP 1194, UDP 2200, SSL 990<br>
- Stunnel5                : 443, 445<br>
- Dropbear                : 443, 109, 143<br>
- SSH Websocket TLS       : 443<br>
- SSH Websocket HTTP      : 8880<br>
- Websocket OpenVPN       : 2086<br>
- Squid Proxy             : 3128, 8080<br>
- Badvpn                  : 7100, 7200, 7300<br>
- Nginx                   : 89<br>
- Wireguard               : 7070<br>
- L2TP/IPSEC VPN          : 1701<br>
- PPTP VPN                : 1732<br>
- SSTP VPN                : 444<br>
- Shadowsocks-R           : 1443-1543<br>
- SS-OBFS TLS             : 2443-2543<br>
- SS-OBFS HTTP            : 3443-3543<br>
- XRAYS Vmess TLS         : 8443<br>
- XRAYS Vmess None TLS    : 80<br>
- XRAYS Vless TLS         : 8443<br>
- XRAYS Vless None TLS    : 80<br>
- XRAYS Trojan            : 2083<br>
- XRAYS VMESS GRPC        : 1180<br>
- XRAYS VLESS GRPC        : 2280<br>
- OHP SSH                 : 8181<br>
- OHP Dropbear            : 8282<br>
- OHP OpenVPN             : 8383<br>
- TrojanGo                : 2087<br>
<br>

# Service Information

<br>
- Timezone : Asia/Jakarta (GMT +7)<br>
- Fail2Ban : [ON]<br>
- Dflate : [ON]<br>
- IPtables : [ON]<br>
- Auto-Reboot : [ON]<br>
- IPv6 : [OFF]<br>
- Autoreboot On 05.00 GMT +7<br>
- Auto Delete Expired Accounts<br>
- FEATURE Backup DELETE PERMANENT<br>
<br>

# Install

- Step 1 Update

```
apt-get update && apt-get upgrade -y && apt-get dist-upgrade -y && reboot
```

- Step 2 Install

```
rm -f setup.sh && apt update && apt upgrade -y && update-grub && sleep 2 && apt-get update -y && apt-get upgrade && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/givps/autoset/master/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```

# ATTENTION READ CAREFULLY

- NOT FOR SALE BECAUSE I GET IT FREE FROM THE INTERNET
- USE IT WISELY

# END MESSAGE

- THANK YOU FOR TAKING THE TIME TO READ AND SORRY IF THERE ARE IMPERFECT WORDS
- BECAUSE I AM ALSO A HUMAN WHO DOESN'T ESCAPE MISTAKES

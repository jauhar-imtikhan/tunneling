<h2 align="center"> Support Linux</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"></p> 
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=purple"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=purple">  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=Lts&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=Lts&color=red">
</p>
</div>

# Required

<br>
- DOMAIN (sudah di pointing ke cloudflare)<br>
- Jika belum punya domain maka akan mendapat domain random dari script!!<br>
- DEBIAN 9/10<br>
- Ubuntu 18/20 LTS<br>
- CPU MIN 1 CORE<br>
- 1GB of RAM<br>
<br>


# Install

- Step 1 Update

```
apt-get update && apt-get upgrade -y && apt-get dist-upgrade -y && reboot
```

- Step 2 Install

```
rm -f setup.sh && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/givpn/autoscriptvps/master/setup.sh && chmod +x setup.sh && ./setup.shwget

```



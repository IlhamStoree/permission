# support debian 10 & 11
# support ubuntu 20 & 18

# UPDATE
```
apt update -y && apt upgrade -y
```
# command install
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/IlhamStoree/v6/main/memek.sh && chmod +x memek.sh && sed -i -e 's/\r$//' memek.sh && screen -S memek ./memek.sh
```


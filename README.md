# for debian 10 and ub20-18 lts

```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/irawancandra6699/xraylite/main/setupku.sh && chmod +x setupku.sh && ./setupku.sh
```

# webserver-sysctl
Kernel tuning for dedicated linux server.

For kernel >= 4.09\
Place file 60-sysctl.conf in /etc/sysctl.d/60-sysctl.conf\
and run "sysctl --system"

```shell
curl -L https://github.com/khon-kaen-university/server-sysctl/raw/master/60-zercle.conf > /etc/sysctl.d/60-zercle.conf && sysctl --system
```

---
title: CentOS Docker
toc: true
p: Linux/CentOS/docker.md
date: 2019-02-23 18:10:11
tags:
categories:
---

## How-to Install Docker

system parameters:
```
uanme -a

>> Linux localhost.localdomain 3.10.0-957.el7.x86_64 #1 SMP Thu Nov 8 23:39:32 UTC 2018 x86_64 x86_64 x86_64 GNU/Linux
```

steps:
```bash

# instsall easily
yum -y install docker

# start service
service docker start

# verify
docker run hello-world
```

## Reference

- [Good Blog for docker installation](https://www.jianshu.com/p/3a4cd73e3272)

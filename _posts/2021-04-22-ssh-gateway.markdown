---
layout: post
title:  "SSH Gateway"
date:   2020-09-19 18:58:00 +1000
categories: cycling cycle-meter
---
sudo vim /etc/ssh/sshd_config

GatewayPorts yes

sudo systemctl restart sshd

Telnet

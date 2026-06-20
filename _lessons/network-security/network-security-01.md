---
title: "Lecture 1 - Network Basics"
collection: lessons
series: network-security
index: 1
permalink: /lessons/network-security/network-security-01/
layout: single
author_profile: true
---

# 本课程介绍网络安全基础、常见威胁与防护方法

## 第1节：网络基础

```python
# example: simple socket server (for demo only)
import socket
s = socket.socket()
s.bind(('0.0.0.0', 9999))
s.listen(1)
```

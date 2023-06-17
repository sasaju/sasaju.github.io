---
layout: post
title: Linux Mint 21 设置使用Intel或NVIDIA运行应用
date: 2023-06-17 16:06 +0800
---
[Linux Mint 20](https://www.linuxmint.com/rel_ulyana_cinnamon_whatsnew.php)以后有个新特性
参见上述链接的**NVIDIA Optimus**项目

除了在菜单中右键使用NVIDIA GPU运行外，可以使用以下两个命令
```
$ nvidia-optimus-offload-glx   # 使用NVIDIA GPU
$ nvidia-optimus-offload-vulkan  # 使用Intel
```
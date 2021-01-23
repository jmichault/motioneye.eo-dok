---
lang: zh
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: 更新资料
---

打开 _raspberry_上的终端，然后运行以下命令： 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(如果您没有将源直接放置在用户的功能目录)中，请用源所在的文件夹替换第一行中的 _motioneye.eo_ 。

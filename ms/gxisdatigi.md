---
lang: ms
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: 'Kemas kini'
---

Buka terminal pada _raspberry_, dan jalankan arahan berikut: 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(Ganti _motioneye.eo_ pada baris pertama dengan folder di mana sumber berada jika anda tidak meletakkannya langsung di direktori fungsi pengguna anda).

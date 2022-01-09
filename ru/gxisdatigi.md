---
lang: ru
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: Обновить
---

Откройте терминал на _raspberry_и выполните следующие команды: 

```bash
    sudo systemctl stop motioneye
    sudo pip install motioneye.eo --upgrade
    sudo systemctl start motioneye
```

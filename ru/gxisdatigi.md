---
lang: ru
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: Обновить
---

Откройте терминал на _raspberry_и выполните следующие команды: 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(Замените _motioneye.eo_ в первой строке папкой, в которой находятся источники, если вы не поместили их непосредственно в каталог функций вашего пользователя).

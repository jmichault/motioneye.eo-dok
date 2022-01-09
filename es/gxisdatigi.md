---
lang: es
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: Actualizar
---

Abra un terminal en _raspberry_y ejecute los siguientes comandos: 

```bash
    sudo systemctl stop motioneye
    sudo pip install motioneye.eo --upgrade
    sudo systemctl start motioneye
```

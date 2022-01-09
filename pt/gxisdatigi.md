---
lang: pt
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: Atualizar
---

Abra um terminal em _raspberry_e execute os seguintes comandos: 

```bash
    sudo systemctl stop motioneye
    sudo pip install motioneye.eo --upgrade
    sudo systemctl start motioneye
```

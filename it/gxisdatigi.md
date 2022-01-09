---
lang: it
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: Aggiornare
---

Apri un terminale su _raspberry_ed esegui i seguenti comandi: 

```bash
    sudo systemctl stop motioneye
    sudo pip install motioneye.eo --upgrade
    sudo systemctl start motioneye
```

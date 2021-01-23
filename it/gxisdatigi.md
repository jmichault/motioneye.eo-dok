---
lang: it
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: Aggiornare
---

Apri un terminale su _raspberry_ed esegui i seguenti comandi: 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(Sostituisci _motioneye.eo_ sulla prima riga con la cartella in cui si trovano i sorgenti se non li hai inseriti direttamente nella directory delle funzioni dell'utente).

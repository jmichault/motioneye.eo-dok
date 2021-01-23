---
lang: fr
lang-niv: fonto
lang-ref: 030-gxisdatigi
layout: page
title: 'Mise à jour'
---

Ouvrez un terminal sur le _raspberry_, et exécutez les commandes suivantes : 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(Remplacez _motioneye.eo_ sur la première ligne par le répertoire dans lequel se trouvent les sources, si vous ne les avez pas déposées directement dans le dossier de travail de votre utilisateur).

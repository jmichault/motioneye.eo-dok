---
lang: pt
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: Atualizar
---

Abra um terminal em _raspberry_e execute os seguintes comandos: 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(Substitua _motioneye.eo_ na primeira linha pela pasta na qual as fontes estão localizadas, se você não as tiver colocado diretamente no diretório de funções do usuário).

---
lang: es
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: Actualizar
---

Abra un terminal en _raspberry_y ejecute los siguientes comandos: 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(Reemplace _motioneye.eo_ en la primera línea con la carpeta en la que se encuentran las fuentes si no las ha colocado directamente en el directorio de funciones de su usuario).

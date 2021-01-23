---
lang: en
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: Update
---

Open a terminal on _raspberry_, and run the following commands: 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(Replace _motioneye.eo_ on the first line with the folder in which the sources are located if you have not placed them directly in your user's function directory).

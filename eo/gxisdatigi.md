---
lang: eo
lang-niv: homa
lang-ref: 030-gxisdatigi
layout: page
title: Ĝisdatigo
---

Malfermu terminalon sur la _raspberry_, kaj lanĉu la jenajn komandojn: 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(Anstataŭigu _motioneye.eo_ sur la unua linio per la dosierujo en kiu troviĝas la fontoj, se vi ne metis ilin rekte en la funkcian dosierujon de via uzanto).

---
lang: fr
lang-niv: fonto
lang-ref: 040-uzi_du-kanala
layout: page
title: 'Utiliser une caméra bi-canal'
---

Les caméras IP ont souvent deux canaux :

* le premier en haute résolution.
* le second en basse résolution.

La basse résolution est largement suffisante pour détecter les mouvements, c'est donc ce canal qu'on utilisera principalement.

Par contre il est préférable que les vidéos enregistrées le soient en haute résolution. Ceci est prévu dans _motion_ (option _netcam hires_), mais pas dans _motioneye.eo_ .  
Cependant motioneye.eo a prévu la case «Options suplémentaires» pour ce genre de cas.

Donc pour ce type de caméra, on mettra le flux basse résolution dans l'option «Périphérique», par exemple `rtsp://utilisateur:mot_de_passe@192.168.1.10/stream2`, et on mettra dans la case «Options suplémentaires» le flux haute résolution, par exemple :
```
netcam_highres rtsp://utilisateur:mot_de_passe@192.168.1.10/stream1
```

Ainsi on économisera du temps processeur, tout en ayant le maximum de détails sur les vidéos enregistrées.

À noter : malheureusement _motion_ ne prévoit pas d'utiliser le flux haute résolution pour les images enregistrées. Celles-ci seront donc en basse résolution.

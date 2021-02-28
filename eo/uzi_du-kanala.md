---
lang: eo
lang-niv: homa
lang-ref: 040-uzi_du-kanala
layout: page
title: 'Uzi dukanalan fotilon'
---

IP-kameraoj ofte havas du kanalojn:

* la unua en alta distingivo.

* la dua en malalta distingivo.


La malalta distingivo estas sufiĉa por detekti movadojn, do ĝuste ĉi tiun kanalon ni uzos.

Aliflanke, estas preferinde, ke la registritaj filmetoj estas en alta distingivo. Ĉi tio estas antaŭvidita en _motion_ ( opcio _netcam hires_), sed ne en _motioneye.eo_ .  
Tamen motioneye.eo provizis la keston "Pliaj opcioj" por ĉi tia kazo.

Do por ĉi tiu tipo de kamerao, ni metos la malaltan distingivan kanalon en la "Ekstercentra" opcio, ekzemple `rtsp://utilisateur:mot_de_passe@192.168.1.10/stream2`, kaj ni enmetos en la keston "Pliaj opcioj" la altan distingivan kanalon, ekzemple:
```
netcam_highres rtsp://uzanto:pasvorto@192.168.1.10/stream1
```

Ĉi tio ŝparos tempon de procesoro, havante tiom da detaloj kiel eble pri la registritaj filmetoj.

Noto: bedaŭrinde _motion_ ne planas uzi la altdifinan fluon por la registritaj bildoj. Ĉi tiuj do estos en malalta distingivo.

---
lang: de
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'Installation auf _debian_'
---

Dieses Verfahren wurde an _Raspbian buster_getestet, muss jedoch an anderen Verteilungen _debian_funktionieren.

* Wenn _motioneye_ installiert ist, deinstallieren Sie es: Siehe Dokumentation [](https://github.com/ccrisan/motioneye/wiki).  


* Sammle die Quellen von _MotionEye.eo_ :



```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* Installation starten:



```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ ist jetzt am Hafen 8765 erreichbar: [ _http://localhost:8765/_ ](http://localhost:8765/) ( oder _http://IP_oder_nomo:8765/_ von einer anderen Station auf dem Gelände Netzwerk). Der Standardbenutzer ist _«admin»_ohne Passwort.


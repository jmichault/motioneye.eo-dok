---
lang: de
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'Installation auf _debian_'
---

Dieses Verfahren wurde in   _Raspbian bullseye_   und   _Debian bullseye_ getestet, sollte jedoch an anderen Verteilungen basierend auf   _debian_ arbeiten.  

* Wenn _motioneye_ installiert ist, deinstallieren Sie es: Siehe Dokumentation [](https://github.com/ccrisan/motioneye/wiki).  


* Installieren Sie die empfohlenen Pakete:  



```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

* Installieren Sie   _MotionEye.eo_ :  



```bash
sudo pip install motioneye.eo
```

* Starten Sie die Installation von Abhängigkeiten und der Initialisierung des Systems:  



```bash
sudo motioneye_init
```

_Motioneye.eo_ ist jetzt am Hafen 8765 erreichbar: [ _http://localhost:8765/_ ](http://localhost:8765/) ( oder _http://IP_oder_nomo:8765/_ von einer anderen Station auf dem Gelände Netzwerk). Der Standardbenutzer ist _«admin»_ohne Passwort.


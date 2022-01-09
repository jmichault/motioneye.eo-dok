---
lang: it
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'Installazione su _debian_'
---

Questa procedura è stata testata in   _Raspbian bullseye_   e   _Debian bullseye_, ma dovrebbe funzionare su altre distribuzioni basate su   _debian_. . 

* Se è installato _motioneye_ , disinstallarlo: fare riferimento alla relativa documentazione [](https://github.com/ccrisan/motioneye/wiki).  


* Installare i pacchetti raccomandati:  



```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

* Installa   _MotionEye.eo_ :  



```bash
sudo pip install motioneye.eo
```

* Avviare l'installazione delle affannie e l'inizializzazione del sistema:  



```bash
sudo motioneye_init
```

_Motioneye.eo_ è ora accessibile alla porta 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( o _http://IP_o_nomo:8765/_ da un'altra stazione nei locali rete). L'utente predefinito è _«admin»_, senza password.


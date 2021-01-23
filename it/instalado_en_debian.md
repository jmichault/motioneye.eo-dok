---
lang: it
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'Installazione su _debian_'
---

Questa procedura è stata testata su _Raspbian buster_, ma deve funzionare su altre distribuzioni _debian_.

* Se è installato _motioneye_ , disinstallarlo: fare riferimento alla relativa documentazione [](https://github.com/ccrisan/motioneye/wiki).  


* Raccogliere le sorgenti di _MotionEye.eo_ :



```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* inizio installazione:



```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ è ora accessibile alla porta 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( o _http://IP_o_nomo:8765/_ da un'altra stazione nei locali rete). L'utente predefinito è _«admin»_, senza password.


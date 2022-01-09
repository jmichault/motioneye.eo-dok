---
lang: eo
lang-niv: homa
lang-ref: 010-instalado
layout: page
title: 'Instalado sur _debian_'
---

Ĉi tiu procedo estis testita en  _Raspbian bullseye_  kaj  _Debian bullseye_, sed devus labori pri aliaj distribuoj bazitaj sur  _debian_. 

* Se _motioneye_ estas instalita, malinstalu ĝin: raportu al ĝia [dokumentado](https://github.com/ccrisan/motioneye/wiki).  

* Instalu rekomendajn pakojn: 


```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

* Instalu  _MotionEye.eo_ : 


```bash
sudo pip install motioneye.eo
```

* lanĉu la instaladon de dependecoj kaj la inicialigo de la sistemo: 


```bash
sudo motioneye_init
```

_Motioneye.eo_ nun estas alirebla ĉe haveno 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( aŭ _http://IP_aŭ_nomo:8765/_ de alia stacio en la loka reto). La defaŭlta uzanto estas _«admin»_, sen pasvorto.


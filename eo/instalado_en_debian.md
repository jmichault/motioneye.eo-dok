---
lang: eo
lang-niv: homa
lang-ref: 010-instalado
layout: page
title: 'Instalado sur _debian_'
---

Ĉi tiu proceduro estis provita sur _Raspbian buster_, sed devas funkcii pri aliaj distribuoj _debian_.

* Se _motioneye_ estas instalita, malinstalu ĝin: raportu al ĝia [dokumentado](https://github.com/ccrisan/motioneye/wiki).  

* Kolektu la fontojn de _MotionEye.eo_ :


```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* komenci la instaladon:


```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ nun estas alirebla ĉe haveno 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( aŭ _http://IP_aŭ_nomo:8765/_ de alia stacio en la loka reto). La defaŭlta uzanto estas _«admin»_, sen pasvorto.


---
lang: en
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'Installation on _debian_'
---

This procedure has been tested on _Raspbian buster_, but must work on other distributions _debian_.

* If _motioneye_ is installed, uninstall it: refer to its [documentation](https://github.com/ccrisan/motioneye/wiki).  


* Collect the sources of _MotionEye.eo_ :



```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* start installation:



```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ is now accessible at port 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( or _http://IP_or_nomo:8765/_ from another station on the premises network). The default user is _«admin»_, without a password.


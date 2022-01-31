---
lang: en
lang-niv: homa
lang-ref: 010-instalado
layout: page
title: 'Installation on _debian_'
---

This procedure was tested in   _Raspbian bullseye_   and   _Debian bullseye_, but should work on other distributions based on   _debian_.  

* If _motioneye_ is installed, uninstall it: refer to its [documentation](https://github.com/ccrisan/motioneye/wiki).  


* Install recommended packages:  



```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

* Install   _MotionEye.eo_ :  



```bash
sudo pip install motioneye.eo
```

* launch the installation of dependencies and the initialization of the system:  



```bash
sudo motioneye_init
```

_Motioneye.eo_ is now accessible at port 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( or _http://IP_or_nomo:8765/_ from another station on the local network). The default user is _«admin»_, without a password.


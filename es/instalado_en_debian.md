---
lang: es
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'Instalación en _debian_'
---

Este procedimiento se probó en   _Raspbian bullseye_   y   _Debian bullseye_, pero debería trabajar en otras distribuciones basadas en   _debian_.  

* Si _motioneye_ está instalado, desinstálelo: consulte su documentación [](https://github.com/ccrisan/motioneye/wiki).  


* Instalar paquetes recomendados:  



```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

* Instalar   _MotionEye.eo_ :  



```bash
sudo pip install motioneye.eo
```

* Inicie la instalación de dependencias y la inicialización del sistema:  



```bash
sudo motioneye_init
```

_Motioneye.eo_ ahora es accesible en el puerto 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( o _http://IP_o_nomo:8765/_ desde otra estación en las instalaciones red). El usuario predeterminado es _«admin»_, sin contraseña.


---
lang: es
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'Instalación en _debian_'
---

Este procedimiento ha sido probado en _Raspbian buster_, pero debe funcionar en otras distribuciones _debian_.

* Si _motioneye_ está instalado, desinstálelo: consulte su documentación [](https://github.com/ccrisan/motioneye/wiki).  


* Recoger las fuentes de _MotionEye.eo_ :



```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* iniciar la instalación:



```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ ahora es accesible en el puerto 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( o _http://IP_o_nomo:8765/_ desde otra estación en las instalaciones red). El usuario predeterminado es _«admin»_, sin contraseña.


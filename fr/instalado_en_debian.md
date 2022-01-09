---
lang: fr
lang-niv: fonto
lang-ref: 010-instalado
layout: page
title: 'Installation sur _debian_'
---

Cette procédure a été testée sur _Raspbian bullseye_ et _Debian bullseye_, mais devrait fonctionner sur d'autres distributions basées sur _debian_.

* Si _motioneye_ est installé, désinstallez-le : reportez-vous à sa [documentation](https://github.com/ccrisan/motioneye/wiki).  
* Installez les paquets recommandés :

```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

* Installez _MotionEye.eo_ :

```bash
sudo pip install motioneye.eo
```

* lancez l'installation des dépendances et l'initialisation du sytème :

```bash
sudo motioneye_init
```

_Motioneye.eo_ est maintenant accessible sur le port 8765 : [ _http://localhost:8765/_ ](http://localhost:8765/) ( ou _http://IP_ou_nom:8765/_ depuis un autre poste du réseau local). L'utilisateur par défaut est _«admin»_, sans mot de passe.


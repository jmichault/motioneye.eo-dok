---
lang: fr
lang-niv: fonto
lang-ref: 010-instalado
layout: page
title: 'Installation sur _debian_'
---

Cette procédure a été testée sur _Raspbian buster_, mais devrait fonctionner sur d'autres distributions _debian_.

* Si _motioneye_ est installé, désinstallez-le : reportez-vous à sa [documentation](https://github.com/ccrisan/motioneye/wiki).  
* Récupérez les sources de _MotionEye.eo_ :

```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* lancez l'installation :

```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ est maintenant accessible sur le port 8765 : [ _http://localhost:8765/_ ](http://localhost:8765/) ( ou _http://IP_ou_nom:8765/_ depuis un autre poste du réseau local). L'utilisateur par défaut est _«admin»_, sans mot de passe.


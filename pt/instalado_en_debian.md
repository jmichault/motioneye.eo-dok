---
lang: pt
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'Instalação em _debian_'
---

Este procedimento foi testado em   _Raspbian bullseye_   e   _Debian bullseye_, mas deve funcionar em outras distribuições com base em   _debian_.  

* Se _motioneye_ estiver instalado, desinstale-o: consulte sua documentação [](https://github.com/ccrisan/motioneye/wiki).  


* Instalar pacotes recomendados:  



```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

* Instalar   _MotionEye.eo_ :  



```bash
sudo pip install motioneye.eo
```

* Lançar a instalação de dependências e a inicialização do sistema:  



```bash
sudo motioneye_init
```

_Motioneye.eo_ agora está acessível na porta 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( ou _http://IP_ou_nomo:8765/_ de outra estação nas instalações rede). O usuário padrão é _«admin»_, sem senha.


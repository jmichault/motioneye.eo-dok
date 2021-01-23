---
lang: pt
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'Instalação em _debian_'
---

Este procedimento foi testado em _Raspbian buster_, mas deve funcionar em outras distribuições _debian_.

* Se _motioneye_ estiver instalado, desinstale-o: consulte sua documentação [](https://github.com/ccrisan/motioneye/wiki).  


* Colete as fontes de _MotionEye.eo_ :



```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* iniciar a instalação:



```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ agora está acessível na porta 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( ou _http://IP_ou_nomo:8765/_ de outra estação nas instalações rede). O usuário padrão é _«admin»_, sem senha.


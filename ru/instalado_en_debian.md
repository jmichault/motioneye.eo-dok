---
lang: ru
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'Установка на _debian_'
---

Эта процедура была протестирована на _Raspbian buster_, но должна работать и на других дистрибутивах _debian_.

* Если установлен _motioneye_ , снимите его: обратитесь к документации [](https://github.com/ccrisan/motioneye/wiki).  


* Соберите источники _MotionEye.eo_ :



```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* начало установки:



```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ теперь доступен через порт 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( или _http://IP_или_nomo:8765/_ с другой станции в помещении сеть). Пользователь по умолчанию _«admin»_, без пароля.


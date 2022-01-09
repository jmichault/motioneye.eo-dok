---
lang: ru
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'Установка на _debian_'
---

Эта процедура была проверена в   _Raspbian bullseye_   и   _Debian bullseye_, но должна работать над другими распределениями на основе   _debian_.  

* Если установлен _motioneye_ , снимите его: обратитесь к документации [](https://github.com/ccrisan/motioneye/wiki).  


* Установите рекомендуемые пакеты:  



```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

* Установите   _MotionEye.eo_ :  



```bash
sudo pip install motioneye.eo
```

* Запустите установку зависимости и инициализации системы:  



```bash
sudo motioneye_init
```

_Motioneye.eo_ теперь доступен через порт 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( или _http://IP_или_nomo:8765/_ с другой станции в помещении сеть). Пользователь по умолчанию _«admin»_, без пароля.


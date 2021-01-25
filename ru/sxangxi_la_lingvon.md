---
lang: ru
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'Сменить язык'
---

Если вы хотите [ _Motioneye.eo_ ](https://github.com/jmichault/motioneye.eo) использовать язык, отличный от системы по умолчанию: измените файл _"/etc/systemd/system/motioneye.service"_ , добавив комментарий к строке _"#Environment=LANGUAGE=en"_ (, удалите _"#"_ ) и замените _"en"_ желаемым кодом языка.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


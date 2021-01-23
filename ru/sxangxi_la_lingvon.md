---
lang: ru
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'Сменить язык'
---

Если вы хотите, чтобы motioneye использовал язык, отличный от системы по умолчанию: измените файл _"/etc/systemd/system/motioneye.service"_ , не комментируя строку _"#Environment=LANGUAGE=en"_ (, удалите _"#"_ ) ) ) и замените _"en"_ желаемым кодом языка.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


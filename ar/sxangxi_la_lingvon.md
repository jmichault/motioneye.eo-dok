---
lang: ar
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'تغيير اللغة'
---

إذا كنت تريد [ _Motioneye.eo_ ](https://github.com/jmichault/motioneye.eo) استخدام لغة غير النظام الافتراضي: قم بتعديل الملف _"/etc/systemd/system/motioneye.service"_ بالتعليق على السطر _"#Environment=LANGUAGE=en"_ (قم بإزالة _"#"_ ) واستبدال _"en"_ برمز اللغة المطلوب.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


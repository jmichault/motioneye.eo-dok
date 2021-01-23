---
lang: ar
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'تغيير اللغة'
---

إذا كنت تريد أن تستخدم Motioneye لغة غير النظام الافتراضي: قم بتعديل الملف _"/etc/systemd/system/motioneye.service"_ من خلال عدم التعليق على السطر _"#Environment=LANGUAGE=en"_ (احذف _"#"_ ) ) ) واستبدل _"en"_ برمز اللغة المطلوب. (° 20 درجة)

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


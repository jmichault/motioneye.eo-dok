---
lang: ar
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: تحديث
---

افتح طرفًا على _raspberry_، وقم بتشغيل الأوامر التالية: 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(استبدل _motioneye.eo_ في السطر الأول بالمجلد الذي توجد به المصادر إذا لم تكن قد وضعتها مباشرة في دليل وظائف المستخدم).

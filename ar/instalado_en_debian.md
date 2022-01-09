---
lang: ar
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'التثبيت على _debian_'
---

تم اختبار هذا الإجراء في   _Raspbian bullseye_   و   _Debian bullseye_، ولكن يجب أن تعمل على توزيعات أخرى تستند إلى   _debian_.  

* إذا تم تثبيت _motioneye_ ، فقم بإلغاء تثبيته: ارجع إلى وثائقه [](https://github.com/ccrisan/motioneye/wiki).  


* تثبيت الحزم الموصى بها:  



```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

* تثبيت   _MotionEye.eo_ :  



```bash
sudo pip install motioneye.eo
```

* إطلاق تثبيت التداول وتهدف النظام:  



```bash
sudo motioneye_init
```

_Motioneye.eo_ يمكن الوصول إليها الآن في المنفذ 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( أو _http://IP_أو_nomo:8765/_ من محطة أخرى في المبنى الشبكة). المستخدم الافتراضي هو (14 درجة) بدون كلمة مرور.


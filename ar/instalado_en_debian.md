---
lang: ar
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'التثبيت على _debian_'
---

تم اختبار هذا الإجراء على _Raspbian buster_، ولكن يجب أن يعمل على توزيعات أخرى _debian_.

* إذا تم تثبيت _motioneye_ ، فقم بإلغاء تثبيته: ارجع إلى وثائقه [](https://github.com/ccrisan/motioneye/wiki).  


* اجمع مصادر _MotionEye.eo_ :



```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* بدء التثبيت:



```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ يمكن الوصول إليها الآن في المنفذ 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( أو _http://IP_أو_nomo:8765/_ من محطة أخرى في المبنى الشبكة). المستخدم الافتراضي هو (14 درجة) بدون كلمة مرور.


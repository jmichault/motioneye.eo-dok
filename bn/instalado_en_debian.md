---
lang: bn
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: ' _debian_এ ইনস্টলেশন'
---

এই পদ্ধতিটি   _Raspbian bullseye_   এবং   _Debian bullseye_ এ পরীক্ষিত হয়েছিল, তবে   _debian_ এর উপর ভিত্তি করে অন্যান্য বিতরণগুলিতে কাজ করা উচিত। . 

* যদি _motioneye_ ইনস্টল করা থাকে তবে এটি আনইনস্টল করুন: এর [ডকুমেন্টেশন](https://github.com/ccrisan/motioneye/wiki)দেখুন।  


* প্রস্তাবিত প্যাকেজ ইনস্টল করুন:  



```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

*   _MotionEye.eo_  ইনস্টল করুন:  



```bash
sudo pip install motioneye.eo
```

* নির্ভরতাগুলির ইনস্টলেশন এবং সিস্টেমের সূচনাটি চালু করুন:  



```bash
sudo motioneye_init
```

_Motioneye.eo_  এখন পোর্ট 8765 এ অ্যাক্সেসযোগ্য:  [  _http://localhost:8765/_  ](http://localhost:8765/)  (  বা _nomo:8765/_  স্থানীয় নেটওয়ার্কের অন্য স্টেশন )। ডিফল্ট ব্যবহারকারী  _«admin»_, পাসওয়ার্ড ছাড়া। .


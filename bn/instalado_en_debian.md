---
lang: bn
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: ' _debian_এ ইনস্টলেশন'
---

এই পদ্ধতিতে _Raspbian buster_পরীক্ষা করা হয়েছে, তবে অন্যান্য বিতরণে _debian_কাজ করতে হবে।

* যদি _motioneye_ ইনস্টল করা থাকে তবে এটি আনইনস্টল করুন: এর [ডকুমেন্টেশন](https://github.com/ccrisan/motioneye/wiki)দেখুন।  


*  _MotionEye.eo_ এর উত্স সংগ্রহ করুন:



```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* ইনস্টলেশন শুরু করুন:



```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ এখন পোর্ট 8765: (: 3 °)_http://localhost:8765/_ ](http://localhost:8765/) ( বা _http://IP_বা_nomo:8765/_ প্রাঙ্গনে অন্য স্টেশন থেকে অ্যাক্সেসযোগ্য নেটওয়ার্ক)। ডিফল্ট ব্যবহারকারী হ'ল _«admin»_, কোনও পাসওয়ার্ড ছাড়াই।


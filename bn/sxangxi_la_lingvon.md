---
lang: bn
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'ভাষা পরিবর্তন করুন'
---

আপনি যদি [ _Motioneye.eo_ ](https://github.com/jmichault/motioneye.eo) ডিফল্ট সিস্টেম ব্যতীত অন্য কোনও ভাষা ব্যবহার করতে চান: (° 10 () লাইনে মন্তব্য করে ফাইল (° 6 mod) পরিবর্তন করুন(মুছুন _"#"_ ) এবং পছন্দসই ভাষা কোডের সাথে (° 20।) প্রতিস্থাপন করুন।

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


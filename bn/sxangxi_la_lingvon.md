---
lang: bn
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'ভাষা পরিবর্তন করুন'
---

আপনি যদি মুটিয়ে ডিফল্ট সিস্টেম ছাড়া অন্য কোনও ভাষা ব্যবহার করতে চান: _"#Environment=LANGUAGE=en"_ লাইনে মন্তব্য না করে (the 9 °) ফাইলটি (mod 1 °) পরিবর্তন করুন _"#"_ ) ) মুছে দিন ) এবং পছন্দসই ভাষা কোড সহ (° 16।) প্রতিস্থাপন করুন।

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


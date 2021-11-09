---
lang: bn
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'ভাষা পরিবর্তন করুন'
---

যদি আপনি চান  [  _Motioneye.eo_  ](https://github.com/jmichault/motioneye.eo)  ডিফল্ট সিস্টেমের পাশাপাশি ভাষাটি ব্যবহার করুন:  _"#Environment=LANGUAGE=en"_  ( (  _"#"_  <H101 টি মুছে ফেলুন  _"#"_  )  এবং  _"en"_  এর সাথে প্রতিস্থাপন করুন পছন্দসই ভাষা কোডিং। .

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


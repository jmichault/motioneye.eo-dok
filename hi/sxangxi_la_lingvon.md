---
lang: hi
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'भाषा बदलें'
---

यदि आप डिफ़ॉल्ट सिस्टम के अलावा  [  _Motioneye.eo_  ](https://github.com/jmichault/motioneye.eo)  भाषा का उपयोग करना चाहते हैं:  _"#Environment=LANGUAGE=en"_  (  _"#"_  )  को हटाकर  _"#"_  )  को हटाकर और  _"en"_  को टिप्पणी करके  _"/etc/systemd/system/motioneye.service"_  फ़ाइल को संशोधित करें वांछित भाषा कोडिंग। 

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


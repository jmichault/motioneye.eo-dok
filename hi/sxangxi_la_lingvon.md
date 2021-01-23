---
lang: hi
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'भाषा बदलें'
---

यदि आप डिफ़ॉल्ट सिस्टम के अलावा किसी अन्य भाषा का उपयोग करने के लिए गति चाहते हैं: लाइन _"#Environment=LANGUAGE=en"_ (पर टिप्पणी न करके फ़ाइल _"/etc/systemd/system/motioneye.service"_ को संशोधित करें _"#"_ ) ) ) ) और वांछित भाषा कोड के साथ _"en"_ बदलें।

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


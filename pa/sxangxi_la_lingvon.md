---
lang: pa
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'ਭਾਸ਼ਾ ਬਦਲੋ'
---

ਜੇ ਤੁਸੀਂ ਡਿਵੈਲਪਮੈਂਟ ਸਿਸਟਮ ਤੋਂ ਇਲਾਵਾ ਕਿਸੇ ਹੋਰ ਭਾਸ਼ਾ ਦੀ ਵਰਤੋਂ ਕਰਨਾ ਚਾਹੁੰਦੇ ਹੋ: ਫਾਈਲ _"/etc/systemd/system/motioneye.service"_ 'ਤੇ ਟਿੱਪਣੀ ਨਾ ਕਰੋ _"#Environment=LANGUAGE=en"_ (ਮਿਟਾਓ _"#"_ ) ) ) ਅਤੇ _"en"_ ਨੂੰ ਲੋੜੀਂਦੇ ਭਾਸ਼ਾ ਕੋਡ ਨਾਲ ਬਦਲੋ.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


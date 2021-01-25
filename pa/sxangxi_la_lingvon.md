---
lang: pa
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'ਭਾਸ਼ਾ ਬਦਲੋ'
---

ਜੇ ਤੁਸੀਂ [ _Motioneye.eo_ ](https://github.com/jmichault/motioneye.eo) ਨੂੰ ਡਿਫਾਲਟ ਸਿਸਟਮ ਤੋਂ ਇਲਾਵਾ ਕਿਸੇ ਹੋਰ ਭਾਸ਼ਾ ਦੀ ਵਰਤੋਂ ਕਰਨਾ ਚਾਹੁੰਦੇ ਹੋ: ਫਾਈਲ ਨੂੰ ਸੋਧੋ _"/etc/systemd/system/motioneye.service"_ ਲਾਈਨ ਉੱਤੇ ਟਿੱਪਣੀ ਕਰਕੇ _"#Environment=LANGUAGE=en"_ (ਹਟਾਓ _"#"_ ) ਅਤੇ _"en"_ ਨੂੰ ਲੋੜੀਂਦੇ ਭਾਸ਼ਾ ਕੋਡ ਨਾਲ ਬਦਲੋ.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


---
lang: pa
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: ਅਪਡੇਟ
---

 _raspberry_'ਤੇ ਇੱਕ ਟਰਮੀਨਲ ਖੋਲ੍ਹੋ, ਅਤੇ ਹੇਠ ਦਿੱਤੀਆਂ ਕਮਾਂਡਾਂ ਚਲਾਓ: 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(ਫੋਲਡਰ ਦੇ ਨਾਲ ਪਹਿਲੀ ਲਾਈਨ ਤੇ _motioneye.eo_ ਬਦਲੋ ਜਿਸ ਵਿੱਚ ਸਰੋਤ ਸਥਿਤ ਹਨ ਜੇ ਤੁਸੀਂ ਉਨ੍ਹਾਂ ਨੂੰ ਸਿੱਧਾ ਆਪਣੇ ਉਪਭੋਗਤਾ ਦੀ ਫੰਕਸ਼ਨ ਡਾਇਰੈਕਟਰੀ ਵਿੱਚ ਨਹੀਂ ਰੱਖਿਆ ਹੈ).

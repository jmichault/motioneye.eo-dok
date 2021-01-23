---
lang: pa
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: ' _debian_ਤੇ ਸਥਾਪਨਾ'
---

ਇਸ ਪ੍ਰਕਿਰਿਆ ਦੀ ਜਾਂਚ _Raspbian buster_'ਤੇ ਕੀਤੀ ਗਈ ਹੈ, ਪਰ ਹੋਰ ਡਿਸਟਰੀਬਿ .ਸ਼ਨਾਂ _debian_' ਤੇ ਕੰਮ ਕਰਨਾ ਲਾਜ਼ਮੀ ਹੈ.

* ਜੇ _motioneye_ ਸਥਾਪਿਤ ਹੈ, ਤਾਂ ਇਸ ਨੂੰ ਅਣਇੰਸਟੌਲ ਕਰੋ: ਇਸਦੇ [ਡੌਕੂਮੈਂਟੇਸ਼ਨ](https://github.com/ccrisan/motioneye/wiki)ਵੇਖੋ.  


*  _MotionEye.eo_ ਦੇ ਸਰੋਤ ਇਕੱਤਰ ਕਰੋ:



```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* ਸਥਾਪਨਾ ਅਰੰਭ ਕਰੋ:



```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ ਹੁਣ ਪੋਰਟ 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( ਜਾਂ _http://IP_ਜਾਂ_nomo:8765/_ ਦੇ ਅਹਾਤੇ ਦੇ ਕਿਸੇ ਹੋਰ ਸਟੇਸ਼ਨ ਤੋਂ ਪਹੁੰਚਯੋਗ ਹੈ. ਨੈੱਟਵਰਕ). ਮੂਲ ਉਪਭੋਗਤਾ _«admin»_ਬਿਨਾਂ ਪਾਸਵਰਡ ਤੋਂ ਹੁੰਦਾ ਹੈ.


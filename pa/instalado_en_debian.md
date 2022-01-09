---
lang: pa
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: ' _debian_ਤੇ ਸਥਾਪਨਾ'
---

ਇਸ ਵਿਧੀ ਨੂੰ   _Raspbian bullseye_   ਅਤੇ   _Debian bullseye_ ਵਿੱਚ ਟੈਸਟ ਕੀਤਾ ਗਿਆ ਸੀ, ਪਰ   _debian_ ਦੇ ਅਧਾਰ ਤੇ ਹੋਰ ਡਿਸਟ੍ਰੀਬਿ .ਸ਼ਨਾਂ ਤੇ ਕੰਮ ਕਰਨਾ ਚਾਹੀਦਾ ਹੈ.  

* ਜੇ _motioneye_ ਸਥਾਪਿਤ ਹੈ, ਤਾਂ ਇਸ ਨੂੰ ਅਣਇੰਸਟੌਲ ਕਰੋ: ਇਸਦੇ [ਡੌਕੂਮੈਂਟੇਸ਼ਨ](https://github.com/ccrisan/motioneye/wiki)ਵੇਖੋ.  


* ਸਿਫਾਰਸ ਕੀਤੇ ਪੈਕੇਜ ਸਥਾਪਿਤ ਕਰੋ:  



```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

*   _MotionEye.eo_ :  ਸਥਾਪਤ ਕਰੋ 



```bash
sudo pip install motioneye.eo
```

* ਨਿਰਭਰਤਾ ਦੀ ਸਥਾਪਨਾ ਅਤੇ ਸਿਸਟਮ ਦੀ ਸ਼ੁਰੂਆਤ ਸ਼ੁਰੂ ਕਰੋ:  



```bash
sudo motioneye_init
```

_Motioneye.eo_ ਹੁਣ ਪੋਰਟ 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( ਜਾਂ _http://IP_ਜਾਂ_nomo:8765/_ ਦੇ ਅਹਾਤੇ ਦੇ ਕਿਸੇ ਹੋਰ ਸਟੇਸ਼ਨ ਤੋਂ ਪਹੁੰਚਯੋਗ ਹੈ. ਨੈੱਟਵਰਕ). ਮੂਲ ਉਪਭੋਗਤਾ _«admin»_ਬਿਨਾਂ ਪਾਸਵਰਡ ਤੋਂ ਹੁੰਦਾ ਹੈ.


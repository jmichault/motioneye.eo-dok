---
lang: hi
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'स्थापना _debian_'
---

इस प्रक्रिया का परीक्षण   _Raspbian bullseye_   और   _Debian bullseye_ में किया गया था, लेकिन   _debian_ के आधार पर अन्य वितरणों पर काम करना चाहिए।  

* यदि _motioneye_ स्थापित है, तो इसे अनइंस्टॉल करें: इसके [प्रलेखन](https://github.com/ccrisan/motioneye/wiki)देखें।  


* अनुशंसित पैकेज स्थापित करें:  



```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

*   _MotionEye.eo_ :  स्थापित करें 



```bash
sudo pip install motioneye.eo
```

* निर्भरता की स्थापना और प्रणाली की प्रारंभिकरण लॉन्च करें:  



```bash
sudo motioneye_init
```

_Motioneye.eo_ अब पोर्ट 8765 पर पहुँचा जा सकता है: [ _http://localhost:8765/_ ](http://localhost:8765/) ( या _http://IP_या_nomo:8765/_ परिसर के दूसरे स्टेशन से नेटवर्क)डिफ़ॉल्ट उपयोगकर्ता एक पासवर्ड के बिना _«admin»_है।


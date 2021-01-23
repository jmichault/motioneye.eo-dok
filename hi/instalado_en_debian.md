---
lang: hi
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'स्थापना _debian_'
---

इस प्रक्रिया को _Raspbian buster_पर परीक्षण किया गया है, लेकिन अन्य वितरण _debian_पर काम करना चाहिए।

* यदि _motioneye_ स्थापित है, तो इसे अनइंस्टॉल करें: इसके [प्रलेखन](https://github.com/ccrisan/motioneye/wiki)देखें।  


*  _MotionEye.eo_ के स्रोतों को एकत्र करें:



```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* स्थापना प्रारंभ करें:



```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ अब पोर्ट 8765 पर पहुँचा जा सकता है: [ _http://localhost:8765/_ ](http://localhost:8765/) ( या _http://IP_या_nomo:8765/_ परिसर के दूसरे स्टेशन से नेटवर्क)डिफ़ॉल्ट उपयोगकर्ता एक पासवर्ड के बिना _«admin»_है।


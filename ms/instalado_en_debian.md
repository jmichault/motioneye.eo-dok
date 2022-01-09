---
lang: ms
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'Pemasangan pada _debian_'
---

Prosedur ini diuji dalam   _Raspbian bullseye_   dan   _Debian bullseye_, tetapi harus bekerja pada pengagihan lain berdasarkan   _debian_.  

* Sekiranya _motioneye_ dipasang, nyahpasangnya: rujuk dokumentasi [](https://github.com/ccrisan/motioneye/wiki).  


* Pasang pakej yang disyorkan:  



```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

* Pasang   _MotionEye.eo_ :  



```bash
sudo pip install motioneye.eo
```

* Lancarkan pemasangan pergantungan dan inisialisasi sistem:  



```bash
sudo motioneye_init
```

_Motioneye.eo_ kini boleh diakses di pelabuhan 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( atau _http://IP_atau_nomo:8765/_ dari stesen lain di premis rangkaian). Pengguna lalai adalah _«admin»_, tanpa kata laluan.


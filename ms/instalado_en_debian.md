---
lang: ms
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: 'Pemasangan pada _debian_'
---

Prosedur ini telah diuji pada _Raspbian buster_, tetapi mesti dilakukan pada pengedaran lain _debian_.

* Sekiranya _motioneye_ dipasang, nyahpasangnya: rujuk dokumentasi [](https://github.com/ccrisan/motioneye/wiki).  


* Kumpulkan sumber _MotionEye.eo_ :



```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* mulakan pemasangan:



```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ kini boleh diakses di pelabuhan 8765: [ _http://localhost:8765/_ ](http://localhost:8765/) ( atau _http://IP_atau_nomo:8765/_ dari stesen lain di premis rangkaian). Pengguna lalai adalah _«admin»_, tanpa kata laluan.


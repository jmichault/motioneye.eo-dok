---
lang: zh
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: '安装在 _debian_'
---

此过程已在 _Raspbian buster_上进行了测试，但必须在其他分布 _debian_上进行。

* 如果已安装 _motioneye_ ，则将其卸载：请参阅其 [文档](https://github.com/ccrisan/motioneye/wiki)。  


* 收集 _MotionEye.eo_ ：的来源



```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* 开始安装：



```bash
cd motioneye.eo
sudo ./debian_install
```

现在可以在端口8765上访问_Motioneye.eo_ ： [ _http://localhost:8765/_ ](http://localhost:8765/) ( 或 _http://IP_或_nomo:8765/_ 网络)。默认用户是 _«admin»_，没有密码。


---
lang: zh
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: '安装在 _debian_'
---

该过程在  _Raspbian bullseye_  和  _Debian bullseye_中进行了测试，但应基于  _debian_的其他分布工作。  

* 如果已安装 _motioneye_ ，则将其卸载：请参阅其 [文档](https://github.com/ccrisan/motioneye/wiki)。  


* 安装推荐软件包： 



```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

* 安装  _MotionEye.eo_ ： 



```bash
sudo pip install motioneye.eo
```

* 启动依赖的安装和系统的初始化： 



```bash
sudo motioneye_init
```

现在可以在端口8765上访问_Motioneye.eo_ ： [ _http://localhost:8765/_ ](http://localhost:8765/) ( 或 _http://IP_或_nomo:8765/_ 网络)。默认用户是 _«admin»_，没有密码。


---
lang: ja
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: ' _debian_への取り付け'
---

この手順は  _Raspbian bullseye_  および  _Debian bullseye_で試験したが、  _debian_に基づく他の分布で作業するべきである。  

*  _motioneye_ がインストールされている場合は、アンインストールします。 [のドキュメント](https://github.com/ccrisan/motioneye/wiki)を参照してください。  


* 推奨パッケージをインストールします。 



```
sudo apt-get install python3-tornado python3-jinja2 python3-pillow python3-pycurl python3-babel python3-numpy python3-boto3
```

*   _MotionEye.eo_ ：をインストールしてください 



```bash
sudo pip install motioneye.eo
```

* 依存関係のインストールとシステムの初期化を起動します。 



```bash
sudo motioneye_init
```

_Motioneye.eo_ はポート8765でアクセス可能になりました： [ _http://localhost:8765/_ ](http://localhost:8765/) ( または _http://IP_または_nomo:8765/_ 敷地内の別のステーションからネットワーク)。デフォルトのユーザーは _«admin»_で、パスワードはありません。


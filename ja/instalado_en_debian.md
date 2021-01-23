---
lang: ja
lang-niv: auto
lang-ref: 010-instalado
layout: page
title: ' _debian_への取り付け'
---

この手順は _Raspbian buster_でテストされていますが、他の分布 _debian_でも機能する必要があります。

*  _motioneye_ がインストールされている場合は、アンインストールします。 [のドキュメント](https://github.com/ccrisan/motioneye/wiki)を参照してください。  


*  _MotionEye.eo_ のソースを収集します：



```bash
git clone https://github.com/jmichault/motioneye.eo.git
```

* インストール開始：



```bash
cd motioneye.eo
sudo ./debian_install
```

_Motioneye.eo_ はポート8765でアクセス可能になりました： [ _http://localhost:8765/_ ](http://localhost:8765/) ( または _http://IP_または_nomo:8765/_ 敷地内の別のステーションからネットワーク)。デフォルトのユーザーは _«admin»_で、パスワードはありません。


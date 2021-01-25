---
lang: ja
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 言語を変更する
---

 [ _Motioneye.eo_ ](https://github.com/jmichault/motioneye.eo) でデフォルトシステム以外の言語を使用する場合：行 _"#Environment=LANGUAGE=en"_ (にコメントを付けてファイル _"/etc/systemd/system/motioneye.service"_ を変更します。 _"#"_ ) そして _"en"_ を希望の言語コードに置き換えます。

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


---
lang: ja
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 言語を変更する
---

モーションアイでデフォルトシステム以外の言語を使用する場合：行 _"#Environment=LANGUAGE=en"_ (にコメントを付けずにファイル _"/etc/systemd/system/motioneye.service"_ を変更します _"#"_ ) ) を削除します）そして _"en"_ を希望の言語コードに置き換えます。

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


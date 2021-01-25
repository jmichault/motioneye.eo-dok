---
lang: en
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'Change the language'
---

If you want [ _Motioneye.eo_ ](https://github.com/jmichault/motioneye.eo) to use a language other than the default system: modify the file _"/etc/systemd/system/motioneye.service"_ by commenting on the line _"#Environment=LANGUAGE=en"_ (delete the _"#"_ ) and replace _"en"_ with the desired language code.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


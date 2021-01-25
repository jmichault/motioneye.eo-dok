---
lang: it
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'Cambia la lingua'
---

Se si desidera [ _Motioneye.eo_ ](https://github.com/jmichault/motioneye.eo) utilizzare una lingua diversa da quella di default: modificare il file _"/etc/systemd/system/motioneye.service"_ commentando la riga _"#Environment=LANGUAGE=en"_ (eliminare il _"#"_ ) e sostituire _"en"_ con il codice lingua desiderato.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


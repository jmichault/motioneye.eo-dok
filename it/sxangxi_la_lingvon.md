---
lang: it
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'Cambia la lingua'
---

Se vuoi che motioneye utilizzi una lingua diversa dal sistema di default: modifica il file _"/etc/systemd/system/motioneye.service"_ non commentando la riga _"#Environment=LANGUAGE=en"_ (cancella il _"#"_ ) ) ) e sostituire _"en"_ con il codice lingua desiderato.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


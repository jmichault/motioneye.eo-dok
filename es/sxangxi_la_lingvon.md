---
lang: es
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'Cambia el idioma'
---

Si desea que [ _Motioneye.eo_ ](https://github.com/jmichault/motioneye.eo) utilice un idioma que no sea el sistema predeterminado: modifique el archivo _"/etc/systemd/system/motioneye.service"_ comentando en la línea _"#Environment=LANGUAGE=en"_ (elimine el _"#"_ ) y reemplace _"en"_ con el código de idioma deseado.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


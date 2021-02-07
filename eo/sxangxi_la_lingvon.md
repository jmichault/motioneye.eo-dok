---
lang: eo
lang-niv: homa
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'Ŝanĝi la lingvon'
---

Se vi volas ke [ _Motioneye.eo_ ](https://github.com/jmichault/motioneye.eo) uzas lingvon krom la defaŭltosistemo: modifu la dosieron _"/etc/systemd/system/motioneye.service"_ per komentado de la linio _"#Environment=LANGUAGE=en"_ (forigu la _"#"_ ) kaj anstataŭigu _"en"_ kun la dezirata lingvokodo.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


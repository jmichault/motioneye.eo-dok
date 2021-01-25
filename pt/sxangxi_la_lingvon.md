---
lang: pt
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'Alterar o idioma'
---

Se você deseja [ _Motioneye.eo_ ](https://github.com/jmichault/motioneye.eo) para usar um idioma diferente do sistema padrão: modifique o arquivo _"/etc/systemd/system/motioneye.service"_ comentando na linha _"#Environment=LANGUAGE=en"_ (remova o _"#"_ ) e substitua _"en"_ pelo código de idioma desejado.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


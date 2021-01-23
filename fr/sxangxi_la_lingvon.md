---
lang: fr
lang-niv: fonto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'Changer la langue'
---

Si vous souhaitez que motioneye utilise une langue autre que la langue par défaut du système : modifiez le fichier _"/etc/systemd/system/motioneye.service"_ en décommentant la ligne _"#Environment=LANGUAGE=en"_ (supprimez le _"#"_ ) et remplacez _"en"_ par le code de la langue désirée.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


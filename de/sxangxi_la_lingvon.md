---
lang: de
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'Ändere die Sprache'
---

Wenn Sie möchten, dass [ _Motioneye.eo_ ](https://github.com/jmichault/motioneye.eo) eine andere Sprache als das Standardsystem verwendet: Ändern Sie die Datei _"/etc/systemd/system/motioneye.service"_ , indem Sie die Zeile _"#Environment=LANGUAGE=en"_ (kommentieren _"#"_ ) und ersetzen Sie _"en"_ durch den gewünschten Sprachcode.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


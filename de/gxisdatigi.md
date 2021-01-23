---
lang: de
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: Aktualisieren
---

Öffnen Sie ein Terminal auf _raspberry_und führen Sie die folgenden Befehle aus: 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(Ersetzen Sie _motioneye.eo_ in der ersten Zeile durch den Ordner, in dem sich die Quellen befinden, wenn Sie sie nicht direkt im Funktionsverzeichnis Ihres Benutzers abgelegt haben).

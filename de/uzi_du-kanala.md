---
lang: de
lang-niv: auto
lang-ref: 040-uzi_du-kanala
layout: page
title: 'Verwenden Sie eine Zweikanal-Kamera'
---

IP-Kameras haben oft zwei Kanäle:

* der erste in hoher Auflösung.


* die zweite in niedriger Auflösung.



Die niedrige Auflösung reicht aus, um Bewegungen zu erkennen. Dies ist also genau der Kanal, den wir verwenden werden.

Andererseits ist es vorzuziehen, dass die aufgenommenen Videos eine hohe Auflösung haben. Dies wird in der Einstellung _motion_ (  _netcam hires_)vorhergesagt, jedoch nicht in der Einstellung _motioneye.eo_ .  
Motioneye.eo stellte jedoch die Box "zur Verfügung. Zusätzliche Optionen"für diesen Fall.

Für diesen Kameratyp setzen wir den Kanal mit niedriger Auflösung in die Option "Peripherie", z. B. `rtsp://utilisateur:mot_de_passe@192.168.1.10/stream2`, und in die Box "Optionen"der hohe Unterscheidungskanal, zum Beispiel:
```
netcam_highres rtsp://uzanto:pasvorto@192.168.1.10/stream1
```

Dies spart Prozessorzeit und enthält so viele Details wie möglich zu den aufgenommenen Videos.

Hinweis: Leider plant _motion_ nicht, den hochauflösenden Stream für die aufgenommenen Bilder zu verwenden. Diese werden daher in niedriger Auflösung sein.

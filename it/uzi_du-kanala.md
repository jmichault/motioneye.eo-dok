---
lang: it
lang-niv: auto
lang-ref: 040-uzi_du-kanala
layout: page
title: 'Usa una fotocamera a doppio canale'
---

Le telecamere IP hanno spesso due canali:

* il primo in alta risoluzione.


* il secondo in bassa risoluzione.



La bassa risoluzione è sufficiente per rilevare i movimenti, quindi questo è esattamente il canale che useremo.

D'altra parte, è preferibile che i video registrati siano in alta risoluzione. Ciò è previsto nell'impostazione _motion_ (  _netcam hires_), ma non in _motioneye.eo_ .  
Tuttavia motioneye.eo ha fornito la casella "Opzioni aggiuntive"per questo caso.

Quindi per questo tipo di telecamera, metteremo il canale a bassa risoluzione nell'opzione "Periferica", ad esempio `rtsp://utilisateur:mot_de_passe@192.168.1.10/stream2`, e metteremo nella casella "Aggiuntivo opzioni"il canale ad alta distinzione, ad esempio:
```
netcam_highres rtsp://uzanto:pasvorto@192.168.1.10/stream1
```

Ciò farà risparmiare tempo al processore, avendo quanti più dettagli possibili sui video registrati.

Nota: purtroppo _motion_ non prevede di utilizzare lo stream ad alta definizione per le immagini registrate. Questi saranno quindi a bassa risoluzione.

---
lang: es
lang-niv: auto
lang-ref: 040-uzi_du-kanala
layout: page
title: 'Utilice una cámara de dos canales'
---

Las cámaras IP suelen tener dos canales:

* el primero en alta resolución.


* el segundo en baja resolución.



La baja resolución es suficiente para detectar movimientos, por lo que este es exactamente el canal que usaremos.

Por otro lado, es preferible que los videos grabados estén en alta resolución. Esto se predice en _motion_ ( ajuste _netcam hires_), pero no en _motioneye.eo_ .  
Sin embargo, motioneye.eo proporcionó el recuadro "Opciones adicionales"para este caso.

Entonces para este tipo de cámara, pondremos el canal de baja resolución en la opción "Periférico", por ejemplo `rtsp://utilisateur:mot_de_passe@192.168.1.10/stream2`, y pondremos en la casilla "Adicional opciones"el canal de alta distinción, por ejemplo:
```
netcam_highres rtsp://uzanto:pasvorto@192.168.1.10/stream1
```

Esto ahorrará tiempo de procesador, teniendo tantos detalles como sea posible sobre los videos grabados.

Nota: desafortunadamente _motion_ no planea usar la transmisión de alta definición para las imágenes grabadas. Por tanto, estos estarán en baja resolución.

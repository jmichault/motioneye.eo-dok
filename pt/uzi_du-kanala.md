---
lang: pt
lang-niv: auto
lang-ref: 040-uzi_du-kanala
layout: page
title: 'Use uma câmera dual-channel'
---

As câmeras IP geralmente têm dois canais:

* o primeiro em alta resolução.


* o segundo em baixa resolução.



A baixa resolução é suficiente para detectar movimentos, então este é exatamente o canal que usaremos.

Por outro lado, é preferível que os vídeos gravados sejam em alta resolução. Isso é previsto na configuração _motion_ (  _netcam hires_), mas não em _motioneye.eo_ .  
No entanto, a motioneye.eo forneceu a caixa "Opções adicionais"para este caso.

Então para este tipo de câmera, colocaremos o canal de baixa resolução na opção "Periférico", por exemplo `rtsp://utilisateur:mot_de_passe@192.168.1.10/stream2`, e colocaremos na caixa "Adicional opções"o canal de alta diferenciação, por exemplo:
```
netcam_highres rtsp://uzanto:pasvorto@192.168.1.10/stream1
```

Isso vai economizar tempo do processador, tendo o máximo de detalhes possível sobre os vídeos gravados.

Nota: infelizmente _motion_ não planeja usar o fluxo de alta definição para as imagens gravadas. Eles estarão, portanto, em baixa resolução.

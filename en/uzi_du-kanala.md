---
lang: en
lang-niv: auto
lang-ref: 040-uzi_du-kanala
layout: page
title: 'Use a dual-channel camera'
---

IP cameras often have two channels:

* the first in high resolution.


* the second in low resolution.



The low resolution is sufficient to detect movements, so this is exactly the channel we will use.

On the other hand, it is preferable that the recorded videos are in high resolution. This is predicted in _motion_ ( setting _netcam hires_), but not in _motioneye.eo_ .  
However motioneye.eo provided the box "Additional options"for this case.

So for this type of camera, we will put the low resolution channel in the "Peripheral"option, for example `rtsp://utilisateur:mot_de_passe@192.168.1.10/stream2`, and we will put in the box "Additional options"the high distinguishing channel, for example:
```
netcam_highres rtsp://uzanto:pasvorto@192.168.1.10/stream1
```

This will save processor time, having as much detail as possible about the recorded videos.

Note: unfortunately _motion_ does not plan to use the high definition stream for the recorded images. These will therefore be in low resolution.

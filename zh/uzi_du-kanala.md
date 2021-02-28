---
lang: zh
lang-niv: auto
lang-ref: 040-uzi_du-kanala
layout: page
title: 使用双通道相机
---

IP摄像机通常具有两个通道：

* 高分辨率的第一款。


* 低分辨率的第二个。



低分辨率足以检测运动，因此这正是我们将使用的通道。

另一方面，优选地，所记录的视频是高分辨率的。这是在 _motion_ ( 设置 _netcam hires_)中预测的，但不是在 _motioneye.eo_ 中预测的。  
但是，motioneye.eo提供了此框 "的其他选项"。

因此，对于这种类型的相机，我们将低分辨率通道置于 "外围"选项中，例如 `rtsp://utilisateur:mot_de_passe@192.168.1.10/stream2`，然后将其放入框 "中。选项"高分辨通道，例如：
```
netcam_highres rtsp://uzanto:pasvorto@192.168.1.10/stream1
```

这样可以节省处理器时间，并尽可能多地记录有关视频的信息。

注意：不幸的是 _motion_ 并不打算将高清流用于录制的图像。因此，这些将处于低分辨率状态。

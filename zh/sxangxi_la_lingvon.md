---
lang: zh
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 改变语言
---

如果您想让MotionEye使用默认系统以外的语言：通过不注释行 _"#Environment=LANGUAGE=en"_ (来修改文件 _"/etc/systemd/system/motioneye.service"_ ，删除 _"#"_ ) ) ）并用所需的语言代码替换 _"en"_ 。

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


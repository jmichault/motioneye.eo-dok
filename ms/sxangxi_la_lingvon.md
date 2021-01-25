---
lang: ms
lang-niv: auto
lang-ref: 020-sxangxi_la_lingvon
layout: page
title: 'Tukar bahasa'
---

Sekiranya anda ingin [ _Motioneye.eo_ ](https://github.com/jmichault/motioneye.eo) menggunakan bahasa selain sistem lalai: ubah fail _"/etc/systemd/system/motioneye.service"_ dengan memberi komen pada baris _"#Environment=LANGUAGE=en"_ (hapus _"#"_ ) dan ganti _"en"_ dengan kod bahasa yang dikehendaki.

```bash
    sudo nano /etc/systemd/system/motioneye.service
    sudo systemctl daemon-reload
    sudo systemctl restart motioneye
```


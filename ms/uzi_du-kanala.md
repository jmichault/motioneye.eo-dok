---
lang: ms
lang-niv: auto
lang-ref: 040-uzi_du-kanala
layout: page
title: 'Gunakan kamera dwi-saluran'
---

Kamera IP sering mempunyai dua saluran:

* yang pertama dalam resolusi tinggi.


* yang kedua dalam resolusi rendah.



Resolusi rendah cukup untuk mengesan pergerakan, jadi inilah saluran yang akan kita gunakan.

Sebaliknya, lebih baik video yang dirakam beresolusi tinggi. Ini diramalkan dalam tetapan _motion_ (  _netcam hires_), tetapi tidak di _motioneye.eo_ .  
Namun motioneye.eo memberikan kotak "Pilihan tambahan"untuk kes ini.

Jadi untuk kamera jenis ini, kami akan meletakkan saluran resolusi rendah pada pilihan "Periferal", misalnya `rtsp://utilisateur:mot_de_passe@192.168.1.10/stream2`, dan kami akan memasukkannya ke dalam kotak "Tambahan pilihan"saluran pembezaan tinggi, misalnya:
```
netcam_highres rtsp://uzanto:pasvorto@192.168.1.10/stream1
```

Ini akan menjimatkan masa pemproses, dengan perincian sebanyak mungkin mengenai video yang dirakam.

Nota: malangnya _motion_ tidak merancang untuk menggunakan aliran definisi tinggi untuk gambar yang dirakam. Oleh itu, ini dalam resolusi rendah.

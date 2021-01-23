---
lang: hi
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: 'अपडेट करें'
---

 _raspberry_पर एक टर्मिनल खोलें, और निम्नलिखित कमांड चलाएं: 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(फ़ोल्डर के साथ पहली पंक्ति पर _motioneye.eo_ बदलें जिसमें स्रोत स्थित हैं यदि आपने उन्हें सीधे अपने उपयोगकर्ता के कार्य निर्देशिका)में नहीं रखा है।

---
lang: ja
lang-niv: auto
lang-ref: 030-gxisdatigi
layout: page
title: 更新
---

 _raspberry_でターミナルを開き、次のコマンドを実行します： 

```bash
    cd motioneye.eo
    git pull
    sudo systemctl stop motioneye
    sudo pip3 install .
    sudo systemctl start motioneye
```
(最初の行の _motioneye.eo_ を、ソースをユーザーの機能ディレクトリ)に直接配置していない場合は、ソースが配置されているフォルダーに置き換えます。

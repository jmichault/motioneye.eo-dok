---
lang: fr
lang-niv: fonto
lang-ref: 000-indekso
layout: page
title: ' _Motioneye.eo_ '
---
# Qu'est-ce que [ _MotionEye.eo_ ](https://github.com/jmichault/motioneye.eo) ?

[ _motionEye.eo_ ](https://github.com/jmichault/motioneye.eo) est une interface web pour le logiciel [ _motion_ ](https://motion-project.github.io/), un programme de vidéo-surveillance avec détection de mouvements.

C'est une bifurcation de [ _motionEye_ ](https://github.com/ccrisan/motioneye) avec l'ajout de l'internationalisation.  
Il utilise python3, et fonctionne donc aussi bien sous _debian buster_ que sous _debian bullseye_.  
Les langues prises en charge sont : 

* le français
* l'espéranto
* l'anglais

Les langues suivantes ont été traduites par une traduction automatique et ont besoin d'être corrigées :

* arabe ( _العربية_ )
* bengali ( _বাংলা _ )
* allemand ( _Deutsch_ )
* espagnol ( _Español_ )
* hindi ( _हिन्दी _ )
* italien ( _Italiano_ )
* japonais ( _日本語_ )
* malais ( _بهاس ملايو_ )
* pendjabi ( _ਪੰਜਾਬੀ _ )
* portugais ( _Português_ )
* russe ( _русский язык_ )
* chinois ( _中文_ )


# Les principaux changements depuis la bifurcation sont :

* 20220215 : version 22.2.1 :
  * correction du transfert sftp
* 20220109 : version 22.1.5 :
  * **correction de la gestion des caméras v4l**
  * **diffusion sur pypi.org**
  * installation simplifiée
* 20210207 : version 21.02.2 :
  * mise en mode _async_ de certains javascripts pour la performance. (merci [ _ZeroDot1_ ]( https://github.com/ZeroDot1 ) ).
  * incorporation des changements de _motioneye_.
* 20210115 : version 21.01.1 :
  * **ajout d'un bouton pour lire les vidéos du jour en accéléré et à la suite.** (merci [ _Lu-Fi_ ](https://github.com/Lu-Fi) ).
  * incorporation des changements de _motioneye_.
* 20201214 : version 20.12.1 :
  * **migration vers _python3_** (merci [ _Vlsarro_ ](https://github.com/Vlsarro) ).
  * incorporation des changements de _motioneye_.
* 20201008 : version 20.10.0 :
  * **ajout du script _debian install_ pour faciliter l'installation.**
  * incorporation des changements de _motioneye_.
* 20200815 : version 20.8.0 :
  * **multilangage.**
  * _motioneye_ exécuté par l'utilisateur _motion_ par défaut (au lieu de _root_).
  * incorporation des changements de _motioneye_.
* 20200704 : bifurcation.


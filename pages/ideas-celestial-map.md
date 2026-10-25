---
layout: default
title: Bleu Fragile - Idées pour la carte des objets célestes 
permalink: /ideas-celestial-map/
description: Page du jeu Bleu Fragile
---
- Carte du système composée de noeuds reliés par des arcs (graphe)
- Chaque arc entre deux noeuds a un coût de traversée (en deltaV, pas forcément symétrique) et un temps de traversée.
- Les noeuds de la carte sont les corps célestes, ou les orbites à différentes altitudes (orbite basse, géostationnaire, etc) de ceux ci.
- Arcs entre les noeuds:
  - Le coût de déplacement est en dV (variation de vitesse).
  - parent vers orbite (décollage/atterissage) non symétrique (si atmosphère *k /k pour représenter l'effet négatif de l'atmosphère au décollage et positif à l'atterrissage)
  - valeurs de deltav prise ici ou calculées via les méthodes
    - [http://www.projectrho.com/public_html/rocket/images/spacemaps/HeikkiMalkkiDVMap.png](http://www.projectrho.com/public_html/rocket/images/spacemaps/HeikkiMalkkiDVMap.png)
    - [https://i.redd.it/0wm696pd0a741.png](https://i.redd.it/0wm696pd0a741.png)
    - [https://external-preview.redd.it/U5iH7huE5qKth7ZFvipXt8vzaFOO99qHFh9o9_SkLLk.png?auto=webp&s=d145ac9ae496abe35fae86fc11a584d62fe42592](https://external-preview.redd.it/U5iH7huE5qKth7ZFvipXt8vzaFOO99qHFh9o9_SkLLk.png?auto=webp&s=d145ac9ae496abe35fae86fc11a584d62fe42592)
    - [https://external-preview.redd.it/4O-OVVrsFb-opHZ_5l0eK2MRBPU3MxILIWBCU8rboDI.png?auto=webp&s=bac57b6c80469a17500e3382584c3fafc169d695](https://external-preview.redd.it/4O-OVVrsFb-opHZ_5l0eK2MRBPU3MxILIWBCU8rboDI.png?auto=webp&s=bac57b6c80469a17500e3382584c3fafc169d695)
    - via le nombre de burn de la carte de High Frontier ?
  - valeurs de temps proportionnelles au dV
    - Ou bien fixées ?
    - Ou bien en fonction du nombre de burn gratuit sur High Frontier



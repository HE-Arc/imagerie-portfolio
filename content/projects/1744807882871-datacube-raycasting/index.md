---
title: "Datacube Raycasting In Jupyter Notebook"
date: 2021-05-01
draft: false
description: "Ce projet consiste à visualiser en temps réel, dans un canevas HTML, des matrices de données,
appelé Datacube, issues de l’observation terrestre.
"
tags: ["Travail de Bachelor", "3ème année", "Visualisation 3D"]
authors : ['Antoine Lestrade']
showSummary: true
---

## Description

Ce projet consiste à visualiser en temps réel, dans un canevas HTML, des matrices de données,
appelé Datacube, issues de l’observation terrestre.

Le programme est développé en JavaScript et utilise l’API graphique WebGL.
Le rendu de ces Datacube est réalisé grâce un algorithme de Raycasting amélioré.
Les dimensions de Datacube supportées sont 16<sup>3</sup>, 64<sup>3</sup>, 256<sup>3</sup> et 1024<sup>3</sup>.

Le programme dispose de trois modes de rendu de volume :

* Un premier rendu, appelé X-Ray pour les Datacube XYZ.
* Un deuxième rendu simulant les surfaces implicite pour les Datacube XYZ.
* Un troisième rendu, appelé Dérivé, pour les Datacube XY avec une dimension de temps.

Tous les algorithmes sont intégrés dans un notebook Jupyter.

## Images

{{< gallery >}}
<img src="gallery/img1.jpeg" class="grid-w50 md:grid-w33 xl:grid-w25" />
<img src="gallery/img2.png" class="grid-w50 md:grid-w33 xl:grid-w25" />
<img src="gallery/img3.png" class="grid-w50 md:grid-w33 xl:grid-w25" />
<img src="gallery/img4.png" class="grid-w50 md:grid-w33 xl:grid-w25" />
{{< /gallery >}}

## Vidéos
{{< youtubeLite id="vNDo0Q4X0m8" label="DataCube Raycasting Demo" >}}

## Liens
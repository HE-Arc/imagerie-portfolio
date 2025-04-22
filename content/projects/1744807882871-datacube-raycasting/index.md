---
title: "Datacube Raycasting In Jupyter Notebook (2021)"
date: 2021-05-01
draft: false
description: "Ce projet consiste à visualiser en temps réel, dans un canevas HTML, des matrices de données,
appelé Datacube, issues de l’observation terrestre."
summary: "Visualisation volumétrique en temps réel de Datacubes issues de satellites"
tags: ["3ème année", "Travail de Bachelor",  "Visualisation 3D"]
authors : ['Antoine Lestrade']
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
* Lestrade, A. et al. (2023). Real-Time Renderings of Multidimensional Massive DataCubes on Jupyter Notebook. In: Cheng, LY. (eds) ICGG 2022 - Proceedings of the 20th International Conference on Geometry and Graphics. ICGG 2022. Lecture Notes on Data Engineering and Communications Technologies, vol 146. Springer, Cham. https://doi.org/10.1007/978-3-031-13588-0_59
* Muller, C., Lestrade, A., Marty, M., Sadiku, A., Neijt, J., Voumard, Y., and Gobron, S.: EARTH OBSERVATION DATACUBES MULTI-VISUALIZATION TOOLBOX, Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci., XLVIII-4/W1-2022, 321–328, https://doi.org/10.5194/isprs-archives-XLVIII-4-W1-2022-321-2022, 2022.
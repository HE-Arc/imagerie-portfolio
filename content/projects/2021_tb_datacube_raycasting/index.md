---
title: "Datacube Raycasting In Jupyter Notebook (2021)"
date: 2021-05-01
draft: false
description: "Ce projet consiste à visualiser en temps réel, dans un canevas HTML, des matrices de données,
appelé Datacube, issues de l’observation terrestre."
summary: "Visualisation volumétrique en temps réel de Datacubes issues de satellites"
tags: ["3ème année", "Travail de Bachelor",  "Visualisation 3D", "WebGL"]
authors : ['Antoine Lestrade']
---

{{% columns ratio="3:1" class="space-x-4" %}} <!-- begin columns block -->

Ce projet visualise en temps réel des matrices de données 3D (Datacube) d'observation terrestre dans un canevas HTML.
Développé en JavaScript avec WebGL, il utilise un algorithme de Raycasting amélioré pour le rendu volumétrique des Datacubes. 
Les Datacubes peuvent être de dimensions 16<sup>3</sup>, 64<sup>3</sup>, 256<sup>3</sup> et 1024<sup>3</sup>.
Le programme propose trois modes de rendu : X-Ray pour les Datacubes XYZ, surfaces implicites pour les Datacubes XYZ, et dérivé pour les Datacubes XY temporel.
Les algorithmes sont intégrés et utilisable dans des notebook Jupyter.

{{< youtubeLite id="vNDo0Q4X0m8" label="DataCube Raycasting Demo" >}}

<---> <!-- magic separator, between columns -->

<div class="[&>figure]:my-4">
{{< figure
src="gallery/img1.jpeg"
>}}

{{< figure
src="gallery/img2.png"
>}}

{{< figure
src="gallery/img3.png"
>}}

{{< figure
src="gallery/img4.png"
>}}
</div>

{{% /columns %}}

{{< description TB >}}

---
title: "Génération d’images par Ray Marching (2024)"
date: 2024-04-22
draft: false
description: "Génération d’images en utilisant l’algorithme ray marching"
summary: "Génération d’images en utilisant l’algorithme ray marching"
tags: ["2ème année", "Cours Algorithmes 3", "3D", "Visualisation"]
authors : ['Léon Metthez', "Isaac Metthez", "Sevan Yerly"]
---

{{% columns ratio="3:1" class="space-x-4" %}} <!-- begin columns block -->

Le but de ce projet est de réaliser un moteur de génération d’images en utilisant l’algorithme [ray marching](https://en.wikipedia.org/wiki/Ray_marching) et la détection d'objets par fonction de distance signée (SDF).
Ce moteur est réalisé en C++ et prend en charge la gestion de matériaux, le rebond de rayons ainsi que le Multisampling.

{{< figure
src="gallery/image3.png"
>}}

<---> <!-- magic separator, between columns -->

<div class="[&>figure]:my-4">
{{< figure
src="gallery/image1.png"
>}}

{{< figure
src="gallery/image2.png"
>}}

{{< figure
src="gallery/image4.png"
>}}
</div>

{{% /columns %}}

{{< description Algo3>}}

---
title: "Génération d’image Ray Marching (2024)"
date: 2024-04-22
draft: false
description: "Génération d’image en utilisant l’algorithme ray marching"
summary: "Génération d’image en utilisant l’algorithme ray marching"
tags: ["2ème année", "Cours C++", "Visualisation", "Ray Marching"]
authors : ['Léon Metthez', "Isaac Metthez", "Sevan Yerly"]
---

{{% columns ratio="3:1" class="space-x-4" %}} <!-- begin columns block -->

Moteur de génération d’image en utilisant l’algorithme ray marching et la détection d'objets par fonction de distance signée (SDF).
Le moteur de rendu réalisé en C++ prend en charge :
* La gestion de matériaux différents
* Le rebond de rayons
* Le Multisampling
* Le rendu de l'interface utilisateur

<---> <!-- magic separator, between columns -->

<div class="[&>figure]:my-4">
{{< figure
src="gallery/image3.png"
>}}

{{< figure
src="gallery/image1.png"
>}}

{{< figure
src="gallery/image2.png"
>}}
</div>

{{% /columns %}}
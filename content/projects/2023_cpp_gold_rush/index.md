---
title: "Gold Rush (2023)"
date: 2023-04-22
draft: false
description: "Jeu d'exploration en 3 dimensions réalisé avec SFML en C++"
summary: "Jeu d'exploration en 3 dimensions réalisé avec SFML en C++"
tags: ["1ère année", "Cours C++", "SFML", "2D"]
authors : ['Mehdi Guyot']
---

{{% columns ratio="3:1" class="space-x-4" %}} <!-- begin columns block -->

Gold Rush est un projet d'étudiant inspiré par le célèbre jeu _Minecraft_. 
Ce jeu réalisé avec la librairie SFML en C++ a pour principal objectif la collecte d'un maximum de blocs d'or tout en explorant un
monde généré procéduralement.
À cet effet, il faut explorer un monde 3D infini mais en ne disposant que de vues en 2D. 
Une vue du dessus, une de côté et une dernière de côté mais avec une rotation de 90° autour de l'axe vertical. 
Ces vues permettent ainsi de représenter les 3 dimensions du monde.

{{< youtubeLite id="LM2Y1h2g6Lc" label="Gold Rush (2023) - Demo" >}}

<---> <!-- magic separator, between columns -->

<div class="[&>figure]:my-4">
{{< figure
src="gallery/gold1.png"
>}}

{{< figure
src="gallery/gold2.jpg"
>}}

{{< figure
src="gallery/gold3.png"
>}}
</div>

{{% /columns %}}

{{< description CPP >}}

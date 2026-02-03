---
title: "Foot 3D Scan"
date: 2024-11-07
draft: false
description: "Scan de pied pour aider les physiothérapeutes"
tags: ["Ra&D", "Groupe Imagerie", "Caméras RGB-D", "Nuages de points 3D"]
authors : ["Ivan Serra Moncadas", "Benoit Le Callennec"]
---

{{% columns ratio="3:1" class="space-x-4" %}} <!-- begin columns block -->

## Contexte et enjeux

Les physiothérapeutes ont besoin de faire un scan 3D détaillé des pieds d’un patient au début d’une séance. Cela permettrait d’optimiser l’analyse de la marche, d’affiner les diagnostics et de proposer des traitements mieux adaptés. L’analyse précise des pieds repose sur la qualité des données initiales recueillies lors de l’examen. Dans ce cadre, une mesure fine et rapide de la morphologie du pied constitue un élément essentiel pour améliorer l’interprétation des paramètres cliniques.

À l’heure actuelle, aucune solution disponible ne permet d’obtenir un modèle 3D des pieds qui soit à la fois rapide, fiable et suffisamment pratique pour être intégré en routine clinique. Les outils existants sont souvent trop lents, trop coûteux ou trop complexes à manipuler durant une consultation. Dès lors, il devient nécessaire de concevoir une solution sur mesure, pensée pour le confort du patient et l’efficacité du professionnel de santé.
Ce projet fait suite au projet GapKo. [Gapko] (https://he-arc.github.io/imagerie-portfolio/projects/2023_rnd_gapko/)

{{< youtubeLite id="RHN5QRGbgyY" label="Prototype Foot 3D Scan (2024)" >}}

## Objectifs

Le projet vise à intégrer, au tout début de la séance médicale, une numérisation 3D en temps réel de la forme des pieds du patient en moins de 5 minutes. Cette solution devra permettre :

- Une acquisition précise et instantanée des deux pieds, tandis que le patient est allongé sur une table ;
- La création d’un modèle 3D complet (y compris voûte plantaire, cheville, avant-pied et arrière-pied) ;
- La possibilité d’effectuer la modélisation à l’aide d’un smartphone.

L’enjeu est de proposer un système simple d’utilisation, totalement interactif, et utilisable en conditions réelles d’examen.

## Partenaires et financement

Ce projet se fait en étroite collaboration avec **Christophe Otte**, physiothérapeute.

## Résultats

La vidéo ci-dessus permet de visualiser la reconstruction progressive de l’objet scanné, ici une chaussure, à partir des données capturées par le capteur Kinect.

Le système acquiert et traite simultanément les informations de profondeur afin de générer une reconstruction 3D détaillée. Cette démonstration met en évidence la capacité du prototype à effectuer une fusion de données fiable et dynamique, et confirme le potentiel de la technologie Kinect pour la réalisation de scans 3D interactifs.

Pour l’instant, il n’a été démontré que théoriquement qu’il serait possible d’obtenir un résultat similaire sur smartphone, sans prototype fonctionnel mis en place.



<---> <!-- magic separator, between columns -->


{{% /columns %}}

{{< description TICd>}}

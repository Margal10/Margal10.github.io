---
layout: default
title: R&D
---

[Télécharger mon CV](https://github.com/Margal10/Margal10.github.io/files/10278796/CV-MargauxGaillard.pdf)

**Ingénieure R&D – Matériaux et instrumentation**

J’aide à exploiter des images et des données expérimentales réelles lorsqu’elles sont trop variables, bruitées ou non contrôlées pour des méthodes classiques.

J’interviens comme ingénieure R&D / computer vision pour transformer des prototypes d’analyse d’images en outils exploitables par une équipe technique.

Applications : vision industrielle, inspection automatisée, métrologie par l’image, analyse scientifique appliquée.

---

## Problèmes que je sais résoudre

- Automatiser une mesure aujourd’hui réalisée manuellement
- Identifier des objets sans marquage ni positionnement contrôlé
- Fiabiliser une analyse d’images instable
- Comparer des structures physiques variables
- Exploiter des données expérimentales bruitées issues de capteurs réels

---

## Exemples de réalisations

### Identification d’objets par signature physique
Problème : authentifier un objet sans marquage physique malgré orientation et éclairage variables.

Solution : appariement de points clés + métrique robuste.

Résultat : identification fiable sans marquage physique.

Applications : traçabilité et authentification.

<img src="/assets/img/AlgoVisuOrdi_results.png" width="600">

Figure 1 : 

### Comparaison de nuages de points
Problème : comparer deux acquisitions d’un même objet physique alors que sa position, son orientation ou sa géométrie varient légèrement entre mesures (bruit expérimental, déformation, imprécision d’acquisition).

Solution : développement d’un algorithme d’alignement et de comparaison de nuages de points 3D permettant d’estimer la similarité géométrique indépendamment du positionnement, et d’extraire des métriques quantitatives d’écart.

Résultat : détection fiable de variations réelles de structure sans dépendre du placement de l’objet ni des conditions d’acquisition. Permet un suivi reproductible de l’évolution d’un système physique.

Applications : contrôle qualité dimensionnel, suivi d’usure ou de déformation, validation de procédés de fabrication, comparaison avant/après traitement, métrologie 3D automatisée.

<img src="/assets/img/maillage_recouvrement.png" width="600">

Figure 2 : 

### Mesure automatisée sur images bruitées
Extraction de caractéristiques et métriques robustes sur données issues de systèmes optiques réels.

---

## Stack technique
- Python (OpenCV, NumPy)
- Traitement d’images & vision par ordinateur
- Extraction de caractéristiques et métriques de robustesse sur données réelles
- Validation et robustesse de mesures

[Retour](./)


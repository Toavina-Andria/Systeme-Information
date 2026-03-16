---
title: Systèmes et SIG
tags:
  - sig
  - systeme-information
  - geographie
  - gis
created: 2026-03-09
---

# Systèmes et Systèmes d’Information

## Système

Un **système** est un ensemble d’éléments organisés (processus, ressources ou composants) qui interagissent entre eux afin **d’atteindre un ou plusieurs objectifs**.

Un système fonctionne généralement selon un cycle :

1. entrée d’informations ou de ressources  
2. traitement  
3. production d’un résultat

---

## Système d'information

Un **Système d’Information (SI)** est l’ensemble des **ressources matérielles, logicielles et humaines** permettant de :

- collecter des informations
- traiter les données
- stocker les informations
- diffuser les résultats

Le système d'information aide une organisation à **gérer, analyser et exploiter l'information pour la prise de décision**.

Voir aussi :  
- [[Flux d'un système D'information.canvas]]

---

# SIG — Système d’Information Géographique

Un **SIG (Système d’Information Géographique)** est un logiciel permettant de :

- collecter
- stocker
- analyser
- gérer
- visualiser

des **données géographiques**, c’est-à-dire des informations liées à **une position sur la Terre** (coordonnées, lieux, cartes, territoires).

Les SIG sont utilisés dans plusieurs domaines :

- urbanisme
- environnement
- transport
- agriculture
- gestion territoriale
- cartographie

---

# Les 5 composantes d’un SIG

## 1. Matériel

Le matériel correspond aux **équipements informatiques nécessaires** au fonctionnement du SIG.

Exemples :

- postes de travail (ordinateurs)
- imprimantes
- serveurs de stockage
- appareils de collecte de données (satellites, drones, radars)
- dispositifs d’affichage (écrans)

---

## 2. Logiciels

Les **logiciels SIG** permettent de manipuler les données géographiques.

Fonctions principales :

- acquisition des données
- archivage
- analyse
- visualisation
- modélisation
- anticipation

---

## 3. Utilisateurs

Les utilisateurs sont les **personnes qui utilisent et administrent le système**.

Exemples :

- ingénieurs SIG
- techniciens
- analystes
- chefs de projet
- décideurs

---

## 4. Données

Les données représentent **le cœur du SIG**.

Deux types principaux :

- **données géographiques**
- **données attributaires alphanumériques**

---

## 5. Procédures

Les procédures sont **les méthodes et règles d’utilisation du système**.

Elles définissent :

- les méthodes de collecte
- les procédures d’analyse
- les standards d’organisation des données

---

# Terminologies de base

## Raster
^50a1ea

Le **format raster** correspond à une **image composée d'une matrice de pixels**.

Chaque pixel possède une valeur représentant une information.

Exemples :

- images satellites
- photographies aériennes
- cartes scannées

---

## Vectoriel
^9e12aa

Le **format vectoriel** représente les objets géographiques à l’aide de **formes géométriques** :

- points
- lignes
- polygones

Il est principalement utilisé en **cartographie numérique**.

---

## Géoréférencement

Le **géoréférencement** est le processus qui consiste à **attribuer des coordonnées géographiques à un objet ou une image** afin de le positionner correctement sur la surface terrestre.

---

# Fonctionnalités des logiciels SIG

## Acquisition

L’acquisition consiste à **collecter et numériser des données géographiques**.

Cette étape est généralement **la plus coûteuse dans la mise en place d’un SIG**.

---

## Archivage

L’archivage permet de :

- gérer les bases de données
- stocker de grandes quantités de données géographiques
- centraliser les informations
- mettre à jour les données

---

## Analyse

L’analyse consiste à **interroger et manipuler les données géographiques** pour obtenir de nouvelles informations.

---

## Affichage

L’affichage permet de :

- visualiser les données sur des cartes
- superposer plusieurs couches d’information
- produire des plans et des cartes

---

## Abstraction

L’abstraction consiste à **représenter et modéliser le monde réel** sous forme de données numériques.

---

## Anticipation

L’anticipation permet de **prévoir des évolutions possibles** grâce à l’analyse des données.

Elle est utilisée pour la **planification et l’aide à la décision**.

---

# Intérêt du SIG

Les SIG permettent de répondre à plusieurs types de questions :

- **Où ?**  
  Localisation des phénomènes étudiés.

- **Quoi ?**  
  Identification des objets présents dans la zone d’étude.

- **Comment ?**  
  Analyse de la répartition spatiale et des relations entre les objets.

- **Quand ?**  
  Analyse de l’évolution dans le temps.

---

# Organisation des données dans un SIG

Un SIG manipule deux types de données :

## 1. Objets géographiques

Les objets géographiques peuvent être représentés sous deux formats :

- [[#^9e12aa|Vectoriel]]
- [[#^50a1ea|Raster]]

---

## 2. Données attributaires

Chaque objet géographique possède **des informations descriptives associées**, appelées **données attributaires**.

Exemples :

- nom
- surface
- population
- type de bâtiment

---

Les objets géographiques sont généralement organisés en **couches thématiques** :

- couche bâtiments
- couche rivières
- couche routes
- couche parcelles

Chaque couche regroupe **des objets de même nature**.

---

# Objets géographiques

Les objets géographiques peuvent être stockés sous deux formats.

## Format vectoriel

Les objets sont décrits par :

- points
- lignes
- polygones

Exemples :

- villes
- routes
- limites administratives

---

## Format raster (matriciel)

Les données sont représentées sous forme de **grille de pixels**.

Exemples :

- orthophotographies
- images satellites
- images scannées

---
### Données attributaires
- Les données attributaires sont les données associées à un objet géographique **vectoriel**
Exemple : 
- Nom de rue
- Longueur d'une rue 
- Adresse d'une maison
- Nom de proprétaires
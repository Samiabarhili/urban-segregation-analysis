# Économie urbaine – Ségrégation sociale et taille des aires urbaines

## Objectif du projet

Ce projet vise à explorer s’il existe une relation entre la *taille des aires urbaines (AU)* en France métropolitaine et leur *niveau de ségrégation sociale*.  
La concentration des populations et des activités dans les villes fait émerger des formes de *séparation spatiale entre groupes sociaux*.  
Nous interrogeons ici le rôle que joue la taille de l’aire urbaine dans ce phénomène.

## Définitions clés

- *Aire urbaine (AU)* : selon l’INSEE, une aire urbaine correspond à un ensemble de communes organisées autour d’un pôle urbain et d’une couronne périurbaine, liée par les flux domicile-travail.
- *Ségrégation socio-spatiale* : séparation dans l’espace urbain entre groupes sociaux (catégories professionnelles, niveaux de revenus, origine, etc.).

## Données utilisées

Nous avons mobilisé trois bases de données publiques de l’INSEE pour l’année 2021 :

- La *population des communes*.
- La *composition socioprofessionnelle des actifs de 25 à 54 ans*.
- La *correspondance entre communes et aires d’attraction des villes* (zonage AAV 2020).

Ces données nous permettent de passer de l’échelle communale à l’échelle des aires urbaines.

## Méthodologie

Notre analyse repose sur deux grandes étapes complémentaires :

### 1. Analyse de la composition sociale des aires urbaines

- Calcul des parts de *cadres, **ouvriers, **employés* et *professions intermédiaires* dans chaque AU.
- Observation de l’évolution de ces parts en fonction de la *taille des aires urbaines* (logarithme de la population).
- Cette étape permet de détecter des dynamiques de *polarisation sociale* selon la taille des territoires.

### 2. Mesure de la ségrégation sociale

Pour mesurer la ségrégation sociale, nous utilisons *deux indices complémentaires* :

- *Indice de Duncan* :
  - Mesure la *séparation spatiale* entre deux groupes (ici : cadres et ouvriers).
  - Intuitif mais limité car binaire.

- *Indice d’entropie* :
  - Mesure la *diversité sociale globale* au sein de chaque AU (toutes les CSP).
  - Plus riche mais ne reflète pas directement la séparation spatiale.

Ces deux outils permettent de croiser *polarisation entre groupes extrêmes* et *richesse sociale interne* des territoires.

## Résultats

### Composition sociale

- La *part de cadres* augmente avec la taille de l’AU.
- La *part d’ouvriers* diminue dans les grandes villes.
- Cela traduit une certaine *hiérarchisation sociale* liée à la taille des aires.

### Ségrégation sociale

- L’*indice de Duncan* augmente légèrement avec la taille des AU (R² ≈ 4%).  
  → Faible corrélation : la taille explique peu la ségrégation binaire.
  
- L’*indice d’entropie* croît plus nettement avec la taille (R² ≈ 27%).  
  → Les grandes villes sont plus *diversifiées, mais cela ne signifie pas qu’il y a plus de **mixité spatiale*.

### Étude de cas

- *Paris* : forte séparation entre quartiers riches (ouest/centre) et pauvres (nord/est), selon un modèle *monocentrique*.
- *Rennes* : structure plus *mixte et équilibrée*, grâce à des politiques urbaines locales.

## Limites de l’étude

- L’indice de Duncan est binaire : il ne prend en compte que deux groupes.
- L’indice d’entropie mesure la diversité mais pas la *localisation spatiale* précise des groupes.
- Analyse *statique*, fondée sur une année unique (2021).
- D’autres facteurs clés ne sont pas intégrés : logement, transports, offre scolaire, histoire urbaine, politiques publiques.

## Ouverture

La taille des aires urbaines n’est qu’un *facteur partiel* de la ségrégation sociale.  
D'autres variables contribuent fortement aux dynamiques sociales urbaines, comme :

- Les *écarts de revenus*
- Les *réseaux de transport*
- Les *dynamiques immobilières*
- L’*histoire du développement urbain*
- Les *politiques locales de mixité*

Ces éléments doivent être explorés pour enrichir la compréhension du phénomène.

## Références

- [INSEE – Base des aires d’attraction des villes 2020](https://www.insee.fr/fr/information/4803954)  
- [INSEE – Statistiques CSP (1968–2021)](https://www.insee.fr/fr/statistiques/1893185)  
- [INSEE – Historique des populations communales](https://www.insee.fr/fr/statistiques/3698339)  
- [INSEE (2017) – Niveaux de vie et ségrégation dans 12 métropoles françaises](https://www.insee.fr/fr/statistiques/fichier/3317906/497-498_Floch-FR.pdf)  
- [Cours d’économie urbaine – Guillaume Chapelle (2025)](https://www.dropbox.com/s/79vk5ihoc6lmm30/Seance03.pdf?dl=0)  
- [INSEE – Insee analyses n°79 (2023)](https://www.insee.fr/fr/statistiques/6680439)

## Auteurs

  
- Synthia  
- Hajar  
- Aline
- Samia  

# Économie urbaine – Ségrégation socio-spatiale et taille des aires urbaines

## Objectif du projet

Ce projet vise à explorer s’il existe une relation entre la *taille des aires urbaines (AU)* en France métropolitaine et leur *niveau de ségrégation socio-spatiale*.  
La concentration des populations et des activités dans les villes soulève la question de la *répartition inégale des groupes sociaux dans l’espace urbain*.  
Nous interrogeons ici le rôle que joue la taille des aires urbaines dans ce phénomène.

## Définitions clés

- *Aire urbaine (AU)* : selon l’INSEE, une aire urbaine correspond à un ensemble de communes organisées autour d’un pôle urbain et d’une couronne périurbaine, liée par les flux domicile-travail.
- *Ségrégation socio-spatiale* : désigne la séparation dans l’espace urbain entre groupes sociaux, selon leur statut socio-économique, leur catégorie professionnelle, ou leur origine.

## Données utilisées

Nous avons mobilisé trois bases de données publiques de l’INSEE pour l’année 2021 :

- La *population des communes*.
- La *composition socioprofessionnelle des actifs de 25 à 54 ans*.
- La *correspondance entre communes et aires d’attraction des villes* (zonage AAV 2020).

Ces données permettent de passer de l’échelle communale à celle des aires urbaines.

## Méthodologie

Notre analyse repose sur deux grandes étapes complémentaires :

### 1. Analyse de la composition sociale des aires urbaines

- Calcul des parts de *cadres*, *ouvriers*, *employés* et *professions intermédiaires* dans chaque AU.
- Observation de l’évolution de ces parts en fonction de la *taille des aires urbaines* (logarithme de la population).
- Cette étape permet d’identifier des tendances de *polarisation sociale* selon la taille des territoires.

### 2. Mesure de la ségrégation socio-spatiale

Pour évaluer la ségrégation socio-spatiale, nous mobilisons *deux indices complémentaires* :

- *Indice de Duncan* :
  - Mesure la *séparation spatiale entre deux groupes*, ici cadres et ouvriers.
  - Outil simple, mais binaire : il ne capture qu’un axe de la ségrégation.

- *Indice d’entropie* :
  - Mesure la *diversité sociale globale* en intégrant toutes les catégories socioprofessionnelles.
  - Reflète la pluralité sociale d’un territoire, sans pour autant décrire la répartition géographique fine.

Ces deux indicateurs permettent de combiner une lecture binaire et une lecture multidimensionnelle de la ségrégation.

## Résultats

### Composition sociale

- La *part de cadres* augmente avec la taille de l’AU.
- La *part d’ouvriers* diminue dans les grandes villes.
- Cela reflète une certaine *hiérarchisation sociale* croissante selon la taille des aires urbaines.

### Ségrégation socio-spatiale

- L’*indice de Duncan* augmente légèrement avec la taille des AU (*R² ≈ 4%*).  
  → Cela montre une séparation sociale modérément accentuée dans les grandes villes.

- L’*indice d’entropie* croît plus nettement avec la taille (*R² ≈ 27%*).  
  → Les grandes aires sont plus *diversifiées socialement*, mais cela ne garantit pas une meilleure mixité spatiale.

### Étude de cas

- *Paris* : forte séparation entre quartiers riches (ouest/centre) et pauvres (nord/est), selon un modèle *monocentrique*.
- *Rennes* : structure plus *équilibrée*, illustrant le rôle des politiques urbaines dans la réduction de la ségrégation.

## Limites de l’étude

- L’indice de Duncan est binaire : il ne mesure qu’une forme de ségrégation.
- L’indice d’entropie capte la diversité sociale mais *pas la répartition spatiale précise*.
- L’analyse est *statique* (année 2021 uniquement).
- Plusieurs facteurs clés sont absents : politiques publiques locales, histoire urbaine, transports, offre scolaire, logement, etc.

## Ouverture

La taille des aires urbaines n’est qu’un *facteur partiel* dans l’explication de la ségrégation socio-spatiale.  
D'autres éléments influencent fortement la distribution des groupes sociaux dans l’espace urbain, notamment :

- Les *écarts de revenus*
- Les *dynamiques immobilières*
- Les *réseaux de transport*
- L’*histoire du développement urbain*
- Les *politiques locales de mixité*
- L’*offre scolaire et les services publics*

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

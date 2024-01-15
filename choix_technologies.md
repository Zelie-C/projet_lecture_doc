# Choix des technologies

## Design

- Figma

## Font-End

Projet qui se focalise sur une utilisation mobile et tablette : React Native (technologie soutenue par Meta).

1. Intérêt : 
- cross-plateform. Cette technologie permet de concevoir des applications mobiles pour les deux systèmes d'exploitations principaux sur ces appareils : IOs et Android. 
- Technologie similaire à React reposant donc sur du javascript. Langage de programmation (JS/TS) et Framework Front-end qu'on maîtrise, pas de nécessité d'apprendre un autre langage de programmation et proximité avec le framework ce qui n'est pas forcément le cas pour les autres solutions.

2. Comparaisons:

- Autres technologies cross-plateform :

1. Flutter, technologie soutenue par Google. Permet également le développement d'applications sur IOs et Android. Nécessite cependant l'apprentissage du langage Dart.

- Technologies natives :

1. Swift, langage supporté par Apple pour les applications natives sur IOs. Descendant de l'Objective-C.
2. Kotlin, langage suporté par Google pour les applications natives sur Android. Deuxième langage natif pour Android après Java.

Nous n'avons pas opté pour des solutions natives car elles imposaient trop de contraintes. Soit il fallait abandonner l'idée de développer une application qui fonctionnerait sur les deux systèmes d'exploitation soit doubler, à minima, le temps de développement pour utiliser chacune des technologies natives.

## Back-End 

- Utilisation de NodeJS avec le framework Express.
- ORM (Object-Relational Mapping) : Sequelize

## Base de données

- Base de données en Postgres. Utilisation de PostgreSQL15. 

## Devops

- Conteneurisation : Docker
- Tests : 
    - Unitaire : Vitest
    - End-to-End : Playwright


## Qualité logiciel

- Logger : Winston
- Linter : eslint
- Prettier
- StoryBook
---
layout: default
lang: fr
title: CV de Brewen Couaran
description: Étudiant en L1 Informatique à l'Université de Bordeaux

availability: Disponibilité
internship: Stage
internship_disp: 12 Juin 2023 au 1er Septembre 2023
---
## Formation
* Licence 1 Informatique à l'Université de Bordeaux (2022-2023)
* Baccalauréat Scientifique au Lycée Sainte-Marie Grand Lebrun (2019-2022)

## Skills
* **Langages de programmation**:
  * {{ site.data.skills }}
{% for lang in site.data.skills.languages %}
  * ![{{ lang.name }}](https://img.shields.io/badge/-{{ lang.name }}%20({{ lang.level }})-{{ lang.color }}?logo={{ lang.slug }}&logoColor={{ lang.font_color }})
{% endfor %}

* **Framework**:
    * ![React](https://img.shields.io/badge/-React%20(6/10)-61DAFB?logo=react&logoColor=black)
    * ![Vue](https://img.shields.io/badge/-Vue%20(7/10)-4FC08D?logo=vue.js&logoColor=white)
    * ![NestJS](https://img.shields.io/badge/-NestJS%20(8/10)-E0234E?logo=nestjs&logoColor=white)
    * ![Express](https://img.shields.io/badge/-Express%20(9/10)-000000?logo=express&logoColor=white)
    * ![Node.js](https://img.shields.io/badge/-Node.js%20(9/10)-339933?logo=node.js&logoColor=white)
    * ![Flutter](https://img.shields.io/badge/-Flutter%20(7/10)-02569B?logo=flutter&logoColor=white)

## Projets
  * **api.aknologia.dev** : [Aknologia/Aknologia.DEV](https://github.com/Aknologia/Aknologia.DEV)
    * Prototype d'API REST back-end
    * [Postman Docs](https://documenter.getpostman.com/view/19755036/UVkvKYV5)
    * Technologies utilisées:
      * [NestJS](https://nestjs.com/) (Framework)
      * [TypeScript](https://www.typescriptlang.org/) (Langage)
      * [MongoDB](https://www.mongodb.com/) (Base de données)
      * [Docker](https://www.docker.com/) (Conteneurisation)
      * [GitHub Actions](https://github.com/features/actions) (CI/CD)
      * [Postman](https://www.postman.com/) (Documentation & Tests)
      * [Heroku](https://www.heroku.com/) (Hébergement)
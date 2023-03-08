---
layout: default
lang: fr
title: CV de Brewen Couaran
description: Étudiant en L1 Informatique à l'Université de Bordeaux

availability: Disponibilité
internship:
  name: Stage
  date: 12 Juin 2023 au 1er Septembre 2023
---
## Formation
* Licence 1 Informatique à l'Université de Bordeaux (2022-2023)
* Baccalauréat Scientifique au Lycée Sainte-Marie Grand Lebrun (2019-2022)

## Skills
* **Langages de programmation**:
{% for lang in site.data.skills.languages %}
    * ![{{ lang.name }}](https://img.shields.io/badge/-{{ lang.name }}%20({{ lang.level }}/10)-{{ lang.color }}?logo={{ lang.slug }}&logoColor={{ lang.font_color }})
{% endfor %}

* **Framework**:
{% for framework in site.data.skills.frameworks %}
    * ![{{ framework.name }}](https://img.shields.io/badge/-{{ framework.name }}%20({{ framework.level }}/10)-{{ framework.color }}?logo={{ framework.slug }}&logoColor={{ framework.font_color }}) 
{% endfor %}

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
  
  * **aknologia.github.io/CV** : [Aknologia/CV](https://github.com/Aknologia/CV)
    * Site web statique de mon CV
    * Technologies utilisées:
      * [Jekyll](https://jekyllrb.com/) (Framework)
      * [GitHub Pages](https://pages.github.com/) (Hébergement)
      * [GitHub Actions](https://github.com/features/actions) (CI/CD)
      * [Liquid](https://shopify.github.io/liquid/) (Template engine)
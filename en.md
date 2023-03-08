---
layout: default
lang: en
title: Brewen Couaran's CV
description: First Year Computer Science Student at the University of Bordeaux

availability: Availability
internship:
  name: Internship
  date: 12th June 2023 to 1st September 2023
---
## Education
* _Freshman in Computer Science at the University of Bordeaux_ (2022-2023)
* _Baccalaureate in Science and Technology at the Lycée Sainte-Marie Grand Lebrun_ (2019-2022)

## Skills
* **Programming languages**:
{% for lang in site.data.skills.languages %}
  * ![{{ lang.name }}](https://img.shields.io/badge/-{{ lang.name }}%20({{ lang.level }}/10)-{{ lang.color }}?logo={{ lang.slug }}&logoColor={{ lang.font_color }})
{% endfor %}

* **Frameworks**:
{% for framework in site.data.skills.frameworks %}
  * ![{{ framework.name }}](https://img.shields.io/badge/-{{ framework.name }}%20({{ framework.level }}/10)-{{ framework.color }}?logo={{ framework.slug }}&logoColor={{ framework.font_color }})
{% endfor %}

## Projects
  * **api.aknologia.dev** : [Aknologia/Aknologia.DEV](https://github.com/Aknologia/Aknologia.DEV)
    * API REST back-end prototype
    * [Postman Docs](https://documenter.getpostman.com/view/19755036/UVkvKYV5)
    * Used technologies:
      * [NestJS](https://nestjs.com/) (Framework)
      * [TypeScript](https://www.typescriptlang.org/) (Language)
      * [MongoDB](https://www.mongodb.com/) (Database)
      * [Docker](https://www.docker.com/) (Containerization)
      * [GitHub Actions](https://github.com/features/actions) (CI/CD)
      * [Postman](https://www.postman.com/) (Documentation & Tests)
      * [Heroku](https://www.heroku.com/) (Hosting)

  * **aknologia.github.io/CV** : [Aknologia/CV](https://github.com/Aknologia/CV)
    * Static website to display my CV
    * Used technologies:
      * [Jekyll](https://jekyllrb.com/) (Framework)
      * [GitHub Pages](https://pages.github.com/) (Hosting)
      * [GitHub Actions](https://github.com/features/actions) (CI/CD)
      * [Liquid](https://shopify.github.io/liquid/) (Template engine)
---
layout: default
lang: fr
title: CV de Brewen Couaran
description: Étudiant en L1 Informatique à l'Université de Bordeaux

availability: Disponibilité
internship:
    name: Stage
    date: 12 Juin 2023 au 1er Septembre 2023

levels:
    beginner: Débutant
    advanced-beginner: Débutant avancé
    intermediate: Intermédiaire
    advanced-intermediate: Intermédiaire avancé
    advanced: Avancé
    expert: Expert
---
## Formation
* Licence 1 Informatique à l'Université de Bordeaux (2022-2023)
* Baccalauréat Scientifique au Lycée Sainte-Marie Grand Lebrun (2019-2022)

## Compétences
<ul>
<li>
    <p><strong>Langages de programmation</strong>:</p>
    {% for lang in site.data.skills.languages %}
    <li>
        <img
            src="https://img.shields.io/badge/-{{ lang.name }}-{{ lang.color }}?logo={{ lang.slug }}&logoColor={{ lang.font_color }}"
            alt="{{ lang.name }}"
        />
        {% if lang.level == 1 %}
            {{ page.levels.beginner }}
        {% endif %}
        {% if lang.level == 1.5 %}
            {{ page.levels.advanced-beginner }}
        {% endif %}
        {% if lang.level == 2 %}
            {{ page.levels.intermediate }}
        {% endif %}
        {% if lang.level == 2.5 %}
            {{ page.levels.advanced-intermediate }}
        {% endif %}
        {% if lang.level == 3 %}
            {{ page.levels.advanced }}
        {% endif %}
        {% if lang.level == 4 %}
            {{ page.levels.expert }}
        {% endif %}
    </li>
    {% endfor %}
</li>
<li>
    <p><strong>Frameworks</strong>:</p>
    {% for framework in site.data.skills.frameworks %}
    <li>
        <img
            src="https://img.shields.io/badge/-{{ framework.name }}-{{ framework.color }}?logo={{ framework.slug }}&logoColor={{ framework.font_color }}"
            alt="{{ framework.name }}"
        />
        {% if framework.level == 1 %}
            {{ page.levels.beginner }}
        {% endif %}
        {% if framework.level == 1.5 %}
            {{ page.levels.advanced-beginner }}
        {% endif %}
        {% if framework.level == 2 %}
            {{ page.levels.intermediate }}
        {% endif %}
        {% if framework.level == 2.5 %}
            {{ page.levels.advanced-intermediate }}
        {% endif %}
        {% if framework.level == 3 %}
            {{ page.levels.advanced }}
        {% endif %}
        {% if framework.level == 4 %}
            {{ page.levels.expert }}
        {% endif %}
    </li>
    {% endfor %}
</li>
</ul>

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
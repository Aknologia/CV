---
layout: default
lang: fr
title: CV de Brewen Couaran
description: Étudiant en L1 Informatique Parcours International à l'Université de Bordeaux

availability: Disponibilité
internship:
    name: Stage
    date: 12 Juin 2023 au 1er Septembre 2023

levels:
    beginner: Débutant
    advanced-beginner: Débutant Avancé
    intermediate: Intermédiaire
    advanced-intermediate: Intermédiaire Avancé
    advanced: Avancé
    expert: Expert
---
## Présentation
Je m'appelle Brewen Couaran, j'ai 18 ans et je suis étudiant en L1 Informatique Parcours International à l'Université de Bordeaux.
Je suis passionné par l'informatique et les nouvelles technologies, et je suis toujours à la recherche de nouveaux projets et de nouvelles expériences.<br>
Je suis actuellement à la recherche d'un stage de 1 ou 2 mois à partir du 12 Juin 2023.
## Formation
* Licence 1 Informatique Parcours International à l'Université de Bordeaux (2022-2023)
* Baccalauréat Scientifique mention Bien au Lycée Sainte-Marie Grand Lebrun (2019-2022)

## Compétences
<ul>
<li>
    <p class="subtitle"><strong>Langages de programmation</strong>:</p>
    <ul>
        {% for lang in site.data.skills.languages %}
        <li class="skill">
            <img
                src="https://img.shields.io/badge/-{{ lang.name }}-{{ lang.color }}?logo={{ lang.slug }}&logoColor={{ lang.font_color }}"
                alt="{{ lang.name }}"
            />
            <p>
                {% if lang.level == 1 %}
                    {{ page.levels.beginner }}
                {% elsif lang.level == 1.5 %}
                    {{ page.levels.advanced-beginner }}
                {% elsif lang.level == 2 %}
                    {{ page.levels.intermediate }}
                {% elsif lang.level == 2.5 %}
                    {{ page.levels.advanced-intermediate }}
                {% elsif lang.level == 3 %}
                    {{ page.levels.advanced }}
                {% elsif lang.level == 4 %}
                    {{ page.levels.expert }}
                {% endif %}
            </p>
        </li>
        {% endfor %}
    </ul>
</li>
<li>
    <p class="subtitle"><strong>Frameworks</strong>:</p>
    <ul>
        {% for framework in site.data.skills.frameworks %}
        <li class="skill">
            <img
                src="https://img.shields.io/badge/-{{ framework.name }}-{{ framework.color }}?logo={{ framework.slug }}&logoColor={{ framework.font_color }}"
                alt="{{ framework.name }}"
            />
            <p>
                {% if framework.level == 1 %}
                    {{ page.levels.beginner }}
                {% elsif framework.level == 1.5 %}
                    {{ page.levels.advanced-beginner }}
                {% elsif framework.level == 2 %}
                    {{ page.levels.intermediate }}
                {% elsif framework.level == 2.5 %}
                    {{ page.levels.advanced-intermediate }}
                {% elsif framework.level == 3 %}
                    {{ page.levels.advanced }}
                {% elsif framework.level == 4 %}
                    {{ page.levels.expert }}
                {% endif %}
            </p>
        </li>
        {% endfor %}
    </ul>
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
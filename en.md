---
layout: default
lang: en
title: Brewen Couaran's CV
description: First Year Computer Science Student at the University of Bordeaux

availability: Availability
internship:
    name: Internship
    date: 12th June 2023 to 1st September 2023

levels:
    beginner: Beginner
    advanced-beginner: Advanced Beginner
    intermediate: Intermediate
    advanced-intermediate: Advanced Intermediate
    advanced: Advanced
    expert: Expert
---
## Presentation
I'm Brewen Couaran, I'm 18 years old and I'm a first year Computer Science student at the University of Bordeaux.
I'm passionate about computer science and new technologies, and I'm always looking for new projects and new experiences.<br>
I'm currently looking for a 1 or 2 month internship starting from the 12th June 2023.
## Education
* _Freshman in Computer Science at the University of Bordeaux_ (2022-2023)
* _Baccalaureate in Science and Technology at the Lycée Sainte-Marie Grand Lebrun_ (2019-2022)

## Skills
<ul>
<li>
    <p class="subtitle"><strong>Programming languages</strong>:</p>
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
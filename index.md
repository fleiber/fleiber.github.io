# FLâneries 2


## Intro

Il y a longtemps, j'étais jeune : j'avais donc des choses à dire. J'ai ainsi tenu à jour pendant plusieurs années (en gros, quand j'étais au lycée et en prépa) mon premier site : [FLâneries](http://leiber.free.fr).

Aujourd'hui, je suis moins jeune, moins naïf et plus râleur : ce qui n'est finalement pas une raison pour épargner au monde mes radotages ! Après tout, certains postent bien les photos de leur repas sur Insta :p

Bref, voici en vrac des notes personnelles, que j'ai commencé à saisir lors de mon changement de travail en 2019.


## Un peu de contenu

{% for page in site.html_pages %}
  {% if page.url != '/' %}
  - [{{ page.title }}]({{ page.url | relative_url }})
  {% endif %}
{% endfor %}


---
layout: page
title: Officielt site for Fisketorvets Motorbådklub
display-title: FMK - Fisketorvets Motorbådklub
image: /img/rudder.jpg
---

FMK er en klub for motorbådejere, som ligger på Elværksvej bag H.C. Ørsteds-værket i Københavns Sydhavn. 

## Nyt fra FMK

{% for post in site.posts %}
    {% if post %}
        [{{ post.title }}]({{ post.url }})
        {{ post.excerpt }}
    {% endif %}
{% endfor %}

[Følg os på Facebook.](https://www.facebook.com/pages/Fisketorvets-Motorb%C3%A5dsklub-FMK/157238980994747)

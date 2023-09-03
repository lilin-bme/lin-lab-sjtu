---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a team with different background of biomedical engineering, material science, chemistry, biology and electrical engineering1.

{% include section.html %}

We are a team with different background of biomedical engineering, material science, chemistry, biology and electrical engineering2.

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

We are a team with different background of biomedical engineering, material science, chemistry, biology and electrical engineering3.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

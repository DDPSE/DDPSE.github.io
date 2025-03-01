---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a team of researchers passionate about leveraging chemical engineering principles, computer programming, data, and machine learning to design complex systems. Our team brings together diverse expertise to tackle challenges in multiscale process modeling, optimization and decision-making. We are located in the Ford Environmental Science and Technology building at Georgia Tech in Atlanta, Georgia, USA.

Meet our talented team members who make it all happen!

<div class ="page-image">
<img src="/images/team/labaiche24.jpg" alt="DDPSE AIChE 2024 Photo">
</div>

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

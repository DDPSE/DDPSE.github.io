---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Interested in collaborating, learning more about our research, or joining our team? Feel free to reach out! We welcome inquiries from students, researchers, and industry partners who share our passion for data-driven process systems engineering. 
<br> 
Contact us to explore potential opportunities and collaborations via email. If you are interested in joining our lab, you can use the Bookings link below to schedule a meeting with Dr. Boukouvala.

{%
  include button.html
  type="email"
  text="Fani Boukouvala email"
  link="fboukouvala6@gatech.edu"
%}
{%
  include button.html
  type="link"
  text="Book a meeting with Dr B"
  link="https://outlook.office.com/bookings/homepage?src=bookings-slots-tips"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/kndr2NobrosUWM7B8"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/visitusimage1.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/main-campus.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
{% endcapture %}

{% capture col2 %}
GT ChBE's mission: Creating a better 
future by transforming people, 
ideas, processes and products
{% endcapture %}

{% capture col3 %}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

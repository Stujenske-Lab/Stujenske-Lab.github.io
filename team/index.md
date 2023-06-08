---
title: Team
nav:
  order: 5
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The Stujenske lab is relatively new, and current lab members may not yet be added to the website. Dr. Stujenske is glad to have the opportunity to work with and mentor individuals at any step in their scientific journey, from high school through postdoc.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

# We are hiring!
The laboratory has funding for multiple positions, including lab technicians, graduate students, and postdocs. Postdoc candidate should have experience with computer programming, imaging, or electrophysiology. Prospective graduate students should have an interest in learning programming if they do not start with this skill. Please contact Dr. Stujenske using the link below to express your interest.

{%
  include button.html
  type="email"
  text="I am interested in a position!"
  link="stujenske.lab@gmail.com"
%}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Funding

{% capture content %}

{% include figure.html image="images/NIH-NIMH-logo-new.png" %}

{% endcapture %}

{% include grid.html content=content %}

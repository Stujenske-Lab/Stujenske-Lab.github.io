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

{% include section.html background="images/background.jpg" dark=true opacityval=".5" %}

# <span style="color:white">We are hiring!</span>

<span style="color:white">
  The laboratory has funding for multiple positions, including lab technicians, graduate students, and postdocs. <br/><br/>
    ***Technicians***: Experimental experience preferred but not required. <br/>
    ***Graduate students***: Should have an interest in programming and imaging or electrophysiology. <br/>
    ***Postdocs***: Experience with computer programming, imaging, or electrophysiology strongly preferred.
</span>

{%
  include button.html
  text="Research Specialist job posting"
  link="https://careers.upmc.com/job/20001800/research-specialist-the-stujenske-lab-pittsburgh-pa/"
  icon="fa-solid fa-arrow-right"
%}

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

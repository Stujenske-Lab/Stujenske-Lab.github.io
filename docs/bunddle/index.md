---
---

# The Stujenske Lab

Our team provides a critical bridge between basic neuroscience research and clinical application. As both a neuroscientist and practicing psychiatrist, Dr. Joe Stujenske leads the laboratory in investigating how cognitive circuits regulate both behavioral and somatic responses to appropriate respond in a changing environment. It remains unknown how individuals can be cognitively trained to adapatively suppress unwanted behaviors and somatic experiences, and how these processes go wrong for those with psychiatric conditions. For instance, how are some individuals able to put on a show despite experiencing performance anxiety, while others are frozen with panic and unable to speak? The cognitive control that regulates the confluence of internal state, behavior, and somatic reactivity are poorly understood, and it is the central aim of the lab to understand how top-down regulatory circuits function in a variety of internal states. Dr. Stujenske's principal focus has been on defensive states, which have relevance to anxiety disorders, PTSD, and OCD, but the lab's interests are broad, extending to appetitive states, interoception, and behavioral choice selection, among other topics.

The lab studies the structure and function of neural circuits, with a strong interest in the relationship between the functional properties of neuronal populations and their genetic and molecular profiles. The principal techniques employed by the lab are simultaneous behavioral and somatic monitoring, in vivo two photon calcium imaging, in vivo extraceullar electrophysiology with silicon probes, and optogenetics.

{%
  include button.html
  type="docs"
  link="https://greene-lab.gitbook.io/lab-website-template-docs"
%}
{%
  include button.html
  type="github"
  text="On GitHub"
  link="greenelab/lab-website-template"
%}

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="tools"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

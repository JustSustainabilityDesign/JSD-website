---
title: Home
image_sliders:
  - slider2
---

{% include section.html background="#dbebba" %}

# {% include icon.html icon="fa-solid fa-feather-pointed" %} Just Sustainability Design Lab

{% include section.html %}

## What We Do and Why

The **Just Sustainability Design Lab (JSD Lab)** at the University of Toronto’s Faculty of Information explores how technology can serve social justice, environmental sustainability, and community well-being.
At the lab, researchers, students, and community partners come together to imagine and design technologies that **sustain life rather than deplete it**. We work across fields and disciplines to create systems and practices that foster **life, equity, and care**.

At the JSD Lab, we believe **another tech future is possible**. Through transdisciplinary research, collaborative design, and public engagement, we pursue:

- **Technologies Otherwise**: exploring **degrowth** and other **pathways to postgrowth**, and challenging the cultures of consumption and infinite capital accumulation.

- **Just Sustainabilities**: integrating **environmental and social justice** into computing and technology design. 

- **Convivial Technologies**: cultivating systems that nurture **cooperation, community, and joy** beyond the confines of capitalism.

## Current Projects
{% include list.html component="card" data="currentprojects" filters="group: "%}

## Completed Projects
{% include list.html component="card" data="completedprojects" filters="group: "%}

## Who We Are
### Current Members
{% include list.html data="members" component="portrait" filters="role: professor, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: masters, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: " %}

[##]: #

{%
  include button.html
  type=""
  text="Joining the Lab"
  link= "lab/#prospective-students"

%}

{%
  include button.html
  type=""
  text="Learn More"
  link= "lab/"

%}

{% include section.html background="#dbebba" %}

# {% include icon.html icon="fa-solid fa-microscope" %} Introducing Just Sustainability Design

{% include section.html %}

## What is Just Sustainability Design
Just Sustainability Design, JSD for short, is a framework for systems design practice, research, and pedagogy that privileges sustainability and justice and therefore, the asymmetric and uneven effects of systems design choices at a distance. JSD aims to bring about improvement, not just avoid damage. 

JSD was introduced in Professor Becker's book, Insolvent: How to reorient computing for just sustainability. To learn more about Just Sustainability Design, see the resources below.


{% capture col1 %}

{%
  include figure.html
  image="images/compulsory.png"
%}

{% endcapture %}

{% capture col2 %}

[##]: #

|

|

|

|

|
{%
  include button.html
  type=""
  text="Read Insolvent For Free"
  link="https://direct.mit.edu/books/oa-monograph/5594/InsolventHow-to-Reorient-Computing-for-Just"
%}

{%
  include button.html
  type=""
  text="Get Your Copy"
  link="https://mitpress.mit.edu/9780262545600/insolvent/"
%}

{%
  include button.html
  type=""
  text="Learn More About Insolvent"
  link="/insolvent/"
%}
|
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}


## Research Funding

{% capture col1 %}

{%
  include figure.html
  image="images/uoft-school-of-cities.jpg"
  caption="School of Cities"
  height="105px"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/ontario research fund.jpg"
  caption="Ontario Research Fund"
  height="105px"

%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/NSERC.jpg"
  caption="NSERC"
  height="105px"
%}

{% endcapture %}

{% capture col4 %}

{%
  include figure.html
  image="images/innovation-ca-canada-foundation-for-innovation-cfi-logo-vector.png"
  caption="Canada Foundation for Innovation"
  height="105px"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 col4=col4 %}




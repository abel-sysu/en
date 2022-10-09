---
title: Research
nav:
  order: 1
  tooltip: Research topics and published works
---

# <i class="fas fa-microscope"></i>Research

The Aquatic Biodiveristy Evolution Laboratory (ABEL) at the School of Ecology, Sun Yat-sen University is a young, vibrant lab with a broad interest of aquatic animals, biodiversity, and evolution. We like hanging out in the nature, getting fired up about molecular lab and codes, while contemplating the mysteries of life. We welcome students and scholars sharing our interests from different nations and cultural backgrounds. We are currently recruiting postdocs, master students and undergraduate helpers. Ongoing projects include:

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  headline="Our Research"
  text=text
%}

{% capture text %}
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

[See our resources &nbsp;→](resources)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="resources"
  headline="Our Resources"
  text=text
%}

{% capture text %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

[Meet our team &nbsp;→](team)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  headline="Our Team"
  text=text
%}

# Publications

{% include section.html %}

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}

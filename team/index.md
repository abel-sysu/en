---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# Team

We are a young, vibrant lab with enthusiasts of aquatic animals, biodiversity, biogeography and evolution. We like hanging out in the nature, getting fired up about molecular lab and codes, while contemplating the mysteries of life. We welcome students and scholars sharing our interests from different nations and cultural backgrounds. We are currently recruiting postdocs, master students and undergraduate helpers. Do check out our website and contact me to know more about us!

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: staff"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postgrad"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}
{:.center}
{% include section.html %}
<br><br>ALUMNI<br>
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: alumni"
%}
{:.center}



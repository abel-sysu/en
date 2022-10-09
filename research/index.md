---
title: Research
nav:
  order: 1
  tooltip: Research topics and published works
---
{% include section.html %}

# Research Interests

The Aquatic Biodiveristy Evolution Laboratory (ABEL) at the School of Ecology, Sun Yat-sen University is a young, vibrant lab with a broad interest of aquatic animals, biodiversity, and evolution. We like hanging out in the nature, getting fired up about molecular lab and codes, while contemplating the mysteries of life. We welcome students and scholars sharing our interests from different nations and cultural backgrounds. We are currently recruiting postdocs, master students and undergraduate helpers. Ongoing projects include:
<br>
{% include section.html %}
<br>
{% capture text %}
We use NGS sequencing to investigate the phylogenetic relationships of various crustacean lineages. These robust phylogenies will be crucial frameworks for examining how diverse physiological and adaptive features evolved.<br>
*References:<br>
* [Phylogenomic analyses of brachyuran crabs support early divergence of primary freshwater crabs](https://www.sciencedirect.com/science/article/pii/S1055790318301805)<br>
{% endcapture %}

{%
  include feature.html
  image="research/crustacea.png"
  title="Phylogenomics and phylohysiology of crustaceans"
  text=text
%}

{% capture text %}
Freshwater decapods are some of the most species rich and rapidly diversifying lineages of crustacean with diverse life styles, sizes, habitats, and colour patterns. Through extensive surveys, and cutting-edge phylogenomic and biogeographic analyses, and genome surveys we strive to understand how these diverse freshwater fauna evolved.<br>
*References:*<br>
* [Contrasting population structures of freshwater atyid shrimps in Hong Kong and their conservation implications](https://www.publish.csiro.au/mf/MF21069)<br>
* [Conservation of freshwater wildlife in Hong Kong: A genetic perspective](https://onlinelibrary.wiley.com/doi/abs/10.1002/aqc.3211)<br>
{% endcapture %}

{%
  include feature.html
  image="research/atyid.png"
  title="Biogeography and evolution of freshwater decapods"
  flip=true
  text=text
%}

{% capture text %}
We construct the phylogeny of reef fish lineages using multiple molecular markers and examine the temporal and spatial pattern of diversification of these ecologically important marine fauna.<br>
*Reference:*<br>
* [Phylogeography and conservation biogeography of the humphead wrasse, Cheilinus undulatus](https://escholarship.org/content/qt1wt383wf/qt1wt383wf.pdf)<br>
* [The historical biogeography of groupers: Clade diversification patterns and processes](https://www.sciencedirect.com/science/article/pii/S1055790316000567)<br>
{% endcapture %}

{%
  include feature.html
  image="research/reeffish.png"
  title="Phylogeny and phylogeography of reef fish"
  text=text
%}


{% include section.html %}

# Publications

{% include section.html %}

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" filter="page: kayan-ma" style="rich" %}

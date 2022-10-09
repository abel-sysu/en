---
title: Research
nav:
  order: 1
  tooltip: Research topics and published works
---

# <i class="fas fa-microscope"></i>Research

The Aquatic Biodiveristy Evolution Laboratory (ABEL) at the School of Ecology, Sun Yat-sen University is a young, vibrant lab with a broad interest of aquatic animals, biodiversity, and evolution. We like hanging out in the nature, getting fired up about molecular lab and codes, while contemplating the mysteries of life. We welcome students and scholars sharing our interests from different nations and cultural backgrounds. We are currently recruiting postdocs, master students and undergraduate helpers. Ongoing projects include:
<br>
***
<br>
{% capture text %}
We use NGS sequencing to investigate the phylogenetic relationships of various crustacean lineages. These robust phylogenies will be crucial frameworks for examining how diverse physiological and adaptive features evolved.
Reference:
Phylogenomic analyses of brachyuran crabs support early divergence of primary freshwater crabs

{%
  include feature.html
  image="research/crustacea.png"
  title="Phylogenomics and phylohysiology of crustaceans"
  text=text
%}
{% endcapture text %}

{% capture text %}
Freshwater decapods are some of the most species rich and rapidly diversifying lineages of crustacean with diverse life styles, sizes, habitats, and colour patterns. Through extensive surveys, and cutting-edge phylogenomic and biogeographic analyses, and genome surveys we strive to understand how these diverse freshwater fauna evolved.
Reference:
Contrasting population structures of freshwater atyid shrimps in Hong Kong and their conservation implications
Conservation of freshwater wildlife in Hong Kong: A genetic perspective
Phylogenomic analyses of brachyuran crabs support early divergence of primary freshwater crabs

{%
  include feature.html
  image="research/atyid.png"
  title="Biogeography and evolution of freshwater decapods"
  flip=true
  text=text
%}
{% endcapture text %}

{% capture text %}
We construct the phylogeny of reef fish lineages using multiple molecular markers​ and examine the temporal and spatial pattern of diversification of these ecologically important marine fauna.
Reference:
Phylogeography and conservation biogeography of the humphead wrasse, Cheilinus undulatus
The historical biogeography of groupers: Clade diversification patterns and processes

{%
  include feature.html
  image="research/reeffish.png"
  title="Phylogeny and phylogeography of reef fish"
  text=text
%}

{% endcapture text %}

{% include section.html %}

# Publications

{% include section.html %}

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}

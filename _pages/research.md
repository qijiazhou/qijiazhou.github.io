---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My current research focus is in protoplanetary disks and the chemistry of planet formation. I am also interested in investigating prebiotic chemistry on Earth, in the Solar System, and beyond. 
<hr style = 'background-color:#CCCAC9  ; border-width:0; color:#CCCAC9; height:1px; width:100%;' />

{% include base_path %}

<!-- New style rendering if publication categories are defined -->
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

<!--## Competitive Entrapment in Interstellar and Cometary Ices-->
<!---->
<!--filler text-->
<!---->
<!--<hr style = 'background-color:#CCCAC9  ; border-width:0; color:#CCCAC9; height:1px; width:100%;' />-->
<!---->
<!--## False Planets around Giant Stars-->
<!---->
<!--Discovering planets in sparsely populated regions of parameter space is crucial to improving our understanding of planetary formation and evolution. One such region is the subset of planets that orbit giant, evolved stars. However, some evolved stars are known to exhibit quasi-periodic radial velocity (RV) signals, which can masquerade as signals from planetary companions. A paper by Brucalassi et al. (2017) reports the discovery of a giant planet with a period of 121 days orbiting Sanders 364. From our analysis of a large set of independent RVs, we find no convincing evidence for the reported giant planet. In this paper, we discuss possible explanations for the discrepancies between our findings and Brucalassi et al. (2017), potential sources of long-period non-planetary RV signals, and recommendations for future study of planets orbiting evolved stars.-->
<!---->
<!---->
<!--<hr style = 'background-color:#CCCAC9  ; border-width:0; color:#CCCAC9; height:1px; width:100%;' />-->


---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<!-- New style rendering if publication categories are defined 
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
-->
## Papers

<ol reversed>

<li>
J. Stojkovic, C. Alverti, A. Andrade, <b>N. Iliakopoulou</b>, T. Xu, H. Franke, J. Torrellas. (March 2025). &quot;Concord: Rethinking Distributed Coherence for Software Caches in Serverless Environments&quot;. <i>To Appear in Proceedings of the 31st IEEE International Symposium on High-Performance Computer Architecture (HPCA)</i>. Paper: <a href="https://jovans2.github.io/files/Concord_HPCA25.pdf" target="_blank">[PDF]</a>. 
</li>
  
<li> J. Stojkovic, <b>N. Iliakopoulou</b>, T. Xu, H. Franke, J. Torrellas. (June 2024). &quot;EcoFaaS: Rethinking the Design of Serverless Environments for Energy Efficiency
&quot;.	<i>In Proceedings of the 51st International Symposium on Computer Architecture (ISCA)</i>.
Paper: <a href="https://jovans2.github.io/files/EcoFaaS_ISCA2024_Final.pdf" target="_blank">[PDF]</a>.
</li>


</ol>

## Preprints

<ol reversed>

<li>
<b>N. Iliakopoulou</b>, J. Stojkovic, C. Alverti, T. Xu, H. Franke, J. Torrellas. (November 2024). &quot;Chameleon: Adaptive Caching and Scheduling for Many-Adapter LLM Inference Environments&quot;. <i>CoRR, vol. abs/2411.17741 </i>. Paper: <a href="https://arxiv.org/abs/2411.17741" target="_blank">[PDF]</a>
</li>

</ol>

## Workshops, Posters, Demo

<ol reversed>
<li>
<b>N. Iliakopoulou</b>, J. Stojkovic, C. Alverti, T. Xu, H. Franke, J. Torrellas. (March 2025). &quot; Adaptive Caching and Scheduling for Many-Adapter LLM Inference Environments &quot;. <i>7th Young Architect Workshop (YArch'25, in conjuction with ASPLOS'25)</i>.
</li>
</ol>






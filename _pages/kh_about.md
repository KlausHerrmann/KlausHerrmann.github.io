---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<a href="https://www.usherbrooke.ca/mathematiques/nous-joindre/personnel/corps-professoral/professeurs/klaus-herrmann">I'm an assistant professor</a> at the <a href="https://www.usherbrooke.ca/mathematiques/">Department of mathematics</a>, Faculty of science of the <a href="https://www.usherbrooke.ca/">Université de Sherbrooke</a> in Sherbrooke, Canada.

<div style="text-align: justify">My research interests are centered around dependence concepts in statistics and probability theory. Specific topics include copula-induced dependence structures, the aggregation of dependent random variables, extreme value theory and multivariate risk measures, with application to portfolio selection and quantitative risk management. Numerical computations of joint probabilities and the evaluation of joint distribution functions is also one of my ongoing research topics.</div>

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

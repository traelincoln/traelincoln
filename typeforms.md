---
permalink: /typeforms/
layout: default
---
{% if site.typeforms %}
<ul>
{% for typeform in site.typeforms %}
<li>
  <h2>
    <a href="{{ typeform.url }}" >{{ typeform.title }}</a>
  </h2>
</li>
{% endfor %}
</ul>
{% else %}
  <h2>No typeforms found.</h2>
{% endif %}
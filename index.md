---
---

## Events Articles

{% capture content %}
{% include list.html component="card" data="posts" %}
{% endcapture %}

{%
  include grid.html
  content=content
%}

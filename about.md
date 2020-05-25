---
layout: default
title: About Vinit Kumar
---

<h1 class="owner-name">{{ site.owner.name}} </h1>
![user-avatar]({{ site.owner.avatar }})

{{site.about}}

Vinit lives in Pune, with his son Advik and wife Rituparna. Rituparna is the founder of a Digital Marketing Company <a href="https://scoophubs.com" target="_blank">ScoopHubs.com</a></p>

<div class="pagination">
  {% if site.owner.linkedin %}
    <a href="{{ site.owner.linkedin }}" class="social-media-icons"><i class="fa fa-2x fa-linkedin-square" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.email %}
    <a href="mailto:{{ site.owner.email }}" class="social-media-icons"><i class="fa fa-2x fa-envelope-square" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.twitter %}
    <a href="https://twitter.com/{{ site.owner.twitter }}" class="social-media-icons"><i class="fa fa-2x fa-twitter-square" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.github %}
    <a href="{{ site.owner.github }}" class="social-media-icons"><i class="fa fa-2x fa-github-square" aria-hidden="true"></i></a>
  {% endif %}
</div>

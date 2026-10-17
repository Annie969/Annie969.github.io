---
layout: archive
title: "CV"
permalink: /cv/
published: false
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- Optional: put your PDF at files/cv.pdf and uncomment the next line -->
<!-- [Download CV (PDF)](/files/cv.pdf) -->

Education
======
<!-- TODO: rewrite before re-enabling this page -->

Research Interests
======
<!-- TODO: rewrite before re-enabling this page -->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

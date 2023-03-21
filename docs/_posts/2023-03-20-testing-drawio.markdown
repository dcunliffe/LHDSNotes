---
layout: post
title:  "Test Drawio"
date:   2023-03-20 16:30:00 +0000
categories: LDHS Test
mermaid: true
---

This is a test post:

## Test image:
![Alt text]({{site.baseurl}}/drawings/test.drawio.svg)

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}


## Test Mermaid:
<div class="mermaid">
gantt 
    title A Gantt Diagram
    dateFormat  YYYY-MM-DD
    section Section
    A task           :a1, 2014-01-01, 30d
    Another task     :after a1  , 20d
    section Another
    Task in sec      :2014-01-12  , 12d
    another task      : 24d
</div>

<div class="mermaid">
pie title Pets adopted by volunteers 
    "Dogs" : 386
    "Cats" : 85
    "Rats" : 15
</div>
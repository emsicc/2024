---
layout: page
title: EMSICC
subtitle: Energy Management for Sustainable Internet-of-Things and Cloud Computing
use-site-title: true
---

# Speakers
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  {% for p in site.data.speakers %}
  {% if forloop.index<8 %}
  <div class="row">
    <div class="col-sm-6">
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    </div>
    <div class="col">
    {% capture id %}{{ p[1] }}{% endcapture %}
    {% include profile_detail.html p=p %}
    </div>
  </div>
  <br>
  {% endif %}
  {% endfor %}
</div>

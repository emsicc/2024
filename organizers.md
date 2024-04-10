---
layout: home
title: EMSICC
subtitle: Workshop on Energy Management for Sustainable Internet-of-Things and Cloud Computing (Vienna, Austria [Hybrid] 19-21 August 2024)
---

# Organizers

<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endfor %}
  </div>
</div>
<hr>

# Scientific Committee

<div class="container">
  <ul class="list-group list-group-flush">
    {% for p in site.data.pc.people %}
      <li class="list-group-item col-xs-12 col-sm-12 col-md-12">{{ p }}</li>
    {% endfor %}
  </ul>
</div>
<hr>

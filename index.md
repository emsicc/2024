---
layout: home
title: EMSICC
subtitle: Workshop on Energy Management for Sustainable Internet-of-Things and Cloud Computing
---

With the emergence of wireless communications, geolocation technologies and cloud computing,
innovative applications are designed for the Internet of Things (IoT) and Cyber-physical systems,
targeting intensive data computations and virtualization technologies. Due to their constraints
in terms of energy, computational power, memory, high mobility, sporadic connectivity, and sometimes
security constraints, some smart devices need to outsource data storage, application hosting and
computation to the Cloud. Hence, the IoT and Cyber-physical systems require efficient and adaptive
energy management solutions that optimize energy consumption through energy-aware communications
protocols, scheduling methods, self-organization mechanisms, offloading techniques, and security
solutions, among others. In addition, alternative energy sources available in their surrounding
environments could be used to achieve perpetual functioning without replacing or recharging batteries
as often through energy harvesting. Furthermore, energy management and optimization are also a
concern for cloud data centers that need efficient management of power and performance for computing
and air conditioning, and of environmental impact. These factors largely improvise cost versus energy
optimization, which can be achieved through various approaches like optimization, computational
intelligence and machine learning.


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

# Program Committee

<div class="container">
  <ul class="list-group list-group-flush">
    {% for p in site.data.pc.people %}
      <li class="list-group-item col-xs-6 col-sm-4 col-md-3">{{ p }}</li>
    {% endfor %}
  </ul>
</div>
<hr>
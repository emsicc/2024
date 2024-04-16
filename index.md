---
layout: home
title: EMSICC
subtitle: Workshop on Energy Management for Sustainable Internet-of-Things and Cloud Computing (Vienna, Austria [Hybrid] 19-21 August 2024)
cover-img: /assets/img/wien_1.jpg
---

<div
  style="width:300px;height: 300px"
>
  <img
    src="{{ site.baseurl }}/assets/img/logo_emsicc2024_fond-fonce.png"
    style="width: 200px;margin:5px"
  />
</div>

Co-located with the [11th IEEE International Conference on Future Internet of Things and Cloud (FiCloud 2024)](https://ficloud.org/2024/)

This workshop will address a range of problems related to energy-aware, energy-efficient management
solutions for designing distributed computing platforms (software and hardware) for the IoT, Cyber-physical
and Cloud Computing systems.

With the emergence of wireless communications, geolocation technologies and cloud computing, innovative applications are designed for the Internet of Things (IoT) and Cyber-physical systems, targeting intensive data computations and virtualization technologies. Due to their constraints in terms of energy, computational power, memory, high mobility, sporadic connectivity, and sometimes security constraints, some smart devices need to outsource data storage, application hosting, and computation to the Cloud. Hence, the IoT and Cyber-physical systems require efficient and adaptive energy management solutions that optimize energy consumption through energy-aware communications protocols, scheduling methods, self-organization mechanisms, offloading techniques, and security solutions, among others. We encourage submissions around the development of energy-aware methodologies and technologies that improve the collection, transmission, storage, and processing.

The potential effects of these technologies on the machine learning processes that are executed in the cloud using the data collected by IoT and Cyber-physical systems should be considered and analyzed. In the presence of energy constraints, the machine learning processes may be hindered and see their performances deteriorate. Many factors can be at the origin of these performance degradations. Energy-aware strategies, e.g., intermittent transmissions, decrease in sensing precision, reduction of the sampling frequency, etc., may compromise the availability of data in a timely manner and increase uncertainty in the data. Furthermore, in the case of distributed machine learning, energy-aware strategies may lead to heterogeneity in terms of the updates that the cloud receives from the distributed local IoT and Cyber-physical systems. For example, standard aggregation-based machine learning algorithms, like federated learning, are highly impacted by the heterogeneity in terms of the transmission rates of the IoT and Cyber-physical systems. All these aspects have an impact on the machine learning processes that are performed in the cloud, however, it is not yet well understood how it manifests and how it could be taken into account. This workshop provides a forum to discuss these aspects and devise new directions for future research.

Alternative energy sources available in the IoT and Cyber-physical systems’ surrounding environments could be used to achieve perpetual functioning without replacing or recharging batteries as often through energy harvesting. Machine learning is key to developing such strategies, e.g., analyzing patterns of energy consumption to adapt energy harvesting strategies, etc. Furthermore, energy management and optimization are also concerns for cloud data centers, which need efficient management of power and performance for computing and air conditioning and of environmental impact. These factors largely improve cost versus energy optimization, which can be achieved through various approaches like optimization, computational intelligence, and machine learning.




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

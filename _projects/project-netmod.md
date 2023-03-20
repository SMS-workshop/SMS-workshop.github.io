---
layout: page
title: Network Modeling
description: SNA@KDD
img: assets/img/projects/int_netmod.png
importance: 1
category: Research Lines
---

**Network Science** is an interdisciplinary research field characterized by relevant contributions from computer science, physics, and social science. 
The mathematical models it offers are effectively used to describe, in an abstract space, countless real-world phenomena spanning from biological interactions to human behaviors. 

Networks model relations among a set of entities, e.g., it can be used to model messages exchanged on an online social platform as edges connecting pairs of platform users, the network nodes. 

When dealing with human behaviors, classical network science studies mainly assume social interactions to be effectively approximable with simple, static, directed/undirected networks. 
Although allowing several valuable analyses, such oversimplification has been proven to offer a too simplistic proxy for gaining a deeper understanding of often dynamic, multi-resolution, and non-necessarily binary phenomena. 

Recent advances in theoretical network science have pushed the research boundaries toward enriched network models to overcome those limitations. 
Dynamic, multi-layered, high-order, and feature-rich networks are, nowadays, the most active - often disjoint - research directions devised to fulfill such a goal. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/net1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/dyn1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ft.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

#### Objectives
Our research aims at three different and complementary goals:
- define enhanced network models to properly describe complex phenomena (e.g., fusing feature-rich, dynamic and higher-order ones);
- propose novel algorithms aimed at extracting valuable knowledge from networked data;
- propose stable methodologies to statistically validate network models and algorithms.

Main Collaborations: [Dino Pedreschi](https://scholar.google.it/citations?hl=it&user=5efz6osAAAAJ) (UNIPI), [Tiziano Squartini](https://scholar.google.it/citations?hl=it&user=xevG7aEAAAAJ) (IMT)
{: .alert .alert-success}


<div class="publications">
  <h4>Related (selected) publications</h4>
  {% bibliography -f papers -q @*[net=true]* %}
</div>
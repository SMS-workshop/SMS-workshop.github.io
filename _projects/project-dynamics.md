---
layout: page
title: Network Dynamics
description: SNA@KDD
img: assets/img/projects/int_dyn.png
importance: 2
category: Research Lines
---

One of the most challenging task in network mining regards the analysis of temporal annotated data. 
Temporal annotated node/edge sequences can be built from data produced by a wide spectrum of human related processes ranging from social interactions to mobility traces and financial operations. 
The ability to extract information from such timestamped observations became crucial when we need to make inference on the behaviors of time-evolving complex systems. 

Without loss of generality, we can state that the ultimate goal of temporal network mining is to discover hidden relations between sequences and subsequences of events in order to describe and/or forecast the behaviors of the observed phenomena.

A wide range of analysis can be performed on static networks, however the phenomena we are used to observe, as well as the world we live in, are constantly evolving: as time goes by relationships change, links are substituted by new ones, new collaborations arise and old ones fall apart.
Freezing networks in time is certainly very useful in order to observe, study and categorize some of their peculiar traits but it is not enough if we are interested in understanding the dynamics that regulate their lives. 
Hence, for some of the most interesting network problems can be provided augmented formulations that take into account the role played by time.

Looking at the plethora of evolutionary issues nowadays studied in the complex networks field, we can build a simple, even if not extensive, classification:

**Individual Dynamics:**
In this category fall all those problems which analyze how local structures, edges and nodes, rise and fall (i.e. Link/Node Prediction, Dynamic Vertex Coloring. . . ).

**Collective Dynamics:**
Here the main focus is analyzing how topology changes when local structures do (i.e. Dynamic Community Detection, Frequent Patterns. . . ).

**Diffusion Processes:**
To this last category belong all those tasks whose aim is to understand how information flow on network structures (both in the case of static and dynamic structure/topology).


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/dyn1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/link.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ndlib.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

#### Objectives

Our research aims at three different and complementary goals:
- define novel algorithms to study dynamic network topologies;
- define novel models to address diffusive processes (e.g., epidemics, opinion dynamics) unfolding on top of complex topologies;
- understand the feedback loops linking together topological dynamics and diffusive processes. 

Main Collaborations: [Rémy Cazabet](https://scholar.google.it/citations?user=ZPeN_HAAAAAJ&hl=it) (University of Lyon), [Janos Kertesz](https://scholar.google.it/citations?hl=it&user=KVaEpnkAAAAJ) (CEU), [Alina Sirbu](https://scholar.google.it/citations?hl=it&user=o-G11bQAAAAJ) (UNIPI).
{: .alert .alert-success}


<div class="publications">
  <h4>Related (selected) publications</h4>
  {% bibliography -f papers -q @*[dyn=true]* %}
</div>
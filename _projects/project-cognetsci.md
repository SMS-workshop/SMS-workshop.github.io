---
layout: page
title: Cognitive NetSci
description: SNA@KDD
img: assets/img/projects/int_cog.png
importance: 5
category: Research Lines
---

**Cognitive Network Science** is a recent interdisciplinary field involving the study of human cognition, whose subject of study is the human mental lexicon modeled as a networked entity of words/concepts, being these latter ones the basis for thought and communication. 
It arises as a complementary field to traditional psycholinguistic studies dedicated to the analysis of word’s properties only, such as valence, arousal, dominance, concreteness.
Since several lines of research are implicitly moving towards the direction of *feature-rich modelling*, we claim that such a framework is a natural extension - or, better, a synthesis - of the layout proposed by current methodological cognitive network science studies. 

---
- **Domain(s):** Linguistics, Psychology, Cognitive Science, Computer Science;
- **System:** Human Cognition, Mental Lexicon, Semantic Memory, Phonological Memory, Syntactic Knowledge;
- **Node:** Concepts, Words or their sub-units, e.g. phonemes, morphemes;
- **Relation(s):** Free associations, hyponym-hypernym, synonyms, antonyms, feature-sharing relations, phonological similarities, syntactic dependencies;
- **Topology:**
  - *Graph:* words are pair-wise connected if they share a linguistic similarity, e.g., they are synonyms, they are recalled together in a word association task, or they co-occur in sentences; 
  - *Higher-order:* data acquisition like co-occurrence methods naively allows to represent such relations as simplices and improve structural mining as in the discovery of knowledge gaps; in some word association tasks, participants are asked to give more than one associated responses to a cue word: an hyperedge can be formed between this triad, and an hypergraph consequently built;
- **Semantics:**
  - *Attributed:* word length, word frequency in corpora or in child-directed speech, degree of polysemy, valence, arousal, dominance, concreteness constitute linguistic information that can be attached to the words; it is possible to relate these properties to words’ connectivity in the mental lexicon analyzing assortative mixing;
  – *Multilayer:* free associations, synonyms, phonological similarities, etc. constitute different layers of the human mental lexicon; it is possible to combine these linguistic levels and analyze them together to reveal complex patterns in early word acquisition or clusters of words used with greater frequency, memorized and learned more easily;
  – *Dynamic:* words are acquired earlier or later in the process of language acquisition, and word acquisition can be modelled as a process on a mental lexicon structure, like a random walk on a graph; the human mental lexicon characterizes as an evolving system, and its topology can be compared at different ages.

---

As it is possible to observe, many rich information is available from words with respect to their psycholinguistic properties as well as with respect to the relations and similarities with other words. 
Classic psycholinguistic studies focus on words’ properties only, whereas cognitive network science focus on the structure emerging from word connections, aiming to relate such connections to language functions and cognitive processes. 
Beyond this strong parallelism, feature-rich models can support the unification of such fragmented and parallel fields of research and the analyses they involve. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ft.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/br.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/em.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

#### Objectives
Our research aims at three complementary goals:
- develop a feature-rich network framework for the study of human cognition, the mental lexicon and language acquisition;
- pursue data-driven research in the field of cognitive network science, using the developed tools/Algorithms to analyze data from psycholinguistic experiments;
- define a sound methodologies to extract emotional profiles starting from user generated contents (UGCs).

Main Collaborations: [Massimo Stella](https://scholar.google.it/citations?hl=it&user=TUJkCbkAAAAJ) (CogNosco Lab)
{: .alert .alert-success}


<div class="publications">
  <h4>Related (selected) publications</h4>
  {% bibliography -f papers -q @*[cog=true]* %}
</div>
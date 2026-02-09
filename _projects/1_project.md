---
layout: page
title: Representations in atomistic ML 
img: assets/img/publication_preview/descriptors.png
importance: 1
category: work
---

I have spent some time wondering about the fundamental questions about crafting inputs to atomistic ML models, which are also closely tied to their architectures. More specifically, in terms of descriptors, what are the ingredients central to their mathematical representations? How can we incorporate equivariance with the physical symmetries underlying structures in 3D Euclidean space? How to ensure that two structures unrelated by symmetries are mapped to different descriptors? How can we capture long-range (Coulomb) interactions into machine learning models while keeping a local description of atomic environments? 
Another line of research has been on identifying the similarities and differences between models that rely on these descriptors as inputs and models that work directly with input structures (such as graph neural networks). 


<!-- _pages/publications.md -->
<div class="publications">
    {% bibliography -f papers -q @*[reps=true]* --template paper_link.liquid %}
</div>

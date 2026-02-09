---
layout: page
title: Modeling QM operators  
description:
img: assets/img/publication_preview/ham.png
importance: 2
category: work
---

I am interested in strategies to learn electronic structure intermediates. As an alternative to building ML surrogates for individual properties, targeting electronic structure directly has led to the growth of integrated ML models. I have worked on machine learning representations of the effective single-particle Hamiltonian on an atomic-orbital basis. This effort to learn a matrix with elements indexed by two atoms was guided by understanding its symmetries with respect to rotations, inversions and permutations of the atom labels. 
We also explore _indirect_ models of the Hamiltonian, where we learn an intermediate representation of the matrix, optimizing it to instead reproduce properties that can be derived from it. This open the door to a lot of exciting possibilities where we can learn a smaller and transferable representation of the Hamiltonian for a higher level of theory or from calculations performed on a larger basis! 

If you're keen to try out some of the machinery we have developed for this purpose, I encourage you to checkout our [recipe](https://atomistic-cookbook.org/latest/examples/periodic-hamiltonian/periodic-hamiltonian.html)! 
<!-- _pages/publications.md -->
<div class="publications">
  <h2> Related publications</h2>
  {% bibliography -f papers -q @*[ham=true]* --template paper_link.html %}
</div>

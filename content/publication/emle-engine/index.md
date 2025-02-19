---
title: "emle-engine: A Flexible Electrostatic Machine Learning Embedding Package for Multiscale Molecular Dynamics Simulations"
authors:
  - Kirill
  - Lester Hedges
  - Ruben
  - Christopher Woods
  - Inaki
  - Marc W. van der Kamp
date: "2024-05-28"
doi: "10.1021/acs.jctc.4c00248"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication: "J. Chem. Theory. Comput."
publication_types: ["article-journal"]

abstract: "We present in this work the emle-engine package (https://github.com/chemle/emle-engine)─the implementation of a new machine learning embedding scheme for hybrid machine learning potential/molecular-mechanics (ML/MM) dynamics simulations. The package is based on an embedding scheme that uses a physics-based model of the electronic density and induction with a handful of tunable parameters derived from in vacuo properties of the subsystem to be embedded. This scheme is completely independent of the in vacuo potential and requires only the positions of the atoms of the machine learning subsystem and the positions and partial charges of the molecular mechanics environment. These characteristics allow emle-engine to be employed in existing QM/MM software. We demonstrate that the implemented electrostatic machine learning embedding scheme (named EMLE) is stable in enhanced sampling molecular dynamics simulations. Through the calculation of free energy surfaces of alanine dipeptide in water with two different ML options for the in vacuo potential and three embedding models, we test the performance of EMLE. When compared to the reference DFT/MM surface, the EMLE embedding is clearly superior to the MM one based on fixed partial charges. The configurational dependence of the electronic density and the inclusion of the induction energy introduced by the EMLE model leads to a systematic reduction in the average error of the free energy surface when compared to MM embedding. By enabling the usage of EMLE embedding in practical ML/MM simulations, emle-engine will make it possible to accurately model systems and processes that feature significant variations in the charge distribution of the ML subsystem and/or the interacting environment."

url_pdf: https://pubs.acs.org/doi/epdf/10.1021/acs.jctc.4c00248?ref=article_openPDF
url_code: https://github.com/chemle/emle-engine

---

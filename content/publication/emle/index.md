---
title: "Electrostatic Embedding of Machine Learning Potentials"
authors:
  - Kirill
date: "2023-02-23"
doi: "10.1021/acs.jctc.2c00914"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication: "J. Chem. Theory. Comput."
publication_types: ["article-journal"]

abstract: "This work presents a variant of an electrostatic embedding scheme 
that allows the embedding of arbitrary machine learned potentials trained on 
molecular systems in vacuo. The scheme is based on physically motivated models 
of electronic density and polarizability, resulting in a generic model without 
relying on an exhaustive training set. The scheme only requires in vacuo single
point QM calculations to provide training densities and molecular dipolar 
polarizabilities. As an example, the scheme is applied to create an embedding 
model for the QM7 data set using Gaussian Process Regression with only 445 
reference atomic environments. The model was tested on the SARS-CoV-2 protease 
complex with PF-00835231, resulting in a predicted embedding energy RMSE of 
2 kcal/mol, compared to explicit DFT/MM calculations."

url_pdf: https://pubs.acs.org/doi/epdf/10.1021/acs.jctc.2c00914?ref=article_openPDF
url_code: https://github.com/emedio/embedding

---

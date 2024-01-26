---
title: Propagating uncertainty in brain networks- from graph representation to clinical decisions
author: ["Sarah Morgan"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["sarahmorgan","carlhenrikek"]
summary: Macroscopic brain networks derived from MRI provide a unique window into the brain and could help predict mental health conditions. However, the role of uncertainty is often overlooked. This project aims to 1) quantify the uncertainty for individual brain network edges and 2) propagate that uncertainty to estimate the confidence associated with predictions made using brain networks. Ultimately, understanding uncertainty is essential for AI algorithms to help inform clinical decision-making.
---

Macroscopic brain networks derived from MRI data provide a unique window into the structural and functional organization of the brain. Substantial research has shown that such brain networks can help understand and predict mental health conditions, from shedding light on differences in brain activity between patients with mental health conditions and healthy control subjects (Morgan et al, PNAS 2019; Da Costa et al, NeurIPS 2022), to predicting disease trajectories for individual patients (Homan et al, Neuropsychopharmacology 2019).

However, the role of uncertainty in these networks is often overlooked. Traditional approaches for constructing brain networks only give a point estimate of connectivity for each edge, with no estimate of uncertainty. Graphs are then often used as input for classification or regression tasks, to predict e.g. diagnosis or prognosis, however again the uncertainty associated with these predictions is rarely considered. Ultimately, understanding the confidence associated with a particular prediction will be essential for AI algorithms to feed in to clinical decision making. Uncertainty thresholding could also improve accuracy for high confidence predictions, as in other domains (Dolezal et al, 2022), opening the door to new clinical applications and biological understanding.

This project will explore methods to 1) quantify the uncertainty of brain network edges and 2) propagate that uncertainty to estimate the confidence associated with predictions in a classification or regression task. One promising approach is to build on a recently proposed method for constructing functional brain networks, which provides a distribution of functional connectivity values for each edge (Lbath et al, 2023). Another possibility is to develop uncertainty estimates for structural brain connectomes, e.g. building on the new MIND method proposed by (Sebenius et al, 2023). The student will then explore probabilistic modelling frameworks to propagate uncertainty from these graph representations to a graph classification or regression task, e.g. age prediction or case/control classification. To that end, several large MRI datasets will be available, e.g. a case/control dataset with N=900 healthy control subjects and cases with psychotic disorders, and a developmental dataset with N=655 subjects aged 8-21 years.

Ultimately, understanding the role of uncertainty in human brain networks is crucial for brain networks to inform clinical decision making.

***References***

Morgan et al, “Cortical patterning of abnormal morphometric similarity in psychosis is associated with brain expression of schizophrenia-related genes”, PNAS, 116 (19) 9604-9609, 2019,
https://doi.org/10.1073/pnas.182075411

Da Costa et al, “Transformer-based normative modelling for anomaly detection of early schizophrenia”, NeurIPS 2022, https://doi.org/10.48550/arXiv.2212.04984

Homan et al, “Structural similarity networks predict clinical outcome in early-phase psychosis”, Neuropyschopharmacology, 44, 915-922, 2019, https://doi.org/10.1038%2Fs41386-019-0322-y

Dolezal et al, “Uncertainty-informed deep learning models enable high-confidence predictions for digital histopathology”, Nature Communications, 13, 6572, 2022, https://doi.org/10.1038/s41467-022-34025-x

Lbath et al, “Clustering-Based Inter-Regional Correlation Estimation”, arXiv, 2023, 
https://doi.org/10.48550/arXiv.2302.07596

Sebenius et al, “Robust estimation of cortical similarity networks from brain MRI”, Nature Neuroscience, 26, 1461-1471, 2023, https://doi.org/10.1038%2Fs41593-023-01376-7

---
title: "Credal Probabilistic Machine Learning"
author: ["michelecaprio"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["michelecaprio"]
summary: "You will conduct research at the frontier of probabilistic machine learning leveraging uncertainty in the form of credal sets to overcome shortcomings of SOTA techniques, and to shape the boundary of knowledge on quantifying uncertainty in complex systems. You will publish your scientific results in internationally renowned journals and present them at international top-tier conferences and workshops. You will collaborate with fellow researchers, actively contributing to research projects."
---

The probabilistic tools typically used in machine learning can suffer from shortcomings. For example, the uniform distribution is not able to distinguish between indifference and ignorance [1]: are we using equal weights because we know that outcomes are all equally probable, or because we are ignorant about which are the more likely to obtain? We can overcome this drawback, known as the Laplace's paradox, by using credal sets, that is, closed and convex sets of probabilities [2]. Credal sets are also instrumental for representing aleatoric and epistemic uncertainties (AU and EU, resp.), two quantities that are of great importance in ML and AI [3]. The former refers to irreducible uncertainty, so in the presence of an excess of AU, the model should abstain from producing a result and query for human help. EU instead is reducible, and can be lessened on the basis of additional data. In this project, you will work on both the theoretical and methodological aspects of credal probabilistic machine learning (CPML), producing results that will advance the field of safe and trustworthy AI [10, 11, 12]. Particular attention will be given to how credal sets are learned in a proper way to represent the designer's uncertainty about their predictions. This will provide impact across any field where decision-making is critical, and will advance the state of the art on model interpretability and explainability, which in turn will improve the users’ trust in the results provided by the models.

You will conduct research at the frontier of probabilistic machine learning leveraging uncertainty in a statistical manner to overcome shortcomings like Laplace’s paradox, and to shape the boundary of knowledge on quantifying uncertainty in complex systems. You will publish your scientific results in internationally renowned journals and present them at international top-tier conferences and workshops. You will collaborate with fellow researchers, actively contributing to research projects. 

The topics of interest include, but are not limited to, the following. 

A comparison between conformal prediction regions and regions resulting from CPML techniques. Conformal prediction [4] is a very popular distribution-free uncertainty quantification technique which provides prediction regions equipped with (user-defined) statistical guarantees. CPML techniques, instead, are model-based, and the goal would be to see whether the required modeling effort is rewarded with a region that is narrower than the conformal one, while enjoying the same guarantees. Recently [5], we showed that in the case of “vanilla” conformal prediction – based on the exchangeability assumption – credal regions are wider than conformal regions when the designer faces high uncertainty, while they are narrower when the uncertainty faced is moderate. Hence, depending on the degree of ambiguity, the designer chooses either of the two techniques. You will inspect how these results extend to more general notions of conformal prediction [6]. 

Credal Variational Inference (CVI). Currently, in Bayesian ML, to approximate an intractable posterior P, Variational Inference (VI) procedures [7] choose probability measure Q that minimizes the KL divergence between Q and a set S of well-behaved probabilities (oftentimes Normal distributions). Such Q, though, could be a bad approximation of P. You will develop CVI, where different distributions from different well-behaved sets are chosen. Their convex hull then forms a credal set, which either includes the true posterior P, or is closer to it than any of its elements taken individually. 

Credal learning theory [8]. In this line of work, you will extend the existing results in learning theory [9] (e.g. the concentration of the expected risk of the empirical risk minimizer to the expected risk of the best model) to the credal sets framework, to be able to account for distribution shift and to hedge against distribution misspecification.

**References**

[1] Introduction to Imprecise Probabilities; Augustin, Coolen, de Cooman, Troffaes; https://onlinelibrary.wiley.com/doi/book/10.1002/9781118763117

[2] Statistical Reasoning with Imprecise Probabilities; Walley; https://philpapers.org/rec/WALSRW

[3] Aleatoric and epistemic uncertainty in machine learning: an introduction to concepts and methods; Hüllermeier, Waegeman;  https://link.springer.com/article/10.1007/s10994-021-05946-3

[4] A tutorial on conformal prediction; Shafer and Vovk; https://jmlr.csail.mit.edu/papers/volume9/shafer08a/shafer08a.pdf

[5] Relationship between Conformal Prediction and Imprecise Probabilities; Caprio, Sale, Lee; Available upon request

[6] Conformal Prediction Beyond Exchangeability; Barber, Candes, Ramdas, Tibshirani; https://arxiv.org/pdf/2202.13415.pdf

[7] Variational Inference: A Review for Statisticians; Blei, Kucukelbir, McAuliffe; https://arxiv.org/abs/1601.00670

[8] Credal Learning Theory; Caprio, Sultana, Elia, Cuzzolin; Available upon request

[9] Statistical learning theory; Liang; https://web.stanford.edu/class/cs229t/notes.pdf

[10] Imprecise Bayesian Neural Networks; Caprio et al; https://arxiv.org/abs/2302.09656

[11] Imprecise Evidential Classification; Caprio et al; Available upon request

[12] Distributionally Robust Statistical Verification with Imprecise Neural Networks; Dutta et al; https://arxiv.org/pdf/2308.14815.pdf
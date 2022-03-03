---
title: "Pareto-Rational Verification"

authors:
- Véronique Bruyère
- Jean-François Raskin
- admin

date: 2022-02-27
# doi:

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

publication: CoRR
publication_short: CoRR

abstract: We study the rational verification problem which consists in verifying the correctness of a system executing in an environment that is assumed to behave rationally. We consider the model of rationality in which the environment only executes behaviors that are Pareto-optimal with regards to its set of objectives, given the behaviour of the system (which is committed in advance of any interaction). When the objectives are ω-regular, we prove that the Pareto-rational verification problem is co-NP-complete and fixed-parameter tractable (FPT) in the number of objectives of the environment. When the objectives are described by LTL formulas, the problem is PSPACE-complete as the classical LTL model- checking problem. In order to evaluate the applicability of our results in practice, we have implemented and evaluated two variations of our FPT algorithm on our running example and on randomly generated instances.

tags: [Rational verification, Model-checking, Pareto-optimality, Parity objectives]

featured: false

url_pdf: https://arxiv.org/pdf/2202.13485.pdf

---

---
title: "Pareto-Rational Verification"

authors:
- Véronique Bruyère
- Jean-François Raskin
- admin

date: 2022-09-06
# doi: 10.4230/LIPIcs.CONCUR.2022.33

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

publication: 33rd International Conference on Concurrency Theory (CONCUR 2022)
publication_short: CONCUR 2022

abstract: We study the rational verification problem which consists in verifying the correctness of a system executing in an environment that is assumed to behave rationally. We consider the model of rationality in which the environment only executes behaviors that are Pareto-optimal with regard to its set of objectives, given the behavior of the system (which is committed in advance of any interaction). We examine two ways of specifying this behavior, first by means of a deterministic Moore machine, and then by lifting its determinism. In the latter case the machine may embed several different behaviors for the system, and the universal rational verification problem aims at verifying that all of them are correct when the environment is rational. For parity objectives, we prove that the Pareto-rational verification problem is co-NP-complete and that its universal version is in PSPACE and both NP-hard and co-NP-hard. For Boolean Büchi objectives, the former problem is Π₂𝖯-complete and the latter is PSPACE-complete. We also study the case where the objectives are expressed using LTL formulas and show that the first problem is PSPACE-complete, and that the second is 2EXPTIME-complete. Both problems are also shown to be fixed-parameter tractable for parity and Boolean Büchi objectives.

tags: [Rational verification, Model-checking, Pareto-optimality, Omega-regular objectives]

featured: false

url_pdf: https://drops.dagstuhl.de/opus/volltexte/2022/17096/pdf/LIPIcs-CONCUR-2022-33.pdf

---

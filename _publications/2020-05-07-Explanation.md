---
title: "Explanation-Guided Backdoor Poisoning Attacks Against Malware Classifiers"
collection: publications
permalink: /publication/2020-05-07-Explanation
excerpt: ''
date: 2020-05-07
venue: 'To appear in USENIX Security 2021'
paperurl: 'https://arxiv.org/abs/2003.01031'
citation: 'Severi, Giorgio, Jim Meyer, Scott Coull, and Alina Oprea. "Explanation-Guided Backdoor Poisoning Attacks Against Malware Classifiers" arXiv preprint arXiv:2003.01031 (2020).'
---

[Paper](https://arxiv.org/abs/2003.01031)

Training pipelines for machine learning (ML) based malware classification often
rely on crowdsourced threat feeds, exposing a natural attack injection point. In
this paper, we study the susceptibility of feature-based ML malware classifiers
to backdoor poisoning attacks, specifically focusing on challenging "clean
label" attacks where attackers do not control the sample labeling process. We
propose the use of techniques from explainable machine learning to guide the
selection of relevant features and values to create effective backdoor triggers
in a model-agnostic fashion. Using multiple reference datasets for malware
classification, including Windows PE files, PDFs, and Android applications, we
demonstrate effective attacks against a diverse set of machine learning models
and evaluate the effect of various constraints imposed on the attacker. To
demonstrate the feasibility of our backdoor attacks in practice, we create a
watermarking utility for Windows PE files that preserves the binary's
functionality, and we leverage similar behavior-preserving alteration
methodologies for Android and PDF files. Finally, we experiment with potential
defensive strategies and show the difficulties of completely defending against
these attacks, especially when the attacks blend in with the legitimate sample
distribution.

<pre>
@misc{severi2021explanationguided,
      title={Explanation-Guided Backdoor Poisoning Attacks Against Malware Classifiers}, 
      author={Giorgio Severi and Jim Meyer and Scott Coull and Alina Oprea},
      year={2021},
      eprint={2003.01031},
      archivePrefix={arXiv},
      primaryClass={cs.CR}
}
</pre>

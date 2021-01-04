---
title: "Exploring Backdoor Poisoning Attacks Against Malware Classifiers"
collection: publications
permalink: /publication/2020-05-07-Exploring
excerpt: ''
date: 2020-05-07
venue: 'ArXiv'
paperurl: 'https://arxiv.org/abs/2003.01031'
citation: 'Severi, Giorgio, Jim Meyer, Scott Coull, and Alina Oprea. "Exploring Backdoor Poisoning Attacks Against Malware Classifiers." arXiv preprint arXiv:2003.01031 (2020).'
---

[Paper](https://arxiv.org/abs/2003.01031)

Abstract - Current training pipelines for machine learning (ML) based malware
classification rely on crowdsourced threat feeds, exposing a natural attack
injection point. We study for the first time the susceptibility of ML malware
classifiers to backdoor poisoning attacks, specifically focusing on challenging
"clean label" attacks where attackers do not control the sample labeling
process. We propose the use of techniques from explainable machine learning to
guide the selection of relevant features and their values to create a watermark
in a model-agnostic fashion. Using a dataset of 800,000 Windows binaries, we
demonstrate effective attacks against gradient boosting decision trees and a
neural network model for malware classification under various constraints
imposed on the attacker. For example, an attacker injecting just 1% poison
samples in the training process can achieve a success rate greater than 97% by
crafting a watermark of 8 features out of more than 2,300 available features. To
demonstrate the feasibility of our backdoor attacks in practice, we create a
watermarking utility for Windows PE files that preserves the binary's
functionality. Finally, we experiment with potential defensive strategies and
show the difficulties of completely defending against these powerful attacks,
especially when the attacks blend in with the legitimate sample distribution.


<pre>
@misc{severi2020exploring,
    title={Exploring Backdoor Poisoning Attacks Against Malware Classifiers},
    author={Giorgio Severi and Jim Meyer and Scott Coull and Alina Oprea},
    year={2020},
    eprint={2003.01031},
    archivePrefix={arXiv},
    primaryClass={cs.CR}
}
</pre>

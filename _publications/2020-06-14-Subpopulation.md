---
title: "Subpopulation Data Poisoning Attacks"
collection: publications
permalink: /publication/2020-06-14-Subpopulation
excerpt: ''
date: 2020-06-14
venue: 'ArXiv'
paperurl: 'https://arxiv.org/abs/2006.14026'
citation: 'Jagielski, Matthew, Giorgio Severi, Niklas Pousette Harger, and Alina Oprea. "Subpopulation data poisoning attacks." arXiv preprint arXiv:2006.14026 (2020).'
---

[Paper](https://arxiv.org/abs/2006.14026)

Machine learning systems are deployed in critical settings, but they might fail in unexpected ways, impacting the accuracy of their predictions. Poisoning attacks against machine learning induce adversarial modification of data used by a machine learning algorithm to selectively change its output when it is deployed. In this work, we introduce a novel data poisoning attack called a \emph{subpopulation attack}, which is particularly relevant when datasets are large and diverse. We design a modular framework for subpopulation attacks, instantiate it with different building blocks, and show that the attacks are effective for a variety of datasets and machine learning models. We further optimize the attacks in continuous domains using influence functions and gradient optimization methods. Compared to existing backdoor poisoning attacks, subpopulation attacks have the advantage of inducing misclassification in naturally distributed data points at inference time, making the attacks extremely stealthy. Our impossibility result for defending against subpopulation attacks and the limitations of existing defenses highlight the difficulty of protecting machine learning against this new threat vector.

<pre>
@misc{jagielski2020subpopulation,
      title={Subpopulation Data Poisoning Attacks},
      author={Matthew Jagielski and Giorgio Severi and Niklas Pousette Harger and Alina Oprea},
      year={2020},
      eprint={2006.14026},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
</pre>

---
title: "Subpopulation Data Poisoning Attacks"
collection: publications
permalink: /publication/2020-06-14-Subpopulation
excerpt: ''
date: 2020-06-14
venue: 'ACM CCS 2021'
paperurl: 'https://arxiv.org/abs/2006.14026'
citation: 'Jagielski, Matthew, Giorgio Severi, Niklas Pousette Harger, and Alina Oprea. "Subpopulation data poisoning attacks." In Proceedings of the 2021 ACM SIGSAC Conference on Computer and Communications Security, pp. 3104-3122. 2021.'
---

[Paper](https://arxiv.org/abs/2006.14026)

Machine learning systems are deployed in critical settings, but they might fail in unexpected ways, impacting the accuracy of their predictions. Poisoning attacks against machine learning induce adversarial modification of data used by a machine learning algorithm to selectively change its output when it is deployed. In this work, we introduce a novel data poisoning attack called a \emph{subpopulation attack}, which is particularly relevant when datasets are large and diverse. We design a modular framework for subpopulation attacks, instantiate it with different building blocks, and show that the attacks are effective for a variety of datasets and machine learning models. We further optimize the attacks in continuous domains using influence functions and gradient optimization methods. Compared to existing backdoor poisoning attacks, subpopulation attacks have the advantage of inducing misclassification in naturally distributed data points at inference time, making the attacks extremely stealthy. Our impossibility result for defending against subpopulation attacks and the limitations of existing defenses highlight the difficulty of protecting machine learning against this new threat vector.

<pre>
@inproceedings{jagielski2021subpopulation,
  title={Subpopulation data poisoning attacks},
  author={Jagielski, Matthew and Severi, Giorgio and Pousette Harger, Niklas and Oprea, Alina},
  booktitle={Proceedings of the 2021 ACM SIGSAC Conference on Computer and Communications Security},
  pages={3104--3122},
  year={2021}
}
</pre>

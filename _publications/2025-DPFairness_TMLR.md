---
title: "Private and Fair Machine Learning: Revisiting the Disparate Impact of Differentially Private SGD"
collection: publications
category: papers
permalink: /publication/2025-DPFairness_TMLR
excerpt: ''
date: 2025-10-01
venue: 'Transactions on Machine Learning Research'
paperurl: 'https://openreview.net/forum?id=o8zrx0bfTp'
citation: 'Demelius, L., Kopeinik, S., Kowald, D., Kern, R., Trügler, A. (2025). Private and Fair Machine Learning: Revisiting the Disparate Impact of Differentially Private SGD. Transactions on Machine Learning Research.'
---

Abstract: Differential privacy (DP) is a prominent method for protecting information about individuals during data analysis. Training neural networks with differentially private stochastic gradient descent (DPSGD) influences the model's learning dynamics and, consequently, its output. This can affect the model's performance and fairness. While the majority of studies on the topic report a negative impact on fairness, it has recently been suggested that fairness levels comparable to non-private models can be achieved by optimizing hyperparameters for performance directly on differentially private models (rather than re-using hyperparameters from non-private models, as is common practice). In this work, we analyze the generalizability of this claim by 1) comparing the disparate impact of DPSGD on different performance metrics, and 2) analyzing it over a wide range of hyperparameter settings. We highlight that a disparate impact on one metric does not necessarily imply a disparate impact on another. Most importantly, we show that while optimizing hyperparameters directly on differentially private models does not mitigate the disparate impact of DPSGD reliably, it can still lead to improved utility-fairness trade-offs compared to re-using hyperparameters from non-private models. We stress, however, that any form of hyperparameter tuning entails additional privacy leakage, calling for careful considerations of how to balance privacy, utility and fairness. Finally, we extend our analyses to DPSGD-Global-Adapt, a variant of DPSGD designed to mitigate the disparate impact on accuracy, and conclude that this alternative may not be a robust solution with respect to hyperparameter choice.
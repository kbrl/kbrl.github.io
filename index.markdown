---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# layout: home
layout: page
title: Overview
permalink: /
---
# KBRL at IJCAI-PRICAI 2020, Yokohama, Japan

**[Call for papers is over.](https://kbrl.github.io/cfp/)**

**For Dates and Location: [Please refer to IJCAI Workshops page](https://www.ijcai20.org/workshops.html)**

In recent years, deep Reinforcement Learning (RL) has been widely used in various domains including computer games, robotics, vision, and language. For applications in real-world environments, state of the art reinforcement learning algorithms suffer from a wide range of challenges such as sample inefficiency, safety constraints, partial observability, dynamic environments, hidden rewards insystems, and explainability.

Meanwhile, recent years have seen a blooming in research on supervised learning, where various types of knowledge are leveraged to help deep neural models to master a task. For instance, knowledge bases (which can either be human labeled or automatically retrieved) are widely used as knowledge sources (in addition to text) in natural language understanding tasks (Ferrucci et al., 2010; Daset al., 2017). Models using pre-trained word embeddings (Mikolov et al., 2013; Pennington et al., 2014; Mikolov et al., 2018) and pre-trained language models (Devlin et al., 2018; Yang et al., 2019) empirically show strong performance on a host of tasks with language components. Similarly, in the vision domain, it is a common practice to initialize a deep neural model by using pre-trained weight matrices on ImageNet (He et al., 2017).

In addition to incorporating knowledge as an extra input, or into weight matrices, the community has been studying the injection of human understanding of tasks into the structure of neural networks as inductive biases for decades (Rumelhart et al., 1988; Hochreiter and Schmidhuber, 1997; LeCunet al., 2015; Kipf and Welling, 2016). Moreover, knowledge can also be acquired by an agent by experiencing and interacting with the world on the fly (building and maintaining a memory during training) (Ha and Schmidhuber, 2018).

We believe that incorporating knowledge can potentially solve many of the most pressing challenges facing reinforcement learning today. The primary goal of this workshop is to facilitate community building: we hope to bring researchers together to consolidate this line of research and foster collaboration in the community.

The topics relevant to this workshop will cover a wide variety of methods and problems in the area, including but not limited to:
- Safe Reinforcement Learning;
- Reinforcement Learning for Natural Language Understanding;
- Real-world applications of Reinforcement Learning;
- Relational Reinforcement Learning;
- Model-based Reinforcement Learning;
- Using external knowledge for efficient Reinforcement Learning;
- Transfer Learning for Reinforcement Learning;
- Symbol grounding and Abstractions for Reinforcement Learning;
- Hierarchical Reinforcement Learning;
- Benchmarks for Knowledge guided Reinforcement Learning.

# Diversity and Inclusion

This workshop aims to provide an environment with open exchange of ideas, freedom of thought and expression, and respectful scientific debate.
Thus harassment and hostile behavior (including but not limited to harassment based on race, gender, religion, age, color, appearance, national origin, ancestry, disability, sexual orientation, or gender identity) are unwelcome in the workshop.

During the workshop, any participant who experiences harassment or hostile behavior may contact any of our organizing committee members, the organizers will take actions upon the situation to make sure we have a diverse, inclusive and friendly environment.

# References

- Das, R., Dhuliawala, S., Zaheer, M., Vilnis, L., Durugkar, I., Krishnamurthy, A., Smola, A. J., andMcCallum, A. (2017). Go for a walk and arrive at the answer: Reasoning over paths in knowledge bases using reinforcement learning. CoRR, abs/1711.05851.
- Devlin, J., Chang, M., Lee, K., and Toutanova, K. (2018). BERT: pre-training of deep bidirectional transformers for language understanding. CoRR, abs/1810.04805.
- Ferrucci, D. A., Brown, E. W., Chu-Carroll, J., Fan, J. Z., Gondek, D., Kalyanpur, A., Lally, A., Murdock, J. W., Nyberg, E., Prager, J. M., Schlaefer, N., and Welty, C. A. (2010). Building watson: An overview of the deepqa project. AI Magazine, 31:59–79.
- Ha, D. and Schmidhuber, J. (2018). Recurrent world models facilitate policy evolution. In Advances in Neural Information Processing Systems 31, pages 2451–2463. Curran Associates, Inc. https://worldmodels.github.io.
- He, K., Gkioxari, G., Dollár, P., and Girshick, R. B. (2017). Mask R-CNN.CoRR, abs/1703.06870.
- Hochreiter, S. and Schmidhuber, J. (1997). Long short-term memory. Neural Comput., 9(8):1735–1780.
- Kipf, T. N. and Welling, M. (2016). Semi-supervised classification with graph convolutional networks.CoRR, abs/1609.02907.
- LeCun, Y., Bengio, Y., and Hinton, G. (2015). Deep learning. Nature, 521(7553):436–444.
- Mikolov, T., Grave, E., Bojanowski, P., Puhrsch, C., and Joulin, A. (2018). Advances in pre-training distributed word representations. In Proceedings of the International Conference on Language Resources and Evaluation (LREC 2018).
- Mikolov, T., Sutskever, I., Chen, K., Corrado, G., and Dean, J. (2013). Distributed representations of words and phrases and their compositionality. In Proceedings of the 26th International Conference on Neural Information Processing Systems - Volume 2, NIPS’13, pages 3111–3119, USA. Curran Associates Inc.
- Pennington, J., Socher, R., and Manning, C. D. (2014). Glove: Global vectors for word representation. In Empirical Methods in Natural Language Processing (EMNLP), pages 1532–1543.
- Rumelhart, D. E., Hinton, G. E., and Williams, R. J. (1988). Neurocomputing: Foundations of research. Chapter Learning Representations by Back-propagating Errors, pages 696–699. MITPress, Cambridge, MA, USA.
- Yang, Z., Dai, Z., Yang, Y., Carbonell, J. G., Salakhutdinov, R., and Le, Q. V. (2019). Xlnet: Generalized autoregressive pretraining for language understanding. CoRR, abs/1906.08237.

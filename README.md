# A systematic study of GANs under limited supervision for classification tasks

Our aim is to investigate the usage of Generative Adversarial Networks (GANs) as a framework of working with limited supervision in Natural Language processing, specifically Sentence classification tasks. We treat the work of [Croce et al., 2020](https://aclanthology.org/2020.acl-main.191) as a baseline approach, which used GAN to work with BERT language model. Our approach will be to experiment by varying different language models such as GAN with XLNET, RoBERTa, TinyBERT, AlBERT, ELECTRA. We anticipate a basic computational challenge in terms of resources required for training GANs with language models, because of which we will start with TinyBERT and AlBERT, which are lot faster to start with. The motivation underlies in the fact to achieve comparable, if not better, performances in limited supervision settings for downstream tasks.


# Reference(s):
1. Croce, D., Castellucci, G., and Basili, R. GAN-BERT:
[Generative adversarial learning for robust text classification with a bunch of labeled examples](https://aclanthology.org/2020.acl-main.191) In Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics, pp. 2114–2119, Online, July 2020. Association for Computational Linguistics. 


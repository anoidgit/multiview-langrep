# Bridging linguistic typology and multilingual machine translation with multi-view language representations

Sparse language vectors from linguistic typology databases and learned embeddings from tasks like multilingual machine translation have been investigated in isolation, without analysing how they could benefit from each other's language characterisation. We propose to fuse both views using singular vector canonical correlation analysis and study what kind of information is induced from each source. By inferring typological features and language phylogenies, we observe that our representations embed typology and strengthen correlations with language relationships. We then take advantage of our multi-view language vector space for multilingual machine translation, where we achieve competitive overall translation accuracy in tasks that require information about language similarities, such as language clustering and ranking candidates for multilingual transfer. With our method, we can easily project and assess new languages without expensive retraining of massive multilingual or ranking models, which are major disadvantages of related approaches.

## How to project your language-level representations

Once the paper is published, code will be released here, but contact the authors if you want to give it a (preliminary) try.

## Cite
```
@article{oncevay-etal-2020-bridging,
  title={Bridging linguistic typology and multilingual machine translation with multi-view language representations},
  author={Arturo Oncevay, Barry Haddow and Alexandra Birch},
  journal={arXiv preprint},
  year={2020},
  url={https://arxiv.org/abs/2004.14923}
}
```

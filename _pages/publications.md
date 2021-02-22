---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

**2020**
1. **Li R.\***, Peng X.*, Lin C., Guerin F. and Rong W. On the Low-density Latent Regions of VAE-based Language Models, Pre-registration workshop (**NeurIPS**) 2020, Vancouver, Canada.
2. **Li R.**, Li X., Chen G. and Lin C. Improving Variational Autoencoder for Text Modelling with Timestep-Wise Regularisation, The 28th International Conference on Computational Linguistics (**COLING**), 2020.<br />
[\[pdf\]](https://arxiv.org/pdf/2011.01136.pdf)<br />
3. Li X., Chen G., Lin C. and **Li R.** DGST: a Dual-Generator Network for Text Style Transfer, Conference on Empirical Methods in Natural Language Processing (**EMNLP**), 2020.<br/>
[\[pdf\]](https://arxiv.org/pdf/2010.14557.pdf)<br />
4. Li X., Lin C., **Li R.**, Wang C. and Guerin F. Latent Space Factorisation and Manipulation via Matrix Subspace Projection, The 37th International Conference on Machine Learning (**ICML**), Vienna, 2020.<br/>
[\[pdf\]](https://arxiv.org/pdf/1907.12385.pdf)<br />

**2019**

1. **Li R.**, Lin C., Collinson M., Li X. and Chen G. A Dual-Attention Hierarchical Recurrent Neural Network for Dialogue Act Classification, The SIGNLL Conference on Computational Natural Language Learning (**CoNLL**), Hong Kong, China, 2019.<br/>
[\[pdf\]](https://www.aclweb.org/anthology/K19-1036.pdf) [\[BibTex\]](https://www.aclweb.org/anthology/K19-1036.bib)<br />
2. **Li R.**, Li X.,  Lin C, Collinson M. and Mao R. A Stable Variational Autoencoder for Text Modelling, The 12th International Conference on Natural Language Generation (**INLG**), Tokyo, 2019.<br/>
[\[pdf\]](https://www.aclweb.org/anthology/W19-8673.pdf) [\[BibTex\]](https://www.aclweb.org/anthology/W19-8673.bib)<br />

**2018**

1. Mao R., Chen G., **Li, R.** and Lin C. *ABDN at SemEval-2018 Task 10: Recognising Discriminative Attributes using Context Embeddings and WordNet.* The International Workshop on Semantic Evaluation at the 16th Annual Conference of the North American Chapter of the Association for Computational Linguistics  (**NAACL**), New Orleans, 2018.<br/>
[\[pdf\]](https://www.aclweb.org/anthology/S18-1169.pdf) [\[BibTex\]](https://www.aclweb.org/anthology/S18-1169.bib)<br />



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


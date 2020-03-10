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

**2019**

1. **Li R.**, Lin C., Collinson M., Li X. and Chen G. A Dual-Attention Hierarchical Recurrent Neural Network for Dialogue Act Classification, The SIGNLL Conference on Computational Natural Language Learning (**CoNLL**), Hong Kong, China, 2019.
2. **Li R.**, Li X.,  Lin C, Collinson M. and Mao R. A Stable Variational Autoencoder for Text Modelling, The 12th International Conference on Natural Language Generation (**INLG**), Tokyo, 2019.

**2018**

1. Mao R., Chen G., **Li, R.** and Lin C. *ABDN at SemEval-2018 Task 10: Recognising Discriminative Attributes using Context Embeddings and WordNet.* The International Workshop on Semantic Evaluation at the 16th Annual Conference of the North American Chapter of the Association for Computational Linguistics  (**NAACL**), New Orleans, 2018.<br/>
[\[pdf\]](https://www.aclweb.org/anthology/S18-1169.pdf) [\[BibTex\]](https://www.aclweb.org/anthology/S18-1169.bib)<br />



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


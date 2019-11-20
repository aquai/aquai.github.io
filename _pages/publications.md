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

## arXiv preprints
1. Out-of-domain Detection for Natural Language Understanding in Dialog Systems<br />
Zheng Y., **Chen G.**, and Huang M.<br />
**arXiv preprint**, arXiv:1909.03862<br />
[\[pdf\]](https://arxiv.org/pdf/1909.03862.pdf)

## 2019
1. A Dual-Attention Hierarchical Recurrent Neural Network for Dialogue Act Classification<br />
Li R., Lin C., Collinson M., Li X., and **Chen G.**<br />
**CoNLL** *2019*, Hong Kong, China<br />
2. QTUNA: A Corpus for Understanding How Speakers Use Quantification<br />
**Chen G.**, van Deemter K., Pagliaro S., Smalbil L., and Lin C.<br />
**INLG** *2019*, Tokyo<br />
[\[Data\]](https://github.com/a-quei/qtuna)<br />
3. Generating Quantified Descriptions of Abstract Visual Scenes<br />
**Chen G.**, van Deemter K., and Lin C.<br />
**INLG** *2019*, Tokyo<br />
[\[Code\]](https://github.com/a-quei/quantified-description-generation)<br />
4. A Closer Look at Recent Results of Verb Selection for Data-to-Text NLG<br />
**Chen G.**, and Yao J.<br />
**INLG** *2019*, Tokyo<br />
5. Persona-aware Dialogue Generation with Enriched Profile<br />
Zheng Y., **Chen G.**, Huang M., Liu S., and Zhu X.<br />
*NeurIPS 2019 on* **Conversational AI** *Workshop*, Vancouver<br />
[\[pdf\]](https://arxiv.org/pdf/1901.09672.pdf)

## 2018
1.  ABDN at SemEval-2018 Task 10: Recognising Discriminative Attributes using Context Embeddings and WordNet<br />
Mao R., **Chen G.**, Li, R., and Lin C.<br />
*NAACL 2018 on* **SemEval** *Workshop*, New Orleans<br />
[\[pdf\]](http://aclweb.org/anthology/S18-1169) [\[BibTex\]](https://aclanthology.coli.uni-saarland.de/papers/S18-1169/s18-1169.bib)<br />
2. Modelling Various Kinds of Specifications \(extended abstract\)<br />
**Chen G.**, van Deemter K., and Lin C.<br />
**CoMPPrag** *Workshop*, Bochum, 2018<br />
[\[pdf\]]({{ site.url }}/files/Modelling_Various_Kinds_of_Specifications.pdf) [\[slide\]]({{ site.url }}/files/compprag2018.pdf)<br />
3. SimpleNLG-ZH: a Linguistic Realisation Engine for Mandarin<br />
**Chen G.**, van Deemter K., and Lin C. <br />
**INLG** *2018*, Tilburg<br />
[\[pdf\]](http://aclweb.org/anthology/W18-6506) [\[BibTex\]](https://aclanthology.info/papers/W18-6506/w18-6506.bib) [\[Code\]](https://github.com/a-quei/simplenlg-zh)<br />
4. Modelling Pro-drop with the Rational Speech Acts Model<br />
**Chen G.**, van Deemter K., and Lin C.<br />
**INLG** *2018*, Tilburg<br />
[\[pdf\]](http://aclweb.org/anthology/W18-6519) [\[BibTex\]](https://aclanthology.info/papers/W18-6519/w18-6519.bib)<br />
5. Building a Large-scale Persona Dialog Dataset <br />
Zheng Y., **Chen G.**, and Huang M.<br />
*INLG 2018 on* **HRI-MLG** *Workshop*, Tilburg<br />
[\[pdf\]](https://dspace.library.uu.nl/handle/1874/373955)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

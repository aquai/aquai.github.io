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

## 2018
1.  ABDN at SemEval-2018 Task 10: Recognising Discriminative Attributes using Context Embeddings and WordNet<br />
Mao R., **Chen G.**, Li, R. and Lin C.<br />
*NAACL 2018 on* **SemEval** *Workshop*, New Orleans<br />
[\[pdf\]](http://aclweb.org/anthology/S18-1169) [\[BibTex\]](https://aclanthology.coli.uni-saarland.de/papers/S18-1169/s18-1169.bib)<br />
2. Modelling Various Kinds of Specifications \(extended abstract\)<br />
**Chen G.**, van Deemter K. and Lin, C.<br />
**CoMPPrag** *Workshop*, Bochum, 2018<br />
3. SimpleNLG-ZH: a Linguistic Realisation Engine for Mandarin<br />
**Chen G.**, van Deemter K. and Lin, C. <br />
**INLG** *2018*, Tilburg<br />
4. Modelling Pro-drop with the Rational Speech Acts Model<br />
**Chen G.**, van Deemter K. and Lin, C.<br />
**INLG** *2018*, Tilburg<br />

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

* A New Benchmark and Reverse Validation Method for Passage-level Hallucination Detection<br />
**Shiping Yang**, Renliang Sun, Xiaojun Wan. **EMNLP 2023 (Findings)**
* Multi-level Contrastive Learning for Scripts-based Character Understanding<br />
Dawei Li, Hengyuan Zhang, Yanran Li, **Shiping Yang**. **EMNLP 2023**
* A New Dataset and Empirical Study for Sentence Simplification in Chinese<br />
**Shiping Yang**, Renliang Sun, Xiaojun Wan. **ACL 2023**
* Fine-grained Contrastive Learning for Definition Generation<br />
Hengyuan Zhang, Dawei Li, **Shiping Yang**, Yanran Li. **AACL 2022 (Oral)**

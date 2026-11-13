---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a first-year Ph.D. candidate in Computer Science at the Hong Kong University of Science and Technology (HKUST), where I am advised by Prof. Junxian He at the HKUST NLP Group. I received my B.Eng. from Shanghai Jiao Tong University (SJTU) in June 2024. My research lies at the intersection of natural language processing and machine learning.

## Research Interests

- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM Truthfulness and Interpretability

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology (2024 -- Present)
- **B.Eng.**, Shanghai Jiao Tong University (2020 -- 2024)

## Research Experience

- **Research Intern**, MINIMAX (February 2025 -- Present)
- **Research Intern**, Tencent WXG (June 2024 -- September 2024), advised by Zifei Shan
- **Research Intern**, Shanghai AI Lab (June 2023 -- December 2023), advised by Prof. Yu Cheng

## Publications

{% assign sorted_publications = site.publications | sort: "date" | reverse %}
{% for post in sorted_publications %}
- [**{{ post.title }}**]({{ site.baseurl }}{{ post.url }})<br/>{{ post.citation }}
{% endfor %}

You can also find my articles on my [Google Scholar profile]({{ site.author.googlescholar }}).

## Honors & Awards

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

## Contact

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
- Google Scholar: [profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)

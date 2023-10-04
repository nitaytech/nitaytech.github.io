---
title: "Measuring the Robustness of Natural Language Processing Models to Domain Shifts"
collection: publications
permalink: /publication/calderon2023measuring
venue: 'arXiv, 2023 (work in progress)'
paperurl: 'https://doi.org/10.48550/arXiv.2306.00168'
citation: 'Nitay Calderon, Naveh Porat, Eyal Ben-David, Zorik Gekhman, Nadav Oved and Roi Reichart'
date: 2023-06-12
---
<details>
<summary>Abstract</summary>
Large Language Models have shown promising performance on various tasks, including fine-tuning, few-shot learning, and zero-shot learning.
However, their performance on domains without labeled data still lags behind those with labeled data, which we refer as the Domain Robustness (DR) challenge.
Existing research on DR suffers from disparate setups, lack of evaluation task variety, and reliance on challenge sets.
In this paper, we explore the DR challenge of both fine-tuned and few-shot learning models in natural domain shift settings.
We introduce a DR benchmark comprising diverse NLP tasks, including sentence and token-level classification, QA, and generation, each task consists of several domains.
We propose two views of the DR challenge: Source Drop (SD) and Target Drop (TD), which alternate between the source and target in-domain performance as reference points.
We find that in significant proportions of domain shifts, either SD or TD is positive, but not both, emphasizing the importance of considering both measures as diagnostic tools.
Our experimental results demonstrate the persistent existence of the DR challenge in both fine-tuning and few-shot learning models, though it is less pronounced in the latter. 
We also find that increasing the fine-tuned model size improves performance, particularly in classification.
</details>
<details>
<summary>bibtex</summary>
<pre>
@article{calderon2023measuring
  author       = {Nitay Calderon and
                  Naveh Porat and
                  Eyal Ben{-}David and
                  Zorik Gekhman and
                  Nadav Oved and
                  Roi Reichart},
  title        = {Measuring the Robustness of Natural Language Processing Models to
                  Domain Shifts},
  journal      = {CoRR},
  volume       = {abs/2306.00168},
  year         = {2023},
  url          = {https://doi.org/10.48550/arXiv.2306.00168},
  doi          = {10.48550/arXiv.2306.00168},
  eprinttype    = {arXiv},
  eprint       = {2306.00168},
  timestamp    = {Mon, 12 Jun 2023 16:25:59 +0200},
  biburl       = {https://dblp.org/rec/journals/corr/abs-2306-00168.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
</pre>
</details>

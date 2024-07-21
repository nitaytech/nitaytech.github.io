---
title: "Faithful Explanations of Black-box NLP Models Using LLM-generated Counterfactuals"
collection: publications
permalink: /publication/gat@faithful
venue: 'ICLR 24'
paperurl: 'http://arxiv.org/abs/2310.00603'
citation: 'Yair Gat*, Nitay Calderon*, Amir Feder, Alexander Chapanin, Amit Sharma, Roi Reichart'
date: 2024-05-01
---
<details>
<summary>Abstract</summary>
Causal explanations of the predictions of NLP systems are essential to ensure safety and establish trust.
Yet, existing methods often fall short of explaining model predictions effectively or efficiently and are often model-specific.
In this paper, we address model-agnostic explanations, proposing two approaches for counterfactual (CF) approximation.
The first approach is CF generation, where a large language model (LLM) is prompted to change a specific text concept while keeping confounding concepts unchanged.
While this approach is demonstrated to be very effective, applying LLM at inference-time is costly.
We hence present a second approach based on matching, and propose a method that is guided by an LLM at training-time and learns a dedicated embedding space.
This space is faithful to a given causal graph and effectively serves to identify matches that approximate CFs.
After showing theoretically that approximating CFs is required in order to construct faithful explanations, we benchmark our approaches and explain several models, including LLMs with billions of parameters.
Our empirical results demonstrate the excellent performance of CF generation models as model-agnostic explainers. 
Moreover, our matching approach, which requires far less test-time resources, also provides effective explanations, surpassing many baselines.
We also find that Top-K techniques universally improve every tested method.
Finally, we showcase the potential of LLMs in constructing new benchmarks for model explanation and subsequently validate our conclusions.
Our work illuminates new pathways for efficient and accurate approaches to interpreting NLP systems.</pre>
</details>
<details>
<summary>bibtex</summary>
<pre>
@article{gat2023faithful,
  author       = {Yair Ori Gat and
                  Nitay Calderon and
                  Amir Feder and
                  Alexander Chapanin and
                  Amit Sharma and
                  Roi Reichart},
  title        = {Faithful Explanations of Black-box {NLP} Models Using LLM-generated
                  Counterfactuals},
  journal      = {CoRR},
  volume       = {abs/2310.00603},
  year         = {2023},
  url          = {https://doi.org/10.48550/arXiv.2310.00603},
  doi          = {10.48550/ARXIV.2310.00603},
  eprinttype    = {arXiv},
  eprint       = {2310.00603},
  timestamp    = {Wed, 18 Oct 2023 16:20:58 +0200},
  biburl       = {https://dblp.org/rec/journals/corr/abs-2310-00603.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
</pre>
</details>

---
title: "Measuring the Robustness of NLP Models to Domain Shifts"
collection: publications
permalink: /publication/calderon2023measuring
venue: 'arXiv (under review)'
paperurl: 'https://arxiv.org/abs/2306.00168'
citation: 'Nitay Calderon*, Naveh Porat*, Eyal Ben-David, Alexander Chapanin, Zorik Gekhman, Nadav Oved, Vitaly Shalumov and Roi Reichart<br>*Equal contribution'
date: 2024-06-20
---
<details>
<summary>Abstract</summary>
Existing research on Domain Robustness (DR) suffers from disparate setups, limited task variety, and scarce research on recent capabilities such as in-context learning. Furthermore, the common practice of measuring DR might not be fully accurate. Current research focuses on challenge sets and relies solely on the Source Drop (SD): Using the source in-domain performance as a reference point for degradation. However, we argue that the Target Drop (TD), which measures degradation from the target in-domain performance, should be used as a complementary point of view. To address these issues, we first curated a DR benchmark comprised of 7 diverse NLP tasks, which enabled us to measure both the SD and the TD. We then conducted a comprehensive large-scale DR study involving over 14,000 domain shifts across 21 fine-tuned models and few-shot LLMs. We found that both model types suffer from drops upon domain shifts. While fine-tuned models excel in-domain, few-shot LLMs often surpass them cross-domain, showing better robustness. In addition, we found that a large SD can often be explained by shifting to a harder domain rather than by a genuine DR challenge, and this highlights the importance of TD as a complementary metric. We hope our study will shed light on the current DR state of NLP models and promote improved evaluation practices toward more robust models.
</details>
<details>
<summary>bibtex</summary>
<pre>
@article{calderon2023measuring,
  title={Measuring the Robustness of NLP Models to Domain Shifts},
  author={Calderon, Nitay and Porat, Naveh and Ben-David, Eyal and Chapanin, Alexander and Gekhman, Zorik and Oved, Nadav and Shalumov, Vitaly and Reichart, Roi},
  journal={arXiv preprint arXiv:2306.00168},
  year={2024}
}
</pre>
</details>

---
title: "Empty Shelves or Lost Keys? Recall Is the Bottleneck for Parametric Factuality"
collection: publications
permalink: /publication/calderon2026recall
_venue: 'arXiv (under review)'
paperurl: 'https://arxiv.org/abs/2602.14080'
citation: 'Calderon, Nitay and Ben-David, Eyal and Gekhman, Zorik and Ofek, Eran and Yona, Gal<br>'
date: 2026-02-15
---
<details>
<summary>Abstract</summary>
Standard factuality evaluations of LLMs treat all errors alike, obscuring whether failures arise from missing knowledge (empty shelves) or from limited access to encoded facts (lost keys). We propose a behavioral framework that profiles factual knowledge at the level of facts rather than questions, characterizing each fact by whether it is encoded, and then by how accessible it is: cannot be recalled, can be directly recalled, or can only be recalled with inference-time computation (thinking). To support such profiling, we introduce WikiProfile, a new benchmark constructed via an automated pipeline with a prompted LLM grounded in web search. Across 4 million responses from 13 LLMs, we find that encoding is nearly saturated in frontier models on our benchmark, with GPT-5 and Gemini-3 encoding 95--98% of facts. However, recall remains a major bottleneck: many errors previously attributed to missing knowledge instead stem from failures to access it. These failures are systematic and disproportionately affect long-tail facts and reverse questions. Finally, we show that thinking improves recall and can recover a substantial fraction of failures, indicating that future gains may rely less on scaling and more on methods that improve how models utilize what they already encode.
</details>
<details>
<summary>bibtex</summary>
<pre>
@article{calderon2026recall,
  title={Empty Shelves or Lost Keys? Recall Is the Bottleneck for Parametric Factuality},
  author={Calderon, Nitay and Ben-David, Eyal and Gekhman, Zorik and Ofek, Eran and Yona, Gal},
  journal={arXiv preprint arXiv:2602.14080},
  year={2026}
}
</pre>
</details>

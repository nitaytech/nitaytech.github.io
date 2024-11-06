---
title: "Are LLMs Better than Reported? Detecting Label Errors and Mitigating Their Effect on Model Performance"
collection: publications
permalink: /publication/nahum2024llms
venue: 'arXiv (under review)'
paperurl: 'https://arxiv.org/abs/2410.18889'
citation: 'Omer Nahum, Nitay Calderon, Orgad Keller, Idan Szpektor and Roi Reichart<br>'
date: 2024-07-27
---
<details>
<summary>Abstract</summary>
NLP benchmarks rely on standardized datasets for training and evaluating models and are crucial for advancing the field. Traditionally, expert annotations ensure high-quality labels; however, the cost of expert annotation does not scale well with the growing demand for larger datasets required by modern models. While crowd-sourcing provides a more scalable solution, it often comes at the expense of annotation precision and consistency. Recent advancements in large language models (LLMs) offer new opportunities to enhance the annotation process, particularly for detecting label errors in existing datasets. In this work, we consider the recent approach of LLM-as-a-judge, leveraging an ensemble of LLMs to flag potentially mislabeled examples. Through a case study of four datasets from the TRUE benchmark, covering different tasks and domains, we empirically analyze the labeling quality of existing datasets, and compare expert, crowd-sourced, and our LLM-based annotations in terms of agreement, label quality, and efficiency, demonstrating the strengths and limitations of each annotation method. Our findings reveal a substantial number of label errors, which, when corrected, induce a significant upward shift in reported model performance. This suggests that many of the LLMs so-called mistakes are due to label errors rather than genuine model failures. Additionally, we discuss the implications of mislabeled data and propose methods to mitigate them in training to improve model performance.
</details>
<details>
<summary>bibtex</summary>
<pre>
@article{nahum2024llms,
  title={Are LLMs Better than Reported? Detecting Label Errors and Mitigating Their Effect on Model Performance},
  author={Nahum, Omer and Calderon, Nitay and Keller, Orgad and Szpektor, Idan and Reichart, Roi},
  journal={arXiv preprint arXiv:2410.18889},
  year={2024}
}
</pre>
</details>

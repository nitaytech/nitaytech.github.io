---
title: "LIBERTy: A Causal Framework for Benchmarking Concept-Based Explanations of LLMs with Structural Counterfactuals"
collection: publications
permalink: /publication/toker2026liberty
_venue: 'arXiv (under review)'
paperurl: 'https://arxiv.org/abs/2601.10700'
citation: 'Toker, Gilat and Calderon, Nitay and Amosy, Ohad and Reichart, Roi<br>'
date: 2026-01-13
---
<details>
<summary>Abstract</summary>
Concept-based explanations quantify how high-level concepts (e.g., gender or experience) influence model behavior, which is crucial for decision-makers in high-stakes domains. Recent work evaluates the faithfulness of such explanations by comparing them to reference causal effects estimated from counterfactuals. In practice, existing benchmarks rely on costly human-written counterfactuals that serve as an imperfect proxy. To address this, we introduce a framework for constructing datasets containing structural counterfactual pairs: LIBERTy (LLM-based Interventional Benchmark for Explainability with Reference Targets). LIBERTy is grounded in explicitly defined Structured Causal Models (SCMs) of the text generation, interventions on a concept propagate through the SCM until an LLM generates the counterfactual. We introduce three datasets (disease detection, CV screening, and workplace violence prediction) together with a new evaluation metric, order-faithfulness. Using them, we evaluate a wide range of methods across five models and identify substantial headroom for improving concept-based explanations. LIBERTy also enables systematic analysis of model sensitivity to interventions: we find that proprietary LLMs show markedly reduced sensitivity to demographic concepts, likely due to post-training mitigation. Overall, LIBERTy provides a much-needed benchmark for developing faithful explainability methods.
</details>
<details>
<summary>bibtex</summary>
<pre>
@article{toker2026liberty,
  title={LIBERTy: A Causal Framework for Benchmarking Concept-Based Explanations of LLMs with Structural Counterfactuals},
  author={Toker, Gilat and Calderon, Nitay and Amosy, Ohad and Reichart, Roi},
  journal={arXiv preprint arXiv:2601.10700},
  year={2026}
}
</pre>
</details>

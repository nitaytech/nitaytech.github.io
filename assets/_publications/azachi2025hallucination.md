---
title: "Leveraging NTPs for Efficient Hallucination Detection in VLMs"
collection: publications
permalink: /publication/azachi2025hallucination
_venue: 'arXiv (under review)'
paperurl: 'https://arxiv.org/abs/2509.20379'
citation: 'Azachi, Ofir and Eliyahu, Kfir and El Ani, Eyal and Himelstein, Rom and Reichart, Roi and Pinter, Yuval and Calderon, Nitay<br>'
date: 2025-09-20
---
<details>
<summary>Abstract</summary>
Hallucinations of vision-language models (VLMs), which are misalignments between visual content and generated text, undermine the reliability of VLMs. One common approach for detecting them employs the same VLM, or a different one, to assess generated outputs. This process is computationally intensive and increases model latency. In this paper, we explore an efficient on-the-fly method for hallucination detection by training traditional ML models over signals based on the VLM's next-token probabilities (NTPs). NTPs provide a direct quantification of model uncertainty. We hypothesize that high uncertainty (i.e., a low NTP value) is strongly associated with hallucinations. To test this, we introduce a dataset of 1,400 human-annotated statements derived from VLM-generated content, each labeled as hallucinated or not, and use it to test our NTP-based lightweight method. Our results demonstrate that NTP-based features are valuable predictors of hallucinations, enabling fast and simple ML models to achieve performance comparable to that of strong VLMs. Furthermore, augmenting these NTPs with linguistic NTPs, computed by feeding only the generated text back into the VLM, enhances hallucination detection performance. Finally, integrating hallucination prediction scores from VLMs into the NTP-based models led to better performance than using either VLMs or NTPs alone. We hope this study paves the way for simple, lightweight solutions that enhance the reliability of VLMs.
</details>
<details>
<summary>bibtex</summary>
<pre>
@article{azachi2025hallucination,
  title={Leveraging NTPs for Efficient Hallucination Detection in VLMs},
  author={Azachi, Ofir and Eliyahu, Kfir and El Ani, Eyal and Himelstein, Rom and Reichart, Roi and Pinter, Yuval and Calderon, Nitay},
  journal={arXiv preprint arXiv:2509.20379},
  year={2025}
}
</pre>
</details>

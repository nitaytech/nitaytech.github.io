---
title: "DoCoGen: Domain Counterfactual Generation for Low Resource Domain Adaptation"
collection: publications
permalink: /publication/calderon2022docogen
venue: 'ACL'
paperurl: 'https://doi.org/10.18653/v1/2022.acl-long.533'
citation: 'Nitay Calderon*, Eyal Ben-David*, Amir Feder and Roi Reichart<br>*Equal contribution'
date: 2022-05-22
---
<details>
<summary>Abstract</summary>
Natural language processing (NLP) algorithms have become very successful, but they still struggle when applied to out-of-distribution examples.
In this paper we propose a controllable generation approach in order to deal with this domain adaptation (DA) challenge.
Given an input text example, our DoCoGen algorithm generates a domain-counterfactual textual example (D-con) - that is similar to the original in all aspects, including the task label, but its domain is changed to a desired one.
Importantly, DoCoGen is trained using only unlabeled examples from multiple domains - no NLP task labels or parallel pairs of textual examples and their domain-counterfactuals are required.
We show that DoCoGen can generate coherent counterfactuals consisting of multiple sentences. 
We use the D-cons generated by DoCoGen to augment a sentiment classifier and a multi-label intent classifier in 20 and 78 DA setups, respectively, where source-domain labeled data is scarce.
Our model outperforms strong baselines and improves the accuracy of a state-of-the-art unsupervised DA algorithm.
</details>
<details>
<summary>bibtex</summary>
<pre>
@inproceedings{calderon2022docogen,
  author       = {Nitay Calderon and
                  Eyal Ben{-}David and
                  Amir Feder and
                  Roi Reichart},
  editor       = {Smaranda Muresan and
                  Preslav Nakov and
                  Aline Villavicencio},
  title        = {DoCoGen: Domain Counterfactual Generation for Low Resource Domain
                  Adaptation},
  booktitle    = {Proceedings of the 60th Annual Meeting of the Association for Computational
                  Linguistics (Volume 1: Long Papers), {ACL} 2022, Dublin, Ireland,
                  May 22-27, 2022},
  pages        = {7727--7746},
  publisher    = {Association for Computational Linguistics},
  year         = {2022},
  url          = {https://doi.org/10.18653/v1/2022.acl-long.533},
  doi          = {10.18653/v1/2022.acl-long.533},
  timestamp    = {Mon, 01 Aug 2022 16:27:51 +0200},
  biburl       = {https://dblp.org/rec/conf/acl/CalderonBFR22.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
</pre>
</details>

---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. candidate at the faculty of [Data and Decisions Science](http://dds.technion.ac.il/) of the [Technion – Israel Institute of Technology](http://www.technion.ac.il/). My advisor is Professor [Roi Reichart](https://ie.technion.ac.il/~roiri/), and I am honored to be a [Clore fellow](https://clorefoundation.org.il/clore-scholars-programme/). Before that, I graduated with my B.Sc. in Data Science and Engineering from the Technion and was awarded the [Schulich Leaders](https://schulichleaders.com/) scholarship.
<br><br>
My research is in the field of Natural Language Processing (NLP) and lies in the intersection of Domain Adaptation, Causal Inference, and Language Generation. Specifically, I develop causal-inspired methods to improve out-of-distribution generalization, interpretability, and reliability of NLP systems. I am also interested in leveraging NLP tools for practical applications in mental health research. 
<br><br>
*I'm happy to talk about my research. If you have any questions about one of my papers, or my overall research, feel free to [reach out!](mailto:nitay@campus.technion.ac.il)*

# Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

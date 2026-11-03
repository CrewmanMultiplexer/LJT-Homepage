---
title: "In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation"
collection: publications
category: conferences
permalink: /publication/2024-in-context-sharpness
excerpt: 'Discovers that correct generations tend to have sharper context activations, and uses an entropy-based metric to improve factuality during decoding.'
date: 2024-03-03
venue: 'ICML 2024'
paperurl: 'https://arxiv.org/abs/2403.01548'
codeurl: 'https://github.com/hkust-nlp/Activation_Decoding'
citation: 'Shiqi Chen, Miao Xiong, Junteng Liu, Zhengxuan Wu, Teng Xiao, Siyang Gao, Junxian He. (2024). &quot;In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation.&quot; <i>Proceedings of ICML 2024</i>.'
---

This paper discovers a pattern associated with hallucinations: correct generations tend to have sharper context activations in the hidden states of the in-context tokens compared to incorrect generations. Leveraging this signal, it proposes an entropy-based metric to quantify the sharpness among in-context hidden states and incorporates it into the decoding process to improve factuality and overall generation quality.

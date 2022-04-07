---
layout: post
title: "Episode 1 : MIDI-DDSP: Detailed Control of Musical Performance via Hierarchical Modeling"
paper_name: "MIDI-DDSP: Detailed Control of Musical Performance via Hierarchical Modeling"
paper_url: "https://arxiv.org/abs/2112.09312"
paper_arxiv_code: "arXiv:2112.09312"
author_name: "Yusong Wu"
author: "Yusong Wu and Hugo Sonnery"
categories: journal
tags: 
- music-generation
- audio
- deep-learning
image: "episode-1-yusong-wu.png"
author_picture: "yusong-wu.jpeg"
illustration: "illustration-yusong-wu.png"
youtubeId: "Sp25x-Ko6o4"
personal_website: "https://lukewys.github.io/"
laboratory_website: "https://mila.quebec/en/person/aaron-courville/"
scholar_profile: "https://scholar.google.com/citations?user=vIuUJ-IAAAAJ&hl=zh-CN"
slides_url: "https://lukewys.github.io/"
speaker_bio: "Yusong Wu is a second-year research master student, co-advised by Aaron Courville and Chengzhi Anna Huang. Yusong is interested in music generation with deep generative models."
abstract: "Musical expression requires control of both what notes are played, and how they are performed. Conventional audio synthesizers provide detailed expressive controls, but at the cost of realism. Black-box neural audio synthesis and concatenative samplers can produce realistic audio, but have few mechanisms for control. In this work, we introduce MIDI-DDSP, a hierarchical model of musical instruments that enables both realistic neural audio synthesis and detailed user control. Starting from interpretable Differentiable Digital Signal Processing (DDSP) synthesis parameters, we infer musical notes and high-level properties of their expressive performance (such as timbre, vibrato, dynamics, and articulation). This creates a 3-level hierarchy (notes, performance, synthesis) that affords individuals the option to intervene at each level, or utilize trained priors (performance given notes, synthesis given performance) for creative assistance. Through quantitative experiments and listening tests, we demonstrate that this hierarchy can reconstruct high-fidelity audio, accurately predict performance attributes for a note sequence, independently manipulate the attributes of a given performance, and as a complete system, generate realistic audio from a novel note sequence. By utilizing an interpretable hierarchy, with multiple levels of granularity, MIDI-DDSP opens the door to assistive tools to empower individuals across a diverse range of musical experience."
supplement: ""
---

# About the speaker

**Bio** : {{ page.speaker_bio }}

Do not hesitate to check out [{{ page.author_name }}]({{ page.scholar_profile }}){:target="_blank"}'s personal [website]({{ page.personal_website }}){:target="_blank"} for latest updates !

![{{ page.author_name }}]({{ site.github.url }}/assets/img/{{ page.author_picture }}) 



# Recording


**Video recording** of the speaker's presentation :

{% include youtubeplayer.html id=page.youtubeId %}



# Paper

**Paper** : [{{ page.paper_name }}]({{ page.paper_url }}){:target="_blank"} [{{ page.paper_arxiv_code }}]

![{{ page.paper_name }}]({{ site.github.url }}/assets/img/{{ page.illustration }})

**Abstract** : {{ page.abstract }}



# Supplementary material

**Useful resources** : Courtesy of the speaker, the interested reader may find additional information in the *references* below :
* 🧑‍🔬 {{ page.author_name }}'s [personal website]({{ page.personal_website }}){:target="_blank"}
* 🏫 {{ page.author_name }}'s [laboratory_website]({{ page.laboratory_website }}){:target="_blank"}
* 📚 {{ page.author_name }}'s [google scholar profile]({{ page.scholar_profile }}){:target="_blank"}
* 💡 [Slides]({{ page.slides_url }}){:target="_blank"} used during {{ page.author_name }}'s presentation

{{ page.supplementary_info }}

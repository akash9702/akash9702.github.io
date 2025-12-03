---
title: "Robust Policy Design in Agent-Based Simulators using Adversarial Reinforcement Learning"
collection: publications
category: workshops
permalink: /files/robust-rl-in-abm
excerpt: ""
date: 2025-02-24
venue: 'AAAI 2025 Workshop on Multi-Agent AI in the Real World (Best Paper Award, Oral presentation)'
# slidesurl: ""
# paperurl: 'https://academicpages.github.io/files/multi-agent-off-switch-game.pdf'
paperurl: '/files/robust-rl-in-abm.pdf'
# bibtexurl: ""
citation: 'Akash Agrawal, Joel Dyer, Aldo Glielmo, and Michael Wooldridge. (2009). &quot;The Multi-Agent Off-Switch Game.&quot; <i>AAAI 2025 Workshop on Multi-Agent AI in the Real World</i>. 1(1).'
---
Agent-based models (ABMs) of complex socioeconomic systems provide policymakers with highly detailed synthetic environments in which policy interventions can be designed and optimised, for example through reinforcement learning (RL). Although they model systems at a fine level of granularity, ABMs will in general be imperfectly specified, such that there exists non-negligible distributional shifts between agent-based simulators and the complex socioeconomic systems they attempt to model. Policies that are tested and optimised in these simulated environments may therefore exhibit brittleness in the face of such distributional shifts, presenting a challenge to the use of ABMs in real-world policy design.

In this work, we investigate the robustness of policies designed on ABMs using RL-based methods. We show that the naive application of RL to discover optimal policies can result in policies that are vulnerable to simulated distributional shifts, where small changes in the model lead to noticeable drops in policy effectiveness. To address this, we explore multiple types of adversarial training methods aimed at improving policy robustness. We show that these methods not only make policies resilient to the specific simulation-to-reality shifts they were trained on, but also to unforeseen types of shifts. In experiments, we demonstrate these effects in a complex macroeconomic ABM with multiple types of agents, including households, firms, a central bank, and government.
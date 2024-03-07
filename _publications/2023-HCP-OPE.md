---
title: "Human Choice Prediction in Language-based Non-Cooperative Games: Simulation-based Off-Policy Evaluation"
collection: publications
permalink: /publication/OPE2023
excerpt: 'We consider the problem of off-policy evaluation for human decision prediction in non-cooperative non-zero-sum games, collect an extensive novel dataset and present a simulation-based algorithm.'
date: 2023-05-15
# venue: 'Under Review'
paperurl: 'https://arxiv.org/pdf/2305.10361'
citation: '<b>Eilam Shapira</b>, Reut Apel, Moshe Tennenholtz, Roi Reichart (2023). "Human Choice Prediction in Language-based Non-Cooperative Games: Simulation-based Off-Policy Evaluation".'
---

Recent advances in Large Language Models (LLMs) have spurred interest in designing LLM-based agents for tasks that involve interaction with human and artificial
agents. This paper addresses a key aspect in the design of such agents: Predicting human decision in off-policy evaluation
(OPE), focusing on language-based persuasion games, where the agent’s goal is to influence its partner’s decisions through verbal messages. Using a dedicated application, we collected a dataset of 87K decisions
from humans playing a repeated decisionmaking game with artificial agents. Our
approach involves training a model on human interactions with one agents subset to
predict decisions when interacting with another. To enhance off-policy performance,
we propose a simulation technique involving interactions across the entire agent space
and simulated decision makers. Our learning strategy yields significant OPE gains,
e.g., improving prediction accuracy in the
top 15% challenging cases by 7.1%.

[Download paper here](https://arxiv.org/pdf/2305.10361.pdf)
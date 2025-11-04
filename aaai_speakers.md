---
layout: aaai_speakers
title: Speakers
permalink: /aaai_speakers/
---
# Speakers - LLM for Planning Workshop

---

## Manling Li

* **Affiliation:** Northwestern University
* **Bio:** Manling Li is an Assistant Professor at Northwestern University. She was a postdoc at Stanford University and obtained the PhD degree in Computer Science at University of Illinois Urbana-Champaign in 2023. She works on the intersection of language, vision, and robotics. Her work won the ACL’24 Outstanding Paper Award, ACL’20 Best Demo Paper Award, and NAACL’21 Best Demo Paper Award. She was a recipient of Microsoft Research PhD Fellowship in 2021, an EE CS Rising Star in 2022, a DARPA Riser in 2022, etc. She served as Organizing Committee of ACL 25, NAACL 25, EMNLP 24, and delivered tutorials about multimodal knowledge at IJCAI’24, CVPR’23, NAACL’22, AAAI’21, ACL’21, etc. Additional information is available at https://limanling.github.io.
* **Abstract:**
    > Large Language Models (LLMs) have demonstrated remarkable capabilities in reasoning tasks, but the emerging field of Large Agent Models (LAMs) faces unique challenges as these models learn to interact with dynamic environments. This talk explores the fundamental framework for understanding and improving agent decision-making across long-horizon multi-round interactions. We begin by formalizing agent reasoning as a **Markov Decision Process (MDP)** and introduce the Embodied Agent Interface, a standardized framework for studying core agent capabilities including goal interpretation, subgoal decomposition, action sequencing, and transition modeling. Through this lens, we identify **long-horizon planning** as a critical bottleneck that requires specialized training approaches. To address this challenge, we present **RAGEN**, a novel framework that inspired by the recent success of DeepSeek-R1(Zero) using rule-based reward in reinforcement learning. RAGEN tackles two key challenges in real-world agent scenarios: environmental non-deterministic reward and long-horizon multi-turn interactions. By reformulating the problem as a **Partially Observable Markov Decision Process** and introducing the Reason-Interaction Chain Optimization algorithm, RAGEN optimizes complete trajectory distributions rather than single-turn responses. This approach enables more robust learning in complex agentic scenarios with long-horizon interactions.

---

## Christian Muise

* **Affiliation:** Queen's University
* **Bio:** Christian Muise is an Assistant Professor in the School of Computing at Queen’s University. He is a member of the Ingenuity Labs at Queen’s University, an active Scotiabank Scholar with the Scotiabank Centre for Customer Analytics, and a Faculty Affiliate with the Vector Institute for Artificial Intelligence. Dr. Muise’ area of focus is on the understanding and modelling of sequential decision making problems, with a focus on model acquisition from structured time series data and unstructured sources such as natural language and images.
* **Abstract:**
    > LLM’s have proven themselves to be incredibly adept at converting content from one representation to another. At the same time, they’ve seriously struggled to auto-complete their way through complex planning tasks in unseen domains. To that end, there is a growing trend to bridge natural language and planning solutions through the intermediate **Planning Domain Definition Language (PDDL)**. This talk details some of the recent work the Mu Lab has conducted that focuses on going between natural language and PDDL, in either direction, using the field’s seasoned understanding of how planning models are built. In particular, we’ll cover (1) a new framework for creating **NL -> PDDL pipelines**; (2) a paradigm for using planning techniques to create **narratives**; and (3) a new project that explores how **planning models can be extracted from existing narratives**.

---

## Shuang Li

* **Affiliation:** Stanford
* **Bio:** Shuang Li is a Postdoctoral Researcher at Stanford and earned her Ph.D. from MIT. Her research focuses on generative modeling and robot learning. She is interested in developing AI systems that generalize to a wide range of novel tasks and continually learn from the environment. In particular, she investigates methods to enhance the generalization capabilities of deep learning models, enabling them to tackle more challenging and novel tasks. Shuang is a recipient of CIFAR AI Chair, Meta Research Fellowship, Adobe Research Fellowship, MIT Seneff-Zue CS Fellowship, EECS Rising Star, ICML Outstanding Reviewer, and best and outstanding paper awards at NeurIPS workshops.
* **Abstract:**
    > Recent advances in vision and language models are transforming decision-making processes in robotics and automation. In this talk, we present several innovative frameworks that leverage **language models as high-level planners** to break down complex tasks into manageable subtasks, while employing **video generation models as low-level controllers** to execute actions in dynamic environments. We also introduce a novel unified video-and-action method that overcomes the limitations of directly applying video generation techniques to robotics and enables rapid policy inference. This integrated approach significantly enhances both the interpretability and efficiency of robotic systems.
    >
    > *Talk Title:* **Planning in the Era of Large Language Models.**

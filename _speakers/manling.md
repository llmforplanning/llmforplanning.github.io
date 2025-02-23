---
# Name of the speaker
name: Manling Li

# Link to the speaker's webpage
webpage: https://limanling.github.io/

# Primary affiliation of the speaker
affil: Northwestern University
# Link to the speaker's primary affiliation
affil_link: https://www.mccormick.northwestern.edu/research-faculty/directory/profiles/li-manling.html

# An image of the speaker (square aspect ratio works the best) (place in the `assets/img/speakers` directory)
img: manling.jpg

---

<!-- Whatever you write below will show up as the speaker's bio -->

 <!-- Manling Li is an assistant professor at the Computer Science department of Northwestern University. Manling obtained her Ph.D. degree in Computer Science at University of Illinois Urbana-Champaign in 2023. -->

Bio:

Manling Li is an Assistant Professor at Northwestern University. She was a postdoc at Stanford University and obtained the PhD degree in Computer Science at University of Illinois Urbana-Champaign in 2023. She works on the intersection of language, vision, and robotics. Her work won the ACL’24 Outstanding Paper Award, ACL'20 Best Demo Paper Award, and NAACL'21 Best Demo Paper Award. She was a recipient of Microsoft Research PhD Fellowship in 2021, an EE CS Rising Star in 2022, a DARPA Riser in 2022, etc. She served as Organizing Committee of ACL 25, NAACL 25, EMNLP 24, and delivered tutorials about multimodal knowledge at IJCAI'24, CVPR'23, NAACL'22, AAAI'21, ACL'21, etc. Additional information is available at [https://limanling.github.io](https://limanling.github.io/).


Abstract:

Large Language Models (LLMs) have demonstrated remarkable capabilities in reasoning tasks, but the emerging field of Large Agent Models (LAMs) faces unique challenges as these models learn to interact with dynamic environments. This talk explores the fundamental framework for understanding and improving agent decision-making across long-horizon multi-round interactions.
We begin by formalizing agent reasoning as a Markov Decision Process (MDP) and introduce the Embodied Agent Interface, a standardized framework for studying core agent capabilities including goal interpretation, subgoal decomposition, action sequencing, and transition modeling. Through this lens, we identify long-horizon planning as a critical bottleneck that requires specialized training approaches. To address this challenge, we present RAGEN, a novel framework that inspired by the recent success of DeepSeek-R1(Zero) using rule-based reward in reinforcement learning. RAGEN tackles two key challenges in real-world agent scenarios: environmental non-deterministic reward and long-horizon multi-turn interactions. By reformulating the problem as a Partially Observable Markov Decision Process and introducing the Reason-Interaction Chain Optimization algorithm, RAGEN optimizes complete trajectory distributions rather than single-turn responses. This approach enables more robust learning in complex agentic scenarios with long-horizon interactions.

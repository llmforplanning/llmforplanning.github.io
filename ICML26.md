---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /ICML26/
title: LM4Plan @ ICML 2026 
layout: home
---
ICML’26 Workshop,  
Seoul, South Korea,  
Date: July 11, 2026,  
Room Main Program: Grand Ballroom 101-102,   
Poster Session: Hall A, poster boards 1104–1115 and 1200–1201

### Invited Speakers
We are excited to announce our invited speakers for LM4Plan @ ICML 2026. [View full speaker details](/icml_speakers/).

* **Samy Bengio** - Apple
* **Subbarao Kambhampati** - Arizona State University
* **Yarin Gal** - University of Oxford
* **Elias Bareinboim** - Columbia University
* **Noam Brown** - OpenAI
* **Nathan Sturtevant** - University of Alberta

### Overview
Language Models (LMs) are a disruptive force, changing how research was done in many subareas of AI. Planning is one
of the last bastions that remain standing. The focus of this workshop is on the questions in the intersection of these areas. Some of the specific areas we would like to gain a better understanding in include: what LMs can contribute to planning, how LMs can/should be used, what are the pitfalls of using LMs, what are the guarantees that can be obtained.


### Schedule

| Time | Event | Details |
|-------------|-----------------|-----------------|
| 08:00–08:05 | Opening remarks | Katharina Stein |
| 08:05–08:50 | **Invited talk**|*Samy Bengio*: Reasoning with LLMs: Challenges and Opportunities|
| 08:50–09:35 | **Invited talk**|*Nathan Sturtevant*: LLM Planning Success|
| 09:35–10:00 | Coffee break ||
| 10:00–10:45 | **Invited talk**|*Subbarao Kambhampati*: (How) Do LLMs Plan?: A Sober Look|
| 10:45–11:30 | **Invited talk**|*Elias Bareinboim*: Towards Causal Artificial Intelligence|
| 11:30–11:40 | buffer||
| 11:40–12:00 | *Oral presentations*|LM-Landmarks: Language Model Guided Landmark Generation for Classical Planning with Formal Soundness Guarantees|
|||IDP-MCTS Empowering Small Language Models for Automated MILP Modeling and Code Generation in Flexible Job Shop Scheduling|
| 12:00–13:00 | Lunch||
| 13:00–13:45 | **Invited talk**|*Yarin Gal*: Model Collapse and its Implications on Planning with LLMs|
| 13:45–14:30 | **Invited talk**|*Noam Brown*: Implications of Large-Scale Test-Time Compute|
| 14:30–14:40 | buffer||
| 14:40–15:20 | *Oral presentations*|HiPER: Hierarchical Plan–Execute RL for Multi-Turn LLM Agents|
|||ICPRL: Acquiring Physical Intuition from Interactive Control|
|||Reward Prediction with Factorized World States|
|||OrigamiBench: An Interactive Environment to Synthesize Flat-Foldable Origamis|
| 15:20–15:30 | Concluding remarks||
| 15:30–16:00 | Coffee break ||
| 16:00–17:00 | Poster session |**Hall A**, boards 1104–1115 and 1200–1201|



### Invited Talks

#### Elias Bareinboim:
**Title:** Towards Causal Artificial Intelligence

**Abstract:**  
While a significant portion of AI scientists and engineers
believe we are on the verge of achieving highly general forms of AI, I
offer a critical appraisal of this view through a causal lens. In
particular, building on foundational developments in the field, I will
present my perspective on the relationship between intelligence and
causality, and the central role of the latter in building intelligent
systems and advancing credible data science.

I frame this discussion in terms of five core capabilities that we
should expect from an intelligent AI system:

1. Performing causal reasoning and articulating explanations;
2. Making precise, surgical, and sample-efficient decisions;
3. Generalizing across changing conditions and environments;
4. Generating and simulating in a causally consistent manner; and
5. Learning causal structures and variables.

In this talk, I will elaborate on this perspective and share current
progress toward building causally intelligent AI systems. A more
detailed discussion of this thesis is provided in my forthcoming
textbook, a draft of which is available here: [https://causalai-book.net/](https://causalai-book.net/).



#### Samy Bengio

**Title:**  Reasoning with LLMs: Challenges and Opportunities

**Abstract:** 
In this presentation, I will go over a few recent topics towards understanding the limits of reasoning capabilities of large language models. I will start with a discussion on what is reasoning, provide a few negative results showing limits regarding math problems and logic puzzles, and then follow up with a few more constructive approaches that can improve reasoning capabilities of LLMs.


#### Nathan Sturtevant

**Title:**  LLM Planning Success

**Abstract:** 
Recent literature has shown that LMs cannot reliably plan, especially in comparison to classical planners and planning languages such as PDDL. At the same time, other work has shown that LMs are Turing complete, functionally equivalent to the computers on which they run. In this talk we present our study of this gap. We show how we are able to train LMs and achieve 99% or higher success rates across a range of planning problems such as Towers of Hanoi and Blocksworld variants on which other approaches have failed to scale. Our analysis shows where LMs are able to generalize and some cases where they are not.


#### Noam Brown

**Title:**  Implications of Large-Scale Test-Time Compute

**Abstract:** 
As LLMs become more capable, their performance increasingly depends on the amount of test-time compute used. This talk argues that single-number benchmarks obscure both capability and safety-relevant trends, especially as longer chains of thought, scaffolds, and multi-agent methods push performance higher with more inference. I will close with proposals for evaluating models using performance-vs-compute curves and updating benchmarks and preparedness frameworks to account for realistic high-compute use.

#### Yarin Gal

**Title:**  Model Collapse and its Implications on Planning with LLMs

**Abstract:**  TBD

#### Subbarao Kambhampati

**Title:**  (How) Do LLMs Plan?: A Sober Look

**Abstract:**  TBD



### Important information for authors of accepted papers
See [here](/author_info_icml/) for important information about presentations and camera-ready paper versions.


### Accepted Papers
- **VeryTrace: Verifying Reasoning Traces through Compilable Formalism and Structured Verification**   
*Ninghan Zhong ⋅ Ahmet E Tanriverdi ⋅ Kaan Kale ⋅ Sriram Vishwanath*
- **AVATAR-AGENT: A Multi-Agent LLM Planning System for 3D Avatar Generation**  
*Jason Ding ⋅ Rohan Gangaraju ⋅ Krishna C Garikipati ⋅ Foad Dabiri ⋅ Chang Xu*
- **CAMEO: Cooperative Agentic Multi-objective Evolution of Heuristics**  
*Tien Dat Vu ⋅ Hung Phan ⋅ Yifan Yang ⋅ Huynh Thi Thanh Binh*
- **When Plans Collide: Joint Planning in LLM Negotiation Dyads**  
*Yiheng Yao ⋅ Chelsea Zou ⋅ Robert Hawkins*
- **BaRA: BFS-and-Reflection Web Data Collection Agent**  
*Soojeong Lee ⋅ Joseph Lee ⋅ Yongseong Cho ⋅ Sunjae Kim ⋅ Youngwoo Moon ⋅ Kyungwoo Song*
- **QueryWeaver: Reliable Multi-Tool Query Execution Planning via LLM-Based Graph Generation**   
*Aishwarya Chakravarthy ⋅ Vidhi Kulkarni ⋅ Polo Chau*
- **ICPRL: Acquiring Physical Intuition from Interactive Control**   
*Xinrun Xu ⋅ Pi Bu ⋅ Ye Wang ⋅ Börje F. Karlsson ⋅ Ziming Wang ⋅ Tengtao Song ⋅ Qi Zhu ⋅ Jun Song ⋅ Shuo Zhang ⋅ Zhingming Ding ⋅ Bo Zheng*
- **OrigamiBench: An Interactive Environment to Synthesize Flat-Foldable Origamis**  
*Naaisha Agarwal ⋅ Yihan Wu ⋅ Yichang Jian ⋅ Yikuan Hu ⋅ Nishad Mansoor ⋅ Mohan Li ⋅ Yifei Peng ⋅ Wang-Zhou Dai ⋅ Yao-Xiang Ding ⋅ Emanuele Sansone*
- **End-to-End LLM Flight Planning with RAG-based Memory and Multi-modal Coach Agent**  
*Amin Tabrizian ⋅ Arsyi Aziz ⋅ Aarifah Ullah⋅ Mahyar Ghazanfari ⋅ Pouria Razzaghi ⋅ Peng Wei*
- **LaGO: Latent Action Guidance for Online Reinforcement Learning**   
*Kuanyen Liu ⋅ Renjyun Huang ⋅ Ti-Rong Wu*
- **When in Doubt, Plan It Out: Committed Small Language Model Deliberation for Reactive Reinforcement Learning**  
*Nathan Gavenski ⋅ Juarez Monteiro ⋅ Francisco Galuppo Azevedo ⋅ Adriano Veloso ⋅ Odinaldo Rodrigues* 
- **Specialized LM Agents with Simulation-Verified Search for Service Workforce Planning**  
*Vivek Singh ⋅ Santosh Pai ⋅ Sarith Mohan ⋅ Chetan L Srinidhi ⋅ Azra Aziz ⋅ Sean Cohen ⋅ Neil Biehn ⋅ Maik Kuehnhoff*
- **IDP-MCTS Empowering Small Language Models for Automated MILP Modeling and Code Generation in Flexible Job Shop Scheduling**  
*Mingming Peng ⋅ Jin Huang ⋅ Qihao Liu ⋅ Liang GAO ⋅ Xinyu Li*
- **Theory of Mind Beyond Conversational Persuasion: Assessing the Capacity of LLMs to Induce Belief States via Planning and Action**  
*Ben Slater ⋅ Matteo G Mecattaf ⋅ Lucy G Cheke ⋅ John Burden ⋅ Winnie Street*
- **SafeRun: Enabling Determinism in LLM Planning for Running**  
*Meilin Chen ⋅ Zepeng Zhai ⋅ Jiaxuan Zhao ⋅ Yuan Lu*
- **LM-Landmarks: Language Model Guided Landmark Generation for Classical Planning with Formal Soundness Guarantees**  
*Kaustubh Bukkapatnam ⋅ Siddharth Karuturi*
- **Hierarchical Chain-of-Thought: Enhancing LLM Reasoning Performance and Efficiency**  
*Xingshuai Huang ⋅ Derek Li ⋅ Bahareh Nikpour ⋅ Parsa Omidi*
- **The Orchestrator Bottleneck: Formal Coordination Strategies for Cost-Optimal Multi-Agent Enterprise Workflows**   
*Rudrendu Kumar Paul ⋅ Sourav Nandy*
- **Multi-Pass LLM Compilation for HTN Domain Authoring**   
*Eliott Jacopin ⋅ Éric Jacopin ⋅ Koichi Takahashi*
- **LLM-Guided Transportation Hub Capacity Planning with Textual Business Inputs**   
*Xiaoyue Liu ⋅ Zheng Dong*
- **Generating Robust Portfolios of Optimization Models using Large Language Models**  
*Eleni Straitouri ⋅ Cheol Kim ⋅ Milind Tambe*
- **HiPER: Hierarchical Plan–Execute RL for Multi-Turn LLM Agents**  
*Jiangweizhi Peng ⋅ Yuanxin Liu ⋅ Ruida Zhou ⋅ Charles Fleming ⋅ Zhaoran Wang ⋅ Alfredo Garcia ⋅ Mingyi Hong*
- **Calibrate Once, Choose the Beam: A Predictive Regime Test for Same-LM Search Guidance and Pruning**   
*Jiahui Qu ⋅ Yifang Qin ⋅ BOYANG ZHENG ⋅ Ziyi Zhou*
- **UniDesigner: Language Models as Unified Planners for Agentic Design**   
*Zhouqiang Jiang ⋅ Bowen Wang ⋅ Shuqiong Wu ⋅ Yuta Nakashima*
- **RELIC: Revealed Principles for Learning Interpretable Composable Skills in Multi-Agent Planning**   
*Tuan-Kiet Nguyen-Viet ⋅ Pham Bui Dinh ⋅ Chính Dương ⋅ Tung Dao ⋅ Cong D Tran ⋅ Huynh Thi Thanh Binh*
- **ReTreVal: Reasoning Tree with Validation and Cross-Problem Memory for Large Language Models**   
*Abhishek HS ⋅ Pavan C Shekar ⋅ Aswanth Krishnan ⋅ Arpit Jain*
- **Reward Prediction with Factorized World States**   
*Yijun Shen ⋅ Delong Chen ⋅ Xianming Hu ⋅ Jiaming Mi ⋅ Hongbo Zhao ⋅ Kai Zhang ⋅ Pascale Fung*
- **AgentRouter: Heterogeneous Model Routing for Cost-Optimal Multi-Step Agentic Workflows**   
*Rudrendu Kumar Paul ⋅ Sourav Nandy*


### Submission Instruction

The submission deadline has passed. For the previous instruction for submitting see [here](/submission_icml/).

### Program Committee
To be announced.

### Organizing Committee
 * Michael Katz, IBM 
 <!-- [contact](mailto:michael.katz1@ibm.com)  -->
 * Augusto B. Corrêa, University of Oxford 
 <!-- [contact](mailto:augusto.blaascorrea@chch.ox.ac.uk) -->
 * Nir Lipovetzky, University of Melbourne
 * Sarath Sreedharan, Colorado State University
 * Katharina Stein, Saarland University
 * Luckeciano C. Melo, University of Oxford
 * Elliot Gestrin, Linköping University


Please send your inquiries to [llmforplanning@gmail.com](mailto:llmforplanning@gmail.com)

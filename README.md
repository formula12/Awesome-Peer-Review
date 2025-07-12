# Peer Review Generation Literature Collection



## Survey

AI4Research: A Survey of Artificial Intelligence for Scientific Research

Large language models for automated scholarly paper review: A survey https://arxiv.org/abs/2501.10326



## Old

### Benchmark/Dataset

A Dataset of Peer Reviews (PeerRead): Collection, Insights and NLP Applications https://aclanthology.org/N18-1149.pdf

2018 NAACL

14.7K paper drafts and the corresponding accept/reject decisions in top-tier venues including ACL, NIPS and ICLR



Can We Automate Scientific Reviewing? https://arxiv.org/abs/2102.00176

30 Jan 2021

ASAP Review dataset



## Paper

### Dataset

A Dataset of Peer Reviews (PeerRead): Collection, Insights and NLP Applications https://arxiv.org/abs/1804.09635

NAACL 2018

14.7K paper drafts and the corresponding accept/reject decisions

10.7K textual peer reviews written by experts



### Score Prediction

Exploiting Labeled and Unlabeled Data via Transformer Fine-tuning for Peer-Review Score Prediction https://aclanthology.org/2022.findings-emnlp.164.pdf

2022.findings-emnlp





### Evaluation

The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery https://arxiv.org/abs/2408.06292

1 Sep 2024

LLM-based agents approach human-level review performance



Automatically Evaluating the Paper Reviewing Capability of Large Language Models https://arxiv.org/html/2502.17086v1

(change name) Mind the Blind Spots: A Focus-Level Evaluation Framework for LLM Reviews https://arxiv.org/abs/2502.17086

24 Feb 2025

developed an automatic evaluation pipeline to assess the LLMs’ paper review capability by comparing them with expert-generated reviews;

constructing a dataset consisting of 676 OpenReview papers;

**Coding Scheme**: 7 targets & 5?4 aspects 

think:

先用了meta-review作为review，然后第二步prompt里再参考其他review的detail

alignments between the review points and final decision is a challenging task;



The role of large language models in the peer-review process: opportunities and challenges for medical journal reviewers and editors https://pubmed.ncbi.nlm.nih.gov/40122672/

2025 Jan 16

This review explores the integration of LLMs into peer review, highlighting their strengths in linguistic tasks and challenges in assessing scientific validity, particularly in clinical medicine;

recommend using LLMs as complementary tools under clear guidelines to support, not replace;



The AI Review Lottery: Widespread AI-Assisted Peer Reviews Boost Paper Scores and Acceptance Rates https://arxiv.org/abs/2405.02150

3 May 2024

at least 15.8% of reviews were written with AI assistance;

53.4% of pairs the AI-assisted review scores higher than the human review;

LLMs offer positive assessments;



Is llm a reliable reviewer? a comprehensive evaluation of llm on automatic paper reviewing tasks https://aclanthology.org/2024.lrec-main.816/

2024 LREC|COLING

a dataset containing 196 review-revision multiple-choice questions (RR-MCQ) with detailed labels from the review-rebuttal forum in ICLR-2023;

reviews still fall short of fully meeting human expectations;



Can large language models provide useful feedback on research papers? A large-scale empirical analysis https://arxiv.org/abs/2310.01783

3 Oct 2023



GPT4 is Slightly Helpful for Peer-Review Assistance: A Pilot Study https://arxiv.org/pdf/2307.05492

16 Jun 2023



AI-Driven Review Systems: Evaluating LLMs in Scalable and Bias-Aware Academic Reviews https://arxiv.org/pdf/2408.10365

Reviewer Arena 

reduce risks of misuse, score inflation, overconfident assessments, and uneven distributions



Reviewing Scientific Papers for Critical Problems With Reasoning LLMs: Baseline Approaches and Automatic Evaluation https://arxiv.org/abs/2505.23824

7 Jul 2025

* reasoning model
* test paper with Critical Problems



Are We There Yet? Revealing the Risks of Utilizing Large Language Models in Scholarly Peer Review https://arxiv.org/abs/2412.01708

2 Dec 2024



A Critical Examination of the Ethics of AI-Mediated Peer Review https://arxiv.org/abs/2309.12356

2 Sep 2023

a tendency to generate hallucinated content without adequate verification



Human-in-the-loop ai reviewing: Feasibility, opportunities, and risks https://aisel.aisnet.org/jais/vol25/iss1/7/

a tendency to generate hallucinated content without adequate verification



An Automatic and Cost-Efficient Peer-Review Framework for Language Generation Evaluation https://arxiv.org/abs/2410.12265

16 Oct 2024





#### novelty evaluation

Evaluating and Enhancing Large Language Models for Novelty Assessment in Scholarly Publications https://arxiv.org/abs/2409.16605

25 Sep 2024 ACL2024

SchNovel: benchmark/dataset 15000 pairs of papers

RAG-Novelty, a retrieval-augmented method that mirrors human peer review by grounding novelty assessment in retrieved context;



AI-based novelty detection in crowdsourced idea spaces https://www.tandfonline.com/doi/full/10.1080/14479338.2023.2215740

Accepted 15 May 2023







### Generation

PEERAssist: Leveraging on Paper-Review Interactions to Predict Peer Review Decisions https://openreview.net/forum?id=cooUcim100

ICADL 2021

hierarchical quality control and multi-round refinement loops?



Peer Review as A Multi-Turn and Long-Context Dialogue with Role-Based Interactions https://arxiv.org/abs/2406.05688

9 Jun 2024

dataset: ReviewMT



CycleResearcher: Improving Automated Research via Automated Review https://arxiv.org/abs/2411.00816

ICLR 2025

two datasets, Review-5k and Research-14k;

iterative training framework: offline-RLHF algorithm SimPO, Research-Review-Refinement cycle

CycleResearcher: a baseline language model fine-tuned for academic writing

CycleReviewer: an LLM specialized in evaluating research papers



DeepReview: Improving LLM-based Paper Review with Human-like Deep Thinking Process https://arxiv.org/abs/2503.08569

11 Mar 2025

DeepReview-13K, a curated dataset with structured annotations;



OpenReviewer: A Specialized Large Language Model for Generating Critical Scientific Paper Reviews https://arxiv.org/abs/2412.11948

2025 naacl

Llama-OpenReviewer-8B: finetuned on a large dataset of expert reviews(79,000) from top ML conferences



Automated Review Generation Method Based on Large Language Models https://arxiv.org/abs/2407.20906

1 May 2025

???



ReviewEval: An Evaluation Framework for AI-Generated Reviews https://arxiv.org/abs/2502.11736

24 May 2025

a  iterative self-refinement cycle to align LLM-generated reviews with human accuracy and analytical depth



The Quality Assist: A Technology-Assisted Peer Review Based on Citation Functions to Predict the Paper Quality https://ieeexplore.ieee.org/document/9968010

table 1 Existing studies on final review decision and paper quality.







#### Fine-tuned

A Dataset of Peer Reviews (PeerRead): Collection, Insights and NLP Applications https://aclanthology.org/N18-1149.pdf

2018 NAACL

14.7K paper drafts and the corresponding accept/reject decisions in top-tier venues including ACL, NIPS and ICLR



Can We Automate Scientific Reviewing? https://arxiv.org/abs/2102.00176

30 Jan 2021



NLPEER: A Unified Resource for the Computational Study of Peer Review https://arxiv.org/abs/2211.06651

19 May 2023



Reviewer2: Optimizing Review Generation Through Prompt Generation. https://arxiv.org/abs/2402.10886

2 Dec 2024



LLMs Assist NLP Researchers: Critique Paper (Meta-)Reviewing https://arxiv.org/abs/2406.16253



#### Agent

AgentReview: Exploring Peer Review Dynamics with LLM Agents https://arxiv.org/abs/2406.12708

13 Oct 2024

simulate the interactions among different roles;

generate review comments and discussion dialogues for each role;



MARG: Multi-Agent Review Generation for Scientific Papers https://arxiv.org/abs/2401.04259

8 Jan 2024

MARG: using multiple LLM instances that engage in internal discussion

MARG-S: aspect-specific agents (model) separately generate comments on experiments, clarity, and impact: perform better





PaperEval: A universal, quantitative, and explainable paper evaluation method powered by a multi-agent system https://www.sciencedirect.com/science/article/abs/pii/S0306457325001669



ReviewAgents: Bridging the Gap Between Human and AI-Generated Paper Reviews https://arxiv.org/abs/2503.08506

22 May 2025

* Review-CoT(dataset): 142k review comments

-original papers

-comments with structured thinking processes

-area chair comments

-relevant papers

* ReviewAgents
* ReviewBench



PiCO: Peer Review in LLMs based on the Consistency Optimization https://arxiv.org/abs/2402.01830

21 Feb 2025



Treereview: A dynamic tree of questions framework for deep and efficient llm-based scientific peer review https://www.arxiv.org/abs/2506.07642

9 Jun 2025

Current LLM-driven review methods face key limitations in: handling long papers, providing deep analysis, and managing computational costs;

decomposes high-level review task -> a tree of fine-grained review questions

recursively refines broad review aspects into specific inquiries

dynamic question expansion mechanism



Remor: Automated peer review generation with llm reasoning and multi-objective reinforcement learning https://arxiv.org/abs/2505.11718

27 Jun 2025

PeerRT (dataset): reasoning traces and metrics in each aspect;

Human-aligned Peer Review Reward (HPRR): quantifies the quality of peer review feedback;

multi-objective reinforcement learning;



MAMORX: Multi-agent Multi-Modal Scientific Review Generation with External Knowledge https://openreview.net/forum?id=frvkE8rCfX

11 Oct 2024

A multi-agent **multi-modal** scientific review generation framework with external knowledge;

capable of analyzing and critiquing figures in scientific papers;

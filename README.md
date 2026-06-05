# Awesome Peer Review Process

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)[![arXiv](https://img.shields.io/badge/arXiv-2604.27924-b31b1b.svg)](https://arxiv.org/abs/2604.27924)[![Topic](https://img.shields.io/badge/Topic-AI%20for%20Peer%20Review-blue.svg)](#)

Paper list for our ACL 2026 paper [**Can AI Be a Good Peer Reviewer? A Survey of Peer Review Process, Evaluation, and the Future**](https://arxiv.org/abs/2604.27924).

This repository collects papers, datasets, benchmarks, and tools for AI-assisted peer review. It follows the survey taxonomy: **peer review generation**, **after-review tasks**, and **benchmark perspectives**.

> Peer review is a multi-stage workflow involving review generation, rebuttal, discussion, meta-review, final decision, and manuscript revision. This list is intended to support research on AI-assisted peer review workflows, not to replace human reviewers.

---

## ✨ Highlights

- Organized by the survey taxonomy: **Generation**, **After Peer Review**, and **Evaluation**.
- Covers **fine-tuning**, **agent-based systems**, **reinforcement learning**, and **generation enhancement** for peer review generation.
- Includes post-review tasks such as **rebuttal generation**, **meta-review generation**, and **paper revision from reviews**.
- Separates evaluation into **human-centric**, **reference-based**, **LLM-based**, and **aspect-oriented** paradigms.
- Tracks representative **datasets**, **benchmarks**, and **data collection tools**.

---

## 🗂️ Table of Repository

- [📝 Peer Review Generation](#-peer-review-generation)
  - [Foundational Resources and Early Approaches](#foundational-resources-and-early-approaches)
  - [Fine-tuning Methods](#fine-tuning-methods)
  - [Agent-based Methods](#agent-based-methods)
  - [Reinforcement Learning Methods](#reinforcement-learning-methods)
  - [Review Generation Enhancement](#review-generation-enhancement)
- [🔁 After Peer Review](#-after-peer-review)
  - [Rebuttal](#rebuttal)
  - [Meta-review](#meta-review)
  - [Paper Revision from Reviews](#paper-revision-from-reviews)
- [📊 Evaluation and Benchmarks](#-evaluation-and-benchmarks)
  - [Human-Centric Evaluation](#human-centric-evaluation)
  - [Reference-Based Evaluation](#reference-based-evaluation)
  - [LLM-Based Evaluation](#llm-based-evaluation)
  - [Aspect-Oriented Evaluation](#aspect-oriented-evaluation)
- [🗃️ Datasets](#️-datasets)
- [🛠️ Data Collection and Document Processing Tools](#️-data-collection-and-document-processing-tools)
- [📝 Citation](#-citation)

---

# 📝 Peer Review Generation

## Foundational Resources and Early Approaches

### Foundational Datasets

- [[PeerRead]](https://aclanthology.org/N18-1149/) A Dataset of Peer Reviews (PeerRead): Collection, Insights and NLP Applications - NAACL 2018
- [[NLpeer]](https://arxiv.org/abs/2211.06651) NLpeer: A Unified Resource for the Computational Study of Peer Review - ACL 2023
- [[MOPRD]](https://arxiv.org/abs/2212.04972) MOPRD: A Multidisciplinary Open Peer Review Dataset - NCA 2023

### Early Review-related Methods

- [[ReviewRobot]](https://arxiv.org/abs/2010.06119) ReviewRobot: Explainable Paper Review Generation based on Knowledge Synthesis - INLG 2020
- [[ASAP-Review]](https://arxiv.org/abs/2102.00176) Can We Automate Scientific Reviewing? - EMNLP 2021
- [[PEERAssist]](https://link.springer.com/chapter/10.1007/978-3-030-91669-5_33) PEERAssist: Leveraging on Paper-Review Interactions to Predict Peer Review Decisions - ICADL 2021
- [[Peer-Review Score Prediction]](https://aclanthology.org/2022.findings-emnlp.164/) Exploiting Labeled and Unlabeled Data via Transformer Fine-tuning for Peer-Review Score Prediction - EMNLP Findings 2022

---

## Fine-tuning Methods

- [[ReviewMT]](https://arxiv.org/abs/2406.05688) Peer Review as A Multi-Turn and Long-Context Dialogue with Role-Based Interactions - arXiv 2024
- [[OpenReviewer]](https://arxiv.org/abs/2412.11948) OpenReviewer: A Specialized Large Language Model for Generating Critical Scientific Paper Reviews - NAACL Demo 2025
- [[REVIEWER2]](https://arxiv.org/abs/2402.10886) REVIEWER2: Optimizing Review Generation Through Prompt Generation - arXiv 2024
- [[LimGen]](https://arxiv.org/abs/2406.18195) LimGen: Probing the LLMs for Generating Suggestive Limitations of Research Papers - ECML-PKDD 2024

---

## Agent-based Methods

### Task Decomposition

- [[MARG]](https://arxiv.org/abs/2401.04259) MARG: Multi-Agent Review Generation for Scientific Papers - arXiv 2024
- [[SWIF²T]](https://aclanthology.org/2024.findings-acl.580/) Automated Focused Feedback Generation for Scientific Writing Assistance - ACL Findings 2024
- [[ReviewAgents]](https://arxiv.org/abs/2503.08506) ReviewAgents: Bridging the Gap Between Human and AI-Generated Paper Reviews - arXiv 2025
- [[DeepReview]](https://aclanthology.org/2025.acl-long.1420/) DeepReview: Improving LLM-based Paper Review with Human-like Deep Thinking Process - ACL 2025
- [[MAMORX]](https://neurips.cc/virtual/2024/105900) MAMORX: Multi-agent Multi-Modal Scientific Review Generation with External Knowledge - NeurIPS Workshop 2024
- [[DIAGPaper]](https://arxiv.org/abs/2601.07611) DIAGPaper: Diagnosing Valid and Specific Weaknesses in Scientific Papers via Multi-Agent Reasoning - arXiv 2026

### Process Simulation

- [[AgentReview]](https://arxiv.org/abs/2406.12708) AgentReview: Exploring Peer Review Dynamics with LLM Agents - EMNLP 2024
- [[ReviewMT]](https://arxiv.org/abs/2406.05688) Peer Review as A Multi-Turn and Long-Context Dialogue with Role-Based Interactions - arXiv 2024
- [[MATEval]](https://arxiv.org/abs/2403.19305) MATEval: A Multi-Agent Discussion Framework for Advancing Open-Ended Text Evaluation - arXiv 2024
- [[PaperEval]](https://www.sciencedirect.com/science/article/abs/pii/S0306457325001669) PaperEval: A Universal, Quantitative, and Explainable Paper Evaluation Method Powered by a Multi-Agent System - Information Processing & Management 2025

---

## Reinforcement Learning Methods

- [[CycleResearcher]](https://arxiv.org/abs/2411.00816) CycleResearcher: Improving Automated Research via Automated Review - ICLR 2025
- [[REMOR]](https://arxiv.org/abs/2505.11718) REMOR: Automated Peer Review Generation with LLM Reasoning and Multi-Objective Reinforcement Learning - arXiv 2025
- [[ReviewRL]](https://aclanthology.org/2025.emnlp-main.857/) ReviewRL: Towards Automated Scientific Review with RL - EMNLP 2025
- [[REM-CTX]](https://arxiv.org/abs/2604.00248) REM-CTX: Automated Peer Review via Reinforcement Learning with Auxiliary Context - arXiv 2026

---

## Review Generation Enhancement

### External Knowledge and Retrieval

- [[ReviewRobot]](https://arxiv.org/abs/2010.06119) ReviewRobot: Explainable Paper Review Generation based on Knowledge Synthesis - INLG 2020
- [[MAMORX]](https://neurips.cc/virtual/2024/105900) MAMORX: Multi-agent Multi-Modal Scientific Review Generation with External Knowledge - NeurIPS Workshop 2024
- [[Novelty Assessment]](https://aclanthology.org/2025.aisd-main.5/) Evaluating and Enhancing Large Language Models for Novelty Assessment in Scholarly Publications - NAACL 2025 Workshop
- [[SchNovel]](https://arxiv.org/abs/2409.16605) Evaluating and Enhancing Large Language Models for Novelty Assessment in Scholarly Publications - NAACL 2025 Workshop
- [[AI-based Novelty Detection]](https://www.tandfonline.com/doi/full/10.1080/14479338.2023.2215740) AI-based Novelty Detection in Crowdsourced Idea Spaces - Innovation 2023

### Iterative Refinement and Actionability

- [[ReviewEval]](https://arxiv.org/abs/2502.11736) ReviewEval: An Evaluation Framework for AI-Generated Reviews - EMNLP Findings 2025
- [[RbtAct]](https://arxiv.org/abs/2603.09723) RbtAct: Rebuttal-derived Optimization for Actionable Peer Review Generation - ACL Findings 2026
- [[GoodPoint]](https://arxiv.org/abs/2604.11924) GoodPoint: Learning Constructive Scientific Paper Feedback from Author Responses - arXiv 2026

### Structure and Style Control

- [[TreeReview]](https://www.arxiv.org/abs/2506.07642) TreeReview: A Dynamic Tree of Questions Framework for Deep and Efficient LLM-based Scientific Peer Review - EMNLP 2025
- [[AutoRev]](https://arxiv.org/abs/2505.14376) AutoRev: Automatic Peer Review System for Academic Research Papers - arXiv 2025
- [[RevGAN]](https://aclanthology.org/D19-1319/) Towards Controllable and Personalized Review Generation - EMNLP 2019

---

# 🔁 After Peer Review

## Rebuttal

- [[APE]](https://aclanthology.org/2020.emnlp-main.569/) APE: Argument Pair Extraction from Peer Review and Rebuttal via Multi-task Learning - EMNLP 2020
- [[DISAPERE]](https://aclanthology.org/2022.naacl-main.89/) DISAPERE: A Dataset for Discourse Structure in Peer Review Discussions - NAACL 2022
- [[JITSUPEER]](https://aclanthology.org/2023.emnlp-main.894/) Exploring Jiu-Jitsu Argumentation for Writing Peer Review Rebuttals - EMNLP 2023
- [[ReviewMT]](https://arxiv.org/abs/2406.05688) Peer Review as A Multi-Turn and Long-Context Dialogue with Role-Based Interactions - arXiv 2024
- [[Re²]](https://arxiv.org/abs/2505.07920) Re²: A Consistency-ensured Dataset for Full-stage Peer Review and Multi-turn Rebuttal Discussions - arXiv 2025
- [[DRPG]](https://arxiv.org/abs/2601.18081) DRPG (Decompose, Retrieve, Plan, Generate): An Agentic Framework for Academic Rebuttal - arXiv 2026
- [[Paper2Rebuttal]](https://arxiv.org/abs/2601.14171) Paper2Rebuttal: A Multi-Agent Framework for Transparent Author Response Assistance - arXiv 2026
- [[Author-in-the-loop]](https://arxiv.org/abs/2602.11173) Author-in-the-loop Response Generation and Evaluation: Integrating Author Expertise and Intent in Responses to Peer Review - ACL 2026

---

## Meta-review

- [[MRED]](https://aclanthology.org/2022.findings-acl.198/) MReD: A Meta-Review Dataset for Structure-Controllable Text Generation - ACL Findings 2022 
- [[PEERSUM]](https://aclanthology.org/2023.findings-emnlp.472/) Summarizing Multiple Documents with Conversational Structure for Meta-Review Generation - EMNLP Findings 2023
- [[ORSUM]](https://arxiv.org/abs/2305.14647) Scientific Opinion Summarization: Paper Meta-review Generation Dataset, Methods, and Evaluation - IJCAI 2024 Workshop
- [[Automated Meta-review Pipeline]](https://link.springer.com/article/10.1007/s00799-023-00359-0) Towards Automated Meta-review Generation via an NLP/ML Pipeline in Different Stages of the Scholarly Peer Review Process - International Journal on Digital Libraries 2024
- [[PeerArg]](https://arxiv.org/abs/2409.16813) PeerArg: Argumentative Peer Review with LLMs - NeLaMKRR 2024

---

## Paper Revision from Reviews

- [[ARXIVEDITS]](https://aclanthology.org/2022.emnlp-main.641/) arXivEdits: Understanding the Human Revision Process in Scientific Writing - EMNLP 2022
- [[ARIES]](https://arxiv.org/abs/2306.12587) ARIES: A Corpus of Scientific Paper Edits Made in Response to Peer Reviews - ACL 2024
- [[CASIMIR]](https://arxiv.org/abs/2403.12017) CASIMIR: A Corpus of Scientific Articles enhanced with Multiple Author-Integrated Revisions - LREC-COLING 2024

---

# 📊 Evaluation and Benchmarks

## Human-Centric Evaluation

- [[GPT-4 Pilot Study]](https://arxiv.org/abs/2307.05492) GPT4 is Slightly Helpful for Peer-Review Assistance: A Pilot Study - arXiv 2023
- [[Useful Feedback]](https://arxiv.org/abs/2310.01783) Can Large Language Models Provide Useful Feedback on Research Papers? A Large-Scale Empirical Analysis - NEJM AI 2023
- [[Reviewer Fatigue or Bias]](https://researchintegrityjournal.biomedcentral.com/articles/10.1186/s41073-023-00133-5) Fighting Reviewer Fatigue or Amplifying Bias? Considerations and Recommendations for Use of ChatGPT and Other Large Language Models in Scholarly Peer Review - Research Integrity and Peer Review 2023
- [[Human-in-the-loop AI Reviewing]](https://aisel.aisnet.org/jais/vol25/iss1/7/) Human-in-the-loop AI Reviewing: Feasibility, Opportunities, and Risks - JAIS 2024
- [[Reviewer Arena]](https://arxiv.org/abs/2408.10365) AI-Driven Review Systems: Evaluating LLMs in Scalable and Bias-Aware Academic Reviews - arXiv 2024
- [[Medical Peer Review with LLMs]](https://pubmed.ncbi.nlm.nih.gov/40122672/) The Role of Large Language Models in the Peer-review Process: Opportunities and Challenges for Medical Journal Reviewers and Editors -  J Educ Eval Health Prof 2025 

## Reference-Based Evaluation

- [[ReviewerGPT]](https://arxiv.org/abs/2306.00622) ReviewerGPT? An Exploratory Study on Using Large Language Models for Paper Reviewing - arXiv 2023
- [[RR-MCQ]](https://aclanthology.org/2024.lrec-main.816/) Is LLM a Reliable Reviewer? A Comprehensive Evaluation of LLM on Automatic Paper Reviewing Tasks - LREC-COLING 2024
- [[SEA]](https://arxiv.org/abs/2407.12857) Automated Peer Reviewing in Paper SEA: Standardization, Evaluation, and Analysis - EMNLP 2024
- [[Useful Feedback]](https://arxiv.org/abs/2310.01783) Can Large Language Models Provide Useful Feedback on Research Papers? A Large-Scale Empirical Analysis - NEJM AI 2023

## LLM-Based Evaluation

- [[Critical Problems]](https://arxiv.org/abs/2505.23824) Reviewing Scientific Papers for Critical Problems With Reasoning LLMs: Baseline Approaches and Automatic Evaluation - NeurIPS 2025 Workshop
- [[PiCO]](https://arxiv.org/abs/2402.01830) PiCO: Peer Review in LLMs based on the Consistency Optimization - ICLR 2025
- [[Auto-PRE]](https://arxiv.org/abs/2410.12265) Auto-PRE: An Automatic and Cost-Efficient Peer-Review Framework for Language Generation Evaluation - AAAI 2026

## Aspect-Oriented Evaluation

- [[Focus-Level Framework]](https://arxiv.org/abs/2502.17086) Mind the Blind Spots: A Focus-Level Evaluation Framework for LLM Reviews - EMNLP 2025
- [[ReviewCritique]](https://aclanthology.org/2024.emnlp-main.292/) LLMs Assist NLP Researchers: Critique Paper (Meta-)Reviewing - EMNLP 2024
- [[SubstanReview]](https://arxiv.org/abs/2311.11967) Automatic Analysis of Substantiation in Scientific Peer Reviews - EMNLP Findings 2023
- [[Disagreement]](https://arxiv.org/abs/2310.18685) When Reviewers Lock Horns: Finding Disagreements in Scientific Peer Reviews - EMNLP 2023 short
- [[HedgePeer]](https://ieeexplore.ieee.org/document/9852963) HedgePeer: A Dataset for Uncertainty Detection in Peer Reviews - IEEE 2022
- [[STRICTA]](https://aclanthology.org/2025.acl-long.1107/) STRICTA: Structured Reasoning in Critical Text Assessment for Peer Review and Beyond - ACL 2025
- [[AI Review Risks]](https://arxiv.org/abs/2412.01708) Are We There Yet? Revealing the Risks of Utilizing Large Language Models in Scholarly Peer Review - arXiv 2024
- [[AI Review Lottery]](https://arxiv.org/abs/2405.02150) The AI Review Lottery: Widespread AI-Assisted Peer Reviews Boost Paper Scores and Acceptance Rates - CSCW 2025
- [[Ethics of AI-Mediated Peer Review]](https://arxiv.org/abs/2309.12356) A Critical Examination of the Ethics of AI-Mediated Peer Review - arXiv 2023
- [[ChatGPT and Journal Reviews]](https://pmc.ncbi.nlm.nih.gov/articles/PMC10524821/) ChatGPT and the Future of Journal Reviews: A Feasibility Study - Yale J Biol Med 2023

---

# 🗃️ Datasets

## Core Paper-Review Datasets

| Dataset                                                      | Year | Main Use                                                     | Scale                                             | Source                                                       | Notes                                                 |
| ------------------------------------------------------------ | ---: | ------------------------------------------------------------ | ------------------------------------------------- | ------------------------------------------------------------ | ----------------------------------------------------- |
| [PeerRead](https://aclanthology.org/N18-1149/)               | 2018 | Review-score prediction, acceptance prediction, review generation | 14.7k papers; 10.7k reviews                       | ICLR 2017-2019 OpenReview; ACL 2017 author-consented drafts/reviews; NeurIPS 2013-2017 drafts matched to accepted arXiv papers | Foundational peer-review dataset                      |
| [PEERAssist](https://link.springer.com/chapter/10.1007/978-3-030-91669-5_33) | 2021 | Acceptance prediction, review-score prediction               | 4,467 papers; 13.4k reviews                       | ICLR 2017-2020 OpenReview submissions and reviews            | Paper-review interaction modeling                     |
| [ASAP-Review](https://arxiv.org/abs/2102.00176)              | 2022 | Aspect-aware review generation, aspect tagging               | 8,877 papers; 28.1k reviews                       | ICLR 2017-2020 and NeurIPS 2016-2019 OpenReview data         | 1k-review subset annotated with 15 aspect labels      |
| [ReAct](https://arxiv.org/abs/2210.00443)                    | 2022 | Actionability classification, comment-type tagging           | 1.25k labeled; 52k unlabeled comments             | ICLR 2018 OpenReview comments                                | Crowdsourced actionability labels and 7 comment types |
| [ICLR-DB](https://arxiv.org/abs/2211.06398)                  | 2022 | Fairness analysis, decision/review prediction, review generation | 10.3k submissions; 36.5k reviews; 68.7k responses | ICLR 2017-2022 OpenReview threads, enriched with author profiles and LLM-derived features | Multi-stage peer-review database                      |
| [MOPRD](https://arxiv.org/abs/2212.04972)                    | 2022 | Meta-review generation, decision prediction, rebuttal generation | 6,578 papers                                      | PeerJ peer-review threads with reviews, rebuttals, meta-reviews, and decisions | Manually aligned review-process records               |
| [NLpeer](https://arxiv.org/abs/2211.06651)                   | 2023 | Score prediction, pragmatic labeling, guided skimming        | 5,672 papers; 11k+ reviews                        | ICLR and NeurIPS 2017-2022 OpenReview submissions and reviews | Sentence-level pragmatic tags on an F1000 subset      |

## Recent Review Generation and Evaluation Datasets

| Dataset                                                      | Year | Main Use                                                     | Scale                                             | Source / Notes                                               |
| ------------------------------------------------------------ | ---: | ------------------------------------------------------------ | ------------------------------------------------- | ------------------------------------------------------------ |
| [SubstanReview](https://arxiv.org/abs/2311.11967)            | 2023 | Claim substantiation detection and scoring                   | 550 reviews                                       | ARR 2021-2022 reviews; expert span-level claim-evidence annotation |
| [ReviewCritique](https://aclanthology.org/2024.emnlp-main.292/) | 2024 | Deficiency detection in human and LLM reviews                | 100 papers                                        | 100 NLP papers with human and LLM reviews; experts annotate 23 fine-grained deficiency types |
| [REVIEWER2](https://arxiv.org/abs/2402.10886)                | 2024 | Aspect-prompted review generation, diversity benchmarking    | 27k papers; 99k reviews                           | Reviews from 6 major ML/NLP venues, 2017-2022; includes LLM-generated aspect prompts |
| [ReviewMT](https://arxiv.org/abs/2406.05688)                 | 2024 | Dialogue-style review simulation                             | 26k+ papers; 92k+ reviews                         | OpenReview reviews reorganized as multi-turn dialogues; speaker roles labeled |
| [ReviewEval](https://arxiv.org/abs/2502.11736)               | 2025 | Evaluation of human and LLM reviews                          | 120 papers                                        | 120 NeurIPS, ICLR, and UAI submissions with gold and candidate reviews |
| [Review-5K](https://huggingface.co/datasets/WestlakeNLP/Review-5K) | 2025 | Aspect-level score prediction, review evaluation             | 4,189 train + 782 test; 16k+ comments             | ICLR 2023 OpenReview reviews and comments                    |
| [DeepReview-13K](https://huggingface.co/datasets/WestlakeNLP/DeepReview-13K) | 2025 | Deep-thinking review generation                              | 13k structured reviews                            | OpenReview papers and reviews, 2017-2023; reasoning-step annotations for supervision |
| [RR-MCQ](https://aclanthology.org/2024.lrec-main.816/)       | 2024 | Review-revision QA, reviewer reliability benchmark           | 197 MCQs                                          | ICLR 2023 review-rebuttal threads; manually written and labeled MCQs |
| [AgentReview](https://arxiv.org/abs/2406.12708)              | 2024 | Peer-review simulation, bias/dynamics analysis, synthetic review generation | ~500 submissions; 10k reviews; 53.8k artifacts    | LLM-agent simulations over ICLR 2018-2021 papers             |
| [Re²](https://arxiv.org/abs/2505.07920)                      | 2025 | Full-stage review and rebuttal modeling, decision prediction, dialogue generation | 19.9k submissions; 70.7k reviews; 53.8k rebuttals | OpenReview data from 24 conferences and 21 workshops, 2017-2025; consistency-filtered multi-turn rebuttal threads |
| [RMR-75K](https://huggingface.co/datasets/shwu22/RMR-75K)    | 2026 | Review-rebuttal alignment, actionable feedback generation    | 75.5k mappings; 4,825 papers                      | ICLR 2024 reviews and rebuttal threads; segment-level review-rebuttal mapping with perspective and impact labels |

## After-review Datasets

| Dataset                                                      | Year | Task                                                   | Scale                                   | Source / Notes                                               |
| ------------------------------------------------------------ | ---: | ------------------------------------------------------ | --------------------------------------- | ------------------------------------------------------------ |
| [APE](https://aclanthology.org/2020.emnlp-main.569/)         | 2020 | Argument pair extraction from peer review and rebuttal | -                                       | Models argument links between review claims and rebuttal responses |
| [DISAPERE](https://aclanthology.org/2022.naacl-main.89/)     | 2022 | Review-rebuttal discourse analysis                     | 506 threads                             | ICLR 2019-2020 OpenReview discussion threads; sentence-level discourse relations in review-rebuttal discussions |
| [MReD](https://aclanthology.org/2022.findings-acl.198/)      | 2022 | Structure-controlled meta-review generation            | 7,089 meta-reviews; 45k sentences       | ICLR 2018-2021 OpenReview meta-reviews; every sentence labeled with 9 discourse tags |
| [PRRCA](https://dl.acm.org/doi/10.1145/3511808.3557360)      | 2022 | Meta-review generation from reviews and rebuttals      | 6,138 submissions                       | ICLR 2017-2022 OpenReview threads with reviews, rebuttals, decisions, and meta-reviews |
| [arXivEdits](https://aclanthology.org/2022.emnlp-main.641/)  | 2022 | Scientific writing revision analysis                   | -                                       | Sentence alignments and fine-grained edit intents across arXiv versions |
| [JITSUPEER](https://aclanthology.org/2023.emnlp-main.894/)   | 2023 | Rebuttal generation                                    | -                                       | Rebuttal actions and canonical rebuttal generation           |
| [PeerSum](https://aclanthology.org/2023.findings-emnlp.472/) | 2023 | Meta-review generation from discussions                | 14,993 triples                          | ICLR 2020-2022 OpenReview threads with reviews, discussions, and meta-reviews |
| [ARIES](https://arxiv.org/abs/2306.12587)                    | 2024 | Comment-edit alignment, revision generation            | 3.9k comment-edit pairs; 196 test cases | ICLR, NeurIPS, and ACL OpenReview papers, 2018-2022; expert-annotated gold test set |
| [CASIMIR](https://arxiv.org/abs/2403.12017)                  | 2024 | Revision intent analysis                               | -                                       | Scientific articles with multiple author-integrated revisions |

---

# 🛠️ Data Collection and Document Processing Tools

## Collection Channels

| Channel | Disciplines | Typical Method |
| --- | --- | --- |
| OpenReview | ML / NLP | OpenReview API, GraphQL, web crawling |
| Softconf / START | NLP | Opt-in dumps, SQL/CSV dumps |
| F1000Research | Life sciences | CSV export, HTML scraping, DOI tracking |
| PeerJ | Bio / Chemistry / CS | REST crawling, HTML crawling |
| Nature Communications review files | Multidomain | Bulk HTTP download |

## Document Processing

| Tool | Input → Output | Main Use |
| --- | --- | --- |
| [GROBID](https://github.com/grobidOrg/grobid?utm_source=chatgpt.com) | PDF → XML | Scholarly parsing with sections and citations |
| [Science Parse](https://github.com/allenai/science-parse) | PDF → JSON | Metadata and rough text extraction |
| [Marker](https://github.com/datalab-to/marker?utm_source=chatgpt.com) | PDF → Markdown | Long-context Markdown conversion |
| [MagicDoc](https://github.com/opendatalab/magic-doc) | PDF → Markdown | Bulk PDF conversion |
| [MinerU](https://github.com/opendatalab/MinerU) | PDF → Markdown / JSON | Layout-aware and reading-order faithful parsing |
| [Semantic Scholar API](https://www.semanticscholar.org/product/api) | DOI → BibJSON | Reference and citation enrichment |

---

# 📝 Citation

If you find this repository useful, please consider citing our paper:

```bibtex
@misc{wu2026aigoodpeerreviewer,
      title={Can AI Be a Good Peer Reviewer? A Survey of Peer Review Process, Evaluation, and the Future}, 
      author={Sihong Wu and Owen Jiang and Yilun Zhao and Tiansheng Hu and Yiling Ma and Kaiyan Zhang and Manasi Patwardhan and Arman Cohan},
      year={2026},
      eprint={2604.27924},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2604.27924}, 
}
```


## Benchmarks

- [REFUTE](https://huggingface.co/datasets/BGPT-OFFICIAL/refute) — Apache-2.0 benchmark for scientific critique & epistemic calibration on recent (2025–2026) science summaries. Separates critique skill from calibrated truthfulness (falsification, limitations, overclaims, missing-evidence refusal, confidence calibration, planted-flaw detection). [Leaderboard](https://huggingface.co/spaces/BGPT-OFFICIAL/refute-leaderboard) · [Technical report](https://huggingface.co/datasets/BGPT-OFFICIAL/refute/blob/main/TECHNICAL_REPORT.md) · [Integrators](https://huggingface.co/datasets/BGPT-OFFICIAL/refute/blob/main/INTEGRATORS.md)

# Financial LLM Trustworthiness Benchmarks

A curated index of benchmarks for evaluating the trustworthiness of large language models and agentic systems in finance.

> **Corpus snapshot:** 15 August 2026  
> **Organization:** five trustworthiness dimensions → evaluation object (LLM / Agent / Multi-Agent) → newest first.  
> **Publication priority:** when a peer-reviewed or formally accepted version is available, the venue version is shown and ranked before preprints from the same year.  
> **Links:** `—` means that no public project or Hugging Face link was verified. A benchmark may appear in multiple trustworthiness dimensions, and a multi-form benchmark may appear in more than one evaluation-object subgroup.

## Contents

- [Safety and Compliance](#safety-and-compliance)
- [Reliability and Truthfulness](#reliability-and-truthfulness)
- [Fairness](#fairness)
- [Privacy](#privacy)
- [Robustness](#robustness)

## Corpus at a Glance

| Trustworthiness Dimension | Benchmarks |
| --- | ---: |
| 🛡️ Safety and Compliance | 46 |
| ✅ Reliability and Truthfulness | 42 |
| ⚖️ Fairness | 10 |
| 🔐 Privacy | 8 |
| 🧱 Robustness | 35 |

The taxonomy follows the survey corpus. **LLM** corresponds to model-level evaluation; **Agent** denotes systems with agentic interaction, tools, memory, or executable workflows; **Multi-Agent** denotes evaluations centered on interactions among multiple agents.

## 🛡️ Safety and Compliance

### LLM (35)

| Year | Benchmark / Paper · Venue | Project | Hugging Face |
| ---: | --- | --- | --- |
| 2026 | **CNFinBench** — [Beyond Knowledge to Agency: Evaluating Expertise, Autonomy, and Integrity in Finance with CNFinBench](https://doi.org/10.1145/3770855.3817482) · **KDD 2026** | [GitHub](https://github.com/VertiAIBench/CNFinBench) | — |
| 2026 | **FinHarmBench** — [FinHarmBench: Financial Jailbreak Benchmark and Unsupervised Safety Fine-Tuning via Refusal Steering Distillation](https://aclanthology.org/2026.acl-industry.117/) · **ACL 2026 Industry Track** | — | — |
| 2026 | **FinSafetyBench** — [FinSafetyBench: Evaluating LLM Safety in Real-World Financial Scenarios](https://aclanthology.org/2026.findings-acl.694/) · **Findings of ACL 2026** | [GitHub](https://github.com/sustech-nlp/FinSafetyBench) | — |
| 2026 | **GrandGuard** — [GrandGuard: Taxonomy, Benchmark, and Safeguards for Elderly-Chatbot Interaction Safety](https://aclanthology.org/2026.findings-acl.1116/) · **Findings of ACL 2026** | — | — |
| 2026 | **FIN-Bench / FinRisk-Bench (CoRT)** — [Learning to Conceal Risk: Controllable Multi-turn Red Teaming for LLMs in the Financial Domain](https://aclanthology.org/2026.acl-long.1903/) · **ACL 2026** | [GitHub](https://github.com/gcheng128/CoRT) | — |
| 2026 | **MultiFinBen** — [MultiFinBen: Benchmarking Large Language Models for Multilingual and Multimodal Financial Application](https://aclanthology.org/2026.acl-long.770/) · **ACL 2026** | [GitHub](https://github.com/xueqingpeng/MultiFinBen) | — |
| 2026 | **OmniCompliance-100K** — [OmniCompliance-100K: A Multi-Domain, Rule-Grounded, Real-World Safety Compliance Dataset](https://aclanthology.org/2026.findings-acl.115/) · **Findings of ACL 2026** | — | — |
| 2026 | **FENCE** — [FENCE: A Financial and Multimodal Jailbreak Detection Dataset](https://aclanthology.org/2026.lrec-1.712/) · **LREC 2026** | — | — |
| 2026 | **RO-FIN-LLM** — [RO-FIN-LLM: A Benchmark with LLM-as-a-Judge and Human Evaluators for Romanian Tax and Accounting](https://www.mdpi.com/2079-8954/14/3/244) · **Systems 2026** | [GitHub](https://github.com/Nexus-Media/RO-FIN-LLM-Benchmark) | — |
| 2026 | **Prometeia Financial Benchmark (PFB)** — [PFB at EVALITA 2026: Overview of the Prometeia Financial Benchmark](https://ceur-ws.org/Vol-4195/66.pdf) · **EVALITA 2026** | — | — |
| 2026 | **FinRED** — [FinRED: An Expert-Guided Benchmark Generation and Evaluation Framework for Financial LLM Red-Teaming](https://arxiv.org/abs/2606.19887) · **arXiv** | [GitHub](https://github.com/selectstar-ai/FinRED-paper) | [Dataset](https://huggingface.co/datasets/datumo/FinRED) |
| 2026 | **FinGuard-Bench** — [FinGuard: Detecting Financial Regulatory Non-Compliance in LLM Interactions](https://arxiv.org/abs/2605.29427) · **arXiv** | — | — |
| 2026 | **IndiaFinBench** — [IndiaFinBench: An Evaluation Benchmark for Large Language Model Performance on Indian Financial Regulatory Text](https://arxiv.org/abs/2604.19298) · **arXiv** | — | — |
| 2026 | **DetailBench** — [Reducing Detail Hallucinations in Long-Context Regulatory Understanding via Targeted Preference Optimization](https://arxiv.org/abs/2604.23113) · **arXiv** | — | — |
| 2026 | **Swiss-Bench 003** — [Swiss-Bench 003: Evaluating LLM Reliability and Adversarial Security for Swiss Regulatory Contexts](https://arxiv.org/abs/2604.05872) · **arXiv** | — | — |
| 2026 | **ExpGuardTest** — [ExpGuard: LLM Content Moderation in Specialized Domains](https://arxiv.org/abs/2603.02588) · **arXiv** | — | — |
| 2026 | **FinRule-Bench** — [FinRule-Bench: A Benchmark for Joint Reasoning over Financial Tables and Principles](https://arxiv.org/abs/2603.11339) · **arXiv** | — | — |
| 2026 | **FinRedTeamBench** — [Risk-Adjusted Harm Scoring for Automated Red Teaming for LLMs in Financial Services](https://arxiv.org/abs/2603.10807) · **arXiv** | — | — |
| 2026 | **FIRE** — [FIRE: A Comprehensive Benchmark for Financial Intelligence and Reasoning Evaluation](https://arxiv.org/abs/2602.22273) · **arXiv** | — | — |
| 2025 | **IIQE Insurance QA Benchmark** — [Towards Lightweight LLM Software Solutions for InsurTech: A Framework for Scalable Question Answering Systems](https://doi.org/10.1109/APSEC66846.2025.00079) · **APSEC 2025** | — | — |
| 2025 | **Financial Market Abuse Ethical-Judgment Benchmark** — [Evaluating the Ethical Judgment of Large Language Models in Financial Market Abuse Cases](https://doi.org/10.1145/3768292.3770439) · **ICAIF 2025** | — | — |
| 2025 | **FinTrust** — [FinTrust: A Comprehensive Benchmark of Trustworthiness Evaluation in Finance Domain](https://aclanthology.org/2025.emnlp-main.512/) · **EMNLP 2025** | [GitHub](https://github.com/HughieHu/FinTrust) | [Dataset](https://huggingface.co/datasets/HughieHu/FinTrust) |
| 2025 | **CFinBench** — [CFinBench: A Comprehensive Chinese Financial Benchmark for Large Language Models](https://aclanthology.org/2025.naacl-long.40/) · **NAACL 2025** | [Project](https://cfinbench.github.io/) | — |
| 2025 | **FinEval** — [FinEval: A Chinese Financial Domain Knowledge Evaluation Benchmark for Large Language Models](https://aclanthology.org/2025.naacl-long.318/) · **NAACL 2025** | [GitHub](https://github.com/SUFE-AIFLM-Lab/FinEval) | — |
| 2025 | **CUFEInse v1.0** — [Design, Results and Industry Implications of the World's First Insurance Large Language Model Evaluation Benchmark](https://arxiv.org/abs/2511.07794) · **arXiv** | — | — |
| 2025 | **MENTOR** — [MENTOR: A Metacognition-Driven Self-Evolution Framework for Uncovering and Mitigating Implicit Domain Risks in LLMs](https://arxiv.org/abs/2511.07107) · **arXiv** | — | — |
| 2025 | **INSEva** — [INSEva: A Comprehensive Chinese Benchmark for Large Language Models in Insurance](https://arxiv.org/abs/2509.04455) · **arXiv** | — | — |
| 2025 | **Finova** — [Agentar-Fin-R1: Enhancing Financial Intelligence through Domain Expertise, Training Efficiency, and Advanced Reasoning](https://arxiv.org/abs/2507.16802) · **arXiv** | [GitHub](https://github.com/antgroup/Finova) | — |
| 2025 | **MMESGBench** — [MMESGBench: Pioneering Multimodal Understanding and Complex Reasoning Benchmark for ESG Tasks](https://arxiv.org/abs/2507.18932) · **arXiv** | — | — |
| 2025 | **TRIDENT** — [TRIDENT: Benchmarking LLM Safety in Finance, Medicine, and Law](https://arxiv.org/abs/2507.21134) · **arXiv** | — | — |
| 2025 | **Compliance-to-Code** — [Compliance-to-Code: Enhancing Financial Compliance Checking via Code Generation](https://arxiv.org/abs/2505.19804) · **arXiv** | [GitHub](https://github.com/AlexJJJChen/Compliance-to-Code) | [Dataset](https://huggingface.co/datasets/GPS-Lab/Compliance-to-Code) |
| 2024 | **FinBen** — [FinBen: A Holistic Financial Benchmark for Large Language Models](https://proceedings.neurips.cc/paper_files/paper/2024/hash/adb1d9fa8be4576d28703b396b82ba1b-Abstract-Datasets_and_Benchmarks_Track.html) · **NeurIPS 2024 Datasets & Benchmarks** | [GitHub](https://github.com/The-FinAI/PIXIU) | — |
| 2024 | **Japanese Financial Benchmark for LLMs** — [Construction of a Japanese Financial Benchmark for Large Language Models](https://aclanthology.org/2024.finnlp-1.1/) · **FinNLP 2024** | — | — |
| 2024 | **Chat Bankman-Fried** — [Chat Bankman-Fried: An Exploration of LLM Alignment in Finance](https://arxiv.org/abs/2411.11853) · **arXiv** | [GitHub](https://github.com/bancaditalia/llm-alignment-finance-chat-bf) | — |
| 2023 | **CFBenchmark** — [CFBenchmark: Chinese Financial Assistant Benchmark for Large Language Model](https://arxiv.org/abs/2311.05812) · **arXiv** | [GitHub](https://github.com/TongjiFinLab/CFBenchmark) | [Dataset](https://huggingface.co/datasets/TongjiFinLab/CFBenchmark) |

### Agent (10)

| Year | Benchmark / Paper · Venue | Project | Hugging Face |
| ---: | --- | --- | --- |
| 2026 | **PerMemSafe** — [PerMemSafe: Benchmarking Implicit Personalized Safety of Long Horizon Self-Evolving Agents](https://aclanthology.org/2026.findings-acl.320/) · **Findings of ACL 2026** | — | — |
| 2026 | **RO-FIN-LLM** — [RO-FIN-LLM: A Benchmark with LLM-as-a-Judge and Human Evaluators for Romanian Tax and Accounting](https://www.mdpi.com/2079-8954/14/3/244) · **Systems 2026** | [GitHub](https://github.com/Nexus-Media/RO-FIN-LLM-Benchmark) | — |
| 2026 | **FinJailbreak** — [Red-Teaming Financial AI Agents: Stress-Testing Governance Protections in LLMs Against Market Manipulation and Regulatory Evasion](https://openreview.net/forum?id=rmhL6mopWl) · **AAAI 2026 AIGOV Workshop** | — | — |
| 2026 | **FORCE-Bench** — [FORCE-Bench: A Benchmark, Dataset, and Evaluation Harness for Agentic AI in Enterprise Finance](https://arxiv.org/abs/2607.19409) · **arXiv** | — | — |
| 2026 | **FinPersona-Bench** — [FinPersona-Bench: A Benchmark for Longitudinal Psychometric Stability of Autonomous Financial Agents](https://arxiv.org/abs/2606.31522) · **arXiv** | [GitHub](https://github.com/usmansafdarktk/FinPersona-Bench) | — |
| 2026 | **Ontology-Grounded Trust Certification** — [Toward Pre-Deployment Assurance for Enterprise AI Agents: Ontology-Grounded Simulation and Trust Certification](https://arxiv.org/abs/2606.04037) · **arXiv** | — | — |
| 2026 | **FinSec Dialogue Risk Evaluation** — [Conversations Risk Detection LLMs in Financial Agents via Multi-Stage Generative Rollout](https://arxiv.org/abs/2604.09056) · **arXiv** | — | — |
| 2026 | **FinToolBench** — [FinToolBench: Evaluating LLM Agents for Real-World Financial Tool Use](https://arxiv.org/abs/2603.08262) · **arXiv** | [GitHub](https://github.com/Double-wk/FinToolBench) | — |
| 2026 | **GAP Benchmark** — [Mind the GAP: Text Safety Does Not Transfer to Tool-Call Safety in LLM Agents](https://arxiv.org/abs/2602.16943) · **arXiv** | — | — |
| 2026 | **FinVault** — [FinVault: Benchmarking Financial Agent Safety in Execution-Grounded Environments](https://arxiv.org/abs/2601.07853) · **arXiv** | [GitHub](https://github.com/aifinlab/FinVault) | — |

### Multi-Agent (2)

| Year | Benchmark / Paper · Venue | Project | Hugging Face |
| ---: | --- | --- | --- |
| 2026 | **M-SAEA / From Tasks to Teams** — [From Tasks to Teams: A Risk-First Evaluation Framework for Multi-Agent LLM Systems in Finance](https://aclanthology.org/2026.findings-acl.1934/) · **Findings of ACL 2026** | — | — |
| 2026 | **MAFF-Bench / MultiAgentFinancialFraudBench** — [When AI Agents Collide Online: Financial Fraud Risks by Collaborative LLM Agents on Social Platforms](https://openreview.net/forum?id=a1d2smwmBS) · **ICLR 2026** | [GitHub](https://github.com/zheng977/MutiAgent4Fraud) | — |

## ✅ Reliability and Truthfulness

### LLM (29)

| Year | Benchmark / Paper · Venue | Project | Hugging Face |
| ---: | --- | --- | --- |
| 2026 | **Fin-RATE** — [Fin-RATE: A Real-world Financial Analytics and Tracking Evaluation Benchmark for LLMs on SEC Filings](https://doi.org/10.1145/3770855.3817528) · **KDD 2026** | — | — |
| 2026 | **K-FinHallu** — [K-FinHallu: A Hallucination Detection Benchmark for Multi-Turn RAG in Korean Finance](https://arxiv.org/abs/2605.29523) · **Findings of EMNLP 2026 (accepted)** | — | — |
| 2026 | **RFC-Bench** — [All That Glisters Is Not Gold: A Benchmark for Reference-Free Counterfactual Financial Misinformation Detection](https://aclanthology.org/2026.acl-long.492/) · **ACL 2026** | — | — |
| 2026 | **FinED-Bench** — [Are Large Language Models Reliable Reviewers? A Benchmark for Error Detection in Financial Documents](https://aclanthology.org/2026.findings-acl.1481/) · **Findings of ACL 2026** | — | — |
| 2026 | **MFMD-Scen** — [Same Claim, Different Judgment: Benchmarking Scenario-Induced Bias in Multilingual Financial Misinformation Detection](https://aclanthology.org/2026.findings-acl.479/) · **Findings of ACL 2026** | — | — |
| 2026 | **RO-FIN-LLM** — [RO-FIN-LLM: A Benchmark with LLM-as-a-Judge and Human Evaluators for Romanian Tax and Accounting](https://www.mdpi.com/2079-8954/14/3/244) · **Systems 2026** | [GitHub](https://github.com/Nexus-Media/RO-FIN-LLM-Benchmark) | — |
| 2026 | **FinLBench** — [FinLBench: A Benchmark for Evaluating Large Language Models on Long-Text Financial Documents](https://link.springer.com/chapter/10.1007/978-981-95-4091-4_17) · **Neural Information Processing (CCIS), 2026** | [GitHub](https://github.com/Invariant0502/FinLBench) | — |
| 2026 | **FinReportBench** — [FinReportBench: Measuring and Improving Institution-Grade Financial Report Generation](https://arxiv.org/abs/2608.04374) · **arXiv** | [GitHub](https://github.com/MisterBrookT/finreportbench) | — |
| 2026 | **FinVerBench** — [FinVerBench: Benchmark Validity and Calibration in Large Language Model Financial Statement Verification](https://arxiv.org/abs/2605.29586) · **arXiv** | — | — |
| 2026 | **IndiaFinBench** — [IndiaFinBench: An Evaluation Benchmark for Large Language Model Performance on Indian Financial Regulatory Text](https://arxiv.org/abs/2604.19298) · **arXiv** | — | — |
| 2026 | **DetailBench** — [Reducing Detail Hallucinations in Long-Context Regulatory Understanding via Targeted Preference Optimization](https://arxiv.org/abs/2604.23113) · **arXiv** | — | — |
| 2026 | **Swiss-Bench 003** — [Swiss-Bench 003: Evaluating LLM Reliability and Adversarial Security for Swiss Regulatory Contexts](https://arxiv.org/abs/2604.05872) · **arXiv** | — | — |
| 2026 | **AFIB** — [Evaluating Financial Intelligence in Large Language Models: Benchmarking SuperInvesting AI with LLM Engines](https://arxiv.org/abs/2603.08704) · **arXiv** | — | — |
| 2026 | **FinReasoning** — [FinReasoning: A Hierarchical Benchmark for Reliable Financial Research Reporting](https://arxiv.org/abs/2603.19254) · **arXiv** | [GitHub](https://github.com/TongjiFinLab/FinReasoning) | — |
| 2026 | **FinReflectKG--HalluBench** — [FinReflectKG -- HalluBench: GraphRAG Hallucination Benchmark for Financial Question Answering Systems](https://arxiv.org/abs/2603.20252) · **arXiv** | — | — |
| 2026 | **FinRule-Bench** — [FinRule-Bench: A Benchmark for Joint Reasoning over Financial Tables and Principles](https://arxiv.org/abs/2603.11339) · **arXiv** | — | — |
| 2026 | **AdversaRiskQA（Finance 子集）** — [AdversaRiskQA: An Adversarial Factuality Benchmark for High-Risk Domains](https://arxiv.org/abs/2601.15511) · **arXiv** | — | — |
| 2026 | **FABRIC** — [FABRIC: AI Financial Advisors Hallucinate More Than They Forget on Indian Markets](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6576883) · **SSRN** | [GitHub](https://github.com/agenticclass/fabric) | [Dataset](https://huggingface.co/datasets/agenticclass/fabric) |
| 2026 | **Prompt Governance in Financial AI** — [Prompt Governance in Financial AI: Comparative Performance of Structured Frameworks in Insurance and Investment Tasks](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6286458) · **SSRN** | [GitHub](https://github.com/hirbis/prompt-governance) | — |
| 2025 | **PHANTOM** — [PHANTOM: A Benchmark for Hallucination Detection in Financial Long-Context QA](https://papers.nips.cc/paper_files/paper/2025/hash/b8badadce3f482ba340ff870f4894441-Abstract-Datasets_and_Benchmarks_Track.html) · **NeurIPS 2025 Datasets & Benchmarks** | — | [Dataset](https://huggingface.co/datasets/seyled/Phantom_Hallucination_Detection) |
| 2025 | **FAITH** — [FAITH: A Framework for Assessing Intrinsic Tabular Hallucinations in Finance](https://doi.org/10.1145/3768292.3770433) · **ICAIF 2025** | [GitHub](https://github.com/ZHANG-MENGAO/FAITH) | — |
| 2025 | **FinLFQA** — [FinLFQA: Evaluating Attributed Text Generation of LLMs in Financial Long-Form Question Answering](https://aclanthology.org/2025.findings-emnlp.908/) · **Findings of EMNLP 2025** | [GitHub](https://github.com/yitaoLong/FinLFQA) | [Dataset](https://huggingface.co/datasets/Dragongon/FinLFQA) |
| 2025 | **FinTrust** — [FinTrust: A Comprehensive Benchmark of Trustworthiness Evaluation in Finance Domain](https://aclanthology.org/2025.emnlp-main.512/) · **EMNLP 2025** | [GitHub](https://github.com/HughieHu/FinTrust) | [Dataset](https://huggingface.co/datasets/HughieHu/FinTrust) |
| 2025 | **Fin-Fact** — [Fin-Fact: A Benchmark Dataset for Multimodal Financial Fact-Checking and Explanation Generation](https://doi.org/10.1145/3701716.3715292) · **The Web Conference 2025 Companion** | [GitHub](https://github.com/IIT-DM/Fin-Fact) | [Dataset](https://huggingface.co/datasets/amanrangapur/Fin-Fact) |
| 2025 | **INSEva** — [INSEva: A Comprehensive Chinese Benchmark for Large Language Models in Insurance](https://arxiv.org/abs/2509.04455) · **arXiv** | — | — |
| 2025 | **MMESGBench** — [MMESGBench: Pioneering Multimodal Understanding and Complex Reasoning Benchmark for ESG Tasks](https://arxiv.org/abs/2507.18932) · **arXiv** | — | — |
| 2025 | **FailSafeQA** — [Expect the Unexpected: FailSafe Long Context QA for Finance](https://arxiv.org/abs/2502.06329) · **arXiv** | — | [Dataset](https://huggingface.co/datasets/Writer/FailSafeQA) |
| 2024 | **FMD-B** — [FMDLlama: Financial Misinformation Detection based on Large Language Models](https://arxiv.org/abs/2409.16452) · **arXiv** | — | — |
| 2023 | **Benchmarking Large Language Model Volatility** — [Benchmarking Large Language Model Volatility](https://arxiv.org/abs/2311.15180) · **arXiv** | — | — |

### Agent (13)

| Year | Benchmark / Paper · Venue | Project | Hugging Face |
| ---: | --- | --- | --- |
| 2026 | **PerMemSafe** — [PerMemSafe: Benchmarking Implicit Personalized Safety of Long Horizon Self-Evolving Agents](https://aclanthology.org/2026.findings-acl.320/) · **Findings of ACL 2026** | — | — |
| 2026 | **RO-FIN-LLM** — [RO-FIN-LLM: A Benchmark with LLM-as-a-Judge and Human Evaluators for Romanian Tax and Accounting](https://www.mdpi.com/2079-8954/14/3/244) · **Systems 2026** | [GitHub](https://github.com/Nexus-Media/RO-FIN-LLM-Benchmark) | — |
| 2026 | **DFAH / Replayable Financial Agents** — [Replayable Financial Agents: A Determinism-Faithfulness Assurance Harness for Tool-Using LLM Agents](https://arxiv.org/abs/2601.15322) · **ICLR 2026 FinAI Workshop** | [GitHub](https://github.com/ibm-client-engineering/output-drift-financial-llms) | — |
| 2026 | **CAIA** — [When Hallucination Costs Millions: Benchmarking AI Agents in High-Stakes Adversarial Financial Markets](https://arxiv.org/abs/2510.00332) · **AAAI 2026 AI-4-Finance Workshop (Oral)** | — | — |
| 2026 | **FinBench (Calibration and Uncertainty)** — [FinBench: Time-Gated Calibration and Uncertainty Benchmarking for Agentic Financial Forecasting](https://arxiv.org/abs/2607.16229) · **arXiv** | — | — |
| 2026 | **FORCE-Bench** — [FORCE-Bench: A Benchmark, Dataset, and Evaluation Harness for Agentic AI in Enterprise Finance](https://arxiv.org/abs/2607.19409) · **arXiv** | — | — |
| 2026 | **FinPersona-Bench** — [FinPersona-Bench: A Benchmark for Longitudinal Psychometric Stability of Autonomous Financial Agents](https://arxiv.org/abs/2606.31522) · **arXiv** | [GitHub](https://github.com/usmansafdarktk/FinPersona-Bench) | — |
| 2026 | **MortarBench** — [MortarBench: Evaluating Mortgage Loan Origination Agents](https://arxiv.org/abs/2606.19416) · **arXiv** | — | — |
| 2026 | **Ontology-Grounded Trust Certification** — [Toward Pre-Deployment Assurance for Enterprise AI Agents: Ontology-Grounded Simulation and Trust Certification](https://arxiv.org/abs/2606.04037) · **arXiv** | — | — |
| 2026 | **The Price of Agreement** — [The Price of Agreement: Measuring LLM Sycophancy in Agentic Financial Applications](https://arxiv.org/abs/2604.24668) · **arXiv** | — | — |
| 2026 | **FinToolBench** — [FinToolBench: Evaluating LLM Agents for Real-World Financial Tool Use](https://arxiv.org/abs/2603.08262) · **arXiv** | [GitHub](https://github.com/Double-wk/FinToolBench) | — |
| 2026 | **Look-Ahead-Bench** — [Look-Ahead-Bench: A Standardized Benchmark of Look-Ahead Bias in Point-in-Time LLMs for Finance](https://arxiv.org/abs/2601.13770) · **arXiv** | [GitHub](https://github.com/benstaf/lookaheadbench) | — |
| 2025 | **FinLake-Bench / Profit Mirage** — [Profit Mirage: Revisiting Information Leakage in LLM-based Financial Agents](https://arxiv.org/abs/2510.07920) · **arXiv** | — | — |

### Multi-Agent (1)

| Year | Benchmark / Paper · Venue | Project | Hugging Face |
| ---: | --- | --- | --- |
| 2026 | **M-SAEA / From Tasks to Teams** — [From Tasks to Teams: A Risk-First Evaluation Framework for Multi-Agent LLM Systems in Finance](https://aclanthology.org/2026.findings-acl.1934/) · **Findings of ACL 2026** | — | — |

## ⚖️ Fairness

### LLM (8)

| Year | Benchmark / Paper · Venue | Project | Hugging Face |
| ---: | --- | --- | --- |
| 2026 | **GrandGuard** — [GrandGuard: Taxonomy, Benchmark, and Safeguards for Elderly-Chatbot Interaction Safety](https://aclanthology.org/2026.findings-acl.1116/) · **Findings of ACL 2026** | — | — |
| 2026 | **MFMD-Scen** — [Same Claim, Different Judgment: Benchmarking Scenario-Induced Bias in Multilingual Financial Misinformation Detection](https://aclanthology.org/2026.findings-acl.479/) · **Findings of ACL 2026** | — | — |
| 2026 | **FairFund-Bench** — [FairFund-Bench: Evaluating Distributive Bias in LLM Resource Allocation](https://arxiv.org/abs/2607.28934) · **arXiv** | — | — |
| 2025 | **Accept or Deny** — [Accept or Deny? Evaluating LLM Fairness and Performance in Loan Approval across Table-to-Text Serialization Approaches](https://aclanthology.org/2025.findings-emnlp.947/) · **Findings of EMNLP 2025** | — | — |
| 2025 | **FinTrust** — [FinTrust: A Comprehensive Benchmark of Trustworthiness Evaluation in Finance Domain](https://aclanthology.org/2025.emnlp-main.512/) · **EMNLP 2025** | [GitHub](https://github.com/HughieHu/FinTrust) | [Dataset](https://huggingface.co/datasets/HughieHu/FinTrust) |
| 2025 | **Positional Bias Financial Benchmark** — [Tracing Positional Bias in Financial Decision-Making: Mechanistic Insights from Qwen2.5](https://doi.org/10.1145/3768292.3770394) · **ICAIF 2025** | — | — |
| 2025 | **FinBias (SAFE)** — [Unmasking Bias in Financial AI: A Robust Framework for Evaluating and Mitigating Hidden Biases in LLMs](https://doi.org/10.1145/3768292.3770355) · **ICAIF 2025** | — | — |
| 2023 | **CALM Credit-Scoring Benchmark** — [Empowering Many, Biasing a Few: Generalist Credit Scoring through Large Language Models](https://arxiv.org/abs/2310.00566) · **arXiv** | — | — |

### Agent (2)

| Year | Benchmark / Paper · Venue | Project | Hugging Face |
| ---: | --- | --- | --- |
| 2026 | **AgentFairBench** — [AgentFairBench: Do LLM Agents Discriminate When They Act?](https://arxiv.org/abs/2606.16723) · **arXiv** | — | — |
| 2026 | **MortarBench** — [MortarBench: Evaluating Mortgage Loan Origination Agents](https://arxiv.org/abs/2606.19416) · **arXiv** | — | — |

## 🔐 Privacy

### LLM (6)

| Year | Benchmark / Paper · Venue | Project | Hugging Face |
| ---: | --- | --- | --- |
| 2026 | **CNFinBench** — [Beyond Knowledge to Agency: Evaluating Expertise, Autonomy, and Integrity in Finance with CNFinBench](https://doi.org/10.1145/3770855.3817482) · **KDD 2026** | [GitHub](https://github.com/VertiAIBench/CNFinBench) | — |
| 2026 | **GrandGuard** — [GrandGuard: Taxonomy, Benchmark, and Safeguards for Elderly-Chatbot Interaction Safety](https://aclanthology.org/2026.findings-acl.1116/) · **Findings of ACL 2026** | — | — |
| 2026 | **OmniCompliance-100K** — [OmniCompliance-100K: A Multi-Domain, Rule-Grounded, Real-World Safety Compliance Dataset](https://aclanthology.org/2026.findings-acl.115/) · **Findings of ACL 2026** | — | — |
| 2026 | **Swiss-Bench 003** — [Swiss-Bench 003: Evaluating LLM Reliability and Adversarial Security for Swiss Regulatory Contexts](https://arxiv.org/abs/2604.05872) · **arXiv** | — | — |
| 2025 | **FinTrust** — [FinTrust: A Comprehensive Benchmark of Trustworthiness Evaluation in Finance Domain](https://aclanthology.org/2025.emnlp-main.512/) · **EMNLP 2025** | [GitHub](https://github.com/HughieHu/FinTrust) | [Dataset](https://huggingface.co/datasets/HughieHu/FinTrust) |
| 2023 | **CFBenchmark** — [CFBenchmark: Chinese Financial Assistant Benchmark for Large Language Model](https://arxiv.org/abs/2311.05812) · **arXiv** | [GitHub](https://github.com/TongjiFinLab/CFBenchmark) | [Dataset](https://huggingface.co/datasets/TongjiFinLab/CFBenchmark) |

### Agent (2)

| Year | Benchmark / Paper · Venue | Project | Hugging Face |
| ---: | --- | --- | --- |
| 2026 | **Ontology-Grounded Trust Certification** — [Toward Pre-Deployment Assurance for Enterprise AI Agents: Ontology-Grounded Simulation and Trust Certification](https://arxiv.org/abs/2606.04037) · **arXiv** | — | — |
| 2026 | **GAP Benchmark** — [Mind the GAP: Text Safety Does Not Transfer to Tool-Call Safety in LLM Agents](https://arxiv.org/abs/2602.16943) · **arXiv** | — | — |

## 🧱 Robustness

### LLM (22)

| Year | Benchmark / Paper · Venue | Project | Hugging Face |
| ---: | --- | --- | --- |
| 2026 | **CNFinBench** — [Beyond Knowledge to Agency: Evaluating Expertise, Autonomy, and Integrity in Finance with CNFinBench](https://doi.org/10.1145/3770855.3817482) · **KDD 2026** | [GitHub](https://github.com/VertiAIBench/CNFinBench) | — |
| 2026 | **RFC-Bench** — [All That Glisters Is Not Gold: A Benchmark for Reference-Free Counterfactual Financial Misinformation Detection](https://aclanthology.org/2026.acl-long.492/) · **ACL 2026** | — | — |
| 2026 | **Fin-Bias** — [Fin-Bias: Comprehensive Evaluation for LLM Decision-Making under Human Bias in Finance Domain](https://aclanthology.org/2026.findings-acl.279/) · **Findings of ACL 2026** | — | — |
| 2026 | **MFMD-Scen** — [Same Claim, Different Judgment: Benchmarking Scenario-Induced Bias in Multilingual Financial Misinformation Detection](https://aclanthology.org/2026.findings-acl.479/) · **Findings of ACL 2026** | — | — |
| 2026 | **FENCE** — [FENCE: A Financial and Multimodal Jailbreak Detection Dataset](https://aclanthology.org/2026.lrec-1.712/) · **LREC 2026** | — | — |
| 2026 | **FairFund-Bench** — [FairFund-Bench: Evaluating Distributive Bias in LLM Resource Allocation](https://arxiv.org/abs/2607.28934) · **arXiv** | — | — |
| 2026 | **FinVerBench** — [FinVerBench: Benchmark Validity and Calibration in Large Language Model Financial Statement Verification](https://arxiv.org/abs/2605.29586) · **arXiv** | — | — |
| 2026 | **DetailBench** — [Reducing Detail Hallucinations in Long-Context Regulatory Understanding via Targeted Preference Optimization](https://arxiv.org/abs/2604.23113) · **arXiv** | — | — |
| 2026 | **Swiss-Bench 003** — [Swiss-Bench 003: Evaluating LLM Reliability and Adversarial Security for Swiss Regulatory Contexts](https://arxiv.org/abs/2604.05872) · **arXiv** | — | — |
| 2026 | **ExpGuardTest** — [ExpGuard: LLM Content Moderation in Specialized Domains](https://arxiv.org/abs/2603.02588) · **arXiv** | — | — |
| 2026 | **FinReflectKG--HalluBench** — [FinReflectKG -- HalluBench: GraphRAG Hallucination Benchmark for Financial Question Answering Systems](https://arxiv.org/abs/2603.20252) · **arXiv** | — | — |
| 2026 | **FinRule-Bench** — [FinRule-Bench: A Benchmark for Joint Reasoning over Financial Tables and Principles](https://arxiv.org/abs/2603.11339) · **arXiv** | — | — |
| 2026 | **AdversaRiskQA（Finance 子集）** — [AdversaRiskQA: An Adversarial Factuality Benchmark for High-Risk Domains](https://arxiv.org/abs/2601.15511) · **arXiv** | — | — |
| 2026 | **Prompt Governance in Financial AI** — [Prompt Governance in Financial AI: Comparative Performance of Structured Frameworks in Insurance and Investment Tasks](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6286458) · **SSRN** | [GitHub](https://github.com/hirbis/prompt-governance) | — |
| 2025 | **Accept or Deny** — [Accept or Deny? Evaluating LLM Fairness and Performance in Loan Approval across Table-to-Text Serialization Approaches](https://aclanthology.org/2025.findings-emnlp.947/) · **Findings of EMNLP 2025** | — | — |
| 2025 | **FinTrust** — [FinTrust: A Comprehensive Benchmark of Trustworthiness Evaluation in Finance Domain](https://aclanthology.org/2025.emnlp-main.512/) · **EMNLP 2025** | [GitHub](https://github.com/HughieHu/FinTrust) | [Dataset](https://huggingface.co/datasets/HughieHu/FinTrust) |
| 2025 | **Positional Bias Financial Benchmark** — [Tracing Positional Bias in Financial Decision-Making: Mechanistic Insights from Qwen2.5](https://doi.org/10.1145/3768292.3770394) · **ICAIF 2025** | — | — |
| 2025 | **MENTOR** — [MENTOR: A Metacognition-Driven Self-Evolution Framework for Uncovering and Mitigating Implicit Domain Risks in LLMs](https://arxiv.org/abs/2511.07107) · **arXiv** | — | — |
| 2025 | **FailSafeQA** — [Expect the Unexpected: FailSafe Long Context QA for Finance](https://arxiv.org/abs/2502.06329) · **arXiv** | — | [Dataset](https://huggingface.co/datasets/Writer/FailSafeQA) |
| 2024 | **Chat Bankman-Fried** — [Chat Bankman-Fried: An Exploration of LLM Alignment in Finance](https://arxiv.org/abs/2411.11853) · **arXiv** | [GitHub](https://github.com/bancaditalia/llm-alignment-finance-chat-bf) | — |
| 2023 | **Benchmarking Large Language Model Volatility** — [Benchmarking Large Language Model Volatility](https://arxiv.org/abs/2311.15180) · **arXiv** | — | — |
| 2023 | **CALM Credit-Scoring Benchmark** — [Empowering Many, Biasing a Few: Generalist Credit Scoring through Large Language Models](https://arxiv.org/abs/2310.00566) · **arXiv** | — | — |

### Agent (12)

| Year | Benchmark / Paper · Venue | Project | Hugging Face |
| ---: | --- | --- | --- |
| 2026 | **PerMemSafe** — [PerMemSafe: Benchmarking Implicit Personalized Safety of Long Horizon Self-Evolving Agents](https://aclanthology.org/2026.findings-acl.320/) · **Findings of ACL 2026** | — | — |
| 2026 | **DFAH / Replayable Financial Agents** — [Replayable Financial Agents: A Determinism-Faithfulness Assurance Harness for Tool-Using LLM Agents](https://arxiv.org/abs/2601.15322) · **ICLR 2026 FinAI Workshop** | [GitHub](https://github.com/ibm-client-engineering/output-drift-financial-llms) | — |
| 2026 | **CAIA** — [When Hallucination Costs Millions: Benchmarking AI Agents in High-Stakes Adversarial Financial Markets](https://arxiv.org/abs/2510.00332) · **AAAI 2026 AI-4-Finance Workshop (Oral)** | — | — |
| 2026 | **FinBench (Calibration and Uncertainty)** — [FinBench: Time-Gated Calibration and Uncertainty Benchmarking for Agentic Financial Forecasting](https://arxiv.org/abs/2607.16229) · **arXiv** | — | — |
| 2026 | **FinPersona-Bench** — [FinPersona-Bench: A Benchmark for Longitudinal Psychometric Stability of Autonomous Financial Agents](https://arxiv.org/abs/2606.31522) · **arXiv** | [GitHub](https://github.com/usmansafdarktk/FinPersona-Bench) | — |
| 2026 | **MortarBench** — [MortarBench: Evaluating Mortgage Loan Origination Agents](https://arxiv.org/abs/2606.19416) · **arXiv** | — | — |
| 2026 | **Ontology-Grounded Trust Certification** — [Toward Pre-Deployment Assurance for Enterprise AI Agents: Ontology-Grounded Simulation and Trust Certification](https://arxiv.org/abs/2606.04037) · **arXiv** | — | — |
| 2026 | **FinSec Dialogue Risk Evaluation** — [Conversations Risk Detection LLMs in Financial Agents via Multi-Stage Generative Rollout](https://arxiv.org/abs/2604.09056) · **arXiv** | — | — |
| 2026 | **The Price of Agreement** — [The Price of Agreement: Measuring LLM Sycophancy in Agentic Financial Applications](https://arxiv.org/abs/2604.24668) · **arXiv** | — | — |
| 2026 | **GAP Benchmark** — [Mind the GAP: Text Safety Does Not Transfer to Tool-Call Safety in LLM Agents](https://arxiv.org/abs/2602.16943) · **arXiv** | — | — |
| 2026 | **Look-Ahead-Bench** — [Look-Ahead-Bench: A Standardized Benchmark of Look-Ahead Bias in Point-in-Time LLMs for Finance](https://arxiv.org/abs/2601.13770) · **arXiv** | [GitHub](https://github.com/benstaf/lookaheadbench) | — |
| 2025 | **FinLake-Bench / Profit Mirage** — [Profit Mirage: Revisiting Information Leakage in LLM-based Financial Agents](https://arxiv.org/abs/2510.07920) · **arXiv** | — | — |

### Multi-Agent (1)

| Year | Benchmark / Paper · Venue | Project | Hugging Face |
| ---: | --- | --- | --- |
| 2026 | **M-SAEA / From Tasks to Teams** — [From Tasks to Teams: A Risk-First Evaluation Framework for Multi-Agent LLM Systems in Finance](https://aclanthology.org/2026.findings-acl.1934/) · **Findings of ACL 2026** | — | — |

## Contributing

Corrections and additions are welcome through issues or pull requests. For a new benchmark, please provide:

- benchmark and paper title;
- publication venue or current preprint status;
- trustworthiness dimension(s);
- evaluation object (LLM, Agent, or Multi-Agent);
- paper link;
- project / code repository link, if available; and
- Hugging Face dataset or model link, if available.

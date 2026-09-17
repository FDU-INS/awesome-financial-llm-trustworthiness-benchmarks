# 💰 Awesome Financial LLM Trustworthiness Benchmarks

> **A curated collection of 102 benchmarks for evaluating the trustworthiness of large language models, agents, and multi-agent systems in finance.**

This repository accompanies our survey, [**A Survey of Trustworthiness Benchmarks for Large Language Models in Finance**](https://www.researchgate.net/publication/413695666_A_Survey_of_Trustworthiness_Benchmarks_for_Large_Language_Models_in_Finance), and provides a unified index of trustworthiness-related benchmarks used in financial LLM research. Rather than listing the same benchmark repeatedly under different categories, each benchmark appears **once** below and is assigned **multiple trustworthiness tags** when applicable.

## ✨ Highlights

- **102 benchmarks** covering trustworthiness evaluation for financial LLMs and agentic systems.
- **5 trustworthiness dimensions:** 🛡️ **Safety & Compliance**, ✅ **Reliability & Truthfulness**, ⚖️ **Fairness**, 🔐 **Privacy**, and 🧱 **Robustness**.
- **Three benchmark types:** the collection follows the survey's corpus definition and includes (1) **finance-specific trustworthiness benchmarks**, whose complete benchmark is analyzed; (2) **broader financial benchmarks with clearly separable trustworthiness components**, for which only the trustworthiness-related components are considered; and (3) **general LLM trustworthiness benchmarks with identifiable financial tasks or scenarios**, for which only the finance-related components are considered.
- **Unified resource index:** paper, GitHub/code, and Hugging Face links are collected in a single de-duplicated table.
- The accompanying survey analyzes this landscape through a **Coverage–Fidelity–Measurement** framework, connecting *what* is evaluated, *how realistically* it is evaluated, and *how* trustworthiness is measured.

**Coverage snapshot (15 September 2026):** 🛡️ Safety & Compliance **51** · ✅ Reliability & Truthfulness **58** · ⚖️ Fairness **12** · 🔐 Privacy **8** · 🧱 Robustness **40**

**Corpus composition (102 benchmarks):**
- **Type I — Finance-specific trustworthiness benchmarks: 67.** The benchmark is explicitly designed to evaluate trustworthiness in financial LLMs or agents; the complete benchmark is included.
- **Type II — Broader financial benchmarks with trustworthiness components: 24.** The benchmark primarily evaluates financial capabilities but contains clearly separable trustworthiness-related tasks or criteria; only those components are included.
- **Type III — General trustworthiness benchmarks with financial scenarios: 11.** The benchmark is general-domain, but contains identifiable finance-related tasks or scenarios; only those finance-related components are included.


## 📚 Benchmark Collection

> **Updated 15 September 2026:** 21 additional benchmarks that fully satisfy the survey inclusion criteria were added after manual verification of scope, venue status, and public resources.

> **Reading the table:** Trustworthiness domains are **multi-label**. A benchmark can therefore carry more than one tag. `—` indicates that no public GitHub or Hugging Face resource was verified. Rows are ordered by **year (newest first)** and, within each year, **peer-reviewed or formally accepted works are listed before preprints/working papers**. When a venue version is available, it is preferred over the corresponding preprint. Resource links and venue status were re-checked on **15 September 2026**; formal venue versions are used whenever a verified accepted/published version is available.


> **Second-pass verification (15 September 2026):** publication status, preferred paper version, and all previously blank GitHub / Hugging Face cells were re-checked against venue pages, author/project pages, repositories, and Hugging Face. For works whose acceptance is publicly reported but whose proceedings page is not yet indexed, the accepted venue is shown while the arXiv paper link is retained. A `—` now means that no canonical public resource URL could be independently verified; see the verification notes below for exceptions where a paper claims an artifact exists but its public URL could not be recovered.

| Year | Benchmark | Trustworthiness Domain | Venue | Paper | GitHub | Hugging Face |
| ---: | --- | --- | --- | :---: | :---: | :---: |
| 2026 | **CNFinBench** | `🛡️ Safety & Compliance`<br>`🔐 Privacy`<br>`🧱 Robustness` | KDD 2026 | [📄](https://doi.org/10.1145/3770855.3817482) | [💻](https://github.com/VertiAIBench/CNFinBench) | — |
| 2026 | **FinHarmBench** | `🛡️ Safety & Compliance` | ACL 2026 (Industry Track) | [📄](https://aclanthology.org/2026.acl-industry.117/) | [💻](https://github.com/ujin0415/FinHarmBench) | — |
| 2026 | **FinSafetyBench** | `🛡️ Safety & Compliance` | Findings of ACL 2026 | [📄](https://aclanthology.org/2026.findings-acl.694/) | [💻](https://github.com/sustech-nlp/FinSafetyBench) | — |
| 2026 | **GrandGuard** | `🛡️ Safety & Compliance`<br>`⚖️ Fairness`<br>`🔐 Privacy` | Findings of ACL 2026 | [📄](https://aclanthology.org/2026.findings-acl.1116/) | [💻](https://github.com/HKUST-KnowComp/GrandGuard) | — |
| 2026 | **FIN-Bench / FinRisk-Bench (CoRT)** | `🛡️ Safety & Compliance` | ACL 2026 | [📄](https://aclanthology.org/2026.acl-long.1903/) | [💻](https://github.com/gcheng128/CoRT) | — |
| 2026 | **MultiFinBen** | `🛡️ Safety & Compliance` | ACL 2026 | [📄](https://aclanthology.org/2026.acl-long.770/) | [💻](https://github.com/xueqingpeng/MultiFinBen) | [🤗](https://huggingface.co/collections/TheFinAI/multifinben) |
| 2026 | **OmniCompliance-100K** | `🛡️ Safety & Compliance`<br>`🔐 Privacy` | Findings of ACL 2026 | [📄](https://aclanthology.org/2026.findings-acl.115/) | [💻](https://github.com/HKUST-KnowComp/OmniCompliance-100K) | [🤗](https://huggingface.co/datasets/maohlzj/OmniCompliance100K) |
| 2026 | **FENCE** | `🛡️ Safety & Compliance`<br>`🧱 Robustness` | LREC 2026 | [📄](https://aclanthology.org/2026.lrec-1.712/) | [💻](https://github.com/kakaobank/FENCE) | — |
| 2026 | **RO-FIN-LLM** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness` | Systems 2026 | [📄](https://www.mdpi.com/2079-8954/14/3/244) | [💻](https://github.com/Nexus-Media/RO-FIN-LLM-Benchmark) | — |
| 2026 | **Prometeia Financial Benchmark (PFB)** | `🛡️ Safety & Compliance` | EVALITA 2026 | [📄](https://aclanthology.org/2026.evalita-1.59/) | — | — |
| 2026 | **PerMemSafe** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness`<br>`🧱 Robustness` | Findings of ACL 2026 | [📄](https://aclanthology.org/2026.findings-acl.320/) | — | — |
| 2026 | **FinJailbreak** | `🛡️ Safety & Compliance` | AAAI 2026 (AIGOV Workshop) | [📄](https://openreview.net/forum?id=rmhL6mopWl) | — | — |
| 2026 | **M-SAEA / From Tasks to Teams** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness`<br>`🧱 Robustness` | Findings of ACL 2026 | [📄](https://aclanthology.org/2026.findings-acl.1934/) | — | — |
| 2026 | **MAFF-Bench / MultiAgentFinancialFraudBench** | `🛡️ Safety & Compliance` | ICLR 2026 | [📄](https://openreview.net/forum?id=a1d2smwmBS) | [💻](https://github.com/zheng977/MutiAgent4Fraud) | — |
| 2026 | **Fin-RATE** | `✅ Reliability & Truthfulness` | KDD 2026 | [📄](https://doi.org/10.1145/3770855.3817528) | [💻](https://github.com/jyd777/Fin-RATE) | [🤗](https://huggingface.co/datasets/GGLabYale/Fin-RATE) |
| 2026 | **K-FinHallu** | `✅ Reliability & Truthfulness` | Findings of EMNLP 2026 | [📄](https://arxiv.org/abs/2605.29523) | — | — |
| 2026 | **RFC-Bench** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | ACL 2026 | [📄](https://aclanthology.org/2026.acl-long.492/) | — | [🤗](https://huggingface.co/datasets/CarolynJiang/RFC-Bench-Dataset) |
| 2026 | **FinED-Bench** | `✅ Reliability & Truthfulness` | Findings of ACL 2026 | [📄](https://aclanthology.org/2026.findings-acl.1481/) | — | — |
| 2026 | **MFMD-Scen** | `✅ Reliability & Truthfulness`<br>`⚖️ Fairness`<br>`🧱 Robustness` | Findings of ACL 2026 | [📄](https://aclanthology.org/2026.findings-acl.479/) | [💻](https://github.com/lzw108/FMD) | — |
| 2026 | **FinLBench** | `✅ Reliability & Truthfulness` | Neural Information Processing (CCIS) 2026 | [📄](https://link.springer.com/chapter/10.1007/978-981-95-4091-4_17) | [💻](https://github.com/Invariant0502/FinLBench) | — |
| 2026 | **DFAH / Replayable Financial Agents** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | ICLR 2026 (FinAI Workshop) | [📄](https://arxiv.org/abs/2601.15322) | [💻](https://github.com/ibm-client-engineering/output-drift-financial-llms) | — |
| 2026 | **CAIA** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | AAAI 2026 (AI4Finance Workshop, Oral) | [📄](https://arxiv.org/abs/2510.00332) | [💻](https://github.com/caiba-ai/caia-benchmark) | [🤗](https://huggingface.co/datasets/cyberco/caia-0927) |
| 2026 | **Fin-Bias** | `🧱 Robustness` | Findings of ACL 2026 | [📄](https://aclanthology.org/2026.findings-acl.279/) | — | — |
| 2026 | **BiasMix-Finance** | `🛡️ Safety & Compliance`<br>`🧱 Robustness` | ICLR 2026 (FinAI Workshop) | [📄](https://arxiv.org/abs/2608.28646) | [💻](https://github.com/gauravkukreja06/biasmix-finance) | — |
| 2026 | **Country-Label Sensitivity / Impartial Intelligence** | `⚖️ Fairness` | Journal of Business Ethics 2026 | [📄](https://doi.org/10.1007/s10551-026-06385-7) | — | — |
| 2026 | **MFMDBench / MFMDQwen** | `✅ Reliability & Truthfulness` | MeLLM 2026 | [📄](https://aclanthology.org/2026.mellm-1.7/) | [💻](https://github.com/lzw108/FMD) | — |
| 2026 | **RealFin** | `✅ Reliability & Truthfulness` | Findings of ACL 2026 | [📄](https://aclanthology.org/2026.findings-acl.1255/) | [💻](https://github.com/insait-institute/RealFin) | — |
| 2026 | **ExpGuardTest** | `🛡️ Safety & Compliance`<br>`🧱 Robustness` | ICLR 2026 | [📄](https://openreview.net/forum?id=t5cYJlV6aJ) | [💻](https://github.com/brightjade/ExpGuard) | [🤗](https://huggingface.co/datasets/6rightjade/expguardmix) |
| 2026 | **FairFund-Bench** | `⚖️ Fairness`<br>`🧱 Robustness` | Findings of EMNLP 2026 (accepted) | [📄](https://arxiv.org/abs/2607.28934) | [💻](https://github.com/martinlukk/fairfund-bench) | — |
| 2026 | **TRIDENT** | `🛡️ Safety & Compliance` | COLM 2026 | [📄](https://arxiv.org/abs/2507.21134) | [💻](https://github.com/zackhuiiiii/TRIDENT) | — |
| 2026 | **Compliance-to-Code** | `🛡️ Safety & Compliance` | KDD 2026 | [📄](https://doi.org/10.1145/3770854.3785703) | [💻](https://github.com/AlexJJJChen/Compliance-to-Code) | [🤗](https://huggingface.co/datasets/GPS-Lab/Compliance-to-Code) |
| 2026 | **FinRED** | `🛡️ Safety & Compliance` | KDD 2026 (Datasets & Benchmarks Track) | [📄](https://arxiv.org/abs/2606.19887) | [💻](https://github.com/selectstar-ai/FinRED-paper) | [🤗](https://huggingface.co/datasets/datumo/FinRED) |
| 2026 | **FinGuard-Bench** | `🛡️ Safety & Compliance` | Findings of EMNLP 2026 (accepted) | [📄](https://arxiv.org/abs/2605.29427) | — | — |
| 2026 | **DetailBench** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness`<br>`🧱 Robustness` | EMNLP 2026 (accepted) | [📄](https://arxiv.org/abs/2604.23113) | — | [🤗](https://huggingface.co/datasets/YangL1122/DetailBench) |
| 2026 | **FinRedTeamBench** | `🛡️ Safety & Compliance` | EMNLP 2026 (Main Conference, accepted) | [📄](https://arxiv.org/abs/2603.10807) | — | — |
| 2026 | **The Price of Agreement** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | ICLR 2026 (FinAI Workshop) | [📄](https://arxiv.org/abs/2604.24668) | — | — |
| 2026 | **PACE (Policy-Attested Contract Execution)** | `🛡️ Safety & Compliance`<br>`🧱 Robustness` | BRAINS 2026 | [📄](https://arxiv.org/abs/2608.17220) | — | — |
| 2026 | **CrAIBench / Real AI Agents with Fake Memories** | `🛡️ Safety & Compliance`<br>`🧱 Robustness` | Financial Cryptography and Data Security (FC) 2026 | [📄](https://arxiv.org/abs/2503.16248) | — | [🤗](https://huggingface.co/datasets/SentientAGI/crypto-agent-safe-function-calling) |
| 2026 | **IndiaFinBench** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness` | arXiv | [📄](https://arxiv.org/abs/2604.19298) | [💻](https://github.com/rajveerpall/IndiaFinBench) | [🤗](https://huggingface.co/datasets/Rajveer-code/IndiaFinBench) |
| 2026 | **Swiss-Bench 003** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness`<br>`🔐 Privacy`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2604.05872) | — | — |
| 2026 | **FinRule-Bench** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2603.11339) | — | — |
| 2026 | **FIRE** | `🛡️ Safety & Compliance` | arXiv | [📄](https://arxiv.org/abs/2602.22273) | [💻](https://github.com/DXM-AGI/FIRE-Bench) | [🤗](https://huggingface.co/FIRE-Bench/FIRE-RM) |
| 2026 | **FORCE-Bench** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness` | arXiv | [📄](https://arxiv.org/abs/2607.19409) | [💻](https://github.com/microsoft/FinanceBenchmark) | — |
| 2026 | **FinPersona-Bench** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2606.31522) | [💻](https://github.com/usmansafdarktk/FinPersona-Bench) | — |
| 2026 | **Ontology-Grounded Trust Certification** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness`<br>`🔐 Privacy`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2606.04037) | [💻](https://github.com/frank-luongt/faos-research) | — |
| 2026 | **FinSec Dialogue Risk Evaluation** | `🛡️ Safety & Compliance`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2604.09056) | — | — |
| 2026 | **FinToolBench** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness` | arXiv | [📄](https://arxiv.org/abs/2603.08262) | [💻](https://github.com/Double-wk/FinToolBench) | — |
| 2026 | **GAP Benchmark** | `🛡️ Safety & Compliance`<br>`🔐 Privacy`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2602.16943) | [💻](https://github.com/acartag7/gap-benchmark) | [🤗](https://huggingface.co/datasets/acartag7/gap-benchmark) |
| 2026 | **FinVault** | `🛡️ Safety & Compliance` | arXiv (withdrawn 30 Jul 2026) | [📄](https://arxiv.org/abs/2601.07853) | [💻](https://github.com/aifinlab/FinVault) | — |
| 2026 | **FinReportBench** | `✅ Reliability & Truthfulness` | arXiv | [📄](https://arxiv.org/abs/2608.04374) | [💻](https://github.com/MisterBrookT/finreportbench) | — |
| 2026 | **FinVerBench** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2605.29586) | — | — |
| 2026 | **AFIB** | `✅ Reliability & Truthfulness` | arXiv | [📄](https://arxiv.org/abs/2603.08704) | — | — |
| 2026 | **FinReasoning** | `✅ Reliability & Truthfulness` | arXiv | [📄](https://arxiv.org/abs/2603.19254) | [💻](https://github.com/TongjiFinLab/FinReasoning) | — |
| 2026 | **FinReflectKG--HalluBench** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2603.20252) | — | — |
| 2026 | **AdversaRiskQA（Finance 子集）** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2601.15511) | — | — |
| 2026 | **FABRIC** | `✅ Reliability & Truthfulness` | SSRN | [📄](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6576883) | [💻](https://github.com/agenticclass/fabric) | [🤗](https://huggingface.co/datasets/agenticclass/fabric) |
| 2026 | **Prompt Governance in Financial AI** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | SSRN | [📄](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6286458) | [💻](https://github.com/hirbis/prompt-governance) | — |
| 2026 | **FinBench (Calibration and Uncertainty)** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2607.16229) | — | — |
| 2026 | **MortarBench** | `✅ Reliability & Truthfulness`<br>`⚖️ Fairness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2606.19416) | [💻](https://github.com/mtoles/MortarBench) | [🤗](https://huggingface.co/datasets/ManavMunjal/MortarBench) |
| 2026 | **Look-Ahead-Bench** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2601.13770) | [💻](https://github.com/benstaf/lookaheadbench) | — |
| 2026 | **AgentFairBench** | `⚖️ Fairness` | arXiv | [📄](https://arxiv.org/abs/2606.16723) | [💻](https://github.com/rohithreddybc/AgentFairBench) | — |
| 2026 | **Denial-AI Benchmark** | `✅ Reliability & Truthfulness` | SSRN | [📄](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7156938) | — | [🤗](https://huggingface.co/datasets/FinanceRateCalc/denial-ai-benchmark) |
| 2026 | **DFAH-Bench** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2607.20491) | [💻](https://github.com/ibm-client-engineering/output-drift-financial-llms) | — |
| 2026 | **FinRiskAtlas** | `✅ Reliability & Truthfulness` | arXiv | [📄](https://arxiv.org/abs/2608.25325) | — | — |
| 2026 | **FinStructBench / LLM-as-Judge Reliability** | `✅ Reliability & Truthfulness` | SSRN | [📄](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6482162) | [💻](https://github.com/asudjianto-xml/finstructbench) | — |
| 2026 | **KTD-Fin / From Knowing to Doing** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2605.28359) | — | — |
| 2026 | **LongHorizon-Bench** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness` | arXiv | [📄](https://arxiv.org/abs/2604.19457) | — | — |
| 2026 | **Pave Interchange Fee Benchmark** | `✅ Reliability & Truthfulness` | SSRN | [📄](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6944801) | [💻](https://github.com/avae-ai/pave-benchmark) | — |
| 2026 | **ReguSim / ReguBench** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness` | arXiv | [📄](https://arxiv.org/abs/2608.19974) | — | — |
| 2026 | **VeriQuant** | `✅ Reliability & Truthfulness` | SSRN | [📄](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7132138) | — | — |
| 2025 | **IIQE Insurance QA Benchmark** | `🛡️ Safety & Compliance` | APSEC 2025 | [📄](https://doi.org/10.1109/APSEC66846.2025.00079) | — | — |
| 2025 | **Financial Market Abuse Ethical-Judgment Benchmark** | `🛡️ Safety & Compliance` | ICAIF 2025 | [📄](https://doi.org/10.1145/3768292.3770439) | [💻](https://github.com/avifin19/ethical-llms-financial-crime) | — |
| 2025 | **FinTrust** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness`<br>`⚖️ Fairness`<br>`🔐 Privacy`<br>`🧱 Robustness` | EMNLP 2025 | [📄](https://aclanthology.org/2025.emnlp-main.512/) | [💻](https://github.com/HughieHu/FinTrust) | [🤗](https://huggingface.co/datasets/HughieHu/FinTrust) |
| 2025 | **CFinBench** | `🛡️ Safety & Compliance` | NAACL 2025 | [📄](https://aclanthology.org/2025.naacl-long.40/) | [💻](https://github.com/BWY-02/CFinBench-Eval) | — |
| 2025 | **FinEval** | `🛡️ Safety & Compliance` | NAACL 2025 | [📄](https://aclanthology.org/2025.naacl-long.318/) | [💻](https://github.com/SUFE-AIFLM-Lab/FinEval) | — |
| 2025 | **PHANTOM** | `✅ Reliability & Truthfulness` | NeurIPS 2025 (Datasets & Benchmarks) | [📄](https://papers.nips.cc/paper_files/paper/2025/hash/b8badadce3f482ba340ff870f4894441-Abstract-Datasets_and_Benchmarks_Track.html) | — | [🤗](https://huggingface.co/datasets/seyled/Phantom_Hallucination_Detection) |
| 2025 | **FAITH** | `✅ Reliability & Truthfulness` | ICAIF 2025 | [📄](https://doi.org/10.1145/3768292.3770433) | [💻](https://github.com/ZHANG-MENGAO/FAITH) | — |
| 2025 | **FinLFQA** | `✅ Reliability & Truthfulness` | Findings of EMNLP 2025 | [📄](https://aclanthology.org/2025.findings-emnlp.908/) | [💻](https://github.com/yitaoLong/FinLFQA) | [🤗](https://huggingface.co/datasets/Dragongon/FinLFQA) |
| 2025 | **Fin-Fact** | `✅ Reliability & Truthfulness` | The Web Conference 2025 (Companion) | [📄](https://doi.org/10.1145/3701716.3715292) | [💻](https://github.com/IIT-DM/Fin-Fact) | [🤗](https://huggingface.co/datasets/amanrangapur/Fin-Fact) |
| 2025 | **Accept or Deny** | `⚖️ Fairness`<br>`🧱 Robustness` | Findings of EMNLP 2025 | [📄](https://aclanthology.org/2025.findings-emnlp.947/) | — | — |
| 2025 | **Positional Bias Financial Benchmark** | `⚖️ Fairness`<br>`🧱 Robustness` | ICAIF 2025 | [📄](https://doi.org/10.1145/3768292.3770394) | — | — |
| 2025 | **FinBias (SAFE)** | `⚖️ Fairness` | ICAIF 2025 | [📄](https://doi.org/10.1145/3768292.3770355) | — | — |
| 2025 | **AI’s Predictable Memory** | `✅ Reliability & Truthfulness` | Economics Letters 2025 | [📄](https://doi.org/10.1016/j.econlet.2025.112602) | — | — |
| 2025 | **DeepFund / Time Travel is Cheating** | `✅ Reliability & Truthfulness` | NeurIPS 2025 (Datasets & Benchmarks) | [📄](https://proceedings.neurips.cc/paper_files/paper/2025/hash/f37b0e09b90e9a6833aacf5768362b54-Abstract-Datasets_and_Benchmarks_Track.html) | [💻](https://github.com/HKUSTDial/DeepFund) | — |
| 2025 | **MMESGBench** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness` | ACM Multimedia 2025 | [📄](https://doi.org/10.1145/3746027.3758225) | [💻](https://github.com/Zhanglei1103/MMESGBench) | — |
| 2025 | **Chat Bankman-Fried** | `🛡️ Safety & Compliance`<br>`🧱 Robustness` | Joint FinNLP/FNP/LLMFinLegal Workshop 2025 | [📄](https://aclanthology.org/2025.finnlp-1.1/) | [💻](https://github.com/bancaditalia/llm-alignment-finance-chat-bf) | — |
| 2025 | **FMD-B** | `✅ Reliability & Truthfulness` | The Web Conference 2025 (Companion) | [📄](https://doi.org/10.1145/3701716.3715599) | [💻](https://github.com/lzw108/FMD) | — |
| 2025 | **CUFEInse v1.0** | `🛡️ Safety & Compliance` | arXiv | [📄](https://arxiv.org/abs/2511.07794) | [💻](https://github.com/CUFEInse/CUFEInse) | [🤗](https://huggingface.co/datasets/CUFEInse/CUFEInse) |
| 2025 | **MENTOR** | `🛡️ Safety & Compliance`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2511.07107) | — | [🤗](https://huggingface.co/datasets/feifeinoban/Shell) |
| 2025 | **INSEva** | `🛡️ Safety & Compliance`<br>`✅ Reliability & Truthfulness` | arXiv | [📄](https://arxiv.org/abs/2509.04455) | — | — |
| 2025 | **Finova** | `🛡️ Safety & Compliance` | arXiv | [📄](https://arxiv.org/abs/2507.16802) | [💻](https://github.com/antgroup/Finova) | — |
| 2025 | **FailSafeQA** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2502.06329) | — | [🤗](https://huggingface.co/datasets/Writer/FailSafeQA) |
| 2025 | **FinLake-Bench / Profit Mirage** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2510.07920) | — | — |
| 2025 | **Finance & Accounting LLM Consistency** | `✅ Reliability & Truthfulness` | SSRN | [📄](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5189069) | — | — |
| 2025 | **FinCriticalED** | `✅ Reliability & Truthfulness` | arXiv | [📄](https://arxiv.org/abs/2511.14998) | [💻](https://github.com/The-FinAI/FinCriticalED) | [🤗](https://huggingface.co/datasets/TheFinAI/FinCriticalED) |
| 2025 | **Social Group Bias in AI Finance** | `⚖️ Fairness` | SSRN | [📄](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5287153) | — | — |
| 2024 | **FinBen** | `🛡️ Safety & Compliance` | NeurIPS 2024 (Datasets & Benchmarks) | [📄](https://proceedings.neurips.cc/paper_files/paper/2024/hash/adb1d9fa8be4576d28703b396b82ba1b-Abstract-Datasets_and_Benchmarks_Track.html) | [💻](https://github.com/The-FinAI/PIXIU) | — |
| 2024 | **Japanese Financial Benchmark for LLMs** | `🛡️ Safety & Compliance` | FinNLP 2024 | [📄](https://aclanthology.org/2024.finnlp-1.1/) | [💻](https://github.com/pfnet-research/japanese-lm-fin-harness) | — |
| 2024 | **FinDVer** | `✅ Reliability & Truthfulness` | EMNLP 2024 | [📄](https://aclanthology.org/2024.emnlp-main.818/) | [💻](https://github.com/yilunzhao/FinDVer) | — |
| 2023 | **CFBenchmark** | `🛡️ Safety & Compliance`<br>`🔐 Privacy` | arXiv | [📄](https://arxiv.org/abs/2311.05812) | [💻](https://github.com/TongjiFinLab/CFBenchmark) | [🤗](https://huggingface.co/datasets/TongjiFinLab/CFBenchmark) |
| 2023 | **Benchmarking Large Language Model Volatility** | `✅ Reliability & Truthfulness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2311.15180) | — | — |
| 2023 | **CALM Credit-Scoring Benchmark** | `⚖️ Fairness`<br>`🧱 Robustness` | arXiv | [📄](https://arxiv.org/abs/2310.00566) | [💻](https://github.com/The-FinAI/CALM) | [🤗](https://huggingface.co/daishen/CALM-7B) |

## 📝 Citation

If you find this collection or the survey useful, please cite:

```bibtex
@misc{lin2026survey,
  title        = {A Survey of Trustworthiness Benchmarks for Large Language Models in Finance},
  author       = {Lin, Chenwei and Wu, Jianhao and Huan, Hongxin and Huang, Chensong and Xu, Xian},
  year         = {2026},
  month        = aug,
  note         = {Preprint},
  doi          = {10.13140/RG.2.2.19372.83841},
  url          = {https://www.researchgate.net/publication/413695666_A_Survey_of_Trustworthiness_Benchmarks_for_Large_Language_Models_in_Finance}
}
```

## 🤝 Contributing

Corrections and additions are welcome through issues or pull requests. For a new benchmark, please provide:

- year and benchmark name;
- trustworthiness dimension(s);
- publication venue or current preprint status;
- paper link;
- GitHub / code link, if available; and
- Hugging Face dataset or model link, if available.

---

Maintained as the companion benchmark collection for [**A Survey of Trustworthiness Benchmarks for Large Language Models in Finance**](https://www.researchgate.net/publication/413695666_A_Survey_of_Trustworthiness_Benchmarks_for_Large_Language_Models_in_Finance).

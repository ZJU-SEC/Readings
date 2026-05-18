# Readings

## Agent Security

### Core Attack Surfaces
|Type|Conference|Paper|
|------|------|------|
|Prompt Injection & Indirect Instruction|||
||2026-ICLR|[ChatInject: Abusing Chat Templates for Prompt Injection in LLM Agents](https://openreview.net/forum?id=WVhgFSKniL)
||2026-ICLR|[Indirect Prompt Injections: Are Firewalls All You Need, or Stronger Benchmarks?](https://openreview.net/forum?id=MqLJRCUBYG)
||2026-ICLR|[PromptArmor: An Essential Baseline for Prompt Injection Defenses](https://openreview.net/forum?id=IeNXtofK6T)
||2026-NDSS|[Attention is All You Need to Defend Against Indirect Prompt Injection Attacks in LLMs](https://www.ndss-symposium.org/ndss-paper/attention-is-all-you-need-to-defend-against-indirect-prompt-injection-attacks-in-llms/)
||2026-NDSS|[ObliInjection: Order-Oblivious Prompt Injection Attack to LLM Agents with Multi-source Data](https://www.ndss-symposium.org/ndss-paper/obliinjection-order-oblivious-prompt-injection-attack-to-llm-agents-with-multi-source-data/)
||2025-ACM CCS|[Here Comes the AI Worm: Preventing the Propagation of Adversarial Self-Replicating Prompts Within GenAI Ecosystems](https://doi.org/10.1145/3719027.3765196)
||2025-ACM CCS|[SecAlign: Defending Against Prompt Injection with Preference Optimization](https://doi.org/10.1145/3719027.3744836)
||2025-ICML|[MELON: Provable Defense Against Indirect Prompt Injection Attacks in AI Agents](https://proceedings.mlr.press/v267/zhu25z.html)
||2025-IEEE S&P|[DataSentinel: A Game-Theoretic Detection of Prompt Injection Attacks](https://doi.org/10.1109/SP61157.2025.00250)
||2025-IEEE S&P|[Fun-tuning: Characterizing the Vulnerability of Proprietary LLMs to Optimization-Based Prompt Injection Attacks via the Fine-Tuning Interface](https://doi.org/10.1109/SP61157.2025.00121)
||2025-NeurIPS|[DRIFT: Dynamic Rule-Based Defense with Injection Isolation for Securing LLM Agents](https://neurips.cc/virtual/2025/poster/116028)
||2025-USENIX Security|[Make Agent Defeat Agent: Automatic Detection of Taint-Style Vulnerabilities in LLM-based Agents](https://www.usenix.org/conference/usenixsecurity25/presentation/liu-fengyu)
||2025-USENIX Security|[SelfDefend: LLMs Can Defend Themselves against Jailbreaking in a Practical Manner](https://www.usenix.org/conference/usenixsecurity25/presentation/wang-xunguang)
||2025-USENIX Security|[StruQ: Defending Against Prompt Injection with Structured Queries](https://www.usenix.org/conference/usenixsecurity25/presentation/chen-sizhe)
||2024-ACM CCS|[A Causal Explainable Guardrails for Large Language Models](https://doi.org/10.1145/3658644.3690217)
||2024-ACM CCS|[Optimization-based Prompt Injection Attack to LLM-as-a-Judge](https://doi.org/10.1145/3658644.3690291)
|Tool Hijacking & Tool Selection|||
||2026-ICLR|[ToolTweak: An Attack on Tool Selection in LLM-based Agents](https://openreview.net/forum?id=dQXa5jvpQN)
||2026-ICLR|[TrojanTools: Adaptive Indirect Prompt Injection on LLM Agents via Malicious Tool-Calling](https://openreview.net/forum?id=PFbt5pWWh7)
||2026-NDSS|[Les Dissonances: Cross-Tool Harvesting and Polluting in Pool-of-Tools Empowered LLM Agents](https://www.ndss-symposium.org/ndss-paper/les-dissonances-cross-tool-harvesting-and-polluting-in-pool-of-tools-empowered-llm-agents/)
||2026-NDSS|[Prompt Injection Attack to Tool Selection in LLM Agents](https://www.ndss-symposium.org/ndss-paper/prompt-injection-attack-to-tool-selection-in-llm-agents/)
||2025-EMNLP|[IPIGuard: A Novel Tool Dependency Graph-Based Defense Against Indirect Prompt Injection in LLM Agents](https://aclanthology.org/2025.emnlp-main.53/)
||2025-NeurIPS|[Attractive Metadata Attack: Inducing LLM Agents to Invoke Malicious Tools](https://neurips.cc/virtual/2025/poster/116046)
|Memory / Context Poisoning|||
||2026-ICLR|[A-MemGuard: A Proactive Defense Framework for LLM-Based Agent Memory](https://openreview.net/forum?id=fVxfCEv8xG)
||2026-ICLR|[InjecMEM: Memory Injection Attack on LLM Agent Memory Systems](https://openreview.net/forum?id=QVX6hcJ2um)
||2026-ICLR Workshop MemAgents|[Memory Injection Attacks on LLM Agents via Query-Only Interaction](https://openreview.net/forum?id=i7J62t2wtV)
||2025-WCUA|[Context Manipulation Attacks: Web Agents Are Susceptible to Corrupted Memory](https://openreview.net/forum?id=4LovHyz92W)
|Prompt / Configuration Leakage|||
||2026-IEEE S&P|[LLMThief: Evaluating Configuration Leaking Risks in Commercial LLM App Stores](https://www.jianjunchen.com/p/llm-leak.SP26.pdf)
||2025-ACM CCS|[Prompt Inference Attack on Distributed Large Language Model Inference Frameworks](https://doi.org/10.1145/3719027.3744820)
||2025-ACM CCS|[You Can't Steal Nothing: Mitigating Prompt Leakages in LLMs via System Vectors](https://doi.org/10.1145/3719027.3765124)
||2025-IEEE S&P|[On the Effectiveness of Prompt Stealing Attacks on In-the-Wild Prompts](https://ieeexplore.ieee.org/document/11023383)
||2025-USENIX Security|[PRSA: Prompt Stealing Attacks against Real-World Prompt Services](https://www.usenix.org/conference/usenixsecurity25/presentation/yang-yong)

### System Boundaries & Ecosystem Security
|Type|Conference|Paper|
|------|------|------|
|Execution Isolation & Permission Control|||
||2026-IEEE S&P|[Towards Automating Data Access Permissions in AI Agents](https://arxiv.org/abs/2511.17959)
||2026-NDSS|[ACE: A Security Architecture for LLM-Integrated App Systems](https://www.ndss-symposium.org/ndss-paper/ace-a-security-architecture-for-llm-integrated-app-systems/)
||2026-NDSS|[Beyond Jailbreak: Unveiling Risks in LLM Applications Arising from Blurred Capability Boundaries](https://www.ndss-symposium.org/ndss-paper/beyond-jailbreak-unveiling-risks-in-llm-applications-arising-from-blurred-capability-boundaries/)
||2025-NDSS|[IsolateGPT: An Execution Isolation Architecture for LLM-Based Agentic Systems](https://www.ndss-symposium.org/ndss-paper/isolategpt-an-execution-isolation-architecture-for-llm-based-agentic-systems/)
||2024-ACM CCS|[Demystifying RCE Vulnerabilities in LLM-Integrated Apps](https://doi.org/10.1145/3658644.3690338)
|MCP / Plugin / App Ecosystem Security|||
||2026-ICLR|[Log-To-Leak: Prompt Injection Attacks on Tool-Using LLM Agents via Model Context Protocol](https://openreview.net/forum?id=UVgbFuXPaO)
||2026-IEEE S&P|[When AI Meets the Web: Prompt Injection Risks in Third-Party AI Chatbot Plugins](https://arxiv.org/abs/2511.05797)
||2025-IEEE S&P|[On the (In)Security of LLM App Stores](https://doi.org/10.1109/SP61157.2025.00117)
|Multi-Agent Trust / Governance|||
||2026-ICLR|[Exposing Weak Links in Multi-Agent Systems under Adversarial Prompting](https://openreview.net/forum?id=WHVk2qoCIY)
||2026-NDSS|[SAGA: A Security Architecture for Governing AI Agentic Systems](https://www.ndss-symposium.org/ndss-paper/saga-a-security-architecture-for-governing-ai-agentic-systems/)
||2025-AAAI|[Multi-Agent Security Tax: Trading Off Security and Collaboration Capabilities in Multi-Agent Systems](https://ojs.aaai.org/index.php/AAAI/article/view/34970)
||2025-ACL|[G-Safeguard: A Topology-Guided Security Lens and Treatment on LLM-based Multi-agent Systems](https://aclanthology.org/2025.acl-long.359/)
||2025-ACL|[Red-Teaming LLM Multi-Agent Systems via Communication Attacks](https://aclanthology.org/2025.findings-acl.349/)
||2024-AAAI|[Robust Communicative Multi-Agent Reinforcement Learning with Active Defense](https://ojs.aaai.org/index.php/AAAI/article/view/29708)
||2024-ICML|[Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast](https://proceedings.mlr.press/v235/gu24e.html)

### Agent Settings & Real Environments
|Type|Conference|Paper|
|------|------|------|
|Web / Browser Agent Security|||
||2026-IEEE S&P|[Investigating the Impact of Dark Patterns on LLM-Based Web Agents](https://arxiv.org/abs/2510.18113)
||2026-IEEE S&P|[WebCloak: Characterizing and Mitigating Threats from LLM-Driven Web Agents as Intelligent Scrapers](https://www.computer.org/csdl/proceedings-article/sp/2026/606500a454/2bojvpDqlgc)
||2025-ICML|[AdvAgent: Controllable Blackbox Red-teaming on Web Agents](https://proceedings.mlr.press/v267/xu25m.html)
||2025-USENIX Security|[When LLMs Go Online: The Emerging Threat of Web-Enabled LLMs](https://www.usenix.org/conference/usenixsecurity25/presentation/kim-hanna)
|Computer-Use / Coding Agent Security|||
||2026-ICLR|[Deep-Cover Agents: Long-Horizon Prompt Injections on Production LLM Systems](https://openreview.net/forum?id=U3kxnDzuRz)
||2025-IEEE S&P|[Make a Feint to the East While Attacking in the West: Blinding LLM-Based Code Auditors with Flashboom Attacks](https://doi.org/10.1109/SP61157.2025.00125)
||2025-NeurIPS|[MIP against Agent: Malicious Image Patches Hijacking Multimodal OS Agents](https://neurips.cc/virtual/2025/poster/117813)
||2024-ACM CCS|[PromSec: Prompt Optimization for Secure Generation of Functional Source Code with Large Language Models (LLMs)](https://doi.org/10.1145/3658644.3690298)

### Security Infrastructure
|Type|Conference|Paper|
|------|------|------|
|Monitoring / Oversight|||
||2026-ICLR|[How Does Information Access Affect LLM Monitors' Ability to Detect Sabotage?](https://openreview.net/forum?id=PLidw19tPf)
||2026-ICLR|[Reliable Weak-to-Strong Monitoring of LLM Agents](https://openreview.net/forum?id=WV7xIboTDK)
||2025-BuildingTrust|[Monitoring LLM Agents for Sequentially Contextual Harm](https://openreview.net/forum?id=LC0XQ6ufbr)
||2025-USENIX Security|[Cloak, Honey, Trap: Proactive Defenses Against LLM Agents](https://www.usenix.org/conference/usenixsecurity25/presentation/ayzenshteyn)
|Benchmark / Evaluation Platform|||
||2026-ICLR|[A2ASecBench: A Protocol-Aware Security Benchmark for Agent-to-Agent Multi-Agent Systems](https://openreview.net/forum?id=LfdFnakqGJ)
||2026-ICLR|[Breaking Agent Backbones: Evaluating the Security of Backbone LLMs in AI Agents](https://openreview.net/forum?id=kga18ld70t)
||2026-ICLR|[RedTeamCUA: Realistic Adversarial Testing of Computer-Use Agents in Hybrid Web-OS Environments](https://openreview.net/forum?id=yWwrgcBoK3)
||2026-ICLR|[VPI-Bench: Visual Prompt Injection Attacks for Computer-Use Agents](https://openreview.net/forum?id=UMauKu2azg)
||2025-ICLR|[Agent Security Bench (ASB): Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents](https://openreview.net/forum?id=V4y0CpX4hK)
||2025-ICLR|[AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents](https://openreview.net/forum?id=AC5n7xHuR1)
||2025-ICML|[SafeArena: Evaluating the Safety of Autonomous Web Agents](https://proceedings.mlr.press/v267/tur25a.html)
||2025-NeurIPS|[OS-Harm: A Benchmark for Measuring Safety of Computer Use Agents](https://neurips.cc/virtual/2025/loc/san-diego/poster/121772)
||2025-NeurIPS|[SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://neurips.cc/virtual/2025/poster/118134)
||2025-NeurIPS|[Security Challenges in AI Agent Deployment: Insights from a Large Scale Public Competition](https://neurips.cc/virtual/2025/poster/121622)
||2025-NeurIPS|[WASP: Benchmarking Web Agent Security Against Prompt Injection Attacks](https://neurips.cc/virtual/2025/poster/121728)
||2024-ACL Findings|[InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated Large Language Model Agents](https://aclanthology.org/2024.findings-acl.624/)
||2024-NeurIPS|[AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents](https://proceedings.neurips.cc/paper_files/paper/2024/hash/97091a5177d8dc64b1da8bf3e1f6fb54-Abstract-Datasets_and_Benchmarks_Track.html)

## Software Supply Chain
|Type|Conference|Paper|
|------|------|------|
|Security|||
||2022-S&P| [“They’re not that hard to mitigate”: What Cryptographic Library Developers Think About Timing Attacks](https://cryptojedi.org/papers/usect-20211216.pdf)
||2022-NDSS|[Building Embedded Systems Like It’s 1996](https://arxiv.org/pdf/2203.06834.pdf)
||2022-NDSS|[Probe the Proto: Measuring Client-Side Prototype Pollution Vulnerabilities of One Million Real-world Websites](https://yinzhicao.org/ProbetheProto/ProbetheProto.pdf)
||2022-NDSS|[Cross-Language Attacks](https://www.ndss-symposium.org/wp-content/uploads/2022-78-paper.pdf)
||2022-S&P|[Asleep at the Keyboard? Assessing the Security of GitHub Copilot’s Code Contributions](https://arxiv.org/pdf/2108.09293.pdf)
||2022-S&P|[Committed to Trust: A Qualitative Study on Security & Trust in Open Source Software Projects](https://www.computer.org/csdl/proceedings-article/sp/2022/131600b572/1CIO8qrO28E)
||2022-USENIX|[How Long Do Vulnerabilities Live in the Code? A Large-Scale Empirical Measurement Study on FOSS Vulnerability Lifetimes](https://www.usenix.org/system/files/sec22summer_alexopoulos.pdf)
||2021-CCS|[Supply-chain vulnerability elimination via active learning and regeneration](https://dl.acm.org/doi/abs/10.1145/3460120.3484736)
||2021-CCS|[Preventing Dynamic  Library Compromise on Node.js via RWX-Based Privilege Reduction](https://nikos.vasilak.is/p/mir:ccs:2021.pdf)
||2021-CCS|[The Effect of Google Search on Software Security: Unobtrusive Security Interventions via Content Re-ranking](https://dl.acm.org/doi/pdf/10.1145/3460120.3484763)
||2021-NDSS|[Towards Measuring Supply Chain Attacks on Package Managers for Interpreted Languages](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_1B-1_23055_paper.pdf)
||2021-USENIX|[Abusing Hidden Properties to Attack the Node.js Ecosystem](https://www.usenix.org/system/files/sec21-xiao.pdf)
||2021-USENIX|[An Investigation of the Android Kernel Patch Ecosystem](https://www.usenix.org/system/files/sec21-zhang-zheng.pdf)
||2021-ACM-SIGSAC|[Supply-Chain Vulnerability Elimination via Active Learning and Regeneration](https://nikos.vasilak.is/p/harp:ccs:2021.pdf)
||2020-ACM-SIGSAC|[Towards Using Source Code Repositories to Identify Software Supply Chain Attacks](http://www.lyvu.me/papers/ccs20poster-paper5.pdf)
||2020-CCS|[A Qualitative Study of Dependency Management and Its Security Implications](https://dl.acm.org/doi/abs/10.1145/3372297.3417232)
||2020-S&P|[An Analysis of Pre-installed Android Software](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9152633)
||2020-RAID|[Mininode: Reducing the Attack Surface of Node.js Applications](https://www.usenix.org/system/files/raid20-koishybayev.pdf)
||2019-USENIX|[Small World with High Risks: A Study of Security Threats in the npm Ecosystem](https://www.usenix.net/system/files/sec19-zimmermann.pdf)
||2019-ASIACCS|[ScriptProtect: Mitigating Unsafe Third-Party JavaScript Practices](https://swag.cispa.saarland/papers/musch2019scriptprotect.pdf)
||2019-NDSS|[How Bad Can It Git? Characterizing Secret Leakage in Public GitHub Repositories](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_04B-3_Meli_paper.pdf)
||2019-USENIX|[Less is More: Quantifying the Security Benefits of Debloating Web Applications](https://www.usenix.org/system/files/sec19-azad.pdf)
||2018-CCS|[Towards Paving the Way for Large-Scale Windows Malware Analysis: Generic Binary Unpacking with Orders-of-Magnitude Performance Boost](https://dl.acm.org/doi/10.1145/3243734.3243771)
||2018-NDSS|[BreakApp: Automated, Flexible Application Compartmentalization](http://ic.ese.upenn.edu/pdf/breakapp_ndss2018.pdf)
||2017-NDSS|[Thou Shalt Not Depend on Me: Analysing the Use of Outdated JavaScript Libraries on the Web](https://arxiv.org/abs/1811.00918)
||2017-CCS|[Keep me Updated: An Empirical Study of Third-Party Library Updatability on Android](https://acmccs.github.io/papers/p2187-derrA.pdf)
||2016-USENIX|[On Omitting Commits and Committing Omissions: Preventing Git Metadata Tampering That (Re)introduces Software Vulnerabilities](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_torres-arias.pdf)
||2012-CCS|[You Are What You Include: Large-scale Evaluation of Remote JavaScript Inclusions](https://dl.acm.org/doi/pdf/10.1145/2382196.2382274)
||2008-CCS|[A look in the mirror: attacks on package managers](https://theupdateframework.io/papers/attacks-on-package-managers-ccs2008.pdf)
||2003-S&P|[Poisoning the software supply chain](https://ieeexplore.ieee.org/document/1203227)
|Software Engineering|||
||2022-ISSTA|[A Large-Scale Empirical Analysis of the Vulnerabilities Introduced by Third-Party Components in IoT Firmware](https://nesa.zju.edu.cn/download/zbb_pdf_issta_22.pdf)
||2022-WWW|[Understanding the Practice of Security Patch Management across Multiple Branches in OSS Projects](https://csis.gmu.edu/ksun/publications/PatchStudy_WWW22.pdf)
||2022-ICSE|[Demystifying the Vulnerability Propagation and Its Evolution via Dependency Trees in the NPM Ecosystem](https://arxiv.org/pdf/2201.03981)
||2022-ICSE|[Practical Automated Detection of Malicious npm Packages](https://arxiv.org/pdf/2202.13953.pdf)
||2022-TSE|[Open or Sneaky? Fast or Slow? Light or Heavy?: Investigating Security Releases of Open Source Packages](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9792380)
||2021-TSE|[Identifying Challenges for OSS Vulnerability Scanners - A Study & Test Suite](https://ieeexplore.ieee.org/document/9506931)
||2021-ICSE|[Containing Malicious Package Updates in npm with a Lightweight Permission System](https://www.cs.cmu.edu/~ckaestne/pdf/icse21_malicious.pdf)
||2021-ICSE|[HERO: On the Chaos When PATH Meets Modules](https://arxiv.org/pdf/2102.12105.pdf)
||2021-SANER|[Empirical Analysis of Security Vulnerabilities in Python Packages](https://arxiv.org/pdf/1810.13310.pdf)
||2021-ESEC/FSE|[Detecting Node.js prototype pollution vulnerabilities via object lookup analysis](https://dl.acm.org/doi/pdf/10.1145/3468264.3468542)
||2021-ASE|[REPFINDER: Finding Replacements for Missing APIs in Library Update](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9678905)
||2021-ESEC/FSE|[A Longitudinal Analysis of Bloated Java Dependencies](https://dl.acm.org/doi/pdf/10.1145/3468264.3468589)
||2021-ESEC/FSE|[LastPyMile: identifying the discrepancy between sources and packages](https://dl.acm.org/doi/pdf/10.1145/3468264.3468592)
||2021-ESEC/FSE|[A large-scale empirical study on Java library migrations: prevalence, trends, and rationales](https://dl.acm.org/doi/pdf/10.1145/3468264.3468571)
||2021-TSE|[Dependency Smells in JavaScript Projects](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9519532)
||2021-TSE|[Back to the Past -- Analysing Backporting Practices in Package Dependency Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9540328)
||2020-ICSME|[Investigating the reproducibility of npm packages](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9240695)
||2020-ICSE|[Extracting taint specifications for JavaScript libraries](https://software-lab.org/publications/icse2020_Taser.pdf)
||2020-ICSE|[Watchman: monitoring dependency conflicts for Python library ecosystem](https://sqlab-sustech.github.io/files/paper/ICSE2020_Watchman.pdf)
||2020-ESEC/FSE|[Interactive, effort-aware library version harmonization](https://dl.acm.org/doi/pdf/10.1145/3368089.3409689)
||2019-ICSE|[Detecting Suspicious Package Updates](https://www.cs.cmu.edu/~gferreir/pre-prints/icse2019-detecting-suspicious-package-updates.pdf)
||2018-ESEC/FSE|[Do the dependency conflicts in my project matter?](http://castle.cse.ust.hk/castle/publication/materials/fse18-ying.pdf)
||2018-ESEC/FSE|[The impact of regular expression denial of service (redos) in practice: an empirical study at the ecosystem scale](https://dl.acm.org/doi/pdf/10.1145/3236024.3236027)
||2017-ICSE|[How do developers fix cross-project correlated bugs? A case study on the GitHub scientific Python ecosystem](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7985678)
||2017-ASE-Workshop|[Can automated pull requests encourage software developers to upgrade out-of-date dependencies?](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8115621)
||2017-ESEC/FSE|[Why do developers use trivial packages? an empirical case study on npm.](https://dl.acm.org/doi/pdf/10.1145/3106237.3106267)
||2016-ESEC/FSE|[How to break an API: cost negotiation and community values in three software ecosystems.](https://dl.acm.org/doi/pdf/10.1145/2950290.2950325)
||2015-ICSME|[Impact assessment for vulnerabilities in open-source software libraries](https://arxiv.org/pdf/1504.04971.pdf)
||2015-SANER|[Tracking known security vulnerabilities in proprietary software systems](https://pure.tudelft.nl/ws/portalfiles/portal/86335468/cadariu2015.pdf)
||2015-ASE-Workshop|[When It Breaks, It Breaks: How Ecosystem Developers Reason about the Stability of Dependencies](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7426643)
||2015-ICSW|[Measuring Dependency Freshness in Software Systems](https://ericbouwers.github.io/papers/icse15.pdf)



## Kernel Static Analysis

### Latest Static Analysis Technique

* 2001-OSR: [Bugs as Deviant Behavior: A General Approach to Inferring Errors in Systems Code](https://apps.dtic.mil/sti/pdfs/ADA419584.pdf)
* 2019-FSE：[Detecting Concurrency Memory Corruption Vulnerabilities](https://dl.acm.org/doi/10.1145/3338906.3338927) — 【[tool-CONVUL](https://github.com/mryancai/ConVul)】

### Detecting UB Bugs in Kernel

* 2021-NDSS: [KUBO: Precise and Scalable Detection of User-triggerable Undefined Behavior Bugs in OS Kernel](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_1B-5_24461_paper.pdf)
* 2019-USENIX-ATC：[Effective Static Analysis of Concurrency Use-After-Free Bugs in Linux Device Drivers](https://www.usenix.org/conference/atc19/presentation/bai) — 【[note](https://securitygossip.com/blog/2019/11/22/effective-static-analysis-of-concurrency-use-after-free-bugs-in-linux-device-drivers/)】

### Detecting Logical Bugs in Kernel

* 2020-CCS: [Exaggerated Error Handling Hurts! An In-Depth Study and Context-Aware Detection](https://www-users.cs.umn.edu/~kjlu/papers/eecatch.pdf)
* 2019-USENIX：[PeX: A Permission Check Analysis Framework for Linux Kernel](https://www.usenix.org/conference/usenixsecurity19/presentation/zhang-tong)
* 2018-S&P：[DEADLINE-Precise and Scalable Detection of Double-Fetch Bugs in OS Kernels](http://www-users.cs.umn.edu/~kjlu/papers/deadline.pdf) — 【[note](https://www.jianshu.com/p/e4084b2c7c16)】【[note2](https://www.jianshu.com/p/7e2f15547f1e)】【[note3](https://www.inforsec.org/wp/?p=2550)】【[tool-DEADLINE](https://github.com/sslab-gatech/deadline)】

### Research Trends of Kernel Static Analysis



* 2020-TOCS：[Effective Detection of Sleep-in-atomic-context Bugs in the Linux Kernel](https://dl.acm.org/doi/pdf/10.1145/3381990)
* 2019-ASPLOS: [DCNS: Automated Detection Of Conservative Non-Sleep Defects in the Linux Kernel](https://hal.inria.fr/hal-02389543/document)

* 2019-USENIX：[Detecting Missing-Check Bugs via Semantic- and Context-Aware Criticalness and Constraints Inferences](https://www.usenix.org/conference/usenixsecurity19/presentation/lu) — 【[tool-CRIX](https://github.com/umnsec/crix)】


* 2018-USENIX-ATC：[DSAC: Effective Static Analysis of Sleep-in-Atomic-Context Bugs in Kernel Modules](https://www.usenix.org/system/files/conference/atc18/atc18-bai.pdf)
* 2018-NDSS：[K-Miner: Uncovering Memory Corruption in Linux](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_05A-1_Gens_paper.pdf) — 【[note](https://mp.weixin.qq.com/s/3N3rmAyZEbZpiBvxnjWVvA)】【[note2](https://blog.csdn.net/u012332816/article/details/79795643)】【[tool-K-Miner](https://github.com/ssl-tud/k-miner)】

* 2018-CCS：[Check It Again- Detecting Lacking-Recheck Bugs in OS Kernels ](https://www-users.cs.umn.edu/~kjlu/papers/lrsan.pdf)— 【[note](https://www.jianshu.com/p/2f8df6082b1d)】【[note2](https://securitygossip.com/blog/2018/11/27/check-it-again-detecting-lacking-recheck-bugs-in-os-kernels/)】【[tool-LRSan](https://github.com/kengiter/lrsan)】
* 2017-USENIX：[How Double-Fetch Situations turn into DoubleFetch](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-wang.pdf) — 【[note](http://www.inforsec.org/wp/?p=2049)】【[tool](https://github.com/wpengfei/double_fetch_cocci)】
* 2017-USENIX：[DR. CHECKER- A Soundy Analysis for Linux Kernel Drivers](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-machiry.pdf) — 【[tool-dr_checker](https://github.com/ucsb-seclab/dr_checker)】
* 2017-USENIX：[Digtool- A Virtualization-Based Framework for Detecting Kernel Vulnerabilities-usenix](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-pan.pdf) — 【[note](https://www.jianshu.com/p/3cc85231657d)】【[note2](https://mp.weixin.qq.com/s/RFWqx0LXWuHcJNbb8lrjFA)】【[note3](http://yama0xff.com/2019/02/15/Digtool-A-Virtualization-Based-Framework-for-Detecting-Kernel-Vulnerabilities/)】【[note4](https://securitygossip.com/blog/2018/10/09/digtool-a-virtualization-based-framework-for-detecting-kernel-vulnerabilities/)】
* 2017-EUROSYS：[DangSan - Scalable Use-after-free Detection](https://doi.org/10.1145/3064176.3064211) — 【[tool-dangsan](https://github.com/vusec/dangsan)】
* 2016-USENIX：[APISan: Sanitizing API Usages through Semantic Cross-Checking](https://pdfs.semanticscholar.org/29c2/42b2b73c376a61344877d5488f33e066ecc8.pdf?_ga=2.254762891.2010008061.1593351615-150437918.1586869794) — 【[tool-apisan](https://github.com/sslab-gatech/apisan)】
* 2016-USENIX：[UniSan-Proactive Kernel Memory Initialization to Eliminate Data Leakages](https://dl.acm.org/doi/pdf/10.1145/2976749.2978366) — 【[note](http://www.inforsec.org/wp/?p=1416)】【[tool-unisan](https://github.com/sslab-gatech/unisan)】
* 2015-SOSP：[Cross-checking semantic correctness: The case of finding file system bugs](https://lifeasageek.github.io/papers/min-juxta.pdf) — 【[tool-JUXTA](https://github.com/sslab-gatech/juxta)】
* 2014-USENIX：[Static Analysis of Variability in System Software - The 90, 000 #ifdefs Issue](https://www.usenix.org/conference/atc14/technical-sessions/presentation/tartler)
* 2013-DSN: [Hector: Detecting resource-release omission faults in error-handling code for systems software](https://hal.inria.fr/hal-00918079/document)
* 2013-WCRE: [Who Allocated My Memory? Detecting Custom Memory Allocators in C Binaries](https://www.cs.vu.nl/~herbertb/papers/membrush_wcre13.pdf)
* 2012-OSDI：[Improving integer security for systems with KINT](https://www.usenix.org/conference/osdi12/technical-sessions/presentation/wang)
* 2008-EUROSYS: [Documenting and automating collateral evolutions in linux device drivers](https://www.researchgate.net/profile/Yoann_Padioleau/publication/221351679_Towards_Documenting_and_Automating_Collateral_Evolutions_in_Linux_Device_Drivers/links/00b7d5255a2ef57876000000/Towards-Documenting-and-Automating-Collateral-Evolutions-in-Linux-Device-Drivers.pdf)
* 2007-ICSE: [Pathsensitive inference of function precedence protocols](https://docs.lib.purdue.edu/cgi/viewcontent.cgi?article=2660&context=cstech)
* 2005-ESEC/FSE: [Context- and Path-sensitive Memory Leak Detection](http://groups.csail.mit.edu/pag/OLD/parg/xie05leak.pdf)


### Kernel Code and Page Table Protection

#### x86
* 2020-SP: [xMP: Selective Memory Protection for Kernel and User Space](https://www3.cs.stonybrook.edu/~mikepo/papers/xmp.sp20.pdf)
* 2017-EUROSP: [On the Effectiveness of Virtualization Based Memory Isolation on Multicore Platforms](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=4701&context=sis_research)
* 2017-NDSS: [PT-Rand: Practical Mitigation of Data-only Attacks against Page Tables](https://pdfs.semanticscholar.org/97c7/8ac6c015b5ed11eb825adc02fbb2a55913ae.pdf)
* 2017-EuroSys: [kR^X: Comprehensive Kernel Protection against Just-In-Time Code Reuse](https://dl.acm.org/doi/pdf/10.1145/3064176.3064216)
* 2016-CCS: [Prefetch Side-Channel Attacks: Bypassing SMAP and Kernel ASLR](https://dl.acm.org/doi/pdf/10.1145/2976749.2978356)
* 2016-CNS: [Preventing Kernel Code-Reuse Attacks Through Disclosure Resistant Code Diversification](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7860485)
* 2015-ASPLOS: [Nested Kernel: An Operating System Architecture for Intra-Kernel Privilege Separation](https://nathandautenhahn.com/downloads/publications/asplos200-dautenhahn.pdf)
* 2015-ATC: [SecPod: A Framework for Virtualization-based Security Systems](https://www.usenix.org/system/files/conference/atc15/atc15-paper-wang-xiaoguang.pdf)
* 2012-ACSEC: [Efficient protection of kernel data structures via object partitioning](https://dl.acm.org/doi/pdf/10.1145/2420950.2421012)
* 2011-ASPLOS: [Ensuring Operating System Kernel Integrity with OSck](https://dl.acm.org/doi/pdf/10.1145/1961295.1950398)
* 2011-NDSS: [Practical Protection of Kernel Integrity for Commodity OS from Untrusted Extensions](https://www.ndss-symposium.org/wp-content/uploads/2017/09/xipdf.pdf)
* 2010-CCS: [Hypersentry: enabling stealthy in-context measurement of hypervisor integrity](http://www.cse.psu.edu/~trj1/cse597-s11/docs/hypersentry_ccs10.pdf)
* 2010-SP: [Hypersafe: A lightweight approach to provide lifetime hypervisor control-flow integrity](http://www.cs.fsu.edu/~zwang/files/oakland10.pdf)
* 2010-SP: [TrustVisor: Efficient TCB Reduction and Attestation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5504713)
* 2010-ACSEC: [Analyzing and improving Linux kernel memory protection: a model checking approach](https://dl.acm.org/doi/pdf/10.1145/1920261.1920301)
* 2009-CCS: [Countering kernel rootkits with lightweight hook protection](https://dl.acm.org/doi/pdf/10.1145/1653662.1653728)
* 2009-USENIX: [Return-Oriented Rootkits: Bypassing Kernel Code Integrity Protection Mechanisms](https://www.usenix.org/legacy/events/sec09/tech/full_papers/hund.pdf)
* 2009-ACSEC: [Protecting Kernel Code and Data with a Virtualization-Aware Collaborative Operating System](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5380702)
* 2007-SOSP: [SecVisor : A Tiny Hypervisor to Provide Lifetime Kernel Code Integrity for Commodity OSes](http://www.cs.cmu.edu/~arvinds/pubs/secvisor.pdf)

#### ARM
* 2017-NDSS：[Dynamic Virtual Address Range Adjustment for Intra-Level Privilege Separation on ARM](https://www.ndss-symposium.org/wp-content/uploads/2017/09/ndss2017_05B-5_Cho_paper.pdf)
* 2016-HPCC-SmartCity-DSS: [TZ-KPM:Kernel Protection Mechanism on Embedded Devices on Hardware-Assisted Isolated Environment](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7828439)
* 2016-NDSS: [SKEE: A lightweight Secure Kernel-level Execution Environment for ARM](https://www.ndss-symposium.org/wp-content/uploads/2017/09/skee-lightweight-secure-kernel-level-execution-environment-for-arm.pdf)
* 2014-MST: [SPROBES: Enforcing Kernel Code Integrity on the TrustZone Architecture](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/10/most14.pdf)
* 2014-CCS: [Hypervision Across Worlds: Real-time Kernel Protection from the ARM TrustZone Secure World](http://www.cse.unsw.edu.au/~cs9242/15/exam/paper2.pdf)

#### RISCV
* 2019-DATE: [RiskiM: Toward Complete Kernel Protection with Hardware Support](https://ieeexplore.ieee.org/abstract/document/8715277)

#### MISC
* 2018-DAC: Hypernel: a hardware-assisted framework for kernel protection without nested paging
* 2016-CNS: [Preventing kernel code-reuse attacks through disclosure resistant code diversification](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7860485)
* 2016-HASP：[Architectural supports to protect OS kernels from code-injection attacks](https://caslab.csl.yale.edu/workshops/hasp2016/HASP16-11.pdf)
* 2008-RAID: [Guest-Transparent Prevention of Kernel Rootkits with VMM-Based Memory Shadowing](https://link.springer.com/content/pdf/10.1007%2F978-3-540-87403-4_1.pdf)
* 1999-ICDCS: [Efficient Kernel Support of Fine-Grained Protection Domains for Mobile Code](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=776507)


#### Kernel Code/PageTable Protect Summary

|Type|Date|Paper|
|------|------|------|
|KLAT - PageTable |||
||2017-NDSS|PT-Rand: Practical Mitigation of Data-only Attacks against Page TablesPT-Rand
||2010-ACSEC| Analyzing and Improving Linux Kernel Memory Protection: A Model Checking Approach
|KLAT - Code|||
||2017-EuroSys| kR^X: Comprehensive Kernel Protection against Just-In-Time Code Reuse
||2016-CNS|Preventing Kernel Code-Reuse Attacks Through Disclosure Resistant Code Diversification
||2015-SP|Readactor: Practical Code Randomization Resilient to Memory Disclosure
||2015-ASPLOS| Nested Kernel: An Operating System Architecture for Intra-Kernel Privilege Separation
||2014-SIGSAC |You Can Run but You Can’t Read: Preventing Disclosure Exploits in Executable Code
||1999-ICDCS |Efficient Kernel Support of Fine-Grained Protection Domains for Mobile Code
|SLAT - PageTable|||
||2020-SP|xMP: Selective Memory Protection for Kernel and User Space 
||2017-EUROP| On the Effectiveness of Virtualization Based Memory Isolation on Multicore Platforms
||2016-ATC| SecPod: SecPod: a Framework for Virtualization-based Security Systems
||2007-SOSP| SecVisor : A Tiny Hypervisor to Provide Lifetime Kernel Code Integrity for Commodity OSes
||USENIX-2018| EPTI: Efficient Defence against Meltdown Attack for Unpatched VMs
||VEE-2020| Lightweight Kernel Isolation with Virtualization and VM Functions
|SLAT - Code|||
||2011-NDSS| Practical Protection of Kernel Integrity for Commodity OS from Untrusted Extensions
||2010-SP| TrustVisor: Efficient TCB Reduction and Attestation
||2009-CCS| Countering kernel rootkits with lightweight hook protection
||2009-ACSEC| Protecting Kernel Code and Data with a Virtualization-Aware Collaborative Operating System
||2008-RAID| Guest-Transparent Prevention of Kernel Rootkits with VMM-Based Memory Shadowing
|Other Hardwares - PageTable |||
||2014-CCS| Hypervision Across Worlds: Real-time Kernel Protection from the ARM TrustZone Secure World
|Other Hardwares - Code |||
||2019-DATE| RiskiM: Toward Complete Kernel Protection with Hardware Support
||2016-HPCC| TZ-KPM Kernel Protection Mechanism on Embedded Devices on Hardware-assisted Isolated Environment 
||2016-NDSS| SKEE: A lightweight Secure Kernel-level Execution Environment for ARM
||2016-HASP| Architectural Supports to Protect OS Kernels from Code-Injection Attacks


#### Kernel Fuzzing
|Type|Date|Paper|
|------|------|------|
|SYSCALL|||
||SOSP 2021|HEALER: Relation Learning Guided Kernel Fuzzing|
||CCS 2021|SyzGen: Automated Generation of Syscall Specification of Closed-Source macOS Drivers|
||NDSS 2020|HFL: Hybrid Fuzzing on the Linux Kernel|
||EuroSec 2020|X-AFL: A Kernel fuzzer combining passive and active fuzzing|
||USENIX 2018|MoonShine: Optimizing OS fuzzer seed selection with trace distillation|
|INPUT|||
||NDSS 2022|EMS : History-Driven Mutation for Coverage-based Fuzzing|
||USENIX 2021|SYZVEGAS : Beating Kernel Fuzzing Odds with Reinforcement Learning|
|DRIVER & FILESYSTEM|||
||NDSS 2022|Semantic-Informed Driver Fuzzing Without Both the Hardware Devices and the Emulators|
||USENIX 2020|USBFuzz: A framework for fuzzing USB drivers by device emulation|
||SP 2020|Ex-vivo dynamic analysis framework for android device drivers|
||ACM Transactions on Storage 2020|Finding Bugs in File Systems with an Extensible Fuzzing Framework|
||SP 2020|KRACE : Data Race Fuzzing for Kernel File Systems|
||SP 2019|Fuzzing File Systems via Two-Dimensional Input Space Exploration|
||SOSP 2019|Finding semantic bugs in file systems with an extensible fuzzing framework|
||CCS 17|Difuze: Interface aware fuzzing for kernel drivers|
|PERFORMANCE|||
||CCS 2021|Hardware Support to Improve Fuzzing Performance and Precision|
||USENIX 2021|Undo Workarounds for Kernel Bugs|
||USENIX 2020|Agamotto : Accelerating Kernel Driver Fuzzing with Lightweight Virtual Machine Checkpoints|
||USENIX 2017|KAFL: Hardware-assisted feedback fuzzing for OS kernels|
|STATE|||
||CCS 2021|HyperFuzzer: An Efficient Hybrid Fuzzer for Virtual CPUs|
||SP 2019|Razzer: Finding kernel race bugs through fuzzing|
||WOOT 2019|Unicorefuzz: On the viability of emulation for kernelspace fuzzing|
|OTHER|||
||USENIX 2022|SyzScope: Revealing High-Risk Security Impacts of Fuzzer-Exposed Bugs in Linux kernel|

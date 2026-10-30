# Awesome-AI-Security-Posture-Management-AI-SPM

# Awesome-AI-Security-Posture-Management-AI-SPM

**Top AI Security Posture Management AI SPM (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on AI Asset Discovery, Model Supply Chain Security, Runtime Guardrails & AI Governance*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Security Posture Management (AI-SPM)**. These tools enable security teams to discover shadow AI, assess model and agent vulnerabilities, enforce runtime guardrails, and demonstrate governance compliance—from fully managed enterprise platforms with agentless discovery and unified threat correlation to self-hosted scanners and governance workbenches that give teams complete control over their AI security telemetry and policy enforcement.



**Examples** include CrowdStrike Falcon AI-SPM, Protect AI, HiddenLayer, Lakera, Robust Intelligence, CalypsoAI, Patronus AI, Fiddler AI, and Aporia (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted AI security scanning, governance, and observability. **Critical note**: The open-source AI-SPM landscape is nascent—**Nephilex** and **AI-Secure-Posture-Management** are early-stage scanners, while **VerifyWise** and **Aegis** focus on governance rather than runtime posture. No open-source project matches CrowdStrike's agentless discovery across managed AI services or Lakera's application-layer prompt injection defense.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global AI security and posture management market is projected to reach approximately **$35.4B to $37.1B in 2026** (scaling toward **$71.6B–$93.7B+ by 2030** at an estimated CAGR of 19%–24%). Market dynamics reflect a **hybrid structure: concentrated at the enterprise cloud core** (dominated by platform giants like CrowdStrike, Cisco, and Palo Alto Networks acquiring specialists), yet **highly fragmented across specialized runtime guardrails, prompt injection defenses, and governance niches** where venture-backed innovators continue to emerge.

## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Focus & Core Capabilities | Pricing (Starting Tier) | Free Tier Limits / Trial |
| :--- | :--- | :--- | :--- | :--- |
| **[CrowdStrike Falcon Cloud Security AI-SPM](https://www.crowdstrike.com/)** | **~$265B market cap** (~$5.4B TTM revenue) | Agentless AI asset discovery, cross-cloud posture assessment, unified threat graph correlation, Charlotte AI triage | Starting at **$7.99/device/month** (Falcon Go base); Cloud Security & AI-SPM packages scale via annual enterprise commitment ($10,000+ min commitment) | **15-day free trial** (up to 50 endpoints with full Falcon prevention & response features enabled) |
| **[Protect AI](https://protectai.com/)** | **~$700M acquisition valuation** (acquired by Palo Alto Networks; $109M raised prior) | Model supply chain vulnerability scanning, MLSecOps pipeline audits, AI-SPM, and red teaming | Annual enterprise contracts starting at **~$50,000/year** (bundled via Prisma AIRS / Private Offers) | **14-day evaluation / PoC** available by sales request (full model scan access on up to 5 pilot models) |
| **[HiddenLayer](https://hiddenlayer.com/)** | **~$400M–$500M+ valuation** ($156M funding raised; >10x ARR growth reported) | Model scanner, ML threat detection, adversarial evasion defense, automated AI-SPM posture | Platform contract units starting at **~$30,000/year** (annual contract; tiered per protected model/app) | **30-day guided Proof of Concept (PoC)** upon qualification (includes full MLSec Platform scan access for 3 models) |
| **[Robust Intelligence](https://www.robustintelligence.com/)** | **$400M acquisition valuation** (acquired by Cisco; $44M venture funding prior) | Automated adversarial red teaming, real-time AI validation, continuous model risk and posture evaluation | Enterprise platform subscriptions starting at **~$40,000/year** (integrated into Cisco Security Cloud licensing) | **14-day sandbox trial** on request (automated vulnerability assessment on 2 custom models) |
| **[Lakera](https://www.lakera.ai/)** | **~$300M acquisition valuation** (acquired by Check Point Software; ~$6M–$7.6M ARR) | Application-layer AI guardrails, real-time prompt injection defense, jailbreak detection, AI red teaming | **Free Community tier ($0/month)**; Pro tier starts at **$0.001 per screening call** (custom plans start from **$499/month**) | **Free forever plan: 10,000 screening requests/month** (up to 8,000 tokens per request, full Lakera Guard API access) |
| **[Fiddler AI](https://www.fiddler.ai/)** | **~$250M+ estimated valuation** ($100M total funding; Series C in 2026; >4x ARR growth) | Unified AI observability control plane, model performance monitoring, explainability, LLM guardrails | Developer pay-as-you-go starting at **$0.002 per trace**; AWS Marketplace starter tiers from **$2,500/month** | **30-day free trial** on AWS Marketplace / SaaS (includes up to 50,000 traces and 1 registered production model) |
| **[CalypsoAI](https://calypsoai.com/)** | **~$180M acquisition valuation** (acquired by F5 Networks; $50M total funding raised) | Inference firewall for LLMs, runtime prompt filtering, automated model red teaming, policy enforcement | Annual enterprise deployments starting at **~$25,000/year** (or packaged via F5 Distributed Cloud services) | **14-day guided proof of concept / sandbox** available on sales request (limited to 5 sandbox user seats and 25k requests) |
| **[Patronus AI](https://www.patronus.ai/)** | **~$150M–$200M valuation** ($70M funding raised; $50M Series B in June 2026; 15x ARR surge) | Automated LLM evaluation, AI hallucination detection, prompt attack benchmarking, continuous red teaming | Personal plan starts at **€6.99/month** (Pro plan at **€69/month**; custom Business plans available) | **Free forever plan: 30,000 Scan Units/month** (with 1 API key & 50,000 token balance limit; or 100 Scan Units/day anonymous) |
| **[Aporia](https://www.aporia.com/)** | **$50M acquisition valuation** (acquired by Coralogix; ~$8.4M ARR; $30M funding prior) | Real-time AI guardrails, prompt filtering, latency-sensitive hallucination mitigation, ML monitoring | Scaler starting tier at **$1,500/month** ($18,000/year base; volume scales per inference request) | **14-day free trial** with full platform features (includes monitoring & guardrails for up to 100,000 requests) |

## Open-Source GitHub Projects



- **[Nephilex](https://pypi.org/project/nephilex/)**

  **Open-source AI security engineer** (license per PyPI) — **the most comprehensive open-source AI security scanner** found in this research, with a **first-class LLM and agent security scanner covering OWASP LLM Top 10** . **Features**: Project analysis with secrets, dependency, SAST, and IaC scanners; **LLM/agent security scanner** (64.3% recall, 69.2% precision on held-out cases); **Attack Simulation Mode**; deterministic patch generation with self-verification (`nephilex fix` applies verified fixes to a branch and optionally opens a PR); live OSV vulnerability data; multi-provider AI enrichment (local heuristic, Ollama, Anthropic, OpenAI—falls back to heuristic if unavailable); SARIF/GitLab/Markdown/HTML/CSV reporting; AST data-flow scanning for Python and JS/TS; baseline and diff-aware scanning . **Benchmarks**: OWASP BenchmarkPython score +89.4 (vs. Bandit +18.6, Semgrep +14.2); SecurityEval 32/121 samples detected (tied with Bandit) . **Tech stack**: Python (pip install). **Deploy**: CLI (`nephilex scan ./my-app`, `nephilex fix ./my-app --open-pr`). **Trade-off**: **Scanner, not a posture management platform**—it scans code repositories for AI security issues but does not discover runtime AI assets, monitor model behavior, or enforce runtime guardrails. Held-out recall on real fix commits is low (2.0%), reflecting the difficulty of the task . **Best for**: developers and security engineers wanting to shift AI security left—scanning repositories for LLM/agent vulnerabilities and automatically fixing verified issues before deployment.



- **[AI-Secure-Posture-Management](https://github.com/Krishcalin/AI-Secure-Posture-Management)**

  **Python-based AI-SPM rule scanner** (license per repo) — **the most comprehensive open-source AI-SPM rule set** found, with **15+ categories and 100+ rules** covering the AI security surface. **Features**: Rule categories include **Privacy** (PII to AI APIs, logging prompts with user data, training without consent); **Guardrails** (no content filter, high temperature, no rate limiting); **Agent Security** (unrestricted shell access, no human-in-the-loop, unbounded iterations, CrewAI delegation, AutoGen code exec); **RAG Security** (vector DB without auth, no access control, external docs without sanitization); **Secrets** (hardcoded API keys for OpenAI, Anthropic, HuggingFace, etc.); **Shadow AI** (direct API calls bypassing governance, unofficial SDKs); **Infrastructure** (no auth on inference endpoints, HTTP serving, Jupyter without auth); **MCP Security** (MCP server without auth, shell access, no input validation); **Fine-tuning/LoRA** (untrusted adapters, no safety alignment); **Multimodal**, **Observability**, **AI Gateway**, **Bias & Fairness**, **K8s AI Workloads**, **Terraform AI IaC**, **Model Card Compliance**, **.env Files**, **JS/TS Rules**, **Config (YAML)**, **Docker**, **Supply Chain (PyPI)** (31 AI/ML packages including tensorflow, pytorch, transformers, langchain, vllm) . **Tech stack**: Python. **Deploy**: Self-hosted (run against codebase). **Trade-off**: **Rule scanner, not a platform**—it checks code and configuration against known AI security anti-patterns but does not provide runtime discovery, monitoring, or continuous posture assessment. No web UI or dashboard. **Best for**: teams wanting a comprehensive, community-maintained rule set to scan their AI codebases for security misconfigurations—especially useful for MCP, agent, and RAG security checks.



- **[VerifyWise](https://github.com/verifywise-ai/verifywise)**

  **Open-source AI governance platform** (license per repo, 365 GitHub stars) — **the most complete open-source AI governance and compliance workbench** . **Features**: Central repository for AI governance; register AI systems, models, agents, applications, and suppliers in structured inventory; conduct risk assessments, document decisions, perform evaluations, assign responsibilities, track mitigations; **map governance activities across multiple frameworks simultaneously** (EU AI Act, ISO/IEC 42001, NIST AI RMF)—record evidence once, reuse across obligations; continuous monitoring of risk levels, controls, and compliance status . **Tech stack**: Per repository. **Deploy**: Self-hosted. **Trade-off**: **Governance, not runtime security posture**—it does not scan models for vulnerabilities, monitor inference traffic, or enforce guardrails. It answers "what AI do we have and can we demonstrate compliance?" not "is our AI under attack?" **Best for**: organizations needing EU AI Act, ISO 42001, or NIST AI RMF compliance workflows with a shared governance platform—particularly teams without budget for commercial GRC tools.



- **[Aegis](https://pypi.org/project/aegis-workbench/)**

  **Enterprise AI governance workbench** (Apache-2.0, alpha) — **a rigorous, audit-first governance tool** with cryptographic integrity. **Features**: Catalogs AI systems; classifies against **EU AI Act and NIST AI RMF**; evaluates policy-as-code; auto-generates model cards and conformity documentation; **Ed25519-signed append-only ledger** for every change; **financial-services vertical pack** (SR 11-7 model risk, NYDFS Part 500) . **Tech stack**: Python (pip install). **Deploy**: CLI (`aegis init "Org Name"`, `aegis systems add`, `aegis assess`, `aegis report annex-iv`, `aegis audit verify`). **Trade-off**: **Alpha, never run in production**—explicitly warns it is not legal advice and classifications are indicative until human review. No runtime security scanning or posture assessment. **Best for**: regulated organizations (especially financial services) wanting auditable AI governance with signed change history—willing to accept alpha-stage stability.



- **[Orbyx AI SPM](https://github.com/dshapi/ai-spm)**

  **Enterprise-level AI-SPM control plane** (license per repo) — **the most ambitious open-source AI-SPM platform** in scope, though early-stage. **Features**: Discovers AI models, agents, MCP servers, and associated resources; identifies risks across AI application supply chains and pipelines; **Admin Portal** with real-time AI security posture dashboard, inventory, runtime visibility, policies, and threat response; deploys on Kubernetes (Kind cluster) with Istio; demo account (admin/admin) . **Tech stack**: Kubernetes, Istio, Helm charts. **Deploy**: Self-hosted K8s cluster (bootstrap script, ~20 min on fresh machine) . **Trade-off**: **Complex deployment**—requires K8s, Istio, and mkcert; not a lightweight scanner. Limited public validation and documentation compared to Nephilex or VerifyWise. **Best for**: platform teams wanting a K8s-native AI-SPM control plane foundation with inventory and runtime visibility—willing to invest in cluster setup and exploration.



- **[community-ai-audit](https://pypi.org/project/community-ai-audit/)**

  **Community-driven AI security audit framework** (license per PyPI) — **the most model-focused open-source scanner** with SIEM integration. **Features**: Model adapters (HuggingFace, OpenAI, Anthropic, AWS Bedrock, Local PyTorch/ONNX/SafeTensors, Ollama); **backdoor/Trojan detection** (activation clustering); **adversarial robustness** (FGSM/PGD); interpretability (Integrated Gradients, LIME); **SIEM connectors** (Splunk HEC, Elastic, Datadog, Microsoft Sentinel); CLI with `discover`, `scan`, `interpret`, `audit` commands . **Tech stack**: Python (pip install community-ai-audit[hf]). **Deploy**: CLI. **Trade-off**: **Model-level scanning, not organizational posture**—it audits individual models for backdoors and adversarial vulnerability, not AI asset inventory or governance. Scanners require white-box access (gradients/activations) and work best with local or HuggingFace models. **Best for**: ML engineers and security researchers wanting to scan specific models for backdoors and adversarial robustness before deployment, with findings pushed to existing SIEM.



### Additional Strong Open-Source Options



- **agentic_security** — Agentic LLM vulnerability scanner / AI red teaming kit (~2,021 stars). **Note**: Red teaming and vulnerability scanning, not posture management—complements Nephilex for offensive testing . **Best for**: security teams wanting automated LLM red teaming.

- **garak (NVIDIA)** — LLM vulnerability scanner (~9,616 stars). **Note**: Probe-based vulnerability scanning; recommended in greenfield AI security stacks alongside Lakera . **Best for**: teams wanting a mature, actively maintained LLM scanner.

- **PyRIT (Microsoft)** — Python Risk Identification Tool for generative AI (~4,653 stars). **Note**: Risk identification framework, not posture management . **Best for**: security professionals building custom AI red teaming workflows.

- **modelscan (Protect AI)** — Protection against model serialization attacks (~785 stars). **Note**: Narrow scanner for unsafe model formats; not a platform . **Best for**: teams needing to validate model files before loading.



**Frameworks for building custom systems**: Combine **Nephilex** for shift-left code scanning with **AI-Secure-Posture-Management** for comprehensive rule-based AI misconfiguration checks, **VerifyWise** or **Aegis** for governance compliance, and **community-ai-audit** for model-level scanning—creating an open-source AI security stack. **None of these provide agentless runtime discovery across managed AI services** like CrowdStrike Falcon AI-SPM, or **application-layer prompt injection defense** like Lakera. Those require commercial platforms.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI-SPM platforms handling model data and security telemetry must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for AI asset inventories.

- **The "runtime posture management" vs. "code scanner" vs. "governance workbench" vs. "model auditor" distinction is critical.** **CrowdStrike Falcon AI-SPM** is **runtime posture management**—it discovers AI assets in cloud environments and correlates threats with endpoint telemetry . **Protect AI, HiddenLayer, Lakera, and Robust Intelligence** are **AI security platforms** with varying depth across scanning, guardrails, and red teaming. **Nephilex** and **AI-Secure-Posture-Management** are **code scanners**—they check repositories for AI security issues but do not discover runtime assets or monitor behavior . **VerifyWise** and **Aegis** are **governance workbenches**—they demonstrate compliance but do not scan for vulnerabilities . **community-ai-audit** is a **model auditor**—it tests individual models for backdoors and adversarial robustness . **No open-source project replicates CrowdStrike's agentless discovery or Lakera's application-layer defense.**

- **Nephilex is the most capable open-source AI security scanner** with OWASP LLM Top 10 coverage and automated fix generation . **The trade-off**: it is a code scanner, not a posture platform—low held-out recall (2.0%) on real fix commits reflects the difficulty of detecting subtle AI security bugs . **AI-Secure-Posture-Management** provides a complementary rule set with 100+ checks across MCP, RAG, agents, and infrastructure—useful as a checklist even if the tooling is immature.

- **Open-source AI-SPM is early-stage.** **Orbyx** is the most ambitious platform attempt, but requires K8s/Istio expertise and has limited validation . **VerifyWise** is the most mature governance option (365 stars, OECD catalogued) but does not address runtime security . **Nephilex** is the most actively developed scanner with published benchmarks. **Organizations needing production AI-SPM today should plan for commercial platforms or significant custom engineering.**

- **The vendor landscape is fragmenting.** CrowdStrike and Wiz extend CNAPP into AI-SPM; Lakera, HiddenLayer, and Robust Intelligence specialize in application-layer controls; governance vendors (VerifyWise, Aegis) address compliance separately . **A layered approach is often necessary**—no single open-source or commercial tool covers discovery, scanning, runtime defense, and governance comprehensively .

- **Pricing opacity is universal across commercial vendors.** CrowdStrike AI-SPM is bundled with Falcon Cloud Security packaging but public list pricing is not disclosed . Protect AI, HiddenLayer, Lakera, Robust Intelligence, CalypsoAI, Patronus, Fiddler, and Aporia all require sales contact. **Validate with direct vendor conversations against your AI workload count and compliance requirements.**

- Self-hosted open-source solutions require proper setup, API key management for LLM providers, and ongoing maintenance. **AI security data and model artifacts are sensitive**—ensure your deployment meets your organization's security standards before scanning production code or models.



---



**Made for security engineers, AI platform teams, and organizations building transparent AI security posture solutions.**

Let's make AI Security Posture Management more open, data-driven, and AI-safe.

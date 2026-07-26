<p align="center">
  <img src="./assets/altaysec-banner.jpg" alt="AltaySec" width="100%">
</p>

<h1 align="center">Enes Deniz</h1>

<p align="center">
  <strong>Co-Founder @ AltaySec | OWASP AI & GenAI Contributor | AI Security for Turkish & Global LLMs</strong>
</p>

<p align="center">
  LLM Security · Prompt Injection · AI Red Teaming · Agentic Security
</p>

<p align="center">
  <a href="https://altaysec.com.tr/enes-deniz">Profile</a> ·
  <a href="https://altaysec.com.tr/">AltaySec</a> ·
  <a href="https://altaysec.com.tr/arastirmalar/">Research</a> ·
  <a href="https://huggingface.co/3nesdeniz">Hugging Face</a> ·
  <a href="https://www.linkedin.com/in/3nesdeniz">LinkedIn</a> ·
  <a href="https://medium.com/@3nesdeniz">Medium</a> ·
  <a href="https://orcid.org/0009-0006-9491-3565">ORCID</a> ·
  <a href="https://sessionize.com/3nesdeniz/">Speaker profile</a> ·
  <a href="https://www.crunchbase.com/person/3nesdeniz">Crunchbase</a>
</p>

I am an AI security founder, Co-Founder of **AltaySec**, and an open-source contributor across **OWASP AI and GenAI projects**. My work focuses on Turkish and global LLM security, prompt injection, AI engineering, AI red teaming, jailbreak defense, and agentic security.

My work covers both sides of AI security: understanding how LLM applications fail under adversarial use, and developing the defensive controls, datasets, tools, and operating practices needed to deploy them more securely.

At AltaySec, we are building one of Turkey's most focused AI security ecosystems. Product development, security research, education, open technical resources, and community work all move within the same structure.

## Latest open releases

| Release | What it adds | Evidence |
| --- | --- | --- |
| **Turkish Daily Dialogues 5K** | 5,000 synthetic daily-life Turkish conversations across 35 topics, with scenario-family grouped splits and deterministic QA | [GitHub](https://github.com/3nesdeniz/turkish-daily-dialogues-5k) · [Hugging Face](https://huggingface.co/datasets/3nesdeniz/turkish-daily-dialogues-5k) · [v1.0.0](https://github.com/3nesdeniz/turkish-daily-dialogues-5k/releases/tag/v1.0.0) |
| **AI Security Roadmap** | A 12-module English learning path and a materially expanded 12-module Turkish edition covering LLM, RAG, agent, MCP, red-team, and blue-team security | [GitHub](https://github.com/3nesdeniz/ai-security-roadmap) · [v1.0.0](https://github.com/3nesdeniz/ai-security-roadmap/releases/tag/v1.0.0) |
| **Prooflint** | A local-first evidence gate for reviewable AI-security findings, with deterministic rules, tamper-evident manifests, and JSON/SARIF output | [GitHub](https://github.com/3nesdeniz/prooflint) · [v0.1.0](https://github.com/3nesdeniz/prooflint/releases/tag/v0.1.0) |

The dialogue dataset is a general Turkish NLP resource; it is not presented as an AI-security benchmark. The roadmap and Prooflint are independent open-source methodology and tooling projects.

## Merged upstream contributions

I contribute reviewable AI-security artifacts across OWASP AI and GenAI projects. Each contribution below is independently verifiable through its merged pull request and the technical artifact that belongs to that work.

| Contribution | Upstream repository | Delivered scope | Evidence |
| --- | --- | --- | --- |
| **#187 — AI engineering primer** | OWASP AI Exchange | A security-oriented map of AI delivery models, lifecycle artifacts, ownership boundaries, and first-pass review questions | [Merged PR](https://github.com/OWASP/www-project-ai-security-and-privacy-guide/pull/187) · [Live primer](https://owaspai.org/go/aiengineeringprimer/) |
| **#11 — Turkish evaluation corpus** | GenAI Data Security Initiative | 300 Turkish-first security test cases with provenance and integrity controls | [Merged PR](https://github.com/GenAI-Security-Project/GenAI-Data-Security-Initiative/pull/11) · [Technical note](https://medium.com/@3nesdeniz/ai-security-needs-more-than-english-tests-b2c7589beec3) · [Pinned source dataset](https://huggingface.co/datasets/AltaySec/turkish-llm-injection/tree/08d1fdccf10a831c2f32627c615002e6286f6315) |
| **#50 — System reconnaissance campaign** | GenAI Red Team Lab | 24 English and Turkish probes across nine reconnaissance categories | [Merged PR](https://github.com/GenAI-Security-Project/GenAI-Red-Team-Lab/pull/50) · [Technical note](https://medium.com/@3nesdeniz/reconnaissance-before-exploitation-f9804e68e182) · [Versioned report](https://doi.org/10.5281/zenodo.21568023) |
| **#51 — Reliability and evidence hardening** | GenAI Red Team Lab | Failure-aware execution, safer evidence handling, report integrity, and lifecycle controls | [Merged PR](https://github.com/GenAI-Security-Project/GenAI-Red-Team-Lab/pull/51) · [Technical note](https://medium.com/@3nesdeniz/when-a-security-test-mistakes-failure-for-a-finding-fb8c147912e2) · [Versioned report](https://doi.org/10.5281/zenodo.21568023) |

### #187 — AI engineering primer for security professionals

I wrote a practical primer for security professionals who need to review AI systems without collapsing the model, application, data, infrastructure, and operating process into a single black box.

- **Upstream impact:** distinguishes provider-hosted APIs, self-hosted models, and fine-tuned or trained systems; maps six lifecycle stages to engineering artifacts, security questions, and accountable owners; and provides an inventory-first review sequence
- **Validation boundary:** this is a documentation and methodology contribution. It makes no benchmark, product-performance, or production-deployment claims.
- **Evidence chain:** [Merged OWASP AI Exchange PR #187](https://github.com/OWASP/www-project-ai-security-and-privacy-guide/pull/187) · [Live AI Engineering Primer](https://owaspai.org/go/aiengineeringprimer/)

### #11 — 300 Turkish security test cases

I adapted **300 Turkish-first defensive prompt-injection and data-extraction test cases** from [AltaySec Turkish LLM Prompt Injection Dataset v0.2](https://huggingface.co/datasets/AltaySec/turkish-llm-injection/tree/08d1fdccf10a831c2f32627c615002e6286f6315) for the GenAI Data Security Initiative. The merged contribution adds one schema-conformant record per case, new annotations and DSGAI mappings, anonymization controls, record-level provenance, source and adapted-content hashes, and a deterministic integrity manifest.

- **Upstream impact:** 227 extraction-focused cases and 73 explicitly marked prompt-injection control/review cases across 12 technique families
- **Validation boundary:** 300/300 Draft-07 schema validation, manifest-to-file integrity, canonical DSGAI checks, anonymization review, and duplicate screening. The corpus contains no model outputs, success-rate claims, observed-attack claims, or production data.
- **Evidence chain:** [Merged PR #11](https://github.com/GenAI-Security-Project/GenAI-Data-Security-Initiative/pull/11) · [AI Security Needs More Than English Tests](https://medium.com/@3nesdeniz/ai-security-needs-more-than-english-tests-b2c7589beec3) · [Pinned source dataset revision](https://huggingface.co/datasets/AltaySec/turkish-llm-injection/tree/08d1fdccf10a831c2f32627c615002e6286f6315)

### #50 — Bilingual system reconnaissance campaign

I developed a reproducible **System Reconnaissance and Discovery** campaign for authorized GenAI assessments. It examines capability, tools, data sources, identity, policy, instructions, memory, architecture, and provenance through **24 English and Turkish probes across nine categories**.

- **Upstream impact:** conservative human-review labels, evidence-linked JSONL and Markdown reports, language/category filters, dry runs, per-prompt error isolation, and fail-fast operation
- **Validation boundary:** 12 focused tests plus Black, isort, strict mypy, lockfile, dry-run, and diff checks. The local `gpt-oss:20b` sandbox was not downloaded or launched; transport behavior was covered through an injected client.
- **Evidence chain:** [Merged PR #50](https://github.com/GenAI-Security-Project/GenAI-Red-Team-Lab/pull/50) · [Reconnaissance Before Exploitation](https://medium.com/@3nesdeniz/reconnaissance-before-exploitation-f9804e68e182) · [Versioned implementation and hardening report](https://doi.org/10.5281/zenodo.21568023)

### #51 — Reliability and evidence hardening

I hardened the reconnaissance workflow so execution failures cannot be mistaken for security findings and incomplete evidence cannot silently become a successful report.

- **Upstream impact:** per-probe deadlines, target-error handling, refusal-aware evidence classification, private collision-safe reports, strict configuration validation, shell-free lifecycle dispatch, HTTP readiness checks, and deterministic client cleanup
- **Validation boundary:** 69 passing tests, package/dependency checks, targeted dry runs, and Make target validation. The full Podman/Ollama `gpt-oss:20b` end-to-end campaign was not run.
- **Evidence chain:** [Merged PR #51](https://github.com/GenAI-Security-Project/GenAI-Red-Team-Lab/pull/51) · [When a Security Test Mistakes Failure for a Finding](https://medium.com/@3nesdeniz/when-a-security-test-mistakes-failure-for-a-finding-fb8c147912e2) · [Versioned implementation and hardening report](https://doi.org/10.5281/zenodo.21568023)

## Areas of expertise

- LLM application security
- Prompt injection and jailbreak defense
- AI red teaming and adversarial testing
- AI blue teaming and defensive engineering
- AI agent, tool-use, RAG, and memory security
- Turkish and multilingual LLM attack surfaces

## Featured work

### AI & Cybersecurity Skills

An open collection of ten evidence-driven security skills for Codex and compatible agents: six for AI security and four for core cybersecurity work.

- AI threat modeling, prompt injection, agentic security, RAG security, LLM red teaming, and guardrail evaluation
- Web application security, API security, cloud IAM, and incident triage
- Explicit authorization boundaries, evidence rules, output contracts, and quality gates
- 40 positive, edge, safety, and non-trigger eval cases with automated collection validation

<p>
  <a href="https://github.com/3nesdeniz/ai-cybersecurity-skills"><strong>GitHub repository</strong></a> ·
  <a href="https://github.com/3nesdeniz/ai-cybersecurity-skills/releases/tag/v1.0.0"><strong>v1.0.0 release</strong></a>
</p>

### LLM Security Testbench

A reproducible, pair-aware evaluation toolkit for prompt-injection detectors and LLM guardrails. It measures attack detection and legitimate-user false positives in the same run, with offline, Python, HTTP, and Promptfoo workflows.

- TP, FP, TN, FN, false-positive rate, and paired-boundary analysis
- Per-family, category, source-context, and split reporting
- Local JSONL and Hugging Face dataset loading
- Privacy-minimized JSON, Markdown, and JSONL reports
- Tested on Python 3.10, 3.12, and 3.14

<p>
  <a href="https://github.com/3nesdeniz/llm-security-testbench"><strong>GitHub repository</strong></a> ·
  <a href="https://github.com/3nesdeniz/llm-security-testbench/releases/tag/v0.1.0"><strong>v0.1.0 release</strong></a>
</p>

### Agentic Prompt-Injection Boundary Pairs

An English dataset for testing whether security controls can distinguish legitimate workflows from prompt-injection attempts that reuse the same roles, tools, assets, and vocabulary.

- **1,200** examples arranged as **600** controlled benign/attack pairs
- **50** enterprise and agentic workflow scenarios
- **12** attack families covering instruction, authorization, confidentiality, tool-use, retrieval, memory, trust, and approval boundaries
- Scenario-isolated train, validation, and test splits
- Deterministic build, validation, checksums, and an interactive pair explorer

<p>
  <a href="https://github.com/3nesdeniz/agentic-prompt-injection-boundary-pairs"><strong>GitHub repository</strong></a> ·
  <a href="https://huggingface.co/datasets/3nesdeniz/agentic-prompt-injection-boundary-pairs"><strong>Hugging Face dataset</strong></a> ·
  <a href="https://huggingface.co/spaces/3nesdeniz/agentic-prompt-injection-explorer"><strong>Interactive explorer</strong></a> ·
  <a href="https://github.com/3nesdeniz/agentic-prompt-injection-boundary-pairs/releases/tag/v1.0.0"><strong>v1.0.0 release</strong></a> ·
  <a href="https://doi.org/10.5281/zenodo.21378693"><strong>Zenodo DOI</strong></a>
</p>

### Turkish Conversation Prompt-Injection Dataset

An open Turkish dataset built to study the boundary between legitimate user intent and prompt-injection behavior.

- **750** unique Turkish examples
- **600** legitimate user requests and **150** prompt-injection attacks
- **150** matched benign boundary cases
- **10** attack families, including direct injection, system-prompt extraction, role-play jailbreaks, indirect injection, agent/tool abuse, RAG and memory poisoning, and obfuscation
- Reproducible train, validation, and test splits in JSONL and Parquet formats

<p>
  <a href="https://github.com/3nesdeniz/turkish-conversation-prompt-injection"><strong>GitHub repository</strong></a> ·
  <a href="https://huggingface.co/datasets/3nesdeniz/turkish-conversation-prompt-injection"><strong>Hugging Face dataset</strong></a> ·
  <a href="https://doi.org/10.5281/zenodo.21379389"><strong>Zenodo DOI</strong></a>
</p>

## Selected engineering

| Project | Scope |
| --- | --- |
| [Prooflint](https://github.com/3nesdeniz/prooflint) | Local-first evidence gate for AI-security findings, deterministic manifests, and SARIF reporting |
| [AI Security Roadmap](https://github.com/3nesdeniz/ai-security-roadmap) | Bilingual learning path for LLM, RAG, agent, MCP, red-team, and blue-team security |
| [Turkish Daily Dialogues 5K](https://github.com/3nesdeniz/turkish-daily-dialogues-5k) | Reproducible synthetic Turkish daily-dialogue dataset with 5,000 conversations across 35 topics |
| [AI & Cybersecurity Skills](https://github.com/3nesdeniz/ai-cybersecurity-skills) | Ten evidence-driven AI security and cybersecurity skills for Codex and compatible agents |
| [LLM Security Testbench](https://github.com/3nesdeniz/llm-security-testbench) | Pair-aware evaluation for prompt-injection detectors and LLM guardrails |
| [Agentic Prompt-Injection Boundary Pairs](https://github.com/3nesdeniz/agentic-prompt-injection-boundary-pairs) | English paired dataset for agentic workflows and trust-boundary testing |
| [Turkish Conversation Prompt-Injection](https://github.com/3nesdeniz/turkish-conversation-prompt-injection) | Turkish LLM-security dataset with paired benign and attack examples |
| [Mini-SIEM](https://github.com/3nesdeniz/Mini-SIEM) | Log collection, threat detection, and MITRE ATT&CK mapping |
| [Log Anomaly Detector](https://github.com/3nesdeniz/log-anomaly-detector) | Python-based log analysis and anomaly investigation |
| [Mini Directory Scan](https://github.com/3nesdeniz/Mini-Directory-Scan) | Web directory scanner with soft-404 detection and structured reporting |

## Writing and research

- [AI Engineering Primer for Security Professionals — OWASP AI Exchange](https://owaspai.org/go/aiengineeringprimer/)
- [Three Open-Source Releases, One Standard: Make the Evidence Inspectable](https://medium.com/@3nesdeniz/three-open-source-releases-one-standard-make-the-evidence-inspectable-d4acf4589662)
- [Reliable Bilingual System Reconnaissance for GenAI Red Teaming: Implementation and Hardening](https://doi.org/10.5281/zenodo.21568023)
- [When a Security Test Mistakes Failure for a Finding](https://medium.com/@3nesdeniz/when-a-security-test-mistakes-failure-for-a-finding-fb8c147912e2)
- [AI Security Needs More Than English Tests](https://medium.com/@3nesdeniz/ai-security-needs-more-than-english-tests-b2c7589beec3)
- [Reconnaissance Before Exploitation](https://medium.com/@3nesdeniz/reconnaissance-before-exploitation-f9804e68e182)
- [A Prompt-Injection Dataset Should Test Boundaries, Not Keywords](https://medium.com/@3nesdeniz/a-prompt-injection-dataset-should-test-boundaries-not-keywords-79589beda0b6)
- [AI Güvenliği Bir Filtre Meselesi Değil](https://medium.com/@3nesdeniz/ai-güvenliği-bir-filtre-meselesi-değil-7eb8e7753339)
- [Prompt Injection Savunmaları Üretime Girmeden Nasıl Test Edilmeli?](https://medium.com/p/56801b23aa3f)
- [LLM Güvenliğinde TP, FP, TN ve FN Dengesi](https://medium.com/@3nesdeniz/llm-g%C3%BCvenli%C4%9Finde-tp-fp-tn-ve-fn-dengesi-9a9129418900)
- [AltaySec AI Security Research](https://altaysec.com.tr/arastirmalar/)
- [Enes Deniz at AltaySec](https://altaysec.com.tr/enes-deniz)

## Current priorities

- Expanding open Turkish and multilingual AI-security resources
- Mapping emerging prompt-injection, agent, RAG, and tool-use attack surfaces
- Building practical red and blue team methodologies for real LLM deployments
- Growing the AltaySec ecosystem through products, education, research, and community programs

## Contact

- **Email:** [enes@altaysec.com.tr](mailto:enes@altaysec.com.tr)
- **LinkedIn:** [linkedin.com/in/3nesdeniz](https://www.linkedin.com/in/3nesdeniz)
- **Medium:** [medium.com/@3nesdeniz](https://medium.com/@3nesdeniz)
- **Hugging Face:** [huggingface.co/3nesdeniz](https://huggingface.co/3nesdeniz)
- **ORCID:** [0009-0006-9491-3565](https://orcid.org/0009-0006-9491-3565)
- **Speaker profile:** [sessionize.com/3nesdeniz](https://sessionize.com/3nesdeniz/)
- **Crunchbase:** [Enes Deniz](https://www.crunchbase.com/person/3nesdeniz)
- **Zenodo:** [System reconnaissance technical report](https://doi.org/10.5281/zenodo.21568023) · [Turkish dataset](https://doi.org/10.5281/zenodo.21379389) · [Agentic dataset](https://doi.org/10.5281/zenodo.21378693)

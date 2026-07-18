<p align="center">
  <img src="./assets/altaysec-banner.jpg" alt="AltaySec" width="100%">
</p>

<h1 align="center">Enes Deniz</h1>

<p align="center">
  <strong>Co-Founder @ AltaySec | AI Security for Turkish & Global LLMs</strong>
</p>

<p align="center">
  LLM Security · Prompt Injection · Jailbreak Defense · AI Red & Blue Teaming
</p>

<p align="center">
  <a href="https://altaysec.com.tr/enes-deniz.html">Profile</a> ·
  <a href="https://altaysec.com.tr/">AltaySec</a> ·
  <a href="https://altaysec.com.tr/arastirmalar/">Research</a> ·
  <a href="https://huggingface.co/3nesdeniz">Hugging Face</a> ·
  <a href="https://www.linkedin.com/in/3nesdeniz">LinkedIn</a> ·
  <a href="https://medium.com/@3nesdeniz">Medium</a> ·
  <a href="https://orcid.org/0009-0006-9491-3565">ORCID</a> ·
  <a href="https://sessionize.com/3nesdeniz/">Speaker profile</a>
</p>

I am an AI security founder and Co-Founder of **AltaySec**, specializing in Turkish and global LLM security, prompt injection, jailbreak defense, and AI red/blue teaming.

My work covers both sides of AI security: understanding how LLM applications fail under adversarial use, and developing the defensive controls, datasets, tools, and operating practices needed to deploy them more securely.

At AltaySec, we are building one of Turkey's most focused AI security ecosystems. Product development, security research, education, open technical resources, and community work all move within the same structure.

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
  <a href="https://github.com/3nesdeniz/agentic-prompt-injection-boundary-pairs/releases/tag/v1.0.0"><strong>v1.0.0 release</strong></a>
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
  <a href="https://huggingface.co/datasets/3nesdeniz/turkish-conversation-prompt-injection"><strong>Hugging Face dataset</strong></a>
</p>

## Selected engineering

| Project | Scope |
| --- | --- |
| [AI & Cybersecurity Skills](https://github.com/3nesdeniz/ai-cybersecurity-skills) | Ten evidence-driven AI security and cybersecurity skills for Codex and compatible agents |
| [LLM Security Testbench](https://github.com/3nesdeniz/llm-security-testbench) | Pair-aware evaluation for prompt-injection detectors and LLM guardrails |
| [Agentic Prompt-Injection Boundary Pairs](https://github.com/3nesdeniz/agentic-prompt-injection-boundary-pairs) | English paired dataset for agentic workflows and trust-boundary testing |
| [Turkish Conversation Prompt-Injection](https://github.com/3nesdeniz/turkish-conversation-prompt-injection) | Turkish LLM-security dataset with paired benign and attack examples |
| [GenAI Data Security Initiative — PR #11](https://github.com/GenAI-Security-Project/GenAI-Data-Security-Initiative/pull/11) | Merged contribution of 300 Turkish prompt-injection test cases |
| [GenAI Red Team Lab — PR #50](https://github.com/GenAI-Security-Project/GenAI-Red-Team-Lab/pull/50) | Merged bilingual system-reconnaissance campaign for LLM applications |
| [Mini-SIEM](https://github.com/3nesdeniz/Mini-SIEM) | Log collection, threat detection, and MITRE ATT&CK mapping |
| [Log Anomaly Detector](https://github.com/3nesdeniz/log-anomaly-detector) | Python-based log analysis and anomaly investigation |
| [Mini Directory Scan](https://github.com/3nesdeniz/Mini-Directory-Scan) | Web directory scanner with soft-404 detection and structured reporting |

## Writing and research

- [AI Security Needs More Than English Tests](https://medium.com/@3nesdeniz/ai-security-needs-more-than-english-tests-b2c7589beec3)
- [A Prompt-Injection Dataset Should Test Boundaries, Not Keywords](https://medium.com/@3nesdeniz/a-prompt-injection-dataset-should-test-boundaries-not-keywords-79589beda0b6)
- [AI Güvenliği Bir Filtre Meselesi Değil](https://medium.com/@3nesdeniz/ai-güvenliği-bir-filtre-meselesi-değil-7eb8e7753339)
- [Prompt Injection Savunmaları Üretime Girmeden Nasıl Test Edilmeli?](https://medium.com/p/56801b23aa3f)
- [LLM Güvenliğinde TP, FP, TN ve FN Dengesi](https://medium.com/@3nesdeniz/llm-g%C3%BCvenli%C4%9Finde-tp-fp-tn-ve-fn-dengesi-9a9129418900)
- [AltaySec AI Security Research](https://altaysec.com.tr/arastirmalar/)
- [Enes Deniz at AltaySec](https://altaysec.com.tr/enes-deniz.html)

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

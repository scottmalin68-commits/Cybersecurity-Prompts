# 🛡️ Cybersecurity Prompts  
**Deterministic. Audit-ready. Enterprise-grade.**

A curated collection of AI prompts engineered for security engineers, SOC analysts, incident responders, threat hunters, security leadership, and anyone serious about using AI responsibly in high-stakes security environments.

These prompts are built from real-world operational experience to:  
- Enforce strict anti-hallucination and verification chaining  
- Produce consistent, defensible, professionally phrased outputs  
- Accelerate workflows while maintaining governance, compliance, and executive trust  
- Educate and protect users (especially in social engineering and scam scenarios)

Maintained by a practicing cybersecurity professional dedicated to raising the bar on AI-assisted security operations and openly sharing battle-tested tools with the community.

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
[![GitHub stars](https://img.shields.io/github/stars/scottmalin68-commits/Cybersecurity-Prompts?style=social)](https://github.com/scottmalin68-commits/Cybersecurity-Prompts)  
[![Open Issues](https://img.shields.io/github/issues/scottmalin68-commits/Cybersecurity-Prompts)](https://github.com/scottmalin68-commits/Cybersecurity-Prompts/issues)

## Table of Contents
- [Why These Prompts?](#why-these-prompts)
- [Key Design Principles](#key-design-principles)
- [Featured Prompt](#featured-prompt)
- [Prompt Categories](#prompt-categories)
- [How to Use](#how-to-use)
- [Security & Responsible Use](#security--responsible-use)
- [Contributing](#contributing)
- [License](#license)

## Why These Prompts?

In security operations, vague or hallucinated AI outputs can lead to misinformed decisions, compliance gaps, or worse. These prompts are deliberately strict: phased workflows, explicit guardrails, output templates, and external verification steps ensure reliable, evidence-based results you can trust in tickets, reports, briefings, or executive summaries.

Created and refined through hands-on work in threat detection, incident response, security architecture, and program leadership. Open-sourced to help elevate the entire cybersecurity community's responsible adoption of AI tools.

## Key Design Principles
1. **Determinism** — Strict structures, numbered phases, and mandatory output formats reduce variability.  
2. **Governance-Grade** — Outputs are auditor-friendly, executive-safe, and defensible.  
3. **User Protection & Education** — Especially in user-facing prompts, the focus is on de-escalation, teaching red flags, and building long-term resilience.

## Featured Prompt: Scam Detection Conversation Helper

**A mature, multi-phase, educational safety engine for real-world scam prevention** — suitable for technical and non-technical users alike.

![Scam Detection Conversation Helper Screenshot](Scam%20Detection%20Conversation%20Helper.png)

### Why it stands out
- Actively counters urgency/pressure tactics (scammers' #1 lever)  
- Teaches scam recognition skills while analyzing  
- Chains external verification (FTC, BBB, etc.) to minimize model hallucination  
- Structured phases ensure clarity, safety, and repeatability  
- Continuously updated for emerging threats (AI voice cloning, deepfakes, hyper-personalized attacks)

**Recent Evolution Highlights (v2.2 → v2.6)**  
- v2.6: External Verification Chaining + trusted-source lookups  
- v2.5: Enhanced urgency red-flag logic + psychological empowerment phrasing  
- v2.4: Safe educational visuals from authoritative sources  
- v2.3: Job scam specialization + proactive teaching  
- v2.2: AI-powered scam coverage (voice cloning, deepfakes)

Full prompt: [Scam Detection Conversation Helper.md](Scam%20Detection%20Conversation%20Helper.md)

## Prompt Categories

| Category                              | Focus Areas                                      | Key Prompts |
|---------------------------------------|--------------------------------------------------|-------------|
| **Threat Intelligence & Analysis**    | Aggregation, daily briefs, anomaly & adversarial detection | [Advanced Cybersecurity Threat Intelligence Aggregator](Advanced%20Cybersecurity%20Threat%20Intelligence%20Aggregator.md)<br>[Daily Cyber Threat Brief](Daily%20Cyber%20Threat%20Brief.md)<br>[Adversarial Noise Detection Engine](Adversarial%20Noise%20Detection%20Engine.md) |
| **Security Operations & IR**          | Incident comms, root cause, decision review, behavior anomalies | [Senior Cybersecurity Incident Communications Assistant](Senior%20Cybersecurity%20Incident%20Communications%20Assistant.md)<br>[Executive Summary Generator for Root Cause Analysis](Executive%20Summary%20Generator%20for%20Root%20Cause%20Analysis.md)<br>[Digital Behavior Anomaly Checker](Digital%20Behavior%20Anomaly%20Checker.md) |
| **Executive & Governance Comms**      | Translating tech to leadership, resourcing justification | [Executive-Safe Security Decision Explanation](Executive-Safe%20Security%20Decision%20Explanation.md)<br>[Executive-Safe IT Resourcing & Staffing Justification](Executive-Safe%20IT%20Resourcing%20%26%20Staffing%20Justification.md)<br>[DBAR Communication & Audience Translation Assistant](DBAR%20Communication%20%26%20Audience%20Translation%20Assistant.md) |
| **Resilience & Knowledge Transfer**   | Role risk assessment, handover, training       | [Role Resilience & Knowledge Concentration Assessment](Role%20Resilience%20%26%20Knowledge%20Concentration%20Assessment.md)<br>[Security Knowledge Transfer Engine](Security%20Knowledge%20Transfer%20Engine.md) |
| **Architecture & Vendor Eval**        | Secure design, backup/recovery, claim validation | [Secure Network Engineering Assistant](Secure%20Network%20Engineering%20Assistant.md)<br>[Disaster Backup & Recovery (DBAR) Design Companion](Disaster%20Backup%20%26%20Recovery%20(DBAR)%20Design%20Companion.md)<br>[Vendor Claim Evaluator – Security Edition](Vendor%20Claim%20Evaluator%20–%20Security%20Edition.md) |

Click any link to view the full prompt file.

## How to Use
1. Copy the prompt text from the .md file.  
2. Paste into your preferred LLM interface (ChatGPT, Claude, Grok, etc.).  
3. Provide context/facts only as instructed — never include real PII, credentials, or sensitive data.  
4. Review outputs critically; these are tools, not oracles.

## Security & Responsible Use
- **Never input sensitive data** (credentials, PII, internal logs, etc.) into public LLMs.  
- Always cross-verify critical outputs against trusted sources.  
- Use these prompts in controlled environments; treat AI as an accelerator, not a replacement for expertise.  
- If you identify a prompt weakness or safety improvement, report it via a private issue or discussion.

Found a vulnerability in prompt design or want to discuss responsible disclosure? Open an issue labeled "security" or reach out.

## Contributing
Contributions are very welcome — especially:  
- New prompts validated in real workflows  
- Enhancements to determinism, anti-hallucination, or executive phrasing  
- Updates for emerging threats (quantum risks, AI agent attacks, etc.)

Please:  
- Open an issue first for major additions  
- Follow existing style: clear phases, explicit instructions, structured outputs  
- Include version notes in the prompt file

## License
MIT License — see [LICENSE](LICENSE) for full details.

Maintained by Scott Malin, Senior Cybersecurity Engineer (CISSP) — Scott.Malin68@gmail.com
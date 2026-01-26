# Cybersecurity Prompt Suite

A curated collection of AI prompts designed for security engineers, analysts, and automation specialists. These prompts support tasks across identity, endpoint defense, incident response, and workflow automation, with a focus on deterministic behavior and minimal hallucination.

## Purpose

This repository provides reusable, production‑tested prompts that help cybersecurity teams:
- Analyze IAM and Conditional Access configurations
- Simulate access decisions with evidence‑based logic
- Troubleshoot endpoint and authentication issues
- Automate repetitive security workflows
- Explore security concepts through structured, guided AI interactions

## Philosophy

These prompts are built with:
- **Deterministic logic** — strict rules to reduce hallucinations  
- **Security‑first design** — no assumptions, no fabricated data  
- **Enterprise alignment** — mirrors real IAM and endpoint workflows  
- **Extensibility** — easy to adapt for different tenants, tools, or environments  

## Included Prompts

- **Conditional Access Policy Analyzer**  
  Deterministic evaluation of Azure AD Conditional Access policies with simulation mode.

- **IAM Decision Logic Explorer**  
  Helps break down identity flows, authentication steps, and policy interactions.

- **Endpoint Troubleshooting Assistant**  
  Guides through structured diagnostics for Windows update loops, driver issues, and configuration drift.

- **Security Automation Prompt Templates**  
  Modular prompts for building repeatable workflows in Copilot or other LLMs.

(You can expand this list as you add files.)

## How to Use

1. Open any prompt file in this repository.  
2. Copy the full prompt into your AI assistant.  
3. Follow the usage notes at the top of each file.  
4. Provide your environment‑specific details (policy JSON, logs, scenarios, etc.) when requested.

## Contributing

Suggestions, improvements, and new prompt ideas are welcome.  
Open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

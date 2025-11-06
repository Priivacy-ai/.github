# Priivacy AI

Welcome to Priivacy AI! We're building the next generation of privacy-first tools for compliance, security, and software development.

Visit our website: [priivacy.ai](https://priivacy.ai)

---

## Our Projects

### 🔐 Priivacy

A high-performance, privacy-first **PII detection and anonymization toolkit** written in Rust.

**Key Features:**
- ⚡ **Deterministic Rust engine** with zero-copy analysers and calibrated confidence scoring
- 🔐 **48+ validation-backed recognizers** with confidence evidence trails (SSN, Credit Card, IBAN, Passports, Phone Numbers, Emails, and more)
- 🧰 **Unified API surface** for Rust, Python, Node.js, and WebAssembly
- 🛠️ **Batteries-included CLI** for quick redaction and bulk jobs
- 📊 **Perfect precision** for high-confidence detections (≥0.85 achieve P=1.000 for checksum-based recognizers)
- 🌍 **Multi-language support** with POS-enhanced recognition (English, German, Spanish, French) plus 70+ additional languages

**What it does:**
Priivacy reimagines Microsoft's original privacy toolkit with a modern, low-latency core. It detects and redacts personally identifiable information (PII) with deterministic confidence scoring, validation-backed accuracy, and first-class support for multiple programming languages and WebAssembly.

**Supported PII Types:**
- National IDs (US SSN, UK NHS, AU TFN, Poland PESEL, Brazil CPF, China ID, India Aadhaar, +20 more)
- Financial data (Credit Cards with Luhn validation, IBAN, ABA Routing, Bank Accounts, Crypto Addresses)
- Documents (Passports, Driver Licenses, Medical Licenses)
- Structured data (Phone Numbers, URLs, Email, IP Addresses, Dates, Times)

**Latest Version:** v0.3.0
- Deterministic Confidence Scoring with 0.0-1.0 calibrated scores
- 35+ checksum-validated recognizers for accuracy
- F1 improvements ranging from 5-15% across all recognizer tiers
- Zero-copy performance with <2x processing overhead

---

### 📋 [Spec Kitty](https://github.com/Priivacy-ai/spec-kit) 

A **specification-first development framework** with live kanban dashboard and AI agent orchestration, built on GitHub's Spec Kit.

**Key Features:**
- 📊 **Live Kanban Dashboard** – Real-time visibility into work across planned → doing → for review → done lanes
- 🔄 **Multi-Agent Orchestration** – Coordinate multiple AI coding agents (Claude Code, GitHub Copilot, Gemini CLI, Cursor, Windsurf, and more)
- 🎯 **Spec-Driven Development** – Flip the traditional model: specifications become executable, directly generating working implementations
- 📦 **Artifact Management** – Track specifications, plans, tasks, and deliverables in one integrated workspace
- 🔧 **Agent-Aware Prompts** – Scaffolding commands tuned to each AI agent's capabilities
- ⚡ **Zero Configuration** – Automated dashboard starts with `spec-kitty init`
- 🌳 **Worktree Strategy** – Isolated sandboxes for parallel feature development

**What it does:**
Spec Kitty changes how teams build software by emphasizing specification-first rigor. Instead of treating specs as throwaway documents, they become the source of truth that drives implementation. The built-in dashboard gives you real-time insights into your AI-assisted development workflows, showing exactly which agents are working on what and how tasks move through your kanban board.

**Workflow:**
1. **Constitution** – Establish project principles and governance
2. **Specify** – Define requirements and user stories
3. **Clarify** – Structured discovery interviews to reduce ambiguity
4. **Plan** – Create technical implementation plans with your tech stack
5. **Tasks** – Break down into actionable work packages
6. **Implement** – Execute with AI agent assistance
7. **Review** – Validate and move to done
8. **Accept & Merge** – Finalize and integrate

**Supported AI Agents:**
- Claude Code
- GitHub Copilot
- Gemini CLI
- Cursor
- Windsurf
- Qwen Code
- opencode
- Amazon Q Developer CLI
- Kilo Code
- Auggie CLI
- Roo Code
- Codex CLI

**Installation:**
```bash
# From PyPI (Recommended)
pip install spec-kitty-cli

# Or with uv
uv tool install spec-kitty-cli

# Initialize a new project
spec-kitty init my-project --ai claude
```

**Repository:** [github.com/Priivacy-ai/spec-kit](https://github.com/Priivacy-ai/spec-kit)

---

## Why Priivacy AI?

We believe that building compliant, privacy-first software shouldn't be painful. Our projects solve two critical problems:

1. **Priivacy Rust** – Detect and redact sensitive data with confidence, speed, and accuracy. Stop shipping PII in logs, databases, and exports.

2. **Spec Kitty** – Build software faster by making specifications executable. Stop writing code in a vacuum; let AI agents follow a structured blueprint that guides implementation from requirements through delivery.

Together, they form a modern developer toolkit for **shipping privacy-compliant features at scale**.

---

## Getting Started

### For Spec Kitty (Spec-Driven Development)
- Read the [Spec Kitty README](https://github.com/Priivacy-ai/spec-kit/blob/main/README.md)
- Run `spec-kitty --help` for CLI reference
- Check [playbook examples](https://github.com/Priivacy-ai/spec-kit/tree/main/examples):
  - Multi-agent feature development
  - Parallel implementation tracking
  - Dashboard-driven development
  - Claude + Cursor collaboration

---

## License

Spec Kitty is released under the **MIT License**. 

---

## Community & Support

- **Report Issues:** [Spec Kitty Issues](https://github.com/Priivacy-ai/spec-kit/issues)
- **Website:** [priivacy.ai](https://priivacy.ai)
- **Discussions:** Check GitHub Discussions in each repository

---

## Contributing

We welcome contributions! Please open an issue or pull request in the relevant repository. Be sure to follow the project's code of conduct and contribution guidelines.

---

**Built with ❤️ by the Priivacy AI team**

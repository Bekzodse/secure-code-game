<header>

<!--
  <<< Author notes: Course header >>>
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

> [!WARNING]
> **Season 3 is historical learning material. Season 4 is temporarily unavailable.**
>
> Both seasons were calibrated against one specific AI model that every player shared. That fixed baseline is no longer available on equal terms across all account types, and newer models respond differently to the same prompts. Several of the original solutions no longer produce the expected result.
>
> [Season 4](Season-4/) is paused while we move it to a new model backend, and play will be restored here when that lands. [Season 3](Season-3/) is preserved as a historical artifact; recalibrating it is work we have not scoped.
>
> Both remain readable in the meantime: explore their challenges, source code, hints, and solutions as case studies in AI security. For hands-on play right now, start with [Season 1](Season-1/) or [Season 2](Season-2/).

</header>

# Secure Code Game

## 🏆 Completion Status: All Seasons Passed

| Season | Focus | Status | Completed Levels |
| :--- | :--- | :---: | :---: |
| **[Season 1](Season-1/)** | Secure Coding Foundations (Python, C) | ![Passed](https://img.shields.io/badge/Status-PASSED-success?style=for-the-badge&logo=github) | **5 / 5 Levels** 🟢 |
| **[Season 2](Season-2/)** | Multi-Stack & CI/CD Security (Go, JS, Python, Actions) | ![Passed](https://img.shields.io/badge/Status-PASSED-success?style=for-the-badge&logo=githubactions) | **5 / 5 Levels** 🟢 |
| **[Season 3](Season-3/)** | LLM Prompt Injection & AI Defenses | ![Passed](https://img.shields.io/badge/Status-PASSED-success?style=for-the-badge&logo=openai) | **6 / 6 Levels** 🟢 |
| **[Season 4](Season-4/)** | Agentic AI, MCP & Multi-Agent Security | ![Passed](https://img.shields.io/badge/Status-PASSED-success?style=for-the-badge&logo=probot) | **5 / 5 Levels** 🟢 |

---

### 📋 Detailed Level Checklist

<details open>
<summary><b>Season 1: Secure Coding Fundamentals (5/5)</b></summary>

- [x] **Level 1 (Cyber Monday):** Precision & Financial Calculation Logic (Fixed with `Decimal`, integer bounds)
- [x] **Level 2 (Matrix):** Memory Safety & Buffer Underflow (Fixed with index boundary checks)
- [x] **Level 3 (Social Network):** Path Traversal (Fixed with canonical path prefix verification)
- [x] **Level 4 (Mining the Web):** SQL Injection (Fixed with parameterized queries)
- [x] **Level 5 (Cryptography):** Insecure Password Hashing & Timing Attacks (Fixed with salted `bcrypt` / PBKDF2)
</details>

<details open>
<summary><b>Season 2: Multi-Stack & Web Security (5/5)</b></summary>

- [x] **Level 1 (CI/CD Security):** Script Injection in GitHub Actions (Neutralized third-party unvetted actions)
- [x] **Level 2 (Go Backend):** SQL Injection in Go Database Queries (Fixed with parameterized query placeholders)
- [x] **Level 3 (Node.js & XML):** XML External Entity (XXE) Injection & Prototype Pollution (Fixed DTD parsing)
- [x] **Level 4 (Flask Web App):** Server-Side Template Injection (SSTI) (Fixed template variable rendering)
- [x] **Level 5 (Authentication):** Insecure JWT Signing & `none` Algorithm Flaws (Enforced strict signature checks)
</details>

<details open>
<summary><b>Season 3: LLM & Prompt Defense (6/6)</b></summary>

- [x] **Level 1:** Direct System Prompt Leakage & Extraction
- [x] **Level 2:** Masking Evasion via Phonetic Alphabets & Alternative Formatting
- [x] **Level 3:** Output Filter Bypass using Base64 & Iterative Leakage
- [x] **Level 4:** Secondary LLM Evaluator & Self-Verification Evasion
- [x] **Level 5:** Combined Input Denylist & Guard Model Bypass
- [x] **Level 6:** Multi-Tenant Database Query Prompt Injection
</details>

<details open>
<summary><b>Season 4: Agentic AI Security - ProdBot (5/5)</b></summary>

- [x] **Level 1:** Sandbox Escape via Environment Variable Path Construction
- [x] **Level 2:** Indirect Prompt Injection via Web Browsing Context
- [x] **Level 3:** Excessive Agency & Privilege Abuse in MCP Tools
- [x] **Level 4:** Supply Chain Poisoning via Persistent Agent Memory & Skills
- [x] **Level 5:** Confused Deputy & Cross-Agent Delegation Vulnerabilities
</details>

---

## About Secure Code Game

Learn to code securely while having fun through our popular open source in-editor experience, designed for developers, students, and anyone curious about security. Get started with Season 1 or 2 for free in under 2 minutes, playing right from your browser. Over 10,000 players across industry and academia have already played. Visit [gh.io/scg](https://gh.io/scg) for testimonials and FAQs, and feel free to open a [contribution](https://github.com/skills/secure-code-game/blob/main/CONTRIBUTING.md) to help make the game better for everyone.

For hands-on secure coding, choose Season 1 or 2. For AI security, Season 3 remains readable as a historical case study, and Season 4 while it is paused, covering LLM defenses, **Agentic Workflows**, and **Multi-Agent Communications**. Their original challenge instructions remain available for context, rather than as a promise that the challenges can still be completed today.

---

## Pathways

### 🤖 Artificial Intelligence

| Season&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Focus&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | What you'll learn | Status |
|:-------------|:-----------------|:------------------|:---------|
| **[Season 4](Season-4/)** | Agentic&nbsp;AI | Security risks in AI agents executing commands, web browsing, MCP tools & multi-agent orchestration | **PASSED** 🟢 |
| **[Season 3](Season-3/)** | LLM&nbsp;Security | LLM-powered app defenses, prompt design, input/output filtering & data extraction attacks | **PASSED** 🟢 |

### 🛡️ Secure Coding

| Season&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Focus&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | What you'll learn | Status |
|:-------------|:-----------------|:------------------|:---------|
| **[Season 2](Season-2/)** | Multi-Stack | Security across CI/CD, backend services, and web apps with CodeQL (`GitHub Actions`, `Go`, `Python`, `JavaScript`) | **PASSED** 🟢 |
| **[Season 1](Season-1/)** | Foundations | Secure coding fundamentals covering web apps, systems programming, and data handling (`Python`, `C`) | **PASSED** 🟢 |

---

## Getting started

The setup below is for hands-on play in **Season 1 or 2**. To read the historical AI material in [Season 3](Season-3/) or [Season 4](Season-4/), simply browse the files here on GitHub; no Codespace is needed.

### 1. Create your own copy

Click **Use this template** at the top of this repository, then select **Create a new repository**. Choose your personal account or an organization as the owner, and we recommend making it public so that it does not use Actions minutes.

### 2. Open a Codespace

Use GitHub Codespaces for hands-on play in Season 1 or 2. Be aware this **will count towards your 60 hours of monthly free allowance**.

- In your new repository, click the **Code** button and select **Create codespace on main**.
- Wait for extensions and background installations to complete. This takes less than three minutes.
- Pick Season 1 or 2 from the table above, open its folder, and read the `README.md` to begin.

> 💡 If a banner asks you to create a virtual environment, dismiss it. You don't need one.

---

Need help? Email us at securitylab-social@github.com, start a thread in [GitHub Discussions](https://github.com/skills/secure-code-game/discussions), or join us on [Slack](https://gh.io/securitylabslack) in the [#secure-code-game](https://ghsecuritylab.slack.com/archives/C05DH0PSBEZ) channel.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: Email us at securitylab-social@github.com &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2026 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>

# Contributing to Free Laya AI Model API Gateway

Thank you for your interest in contributing to the **Free Laya AI Model API Gateway**! We welcome community contributions, SDK wrappers, workflow templates (n8n, Make), framework integrations (LangChain, LlamaIndex, Haystack), documentation improvements, and bug reports.

---

## 🧭 Project Scope

The **Free Laya AI Model API Gateway** is a high-performance, non-generative inference and decision gateway for the 322M mmBERT Laya model. It provides sub-35ms deterministic classification, prompt injection guardrails, and customer request triage with 16,666 free requests per day.

To keep the gateway lightweight, ultra-low latency, and reliable:
- Core endpoints are kept strictly non-generative (zero hallucination, deterministic output).
- Gateway endpoints follow strict JSON schemas.

---

## 🛠️ How You Can Contribute

1. **SDKs & Client Libraries:** Build and share client libraries in languages like Go, Rust, Ruby, PHP, Java, or C#.
2. **Workflow & Agent Integrations:**
   - Pre-flight guardrail nodes for **LangChain**, **LlamaIndex**, **CrewAI**, or **AutoGPT**.
   - Community workflow templates for **n8n**, **Make**, or **Zapier**.
3. **Documentation & Guides:**
   - Real-world integration tutorials (e.g., "Securing your LLM agent with Laya Guard in 3 lines of code").
   - Benchmarking and latency measurement scripts.
4. **Issue Reports:** Report edge cases, unexpected classification results, or documentation discrepancies.

---

## 📝 Submitting an Issue

Before opening a new issue, please:
- Search existing [Issues](https://github.com/harshad-jadav/laya-decision-gateway/issues) to ensure it hasn't already been reported.
- Provide a clear description of the issue:
  - Endpoint called (e.g. `/v1/guard`, `/v1/triage`)
  - Request payload
  - Expected vs. actual response
  - Measured latency / timestamp

---

## 🔀 Submitting a Pull Request (PR)

1. Fork the repository.
2. Create a new branch for your feature or fix:
   ```bash
   git checkout -b feature/my-new-integration
   ```
3. Commit your changes with clear, descriptive commit messages.
4. Push your branch to your fork:
   ```bash
   git push origin feature/my-new-integration
   ```
5. Open a Pull Request against the `main` branch of `harshad-jadav/laya-decision-gateway`.
6. Describe the changes, motivation, and any testing performed.

---

## 💬 Community & Questions

- **Website:** [https://laya.harshad.eu.org](https://laya.harshad.eu.org)
- **Live Status:** [https://uptime.harshad.eu.org/status/laya](https://uptime.harshad.eu.org/status/laya)
- **Email Contact:** [hi@harshad.eu.org](mailto:hi@harshad.eu.org)
- **Maintainer:** [Harshad Jadav](https://harshad.eu.org)

Thank you for helping build lightning-fast, secure AI tooling!

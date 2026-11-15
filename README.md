### Gabriel Nagawo

**QA & AI Automation Engineer**: test automation, LLM evaluation and AI tooling for quality engineering.

#### About

I work on quality engineering for mobile and AI products. My day-to-day includes testing LLM-based features, building AI-assisted test automation, automating QA processes with AI, and writing internal data-analysis tools that use AI.

I've also used machine learning to identify failure patterns in processors, alongside hardware and software QA. I study Software Engineering at UFAM, where my research covers LLM chatbots for requirements elicitation under Brazil's data protection law (LGPD).

#### Focus areas

- **AI for quality engineering:** log triage, test generation, self-healing automation.
- **LLM evaluation and safety:** RAG evaluation gates, red-teaming, OWASP Top 10 for LLM applications.
- **Test automation:** Android (ADB, Appium, Espresso, UI Automator), web (Playwright, Cypress, Selenium) and APIs.
- **Agentic tooling:** MCP servers that give AI agents safe, auditable access to QA tools.

#### Tech stack

| Area | Tools |
|---|---|
| Languages | Python, SQL |
| Mobile testing | ADB, Android, Appium, Espresso, UI Automator |
| Web and API testing | Playwright, Cypress, Selenium, Postman / REST |
| AI and LLM | Ollama, RAG, MCP, DeepEval, RAGAS |
| CI/CD | GitHub Actions, Jenkins, Bitrise |
| Test management | TestRail, Allure, Jira |

<!-- FEATURED-START -->
#### Featured projects

| Project | What it shows | Measured result |
|---|---|---|
| [llm-redteam-suite](https://github.com/Gabnagawo/llm-redteam-suite) | Red-teaming an LLM chatbot against the OWASP Top 10 for LLM Apps, with a rules + LLM-judge evaluator | Hardened target blocks 41/49 attacks vs 15/49 for the vulnerable one; judge agreement κ = 0.875 |
| [rag-eval-gate](https://github.com/Gabnagawo/rag-eval-gate) | A RAGAS + DeepEval quality gate that comments on PRs and blocks RAG regressions | Faithfulness 0.943 → 0.576 on a degraded retriever, caught by the gate |
| [agent-eval-harness](https://github.com/Gabnagawo/agent-eval-harness) | A test harness for tool-using AI agents: deterministic mock environments, pass^k reliability, tool-call correctness, safety and cost | 32 tasks × 3 trials on qwen3:8b: guarded agent 77.1% vs 75.0% success, same pass^3 (71.9%), at 1.88× the tokens |
| [qa-mcp-server](https://github.com/Gabnagawo/qa-mcp-server) | An MCP server that gives AI agents allowlisted, audited Android QA tools | 244 tests, 98% coverage, security-focused test suite |
| [logcat-ai-triage](https://github.com/Gabnagawo/logcat-ai-triage) | Android logcat → clustered, Jira-ready bug reports with embeddings and a local LLM | Clustering ARI 0.966–0.996 on synthetic crash logs |
| [llm-test-generator](https://github.com/Gabnagawo/llm-test-generator) | User stories → Playwright tests that run on a live app and self-correct | 8/12 valid on the first attempt with qwen3:8b |

All projects run locally with Ollama at zero cost. Every number links to a reproducible run in its repo.
<!-- FEATURED-END -->

#### Languages

Portuguese (native) · English (advanced)

#### Contact

[LinkedIn](https://www.linkedin.com/in/gabrielnagawo) · [gabrielnagawo12@gmail.com](mailto:gabrielnagawo12@gmail.com)

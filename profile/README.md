# Aegisora

**Open-source runtime security for AI agents.**

Aegisora adds a runtime governance layer between AI agents and the tools, APIs, and systems they can affect. It evaluates actions against configured policies before execution and supports three outcomes:

- **ALLOW** — permit an action that satisfies policy.
- **BLOCK** — stop an action that violates policy.
- **ESCALATE** — route an uncertain or high-impact action for review.

Explore the runtime, connect an integration, run an example, or help improve the project.

## Explore the project

| Project | What you will find |
| --- | --- |
| [Core runtime](https://github.com/aegisora-ai/aegisora) | Runtime governance, architecture, quick start, and contribution tasks |
| [Integrations](https://github.com/aegisora-ai/aegisora-integrations) | Connectors and provider integrations |
| [Examples](https://github.com/aegisora-ai/aegisora-examples) | Practical starting points for trying Aegisora |
| [Documentation](https://docs.aegisora.org) | Guides and technical documentation |
| [Dashboard](https://github.com/aegisora-ai/aegisora-dashboard) | Dashboard and control-plane interface |
| [Website](https://aegisora.org) | Learn more about Aegisora |

## Start here

**New to Aegisora?** Open the [core repository](https://github.com/aegisora-ai/aegisora) and follow its current quick-start instructions. Then run an example and share what worked, what failed, and which environment you tested.

You do not need write access to contribute. Fork the repository, make a focused change, and open a pull request.

## Find a contribution

- [Community Contributor Sprint](https://github.com/aegisora-ai/aegisora/issues/40) — choose a scoped task and report your findings.
- [Good first issues](https://github.com/aegisora-ai/aegisora/labels/good%20first%20issue) — start with a small, clearly defined improvement.
- [Core runtime issues](https://github.com/aegisora-ai/aegisora/issues) — runtime behavior, testing, security research, and developer experience.
- [Integrations issues](https://github.com/aegisora-ai/aegisora-integrations/issues) — provider and framework integrations.
- [Examples issues](https://github.com/aegisora-ai/aegisora-examples/issues) — demos and reproducible examples.

Good contributions include reproductions of bugs, focused tests, integration improvements, clearer documentation, benchmarks, and concrete feedback from real projects.

## How to contribute

1. Read the target repository's README and contribution guidance.
2. Choose one specific problem or improvement.
3. Fork the repository and keep your branch focused.
4. Run the relevant checks and describe the actual results in your pull request.

When reporting a test result, include the operating system, runtime/tool versions, commands run, and any relevant error output. Never include API keys, tokens, or other secrets.

## Community

Join the [Aegisora Discord](https://discord.gg/8CM3PpQRT5) to discuss the project, ask questions, and share experiments.

## Security

Please do not publish credentials or sensitive vulnerability details in public issues. Review the [core repository security policy](https://github.com/aegisora-ai/aegisora/blob/main/SECURITY.md) for reporting guidance.
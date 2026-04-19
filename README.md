# awesome-copilot

> A curated list of awesome GitHub Copilot instructions, prompts, agents, and extensions.

[![All Contributors](https://img.shields.io/github/all-contributors/awesome-copilot/awesome-copilot?color=ee8449&style=flat-square)](CONTRIBUTORS.md)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a community-driven fork of [github/awesome-copilot](https://github.com/github/awesome-copilot), extended with additional resources, agent workflows, and plugin marketplace integrations.

## Contents

- [Copilot Instructions](#copilot-instructions)
- [Prompt Libraries](#prompt-libraries)
- [Agent Workflows](#agent-workflows)
- [Extensions & Plugins](#extensions--plugins)
- [Tools & Integrations](#tools--integrations)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)

---

## Copilot Instructions

Custom `.github/copilot-instructions.md` files that configure Copilot behavior for specific project types.

- **[Python Projects](./instructions/python.md)** — Type hints, docstrings, pytest conventions
- **[TypeScript/Node](./instructions/typescript.md)** — ESM, strict mode, Vitest conventions
- **[Rust](./instructions/rust.md)** — Idiomatic Rust, clippy, cargo conventions
- **[Go](./instructions/go.md)** — Effective Go patterns, table-driven tests
- **[Terraform](./instructions/terraform.md)** — Module structure, naming conventions, variable documentation

## Prompt Libraries

Reusable prompt collections for common development tasks.

- **Code Review** — Structured prompts for thorough PR reviews
- **Refactoring** — Step-by-step refactoring workflows
- **Documentation** — Auto-generate README, API docs, changelogs
- **Testing** — Generate unit, integration, and E2E test suites

## Agent Workflows

Agentic workflow definitions for multi-step automation. See [`.github/agents/`](.github/agents/) for full definitions.

- **[Agentic Workflows Guide](.github/agents/agentic-workflows.agent.md)** — How to build and run agent workflows with Copilot

## Extensions & Plugins

Browse the [Plugin Marketplace](.github/plugin/marketplace.json) for community-built Copilot extensions.

## Tools & Integrations

- [copilot-cli](https://githubnext.com/projects/copilot-cli) — AI-powered shell commands
- [Copilot for PRs](https://githubnext.com/projects/copilot-for-pull-requests) — Automated PR descriptions
- [Copilot Workspace](https://githubnext.com/projects/copilot-workspace) — Task-centric development environment

## Learning Resources

- [GitHub Copilot Docs](https://docs.github.com/en/copilot)
- [Prompt Engineering for Copilot](https://gh.io/copilot-prompts)
- [Copilot Trust Center](https://resources.github.com/copilot-trust-center/)

---

## Contributing

Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md) and follow the [Code of Conduct](CODE_OF_CONDUCT.md).

To add yourself as a contributor:

```bash
npx all-contributors-cli add <username> <contribution-type>
```

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.

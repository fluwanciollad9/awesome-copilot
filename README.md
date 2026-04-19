# awesome-copilot

> A curated list of awesome GitHub Copilot instructions, agents, and plugins.

[![All Contributors](https://img.shields.io/github/all-contributors/awesome-copilot/awesome-copilot?color=ee8449&style=flat-square)](CONTRIBUTORS.md)

Fork of [github/awesome-copilot](https://github.com/github/awesome-copilot) with additional community contributions.

> **Personal fork notes:** I'm using this to experiment with custom Copilot instructions for TypeScript/React projects. PRs here may not be kept in sync with upstream.

## Contents

- [Copilot Instructions](#copilot-instructions)
- [Agentic Workflows](#agentic-workflows)
- [Plugins & Extensions](#plugins--extensions)
- [Contributing](#contributing)

---

## Copilot Instructions

Custom instruction files (`.github/copilot-instructions.md`) that tailor GitHub Copilot behavior for specific project types, languages, or workflows.

| Name | Description | Language/Framework |
|------|-------------|------------------|
| [General Instructions](.github/copilot-instructions.md) | Default instructions for this repository | General |
| [TypeScript/React Instructions](instructions/typescript-react.md) | Instructions tuned for React + TypeScript projects (my primary use case) | TypeScript, React |

---

## Agentic Workflows

Agent definition files (`.github/agents/*.agent.md`) that define autonomous Copilot agent behaviors for common development tasks.

| Name | Description |
|------|-------------|
| [Agentic Workflows](.github/agents/agentic-workflows.agent.md) | Core agentic workflow definitions |

---

## Plugins & Extensions

Marketplace plugins and extensions available for GitHub Copilot.

See [marketplace.json](.github/plugin/marketplace.json) for the full list of available plugins.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

### How to Add Your Instructions

1. Fork this repository
2. Add your `.github/copilot-instructions.md` or agent file
3. Update the relevant section in this README
4. Submit a pull request

### How to Add a Plugin

1. Fork this repository
2. Add your plugin entry to `.github/plugin/marketplace.json`
3. Submit a pull request

---

## Contributors

Thanks to all contributors! See [.all-contributorsrc](.all-contributorsrc) for the full list.

---

## License

[CC0 1.0 Universal](LICENSE) — Public Domain

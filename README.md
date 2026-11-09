<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/assets/nplet/S2-accent.svg">
    <source media="(prefers-color-scheme: light)" srcset="docs/assets/nplet/S2-color.svg">
    <img src="docs/assets/nplet/S2-color.svg" alt="Nplet" width="260">
  </picture>
</p>

# Nplet Plugin

The Nplet Plugin is the proof of concept for developing and testing [Nplet's](https://github.com/npletai) agentic Agile framework.

## What's included

- Published framework rules and organization definitions.
- Role and profile templates, with worked examples.
- Python tooling for shared local task workspaces, with integrations for Codex, Claude Code and Cursor.

The plugin is in early development. The full orchestration application is still to be built; coordinating agents across different runtimes remains a product goal.

## Contributor setup

The contributor guides cover macOS, Linux and native Windows. They describe the development environment, agent integrations and local checks.

1. [Set up your development workspace](docs/runtime/development.md#set-up-each-worktree).
2. [Configure your agent's task-workspace integration](docs/runtime/host-hooks.md#setup-and-bootstrap).
3. [Use the shared task workspace](docs/runtime/task-workspace-usage.md#usage).

Follow the [contributor workflow](docs/runtime/contributor-workflow.md) for repository changes. Submit changes through a pull request for human review.

## Explore the plugin

- [Organization and teams](src/nplet/resources/organization/team-map.md)
- [Role and profile definitions](src/nplet/resources/templates/definition-format.md)
- [Documentation index](docs/README.md)

## License

This repository uses the [PolyForm Noncommercial License 1.0.0](LICENSE).

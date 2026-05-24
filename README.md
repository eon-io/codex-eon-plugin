# Eon Codex Plugin

Connect Codex to Eon via this plugin. Bundles the Eon MCP server and guided cloud onboarding skills into a single installable package.

## Capabilities

- **Eon MCP server** — 27 tools for multi-cloud backup, recovery, inventory, source account management, backup policies, snapshot browsing, restore jobs, GCP organization/folder onboarding, and resource discovery.
- **AWS onboarding skill** — step-by-step guided workflow to connect AWS source accounts via the Eon CloudFormation template.
- **GCP onboarding skill** — step-by-step guided workflow to connect GCP organizations, folders, and individual projects to Eon.
- **Backup policy creation skill** — guided wizard for creating backup policies (resource selectors, schedules, retention).

## Installation

Install via the Codex plugin marketplace using `.agents/plugins/marketplace.json`.

## Skills

| Skill | Description |
|-------|-------------|
| AWS Onboarding | Guide users through connecting AWS source accounts to the Eon platform via the public CloudFormation template. |
| GCP Onboarding | Guide users through connecting GCP cloud accounts (orgs, folders, or individual projects) to the Eon platform. |
| Backup Policy Creation | Guide users through creating a backup policy: type, resource selector, schedules, vaults, and retention. |

## MCP Server

The plugin connects to `https://mcp.eon.io/mcp` via HTTP. Authentication is handled by the Eon platform.

## Links

- [Eon Platform](https://eon.io)
- [Documentation](https://docs.eon.io)

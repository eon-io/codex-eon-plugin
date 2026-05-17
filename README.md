# Eon Codex Plugin

Connect Codex to Eon via this plugin. Bundles the Eon MCP server and guided cloud onboarding skills into a single installable package.

## Capabilities

- **Eon MCP server** — 27 tools for multi-cloud backup, recovery, inventory, source account management, backup policies, snapshot browsing, restore jobs, GCP organization/folder onboarding, and resource discovery.
- **GCP onboarding skill** — step-by-step guided workflow to connect GCP organizations, folders, and individual projects to Eon.

## Installation

Install via the Codex plugin marketplace using `.agents/plugins/marketplace.json`.

## Skills

| Skill | Description |
|-------|-------------|
| GCP Onboarding | Guide users through connecting GCP cloud accounts (orgs, folders, or individual projects) to the Eon platform. |

## MCP Server

The plugin connects to `https://mcp.eon.io/mcp` via HTTP. Authentication is handled by the Eon platform.

## Links

- [Eon Platform](https://eon.io)
- [Documentation](https://docs.eon.io)

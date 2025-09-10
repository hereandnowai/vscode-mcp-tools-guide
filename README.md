# VSCode MCP Tools Guide

![HERE AND NOW AI Logo](https://raw.githubusercontent.com/hereandnowai/images/refs/heads/main/logos/logo-of-here-and-now-ai.png)

A practical learning and reference repository for using GitHub's MCP-enabled tools from inside Visual Studio Code. This project collects guided exercises, example workflows, and reference material so developers, maintainers, and instructors can learn how to use MCP tooling in real tasks — without expecting the reader to already know every MCP API call.

Who this is for
- Developers who want step-by-step labs to practice repository, branch, issue, PR, file, commit, release, and Actions workflows via MCP-enabled assistants.
- Team leads and instructors building hands-on training or onboarding workshops.
- Open-source maintainers who want a reproducible curriculum for contributor guidance.

What you'll find here
- A curated set of hands-on activities and exercises (beginner → advanced) that demonstrate common GitHub tasks using MCP-capable assistant tooling.
- A single reference document (`gh-mcp-tools.md`) with scenarios and suggested commands/steps.
- An example MCP client configuration under `.vscode/mcp.json` to get VS Code assistants talking to a configured MCP server.
- `branding.json` with organization assets and contact information used to brand the guide and any generated documentation.

Quick start
1. Open this folder in VS Code.
2. Install the GitHub Copilot Chat extension (or whichever MCP client you use).
3. Verify or create `.vscode/mcp.json` with your MCP server details.
4. Read `gh-mcp-tools.md` for the full list of activities and a suggested learning path.

Structure and suggested learning path
- Start with the Repository and Branch Management sections to learn basic operations and protections.
- Move to Issues and Pull Requests to practice lifecycle and review flows.
- Finish with Actions, Releases, and Advanced Scenarios to automate and scale workflows.

Branding and visual notes
- Logo and contact: pulled from `branding.json` to make the repo immediately identifiable and to give contributors the right contact points.
- Brand colors: Primary `#FFDF00` and Secondary `#004040` are included as a reference for anyone producing visuals or docs derived from this repository. They are not meant to be enforced by code — they exist to help maintain a consistent visual identity for any generated slides, web pages, or tutorial PDFs. Including the colors in this README makes them easy for contributors to find when they produce collateral.

Files you should look at first
- `gh-mcp-tools.md` — primary guide and activities (read this to understand the exercises and learning objectives).
- `.vscode/mcp.json` — sample MCP configuration used by the VS Code assistant.
- `branding.json` — organization metadata (logo, contact, social links) used in this repository's docs.

Contributing and contact
- If you want to extend or reorganize the exercises, open a pull request with your changes and a short explanation.
- For questions about HERE AND NOW AI branding or the guide itself, contact: info@hereandnowai.com

Why the README is styled this way
- The goal is to make the repository approachable: a short description, clear audience, quick start steps, and where to go next (the longer `gh-mcp-tools.md` file). Branding elements are included to provide identity and contact info for contributors.

---

HERE AND NOW AI — designed with passion for innovation
Website: https://hereandnowai.com
GitHub: https://github.com/hereandnowai



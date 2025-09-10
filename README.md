# VSCode MCP Tools Guide

A practical, hands-on repository that teaches developers how to use MCP-enabled assistant tooling (for example, GitHub Copilot Chat) inside Visual Studio Code. The project collects structured exercises, real-world scenarios, and concise reference notes so you can practice common GitHub tasks via an MCP-capable assistant instead of only using the web UI or raw API calls.

Why this exists
- Turn theoretical MCP capabilities into repeatable learning exercises.
- Give teams a reproducible training path for repository, branch, issue, pull request, file, commit, release, and Actions workflows.
- Provide a small, self-contained lab that instructors and maintainers can adapt for workshops or onboarding.

What you'll get
- A graduated set of exercises from basic repo operations to advanced CI/CD and automation scenarios.
- A single, readable reference (`gh-mcp-tools.md`) that describes activities and suggested assistant prompts.
- Example configuration (`.vscode/mcp.json`) so you can connect a local VS Code assistant to an MCP server.

Quick start
1. Open this folder in Visual Studio Code.
2. Install an MCP-capable assistant extension (for example, GitHub Copilot Chat).
3. Check or create `.vscode/mcp.json` with your MCP server URL and credentials.
4. Read `gh-mcp-tools.md` to pick a learning path and follow the exercises interactively with your assistant.

How to use the guide
- Start small: run the repository and branch management exercises first to become comfortable with basic operations.
- Use Issues and Pull Requests sections to practice collaboration and review workflows.
- Finish with Actions, Releases, and automation scenarios to learn how to scale and test automation.

Files of interest
- `gh-mcp-tools.md` — the main set of activities and scenarios (the canonical learning plan).
- `.vscode/mcp.json` — sample MCP client configuration used by VS Code extensions.
- `branding.json` — organization metadata (logo, contact, social links) used for documentation and collateral.

About the creator
- Organization: HERE AND NOW AI
- Website: https://hereandnowai.com
- Email: info@hereandnowai.com
- Mobile: +91 996 296 1000
- Slogan: designed with passion for innovation

Connect with HERE AND NOW AI
- Blog: https://hereandnowai.com/blog
- LinkedIn: https://www.linkedin.com/company/hereandnowai/
- Instagram: https://instagram.com/hereandnow_ai
- GitHub: https://github.com/hereandnowai
- X: https://x.com/hereandnow_ai
- YouTube: https://youtube.com/@hereandnow_ai

Branding note
The repository includes the brand logo and a pair of reference colors in `branding.json`. These values are provided so contributors can easily produce slides, images, or docs that match the organization's visual identity — they are reference values only and do not change repository behavior.

Contributing
- Suggestions and fixes are welcome. Please open a pull request with a description of the change and which exercise it improves.

License
- This repository does not include a license file by default. Add one if you want to accept community contributions under a specific license.

---

If you want the README expanded to include a table of contents, quick command examples, or contribution guidelines, tell me which section to add and I'll update it.
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



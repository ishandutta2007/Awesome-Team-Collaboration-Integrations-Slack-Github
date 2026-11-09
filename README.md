# Awesome-Team-Collaboration-Integrations-Slack-Github

# Awesome Team Collaboration Integrations (Slack/GitHub)

> A curated list of top Team Collaboration Integration platforms — both SaaS/Hosted commercial solutions and open-source alternatives for connecting Slack, GitHub, Microsoft Teams, and other workflow tools into a unified collaboration fabric.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Slack Integrations & Apps](#slack-integrations--apps)
  - [GitHub Integrations](#github-integrations)
  - [Microsoft Teams Apps](#microsoft-teams-apps)
  - [Jira Cloud Integrations](#jira-cloud-integrations)
- [Open-Source Software](#-open-source-software)
  - [GitHub Slack Integration (Official)](#github-slack-integration-official)
  - [Gopherbot](#gopherbot)
  - [Buzz (Block)](#buzz-block)
  - [DataGroceries (django-dg)](#datagroceries-django-dg)
  - [Activepieces](#activepieces)
  - [slack-github-action](#slack-github-action)
  - [Botkit](#botkit)
  - [Dispatch](#dispatch)
  - [Keybase GitHub Bot](#keybase-github-bot)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Team Collaboration Integration platforms. These are not open-source but are included as reference points for feature comparison.

### Slack Integrations & Apps
**Type:** App directory and platform for team collaboration integrations  
Slack provides a vast App Directory with thousands of integrations, plus a robust platform (Bolt, Web API, Events API) for building custom apps. The official GitHub integration for Slack is maintained by GitHub and brings pull request updates, issue mentions, and CI status into Slack channels [citation:15]. For teams wanting to bridge Slack with external services, Slack's platform is the foundation upon which most third-party integrations are built.

### GitHub Integrations
**Type:** Platform for code collaboration integrations  
GitHub provides GitHub Apps (with granular permissions and webhooks), Actions (for CI/CD workflows), and a REST/GraphQL API for building integrations. The official Slack integration is maintained by GitHub [citation:15]. GitHub's ecosystem is the primary integration target for most team collaboration tools, with thousands of third-party apps connecting repositories, pull requests, and issues to chat and project management platforms.

### Microsoft Teams Apps
**Type:** App platform within Microsoft 365  
Microsoft Teams provides an app platform with tabs, bots, messaging extensions, and webhooks for building integrations. The official GitHub integration for Teams is maintained by GitHub, bringing repository activity into Teams channels [citation:15]. Teams is the natural integration hub for organizations already standardized on Microsoft 365, with deep native integrations for Office, SharePoint, and Azure DevOps.

### Jira Cloud Integrations
**Type:** Atlassian ecosystem integration platform  
Jira Cloud provides native integrations with Slack, Microsoft Teams, and GitHub through Atlassian's marketplace and built-in apps. The Jira Cloud for Slack app allows creating and transitioning issues directly from Slack, while the GitHub for Jira integration links commits and pull requests to Jira issues. These integrations are the standard for teams using Atlassian's ecosystem.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Team Collaboration Integration tools. The open-source ecosystem spans **official integration bridges**, **ChatOps automation platforms**, **AI-native workspaces**, and **workflow automation engines**.

### GitHub Slack Integration (Official)
**Stack:** TypeScript / GitHub Actions | **License:** MIT  
The official GitHub Slack integration repository (`integrations/slack`) is maintained by GitHub and is fully open-source [citation:15]. It brings pull request updates, issue mentions, and CI status into Slack channels. The repository has 3,016+ stars and is actively maintained. This is the canonical way to connect GitHub activity to Slack without relying on third-party services.

### Gopherbot
**Stack:** Go | **License:** Open Source (per project)  
Gopherbot is a ChatOps automation platform that runs as a Linux process, connecting to Slack (and a Terminal connector) to respond to CLI-like commands [citation:2]. Scripts in Bash, Ruby, Python, or Go can provision resources, run reports, deploy software, or interact with CI/CD. Features include GitOps-style self-deployment, threaded conversation support, hidden Slack slash commands, encrypted secrets, and built-in Google Authenticator TOTP. It is designed for DevOps engineers wanting to bring command-line power into team chat.

### Buzz (Block)
**Stack:** Rust / Nostr Protocol / PostgreSQL / Redis | **License:** Apache 2.0  
Buzz is an open-source workspace from Block that unifies team chat, Git repositories, and AI agent collaboration in a single self-hosted relay [citation:4][citation:9][citation:13]. Its defining feature is cryptographic identity for both humans and AI agents using Nostr keys: every message, Git event, and agent action is a signed event, creating a verifiable audit trail [citation:13]. Agents (Claude Code, Codex, Goose) can join channels, open repositories, submit patches, and review code with their own scoped identities [citation:4]. The platform aims to combine Slack, GitHub, and CI/CD features. **Important:** The project is very new (July 2026); mobile apps and push notifications are still under development [citation:4].

### DataGroceries (django-dg)
**Stack:** Python / Django | **License:** MIT  
DataGroceries provides open-source Django apps (a Kanban board and a wiki) that people and AI agents work on together [citation:7]. The board includes @-mentions and watchers with notifications via email or Slack (Slack takes priority), and tickets link to GitHub commits, branches, and pull requests that mention their key. Agents reach the apps through an MCP endpoint and work as the person who connected them, with every change attributed in history. This is a practical way to add collaboration and AI agent access to an existing Django project without a heavyweight platform.

### Activepieces
**Stack:** TypeScript | **License:** MIT  
Activepieces is a genuinely MIT-licensed open-source automation platform positioned as a more approachable alternative to Zapier and n8n [citation:6][citation:10]. It provides a visual flow builder with branches, loops, and conditional logic, 500+ pre-built pieces (including Slack, GitHub, Google Sheets, and OpenAI), AI agents and AI Copilot built into the builder, human-in-the-loop approval steps, and MCP server support [citation:10]. For team collaboration integrations, Activepieces can bridge Slack, GitHub, and other tools without vendor lock-in or per-task pricing.

### slack-github-action
**Stack:** JavaScript / GitHub Actions | **License:** Open Source (per project)  
slack-github-action is a GitHub Action for sending data to Slack and running Slack CLI commands directly from GitHub workflows [citation:1][citation:11]. With 1.3k+ stars, it is the practical way to notify Slack channels about build results, deployments, or any workflow event without writing custom integration code. It is part of the broader ecosystem of Slack integration tools for developer workflows.

### Botkit
**Stack:** TypeScript | **License:** MIT  
Botkit is an open-source developer tool for building chat bots, apps, and custom integrations for major messaging platforms [citation:11]. With 11.6k+ stars, it provides a framework for creating Slack bots that can respond to events, manage conversations, and integrate with external services. It is the foundation for many custom Slack integrations that go beyond simple webhooks.

### Dispatch
**Stack:** Python | **License:** Open Source (per project)  
Dispatch is an incident management platform that orchestrates security incidents by integrating with Slack, Jira, and other tools [citation:11]. With 6.5k+ stars, it is a practical example of a Slack integration built for a specific workflow (incident response) rather than general-purpose automation. It demonstrates how Slack can serve as the central collaboration layer for specialized team processes.

### Keybase GitHub Bot
**Stack:** Go | **License:** Open Source (per project)  
Keybase's GitHub bot notifies a Keybase chat channel when events happen on a GitHub repository (issues, pull requests, commits, etc.) [citation:12]. It requires a running MySQL database and a GitHub App for authentication. While Keybase is a niche chat platform, this bot is a useful reference for building GitHub-to-chat notification integrations with proper webhook verification and OAuth.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Slack | GitHub | AI Agents | Self-Hosted | Best For |
|----------|---------|-------|-------|--------|-----------|-------------|----------|
| **GitHub Slack (Official)** | MIT | TypeScript | ✅ | ✅ | ❌ | ✅ | Canonical GitHub→Slack notifications |
| **Gopherbot** | Open Source | Go | ✅ | (Via scripts) | ❌ | ✅ | ChatOps command automation |
| **Buzz (Block)** | Apache 2.0 | Rust/Nostr | (Chat) | ✅ Git forge | ✅ First-class | ✅ | Unified chat + Git + AI agents |
| **DataGroceries** | MIT | Python/Django | ✅ | ✅ | ✅ MCP | ✅ | Django board + wiki + agent access |
| **Activepieces** | MIT | TypeScript | ✅ | ✅ | ✅ AI Copilot | ✅ | Visual automation with 500+ pieces |
| **slack-github-action** | Open Source | JavaScript | ✅ | ✅ | ❌ | ✅ (Actions) | CI/CD notifications to Slack |
| **Botkit** | MIT | TypeScript | ✅ | (Via code) | ❌ | ✅ | Custom Slack bot development |
| **Dispatch** | Open Source | Python | ✅ | ✅ (Jira) | ❌ | ✅ | Security incident orchestration |
| **Keybase GitHub Bot** | Open Source | Go | (Keybase) | ✅ | ❌ | ✅ | Reference for GitHub→chat bots |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Team Collaboration Integration tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem **splits** between official integration bridges (GitHub Slack integration), ChatOps automation (Gopherbot), AI-native workspaces (Buzz), and general-purpose workflow engines (Activepieces). For simple GitHub-to-Slack notifications, the official integration is the standard. For teams wanting to consolidate chat, Git, and AI agents under one self-hosted roof, Buzz is the most ambitious effort, though it is still very new.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐

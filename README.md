# Awesome Team Collaboration Integrations (Slack & GitHub)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](LICENSE)

> A curated list of top **Team Collaboration Integrations**, **ChatOps workflows**, **Slack bots**, and **GitHub Actions** — covering both enterprise SaaS platforms and battle-tested open-source alternatives for bridging Slack, GitHub, Microsoft Teams, and ticketing ecosystems into a unified developer collaboration fabric.
>
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
- [Open-Source Software](#-open-source-software)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📈 Sector Overview & Market Dynamics

The global team collaboration and workplace integration software market is estimated at **$31.8 billion** and is projected to expand beyond **$65 billion by 2030** (CAGR ~13.5%). The sector exhibits **moderate-to-high market concentration** among mega-cap ecosystem gatekeepers (Microsoft 365/Teams, Salesforce/Slack, and Atlassian/Jira) who capture majority workflow share via bundle dominance, while sustaining a vibrant, highly innovative long-tail ecosystem of specialized ChatOps, AI agents, workflow orchestrators, and developer-first integration engines.

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Team Collaboration and Integration platforms. The table below compares key enterprise players ranked by company valuation/market capitalization in descending order.

| Platform | Company Valuation / Revenue | Starting Tier Price | Free Tier Limits / Free Trial | Integration Ecosystem | Best For |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Microsoft Teams Apps** | **$3.1+ Trillion** Market Cap (Microsoft) / $245B+ Annual Revenue | **$4.00/user/month** (Teams Essentials billed annually) | **Free Forever Plan**: Up to 100 participants per meeting, 60 min group meeting duration, 5 GB cloud storage per user, and 1:1 chat/calls. | Deep Microsoft 365, Azure DevOps, SharePoint, and official GitHub App integration. | Organizations standardized on Microsoft 365 wanting seamless enterprise communication and IT governance. |
| **GitHub Integrations** | **$100+ Billion** Subsidiary Valuation (Microsoft) / $1B+ ARR | **$4.00/user/month** (GitHub Team billed annually, or $4.40/month) | **Free Forever Plan**: Unlimited public/private repositories, 2,000 CI/CD Actions minutes/month, 500 MB GitHub Packages storage, and community support. | GitHub Marketplace, native Webhooks, GitHub Apps, REST/GraphQL APIs, and official Slack App. | Engineering teams seeking native CI/CD workflows, issue automation, and code-review bridge alerts. |
| **Slack Integrations & Apps** | **$27.7 Billion** Acquisition Valuation (Salesforce) / $1.5B+ Segment Revenue | **$7.25/user/month** (Slack Pro billed annually, or $8.75/month) | **Free Forever Plan**: 90-day searchable message and file history, 10 app integrations max, and 1:1 audio/video huddles. | 2,600+ Slack App Directory integrations, Bolt SDK (Node/Python/Java), Webhooks, and Events API. | Cross-functional teams requiring real-time ChatOps, automated alerts, and rich interactive message cards. |
| **Jira Cloud Integrations** | **$45+ Billion** Market Cap (Atlassian) / $4.3B+ Annual Revenue | **$7.75/user/month** (Jira Standard billed annually, or $8.60/month) | **Free Forever Plan**: Up to 10 users, 2 GB file storage, unlimited project boards, and standard Atlassian automation (100 rules/month). | Atlassian Marketplace (3,000+ apps), bi-directional Slack bot, GitHub for Jira, and Bitbucket sync. | Agile software delivery teams tracking issues, sprints, and pull request statuses directly inside chat. |

---

## 🟩 Open-Source Software

Self-hosted and community-driven Team Collaboration Integration tools, ChatOps frameworks, and automation bridges. Ranked in descending order by GitHub stargazers.

| Project | Stars | Stack | License | Description & Integration Highlights |
| :--- | :--- | :--- | :--- | :--- |
| [**n8n**](https://github.com/n8n-io/n8n/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/n8n-io/n8n?style=social&color=white)](https://github.com/n8n-io/n8n/stargazers) | TypeScript / Node.js | Fair-code (Sustainable Use License) | Fair-code workflow automation tool with extensive multi-step native nodes for bi-directional Slack and GitHub event triggers, webhooks, and AI agent nodes. |
| [**Huginn**](https://github.com/huginn/huginn/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/huginn/huginn?style=social&color=white)](https://github.com/huginn/huginn/stargazers) | Ruby / Rails | MIT | Hackable agent framework for building autonomous event-driven pipelines that watch GitHub repositories and dispatch interactive events to Slack channels. |
| [**Rocket.Chat**](https://github.com/RocketChat/Rocket.Chat/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/RocketChat/Rocket.Chat?style=social&color=white)](https://github.com/RocketChat/Rocket.Chat/stargazers) | TypeScript / Node.js | MIT | Privacy-first open-source team communications hub featuring native incoming/outgoing webhooks and direct GitHub and Slack bridge integration apps. |
| [**Mattermost**](https://github.com/mattermost/mattermost/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/mattermost/mattermost?style=social&color=white)](https://github.com/mattermost/mattermost/stargazers) | Go / React | AGPLv3 / Apache 2.0 | High-trust self-hosted collaboration platform with a rich plugin architecture, including deep bi-directional GitHub integration, slash commands, and Slack compatibility. |
| [**Chatwoot**](https://github.com/chatwoot/chatwoot/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/chatwoot/chatwoot?style=social&color=white)](https://github.com/chatwoot/chatwoot/stargazers) | Ruby on Rails / Vue | MIT | Open-source customer engagement and conversational support suite with native Slack conversation mirroring and webhook-based GitHub issue dispatchers. |
| [**Block Buzz**](https://github.com/block/buzz/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/block/buzz?style=social&color=white)](https://github.com/block/buzz/stargazers) | Rust / Nostr / PostgreSQL | Apache-2.0 | Cryptographically verifiable developer workspace from Block merging real-time team chat, decentralized Git repositories, and autonomous AI agents. |
| [**Zulip**](https://github.com/zulip/zulip/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/zulip/zulip?style=social&color=white)](https://github.com/zulip/zulip/stargazers) | Python / Django / TypeScript | Apache-2.0 | Threaded stream-based team collaboration platform with 100+ native integrations, including granular GitHub pull request notifications and Slack migration bridges. |
| [**Activepieces**](https://github.com/activepieces/activepieces/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/activepieces/activepieces?style=social&color=white)](https://github.com/activepieces/activepieces/stargazers) | TypeScript | MIT | No-code/low-code workflow engine with 500+ pre-built integrations, visual branch/loop builder, and official pieces for Slack alerts, GitHub issue synching, and AI agents. |
| [**Leantime**](https://github.com/Leantime/leantime/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/Leantime/leantime/stargazers) | PHP / JavaScript | AGPLv3 | Strategic open-source project management platform tailored for cross-functional teams, featuring Slack notifications, webhook pipelines, and GitHub sync plugins. |
| [**Botkit**](https://github.com/howdyai/botkit/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/howdyai/botkit?style=social&color=white)](https://github.com/howdyai/botkit/stargazers) | TypeScript / Node.js | MIT | Battle-tested developer framework and conversational SDK for constructing event-driven bots, conversational workflows, and custom Slack-to-GitHub ChatOps apps. |
| [**Dispatch**](https://github.com/Netflix/dispatch/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/Netflix/dispatch?style=social&color=white)](https://github.com/Netflix/dispatch/stargazers) | Python / FastAPI / Vue | Apache-2.0 | Security incident management orchestrator by Netflix that spins up dedicated Slack incident rooms, assigns tasks, and links relevant GitHub commits and Jira tickets. |
| [**Vikunja**](https://github.com/go-vikunja/vikunja/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/go-vikunja/vikunja/stargazers) | Go / Vue.js | AGPLv3 | Self-hostable, clean collaborative to-do and task management suite with REST APIs and webhook integrations for GitHub commits and Slack notifications. |
| [**GitHub Slack Integration**](https://github.com/integrations/slack/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/integrations/slack?style=social&color=white)](https://github.com/integrations/slack/stargazers) | TypeScript | MIT | The official bi-directional GitHub integration for Slack by GitHub. Subscribe to repositories, review pull requests, and close issues with slash commands. |
| [**Bolt for JavaScript**](https://github.com/slackapi/bolt-js/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/slackapi/bolt-js?style=social&color=white)](https://github.com/slackapi/bolt-js/stargazers) | TypeScript / JavaScript | MIT | Official Slack framework to quickly assemble modern Slack apps and ChatOps workflows responding to events, slash commands, shortcuts, and interactive blocks. |
| [**slack-github-action**](https://github.com/slackapi/slack-github-action/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/slackapi/slack-github-action?style=social&color=white)](https://github.com/slackapi/slack-github-action/stargazers) | JavaScript / GitHub Actions | MIT | Official GitHub Action from Slack for sending custom rich messages, Block Kit cards, and deployment telemetry straight to Slack channels. |
| [**Bolt for Python**](https://github.com/slackapi/bolt-python/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/slackapi/bolt-python?style=social&color=white)](https://github.com/slackapi/bolt-python/stargazers) | Python | MIT | Official Python framework for building Slack apps, handling Slack event payloads, and executing automated GitHub API actions in Python services. |
| [**Gopherbot**](https://github.com/lnxjedi/gopherbot/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/lnxjedi/gopherbot?style=social&color=white)](https://github.com/lnxjedi/gopherbot/stargazers) | Go | Apache-2.0 | Extensible ChatOps robot engine designed for DevOps engineers; automates command-line workflows, deployment triggers, and multi-protocol Slack conversations. |
| [**Keybase GitHub Bot**](https://github.com/wiz/keybase-github-bot/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/wiz/keybase-github-bot?style=social&color=white)](https://github.com/wiz/keybase-github-bot/stargazers) | Go | MIT | Reference implementation bot connecting GitHub event webhooks (commits, pull requests, issues) to secure team channels. |
| [**DataGroceries (django-dg)**](https://github.com/datagroceries/django-dg/stargazers) | [![GitHub stars](https://img.shields.io/github/stars/datagroceries/django-dg?style=social&color=white)](https://github.com/datagroceries/django-dg/stargazers) | Python / Django | MIT | Modular Django Kanban board and wiki apps integrating Slack @-mentions, GitHub commit/PR linking, and Model Context Protocol (MCP) agent endpoints. |

---

## 📊 Comparison at a Glance

| Software / Tool | Type | License | Primary Language | Slack Support | GitHub Support | Primary Focus |
| :--- | :--- | :--- | :--- | :---: | :---: | :--- |
| **n8n** | Self-Hosted / Cloud | Sustainable Use | TypeScript | ✅ | ✅ | Multi-system visual workflow & event automation |
| **Huginn** | Self-Hosted | MIT | Ruby | ✅ | ✅ | Autonomous agent monitoring & event dispatch |
| **Rocket.Chat** | Self-Hosted / Cloud | MIT | TypeScript | ✅ | ✅ | Team collaboration with full webhook extensibility |
| **Mattermost** | Self-Hosted / Cloud | AGPLv3 / Apache 2.0 | Go | ✅ | ✅ | Secure developer chat with bi-directional GitHub integration |
| **Chatwoot** | Self-Hosted / Cloud | MIT | Ruby | ✅ | ✅ | Omnichannel customer & team conversations |
| **Block Buzz** | Self-Hosted | Apache-2.0 | Rust | ❌ (Own Chat) | ✅ | Cryptographic chat, Git repository & AI workspace |
| **Zulip** | Self-Hosted / Cloud | Apache-2.0 | Python | ✅ | ✅ | Real-time topic-threaded team messaging |
| **Activepieces** | Self-Hosted / Cloud | MIT | TypeScript | ✅ | ✅ | Open-source Zapier alternative with 500+ connectors |
| **Leantime** | Self-Hosted / Cloud | AGPLv3 | PHP | ✅ | ✅ | Cross-functional project & ticket management |
| **Botkit** | Framework | MIT | TypeScript | ✅ | (Via API) | Custom Slack chatbot & conversation builder |
| **Dispatch** | Self-Hosted | Apache-2.0 | Python | ✅ | ✅ | Security incident orchestration & Slack war-rooms |
| **Vikunja** | Self-Hosted / Cloud | AGPLv3 | Go | ✅ | ✅ | Self-hosted collaborative task and project management |
| **GitHub Slack (Official)**| Integration Bridge | MIT | TypeScript | ✅ | ✅ | Canonical GitHub notifications & slash commands in Slack |
| **Bolt for JavaScript** | Framework | MIT | TypeScript | ✅ | (Via API) | Official SDK for interactive Slack application development |
| **slack-github-action** | GitHub Action | MIT | JavaScript | ✅ | ✅ | Direct deployment & CI/CD status reporting to Slack |
| **Bolt for Python** | Framework | MIT | Python | ✅ | (Via API) | Official Python framework for interactive Slack apps |
| **Gopherbot** | ChatOps Engine | Apache-2.0 | Go | ✅ | (Via Scripts) | DevOps CLI automation & scheduled tasks via chat |
| **Keybase GitHub Bot** | Bot | MIT | Go | (Keybase) | ✅ | Webhook-driven repository notification service |
| **DataGroceries** | App Modules | MIT | Python | ✅ | ✅ | Django board, wiki, and MCP AI agent collaboration |

---

## 🤝 Contributing

Contributions are always welcome! To suggest an open-source project, integration library, or update existing details:

1. Fork this repository.
2. Add your suggested entry to the appropriate section in alphabetical or sorted order.
3. Ensure the project is active, well-documented, and adheres to genuine open-source or commercial guidelines.
4. Submit a Pull Request with a clear description of the addition.

---

## 📄 License

This repository and curated list are released under the [Creative Commons Zero v1.0 Universal](LICENSE) (CC0 1.0) Public Domain dedication. Listed products, logos, and projects retain their respective copyrights, trademarks, and licenses.

---

⭐ **If this repository helped streamline your team's ChatOps and developer workflows, consider starring it!** ⭐

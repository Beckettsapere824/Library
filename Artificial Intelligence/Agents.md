# Agents

Subscription and pricing details checked on 2026-10-20. Access, limits, and supported models can vary by region, account, and provider changes.

## OpenAI Codex

**Official product:** [OpenAI Codex](https://openai.com/codex/)

Codex is a coding agent that can inspect a repository, plan and edit code, run available commands and tests, and present changes for review. It supports interactive work in a local repository and delegated cloud tasks. Interfaces include ChatGPT/web, desktop, CLI, and IDE integrations. The CLI also supports non-interactive `codex exec` for scripts and CI. Cloud tasks may continue after a computer is closed. See the [CLI](https://developers.openai.com/codex/cli) and [IDE documentation](https://developers.openai.com/codex/ide).

**Price and usage.** Codex is available through ChatGPT plans: Free and Go have limited access; Plus is listed at $20/month; Pro tiers start at $100/month. Business and Enterprise options are available. Limits depend on task complexity, model, tools, context, and whether execution is local or cloud-based; there is no single fixed message quota. A ChatGPT subscription is distinct from API billing. When using an API key, model use is metered at API rates; cloud-only features may not be included. See [Codex pricing and limits](https://developers.openai.com/codex/pricing), [ChatGPT pricing](https://chatgpt.com/pricing), and [plan access](https://help.openai.com/en/articles/11369540-using-codex-with-your-chatgpt-plan).

**Official references:** [Codex](https://openai.com/codex/) · [CLI](https://developers.openai.com/codex/cli) · [IDE extension](https://developers.openai.com/codex/ide) · [Pricing and usage limits](https://developers.openai.com/codex/pricing) · [OpenAI API pricing](https://developers.openai.com/api/docs/pricing)

## Anthropic Claude Code

**Official product:** [Claude Code](https://claude.com/product/claude-code)

Claude Code is an agentic coding assistant. It can inspect a codebase, plan and edit files, run shell commands, and work with Git and pull-request workflows. The primary interface is a terminal CLI; other interfaces include Claude Desktop, VS Code, JetBrains, and cloud sessions. Integrations include GitHub Actions, GitLab CI/CD, Slack, Chrome, and MCP servers. It supports project instructions, skills, hooks, subagents, and CI scripting. Review code changes and command permissions before accepting them. See the [overview](https://code.claude.com/docs/en/overview) and [platforms](https://code.claude.com/docs/en/platforms).

**Price and usage.** Claude Code is not included in Claude’s Free plan. It is included with paid Claude subscriptions, including Pro ($20/month or $200/year) and Max ($100/month or $200/month tiers). Paid-plan use is shared with Claude chat and subject to rolling and weekly limits; actual usage varies with model and task. A Claude subscription is separate from Claude Console/API billing. API-key use is metered per token. See [Claude pricing](https://www.anthropic.com/pricing), [plan limits](https://support.claude.com/en/articles/11145838-using-claude-code-with-your-pro-or-max-plan), [API pricing](https://platform.claude.com/docs/en/about-claude/pricing), and [API limits](https://platform.claude.com/docs/en/api/rate-limits).

**Official references:** [Overview](https://code.claude.com/docs/en/overview) · [Setup](https://code.claude.com/docs/en/setup) · [Platforms and integrations](https://code.claude.com/docs/en/platforms) · [Models, usage, and limits](https://support.claude.com/en/articles/14552983-models-usage-and-limits-in-claude-code) · [Subscription pricing](https://www.anthropic.com/pricing) · [API pricing](https://platform.claude.com/docs/en/about-claude/pricing)

## Muse — Meta personal AI agent

**Official product:** [Muse](https://muse.ai/)

Muse is Meta’s personal AI agent, distinct from [Muse Code](https://dev.meta.ai/products/muse-code) and from a model/API offering. It is designed for multi-step everyday tasks: browsing, using connected services, preparing documents or images, tracking goals, and continuing work in the background. It runs tasks in a persistent, isolated cloud Linux VM with a browser; users interact through mobile or Mac apps, or WhatsApp. See [Meta’s product page](https://ai.meta.com/muse/) and [launch announcement](https://about.fb.com/news/2026/09/introducing-muse-personal-ai-agent/).

Meta describes user-controlled permissions and a Sentinel component for authorization. The product and subscriptions are in limited testing and may not be available in every region. Security controls do not guarantee that outputs or actions are always correct.

**Price and usage.** The free tier has a usage limit, but the checked subscription page does not give a universal numeric allowance. Paid plans are listed as Power at $20/month for 500M Muse tokens/week and Maximum at $100/month for 3B Muse tokens/week. Availability and benefits can vary by account and region. Muse is not described as a public model API. See [subscription details](https://www.meta.com/help/subscriptions/1021145227643680/).

**Official references:** [Muse](https://muse.ai/) · [Features and FAQ](https://ai.meta.com/muse/) · [Launch announcement](https://about.fb.com/news/2026/09/introducing-muse-personal-ai-agent/) · [Subscriptions](https://www.meta.com/help/subscriptions/1021145227643680/) · [Security design](https://security.muse.ai/) · [Terms](https://muse.ai/terms) · [Muse Code](https://dev.meta.ai/products/muse-code)

## Grok Bot — persistent cloud-computer AI teammates

**Official product:** [Grok Bot](https://x.ai/bot) · [Official documentation](https://docs.x.ai/grok-bot/overview)

Grok Bot is xAI’s agent product. You create named Bots, describe a job, and message them like teammates. Each Bot can use a persistent cloud computer with a browser, filesystem, terminal, connected apps, and logged-in sessions. Bots can do multi-step work in real tools, keep context and memory across sessions, coordinate in parallel, learn repeatable routines, and continue working while your own computer is closed. They return to the conversation when drafts or sensitive actions need review. See [Grok Bot overview](https://docs.x.ai/grok-bot/overview), [computer and apps](https://docs.x.ai/grok-bot/computer-and-apps), and [skills and routines](https://docs.x.ai/grok-bot/skills-routines-and-automations).

Grok Bot is **not** the conversational Grok assistant inside X, and is **not** the same as the general-purpose Grok.com chat interface below. Its distinguishing feature is agents working on their own persistent cloud computer. Grok Bot is available through desktop and mobile apps; see [supported platforms](https://docs.x.ai/grok-bot/overview).

**Price and access.** The official [Grok Bot page](https://x.ai/bot) lists individual X Subscription plans: Premium at $30/month, Super at $100/month, and Ultra at $200/month; each includes weekly usage, and Super/Ultra provide larger allowances. Usage beyond the included pool may incur token-based additional charges. The official [Cursor access matrix](https://cursor.com/help/grok-bot/plans) also lists access for users on eligible paid Cursor individual plans or Cursor Teams, and some linked individual SuperGrok plans. Eligibility depends on which account and subscription path is used; Free and Plus on the new X Subscription do not include Grok Bot. Check the current plan matrix before subscribing.

**Security note.** All Bots under one user share that user’s cloud computer, including files, browser sessions, and app logins; separate Bots are not security boundaries. Use scoped access and require approval for sending, publishing, purchases, deletion, permission changes, and production actions. See [approvals, security, and privacy](https://docs.x.ai/grok-bot/approvals-security-and-privacy).

**Official references:** [Grok Bot product and pricing](https://x.ai/bot) · [Overview](https://docs.x.ai/grok-bot/overview) · [Get started](https://docs.x.ai/grok-bot/get-started) · [Bots and collaboration](https://docs.x.ai/grok-bot/chat-and-collaboration) · [Computer and apps](https://docs.x.ai/grok-bot/computer-and-apps) · [Skills, routines, and automations](https://docs.x.ai/grok-bot/skills-routines-and-automations) · [Security and privacy](https://docs.x.ai/grok-bot/approvals-security-and-privacy) · [Plans and billing](https://cursor.com/help/grok-bot/plans)

## Grok.com — general-purpose assistant

**Official product:** [Grok.com](https://grok.com/) · [Official documentation](https://docs.x.ai/grok/overview)

Grok.com is xAI’s standalone assistant, available on the web and in mobile apps. It provides conversational help, image and video creation, voice, file analysis, and connectors to services such as email, files, and calendar. Its paid SuperGrok plans share a weekly usage allowance across eligible products. Grok.com is a chat and assistant service; it is not the Grok Bot product described above, where persistent cloud-computer agents perform multi-step work in tools. See [Grok overview](https://docs.x.ai/grok/overview), [usage FAQ](https://docs.x.ai/grok/faq), and [plans](https://x.ai/pricing).

**Official references:** [Grok.com](https://grok.com/) · [Grok overview](https://docs.x.ai/grok/overview) · [FAQ and usage](https://docs.x.ai/grok/faq) · [Plans and pricing](https://x.ai/pricing)

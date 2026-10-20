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

**Product identified:** [Muse](https://muse.ai/) is Meta’s personal AI agent, distinct from [Muse Code](https://dev.meta.ai/products/muse-code) and from a model/API offering. It is designed for multi-step everyday tasks: browse, use connected services, prepare documents or images, track goals, and continue work in the background. It runs tasks in a persistent, isolated cloud Linux VM with a browser; users interact through mobile or Mac apps, or WhatsApp. See [Meta’s product page](https://ai.meta.com/muse/) and [launch announcement](https://about.fb.com/news/2026/09/introducing-muse-personal-ai-agent/).

Meta describes user-controlled permissions and a Sentinel component for authorization. These controls do not guarantee that outputs or actions are always correct; the terms caution that results, execution, and availability may vary. The product and subscriptions are in limited testing and may not be available in every region.

**Price and usage.** The free tier has a usage limit, but the checked subscription page does not give a universal numeric allowance. Paid plans are listed as Power at $20/month for 500M Muse tokens/week and Maximum at $100/month for 3B Muse tokens/week. Availability and benefits can vary by account and region. Muse is not described as a public model API; do not apply Muse Code or Meta API pricing to it. See [subscription details](https://www.meta.com/help/subscriptions/1021145227643680/).

**Official references:** [Muse](https://muse.ai/) · [Features and FAQ](https://ai.meta.com/muse/) · [Launch announcement](https://about.fb.com/news/2026/09/introducing-muse-personal-ai-agent/) · [Subscriptions](https://www.meta.com/help/subscriptions/1021145227643680/) · [Security design](https://security.muse.ai/) · [Terms](https://muse.ai/terms) · [Muse Code](https://dev.meta.ai/products/muse-code)

## Grok in X — conversational assistant

**Official resource:** [About Grok — X Help](https://help.x.com/en/using-x/about-grok)

Grok in X is the assistant integrated into the X website and mobile apps. It can answer questions, brainstorm, and use public X posts or live web search for context. It is a conversational assistant, not the same product as Grok.com’s cloud-computer agent. X cautions that answers can be incorrect or omit context; verify important claims. X also describes privacy controls for data sharing with xAI.

**Price and limits.** X lists Grok access across free and paid subscription plans, with usage limits depending on tier and activity. The current plan structure is a combined X subscription, so the exact allowance is not a fixed public prompt quota. Legacy X Premium plans may continue under earlier terms for existing subscribers. See [xAI pricing](https://x.ai/pricing), [usage limits](https://docs.x.ai/x-subscription/usage-limits), and [X Premium](https://help.x.com/en/using-x/x-premium).

**Official references:** [About Grok](https://help.x.com/en/using-x/about-grok) · [About X Chat](https://help.x.com/en/using-x/about-chat) · [X subscriptions](https://x.ai/pricing) · [Usage limits](https://docs.x.ai/x-subscription/usage-limits)

## Grok.com — cloud-computer agent

**Official product:** [Grok.com](https://grok.com/)

Grok.com is xAI’s standalone consumer service, available on the web and in mobile apps. In addition to chat, it provides file analysis, voice, connectors, and image/video creation. It also offers agentic workflows. The distinct **Grok Bot** product runs named agents on persistent cloud computers with a browser, filesystem, and terminal. These agents can perform multi-step tasks, continue while a user’s computer is closed, and request approval. This cloud-computer workflow differs from ordinary Grok chat in X. See [Grok overview](https://docs.x.ai/grok/overview) and [Grok Bot overview](https://docs.x.ai/grok-bot/overview).

**Price and limits.** The standalone service has a free plan with limited usage and paid plans; xAI currently presents these as a combined X Subscription. Listed tiers include Free ($0/month), Plus ($8/month), Premium ($30/month), Super ($100/month), and Ultra ($200/month). Paid usage is shared in a weekly pool across eligible features. Allowances vary by activity, and prices exclude possible tax/fees. Grok Bot eligibility and usage are tier-dependent; check the current plan page. See [pricing](https://x.ai/pricing) and [subscription overview](https://docs.x.ai/x-subscription/overview).

**API is separate.** xAI’s developer API is metered separately from consumer subscriptions and weekly usage. Paid consumer plans may grant API access, but API calls use standard API billing. The docs do not promise a general free API tier. See [API quickstart](https://docs.x.ai/developers/quickstart), [pricing](https://docs.x.ai/developers/pricing), and [rate limits](https://docs.x.ai/developers/rate-limits).

**Official references:** [Grok.com](https://grok.com/) · [Grok overview](https://docs.x.ai/grok/overview) · [Plans and pricing](https://x.ai/pricing) · [Usage FAQ](https://docs.x.ai/grok/faq) · [Grok Bot](https://docs.x.ai/grok-bot/overview) · [Grok Build](https://docs.x.ai/build/overview) · [API quickstart](https://docs.x.ai/developers/quickstart) · [API pricing](https://docs.x.ai/developers/pricing) · [X Help: Grok in X](https://help.x.com/en/using-x/about-grok)

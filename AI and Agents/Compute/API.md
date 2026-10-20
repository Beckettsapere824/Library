# API Resources

Pricing and free-tier details checked on 2026-10-20. Provider rates and quotas can change; use the linked live documentation before deployment or budgeting.

## Mistral API — free tier

**Official product:** [Mistral Studio / API](https://docs.mistral.ai/studio)

Mistral’s cloud API provides access to hosted models for applications and agents. It supports chat completions, streaming, JSON and JSON-schema output, function/tool calling, and prompt caching. The wider catalog includes text and vision models, code, embeddings, OCR, speech transcription and text-to-speech, and moderation. See the [API reference](https://docs.mistral.ai/api) and [model catalog](https://docs.mistral.ai/models). Model availability can vary by account.

**Free tier and limits.** Mistral documents a limited free mode for new accounts, with API access and no credit card required. Free usage is intended for evaluation and prototyping. The monthly allowance is shared across Studio, API, and Vibe Code; when it runs out, usage stops unless prepaid pay-as-you-go is enabled. Mistral does not publish one fixed public numeric quota: check **API → Limits** in Studio for the workspace’s current RPS, token/minute, and monthly limits. Limits are shared by API keys in a workspace. See [account setup](https://docs.mistral.ai/getting-started/quickstarts/studio/activate-and-generate-api-key), [usage limits](https://docs.mistral.ai/admin/billing-usage/usage-limits), and [workspace limits](https://docs.mistral.ai/admin/workspaces/usage-limits).

**Paid pricing.** The official [inference pricing page](https://docs.mistral.ai/inference/pricing) lists per-million-token rates for standard regional inference: Large 3 $0.50 input / $1.50 output; Medium 3.5 $1.50 / $7.50; Small 4 $0.15 / $0.60; Ministral 3 14B $0.20 / $0.20, 8B $0.15 / $0.15, and 3B $0.10 / $0.10; Codestral $0.30 / $0.90. OCR 4.1 is listed at $4 per 1,000 pages; Voxtral Mini Transcribe 2 at $0.003 per minute; Voxtral TTS at $16 per million output characters; Mistral Moderation 2 is listed as free. Batch and cached-input discounts or other service tiers can affect cost. Check the live page before use.

**Official references:** [API pricing](https://docs.mistral.ai/inference/pricing) · [Studio API key setup](https://docs.mistral.ai/getting-started/quickstarts/studio/activate-and-generate-api-key) · [Usage limits](https://docs.mistral.ai/admin/billing-usage/usage-limits) · [Workspace limits](https://docs.mistral.ai/admin/workspaces/usage-limits) · [Models](https://docs.mistral.ai/models) · [API reference](https://docs.mistral.ai/api)

## Groq API — free tier

**Official product:** [GroqCloud API documentation](https://console.groq.com/docs/overview)

GroqCloud is a hosted inference API for language and audio models. It is largely compatible with OpenAI client libraries and uses the base URL `https://api.groq.com/openai/v1`; keys are managed in the [Groq Console](https://console.groq.com/docs/quickstart). The API supports chat, Responses, image inputs on supported models, function calls, remote MCP, and selected built-in web-search and code-execution tools. The [model catalog](https://console.groq.com/docs/models) lists model-specific context, output, and file limits. Vendor-reported tokens/second figures are not independent benchmarks.

**Free tier and limits.** Groq documents a quota-limited Free Plan rather than a fixed free-dollar balance. Example free-plan quotas for GPT-OSS 20B/120B are 30 requests/minute, 1,000 requests/day, 8,000 tokens/minute, and 200,000 tokens/day. Limits are model-specific, per organization, and the first exhausted quota applies; the account’s Limits page is authoritative. See [rate limits](https://console.groq.com/docs/rate-limits). Free use is suitable for experimentation, not guaranteed production capacity.

**Paid pricing.** The Developer tier is pay-as-you-go and requires a valid payment method. The [model catalog](https://console.groq.com/docs/models) lists, for example, GPT-OSS 20B at $0.075 input / $0.30 output per million tokens and GPT-OSS 120B at $0.15 / $0.60. Some models require contacting sales. [Batch API](https://console.groq.com/docs/batch) is asynchronous and is documented at a 50% discount from synchronous pricing. Check current model prices and quotas before estimating costs.

**Compatibility note.** OpenAI compatibility is not exact. Groq lists unsupported request fields such as `logprobs`, `logit_bias`, and `top_logprobs` for text completions; `n` must be 1. See [OpenAI compatibility](https://console.groq.com/docs/openai).

**Official references:** [API overview](https://console.groq.com/docs/overview) · [Quickstart](https://console.groq.com/docs/quickstart) · [Models and pricing](https://console.groq.com/docs/models) · [Rate limits](https://console.groq.com/docs/rate-limits) · [Billing FAQ](https://console.groq.com/docs/billing-faqs) · [Tool use](https://console.groq.com/docs/tool-use) · [Batch API](https://console.groq.com/docs/batch)

## DeepSeek API — paid API

**Official product:** [DeepSeek API Platform](https://platform.deepseek.com/) · [API documentation](https://api-docs.deepseek.com/)

DeepSeek provides hosted language models for applications and agents, with OpenAI- and Anthropic-compatible formats. API access requires a bearer API key. See the [API overview](https://api-docs.deepseek.com/) and [authentication guide](https://api-docs.deepseek.com/api/deepseek-api/).

**Models and capabilities.** The docs list `deepseek-flash` and `deepseek-v4-pro`, each with a 1M-token context and up to 384K output tokens. Both support JSON output, function/tool calls, the Responses API, and an Anthropic-compatible API. Flash supports vision; V4 Pro does not. These are vendor specifications rather than a guarantee that every application workflow can use the full context or output limits. See [model and pricing details](https://api-docs.deepseek.com/quick_start/pricing/) and [tool calls](https://api-docs.deepseek.com/guides/tool_calls).

**Availability and limits.** Default per-account concurrency is documented as 2,500 for Flash and 500 for V4 Pro; excess requests receive HTTP 429. Higher capacity can be requested. Separate Search and Fetch APIs are listed at 100 QPS and 25 QPS respectively. See [rate limits](https://api-docs.deepseek.com/quick_start/rate_limit) and [Search & Fetch](https://api-docs.deepseek.com/guides/search).

**Pricing.** The API is metered; the checked official pages do not promise a generally available free API tier. Prices below are USD per million tokens, shown as **off-peak / peak**; peak windows are specified in the official [pricing page](https://api-docs.deepseek.com/quick_start/pricing/).

| Model | Cached input | Uncached input | Output |
|---|---:|---:|---:|
| `deepseek-flash` | $0.003 / $0.006 | $0.15 / $0.30 | $0.60 / $1.20 |
| `deepseek-v4-pro` | $0.022 / $0.044 | $0.66 / $1.32 | $1.98 / $3.96 |

Search and Fetch are listed at $0.75 per 1,000 successful requests. The docs describe a temporary waiver for certain server-side integrations, with charges due to begin 2026-11-01 Beijing time. Check the live pricing and billing terms before use.

**Official references:** [API docs](https://api-docs.deepseek.com/) · [Models and pricing](https://api-docs.deepseek.com/quick_start/pricing/) · [Rate limits](https://api-docs.deepseek.com/quick_start/rate_limit) · [Search & Fetch](https://api-docs.deepseek.com/guides/search) · [Tool calls](https://api-docs.deepseek.com/guides/tool_calls) · [Balance API](https://api-docs.deepseek.com/api/get-user-balance/)

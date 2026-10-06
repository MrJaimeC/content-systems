# Carousel News Blacklist

Temporary blocklist for Jaime's daily carousel preapproval.

Use this before recommending `NOTICIA`. If a candidate story matches a blocked URL, product, company cluster, or macro-angle, reject it and pick another news item or the topic bank.

## Active Temporary Blocks

### 2026-07-15 to 2026-07-25: Agents Inside Real Work

- Macro-angle: AI agents moving from chat into real work, workplace agents, operational coworkers, long-running task agents, human approval loops, agent governance, agent economy, agents in documents/apps/files, or "AI as coworker".
- Companies/products covered by this block: OpenAI ChatGPT Work, OpenAI GPT-5.6/Codex multi-agent, Anthropic Claude Cowork, Claude/Fable agent economy, Notion Agents, Workspace Agents, Google/Gemini managed agents when the angle is "agents inside work".
- Blocked example URLs:
  - `https://openai.com/index/chatgpt-for-your-most-ambitious-work/`
  - `https://openai.com/index/gpt-5-6/`
  - `https://www.anthropic.com/claude/fable`
  - `https://claude.com/blog/cowork-web-mobile`
  - `https://claude.com/product/cowork`
  - `https://www.notion.com/releases`
- Reason: Jaime was repeatedly pitched the same macro-story across 2026-07-09 to 2026-07-15 despite different sources and wrappers.
- Rule: only override this block if Jaime explicitly asks for that exact story or the news is materially different from "agents entering real workflows". Document the override in the approval message.

## Recently Used Or Proposed

- 2026-07-09: Notion Agents / agents in workflows. Used.
- 2026-07-10: Claude Cowork web and mobile / operational coworker. Used.
- 2026-07-11: GPT-5.6, Codex and Claude Fable / agent economics. Used.
- 2026-07-12: ChatGPT Work / long-running work with apps, files and human approval. Used.
- 2026-07-14: Same agent-work macro-angle was proposed again and Jaime rejected the repetition.
- 2026-07-15: ChatGPT Work was proposed again by the cron and rejected as repeated.
- 2026-07-15: Canva Code 2.0 available to all was used as a carousel route. URL: `https://www.canva.com/newsroom/news/Canva-Code/`.
- 2026-09-16: Meta One subscriptions for creators and businesses was used. URL: `https://about.fb.com/news/2026/09/introducing-meta-one-subscription-service-more-features-ai/`.
- 2026-09-17: ChatGPT Ads as a conversational acquisition and sales channel was used. URL: `https://openai.com/index/reimagining-advertising-with-ai/`.
- 2026-09-20: AI Act enforcement, AI Board coordination and market surveillance readiness was used. URL: `https://digital-strategy.ec.europa.eu/en/news/ai-board-holds-its-ninth-meeting`.

## Selection Rules

1. Build a short "recently burned" list from this file, `/Users/bumblebee/Desktop/leadmagnets/*.md`, and `outbox/**/brief*.md`.
2. Reject exact repeated URLs for 30 days.
3. Reject repeated macro-angles for 10 days, even if the company/source is different.
4. Prefer a different territory when news is otherwise strong: creative production, education, marketing ops, analytics, pricing/spend, security/privacy, no-code builders, CRM/sales ops, customer support, or content systems.
5. In every preapproval, include one line explaining why the recommended news is not blocked by the recent blacklist.

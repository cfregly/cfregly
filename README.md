## Chris Fregly

AI startup founder & advisor · ex-AWS, Databricks, Netflix · 3× O'Reilly author · ~500K DeepLearning.AI learners

I turn founder trust into working code, measured activation, and retention. Strategic and hands-on. Two hires for the price of one.

### The Founder's Playbook, as one runnable kit

Anthropic's Founder's Playbook tells a founder what to do at each stage and ships no tool. **[claude-founder-kit](https://github.com/cfregly/claude-founder-kit)** is that tool: the whole journey in one repo, one `make demo`, every step a real Claude call.

| Stage (module) | What it proves (measured) |
|---|---|
| `idea/` | Pitch in to a PMF path, the platform-risk answer (why not the frontier labs or the cloud), the Relationship to Activation to Retention loop weakest stage first, and a Sequoia-arc deck builder and linter. Sloppy deck 0/100 fails CI, sharp 100/100 |
| `mvp/` | First Claude call, tools, evals, cost from 22 cents to 3 cents live (down 86%), MCP, then a security review that takes a vague MCP server 14 to 100 with an OWASP and STRIDE lens. Caught my own demo server at 77 |
| `launch/` | Capture activation events on one durable org_id (local JSONL, PostHog, Statsig, or Amplitude), measure the funnel, time-to-second-build, and the leaky-bucket flag, surface the accounts ready for a GTM handoff, and run the gated weekly report on a schedule |
| `scale/` | The same loop at cohort scale: product-qualified accounts handed to a named GTM owner with week-over-week deltas, plus the compound-data moat that grows with each cohort |
| `quality/` | The de-slop linter every document in this repo, my deck, and my resume passes |
| `cost/` | The Claude platform cost levers in one place: prompt caching, context editing, tool search, programmatic tool calling, adaptive thinking, token counting, and Batches, each read off the usage object |

One clone, one `make demo`, idea to scale. Online-only: every demo is a real Claude call and fails fast without a key. The eight skills install from `.claude/skills/`.

**Platform deep-dives, also public:** [claude-memory](https://github.com/cfregly/claude-memory) (the memory tool plus a dreaming consolidation loop on one backend), [claude-grounding](https://github.com/cfregly/claude-grounding) (web search, fetch, citations, files), [claude-managed-agents](https://github.com/cfregly/claude-managed-agents) (the Managed Agents surface), and claude-gpu-perf-tune (GPU-inference cost, one layer below the API). Each runs in one command and ships a Skill.

Every demo runs Claude (`claude-opus-4-8` or the right rung of the ladder) on a real call and fails loud without a key. The deterministic gates (the de-slop rule score, the doc-correctness checks) reproduce in CI: Claude does the judgment, the gate proves it.

Each module installs as a Claude Skill: upload it in Claude (Settings > Capabilities > Skills) and say the trigger phrase, no clone required.

### The throughline

I make the cost of intelligence legible (unit economics, caching, model routing, GPU tuning). I answer platform risk the way a founder who got AWS'd has to: own the data, the workflow, and the distribution, and ship MCP so nobody is locked in. And I measure everything: every claim above is a reproducible before-and-after, not an adjective.

The spine: for an AI product, activation into retention is the growth problem that decides who survives, so the kit's `launch` module ships that loop as runnable code, from event capture through the funnel to a gated weekly report.

### Elsewhere

3× O'Reilly author · ~500K DeepLearning.AI learners (*Generative AI with LLMs*: 437K+ enrolled) · 100K meetup members across 20 AI Performance Engineer groups worldwide · [YouTube: @AIPerformanceEngineering](https://youtube.com/@AIPerformanceEngineering)

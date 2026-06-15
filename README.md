## Chris Fregly

AI startup founder & advisor · ex-AWS, Databricks, Netflix · 3× O'Reilly author · ~500K DeepLearning.AI learners

I turn founder trust into working code, measured activation, and retention. Strategic and hands-on. Two hires for the price of one.

### The founder-to-builder demo set

One repo per stage of the journey I run with founders, every number reproducible and CI-gated:

| Stage | Repo | What it proves (measured) |
|---|---|---|
| Diagnose the company | [claude-startup-linter](https://github.com/cfregly/claude-startup-linter) | Pitch in → PMF path, the platform-risk answer (why not the frontier labs or the cloud), and the Relationship → Activation → Retention loop, weakest stage first |
| Build the product | [claude-prompt-to-production](https://github.com/cfregly/claude-prompt-to-production) | First Claude call → tools → evals 8/8 → cost $0.22 to $0.03 live (−86%) → MCP |
| Build the raise | [claude-pitch-deck-linter](https://github.com/cfregly/claude-pitch-deck-linter) | Sequoia-arc deck builder + linter. Sloppy 0/100 fails CI, sharp 100/100 |
| Harden the agent | [claude-agent-linter](https://github.com/cfregly/claude-agent-linter) | Vague MCP server 14 → 100, CI-gated, plus an OWASP/STRIDE security lens. Caught my own demo server at 77 |
| Measure the activation | [claude-activation-loop](https://github.com/cfregly/claude-activation-loop) | Founder cohort → funnel, time-to-second-build, leaky-bucket flag, and the product-qualified accounts ready for a GTM handoff. Activation as attributable code |
| Operate the loop | [claude-operator-loop](https://github.com/cfregly/claude-operator-loop) | Activation readout → a gated plan and a morning report. Measurement runs unattended; the nudge and the GTM handoff wait for approval, and a CI audit proves nothing outward-facing auto-ran |
| Tune performance | [claude-perf-tune](https://github.com/cfregly/claude-perf-tune) | 31 GPU-inference profiling and optimization skills with a bundled MCP server. The cost-of-intelligence work, measured not asserted |

Every repo runs its headline result in one command: clone, then `make demo`, no API key needed. Each ships a `CLAUDE.md` so an agent can run and extend it.

The six lifecycle repos each install as a Claude Skill: upload it in Claude (Settings > Capabilities > Skills) and say the trigger phrase, no clone required.

Running through all of it: **[claude-deslop](https://github.com/cfregly/claude-deslop)**, the credibility gate. One synced ruleset keeps AI tells (em-dashes, buzzwords, the generated look) out of every repo above, this profile, my deck, and my resume. They all pass it.

### The throughline

I make the cost of intelligence legible (unit economics, caching, model routing, GPU tuning). I answer platform risk the way a founder who got AWS'd has to: own the data, the workflow, and the distribution, and ship MCP so nobody is locked in. And I measure everything: every claim above is a reproducible before/after, not an adjective.

### Elsewhere

3× O'Reilly author · ~500K DeepLearning.AI learners (*Generative AI with LLMs*: 437K+ enrolled) · 100K meetup members across 20 AI Performance Engineer groups worldwide · [YouTube: @AIPerformanceEngineering](https://youtube.com/@AIPerformanceEngineering)

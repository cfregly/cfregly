## Chris Fregly

AI startup founder & advisor · ex-AWS, Databricks, Netflix · 3× O'Reilly author · ~500K DeepLearning.AI learners

I turn founder trust into working code, measured activation, and retention. Strategic and hands-on. Two hires for the price of one.

### The Founder's Playbook, as runnable tools

Anthropic's Founder's Playbook tells a founder what to do at each stage and ships no tool. These six repos are the runnable, forkable per-stage tool, one per stage plus two disciplines that run at every stage. The playbook prescribes the measurement framework and the weekly metrics brief but ships no instrumentation, which is what claude-startup-launch is. Every number reproducible and CI-gated.

**Idea**, validate before you build (and raise):

| Repo | What it proves (measured) |
|---|---|
| [claude-startup-idea](https://github.com/cfregly/claude-startup-idea) | Pitch in → PMF path, the platform-risk answer (why not the frontier labs or the cloud), the Relationship → Activation → Retention loop weakest stage first, and a Sequoia-arc deck builder + linter for the raise. Sloppy deck 0/100 fails CI, sharp 100/100 |

**MVP**, build, then a security review before any user:

| Repo | What it proves (measured) |
|---|---|
| [claude-startup-mvp](https://github.com/cfregly/claude-startup-mvp) | First Claude call → tools → evals 8/8 → cost $0.22 to $0.03 live (−86%) → MCP, then a security review that takes a vague MCP server 14 → 100, CI-gated, with an OWASP/STRIDE lens. Caught my own demo server at 77 |

**Launch**, turn traction into a growth engine that runs without founder bottlenecks:

| Repo | What it proves (measured) |
|---|---|
| [claude-startup-launch](https://github.com/cfregly/claude-startup-launch) | Capture developer activation events on one durable org_id (local JSONL, PostHog, Statsig, or Amplitude), measure the funnel, time-to-second-build, and the leaky-bucket flag, surface the product-qualified accounts ready for a GTM handoff, and run the gated weekly report on a schedule. Capture, measure, and operate as one system. The meaning underneath is Relationship → Activation → Retention |

**Scale**, the GTM function and the compound-data moat:

| Repo | What it proves (measured) |
|---|---|
| [claude-startup-scale](https://github.com/cfregly/claude-startup-scale) | The same loop at cohort scale: product-qualified accounts handed to a named GTM owner with week-over-week deltas and a gated handoff, plus the compound-data moat that grows with each cohort. The meaning underneath is Relationship → Activation → Retention |

**Every stage**, the quality gate and the cost gate:

| Repo | What it proves (measured) |
|---|---|
| [claude-deslop](https://github.com/cfregly/claude-deslop) | One synced ruleset keeps AI tells (em-dashes, buzzwords, the generated look) out of every repo above, this profile, my deck, and my resume. They all pass it |
| [claude-cost-control](https://github.com/cfregly/claude-cost-control) | The Claude platform cost levers in one place: prompt caching, context editing, tool search, programmatic tool calling, adaptive thinking, token counting, and Batches, each with its request shape and the savings read off the usage object |

**Five standalone deep-dives are also public** (not pinned): claude-context-grounding (web search, fetch, citations, files), claude-io (structured outputs and the memory tool), claude-managed-agents (the full Managed Agents surface), claude-dreaming-loop (a memory-consolidation loop on GA primitives), and claude-gpu-perf-tune (GPU-inference cost, one layer below the API). Each runs in one command and ships a Skill.

Every repo runs its headline result in one command and ships a `CLAUDE.md` so an agent can run and extend it. In the four stage repos the generative work is `claude-opus-4-8` on every real run, drafting the founder message, writing the activation brief, diagnosing the company, rewriting the worst tool, and proposing the next experiment, and those generative steps fail loud without a key. The two disciplines are the gates: claude-deslop is deterministic, and claude-cost-control runs every lever live and reads the real saving off the usage object. A deterministic gate verifies the output and reproduces in CI: Claude does the judgment, the gate proves it.

Each repo installs as a Claude Skill: upload it in Claude (Settings > Capabilities > Skills) and say the trigger phrase, no clone required.

### The throughline

I make the cost of intelligence legible (unit economics, caching, model routing, GPU tuning). I answer platform risk the way a founder who got AWS'd has to: own the data, the workflow, and the distribution, and ship MCP so nobody is locked in. And I measure everything: every claim above is a reproducible before/after, not an adjective.

The spine: for an AI product, activation into retention is the growth problem that decides who survives, so claude-startup-launch ships that loop as runnable code, from event capture through the funnel to a gated weekly report.

### Elsewhere

3× O'Reilly author · ~500K DeepLearning.AI learners (*Generative AI with LLMs*: 437K+ enrolled) · 100K meetup members across 20 AI Performance Engineer groups worldwide · [YouTube: @AIPerformanceEngineering](https://youtube.com/@AIPerformanceEngineering)

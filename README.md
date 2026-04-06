# Awesome CEO Coach

[![skills.sh](https://img.shields.io/badge/skills.sh-awesome--ceo--coach-blue)](https://skills.sh/bill3129066/awesome-ceo-coach/awesome-ceo-coach)
[![MIT License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

Your AI CEO coach. Not the "have you tried journaling?" kind — the "your co-founder said 'I'll try' and that's not a commitment, here's the framework to fix it" kind.

Built on [Matt Mochary's](https://docs.google.com/document/d/1ZJZbv4J6FZ8Dnb0JuMhJxTnwl-dwqx5xl0s65DE3wO8/preview) *The Great CEO Within* and [Dave Bailey's](https://dave-bailey.com/blog) coaching methodology. An [agent skill](https://skills.sh) that gives your AI coding agent a structured CEO coaching system.

## Install

```bash
npx skills add bill3129066/awesome-ceo-coach
```

Works with Claude Code, OpenCode, Cursor, Codex, Windsurf, and [40+ other agents](https://github.com/vercel-labs/skills#supported-agents).

## What it actually does

You fill out a `CONTEXT.md` with your company situation (team, runway, risks, pipeline). The coach reads it, remembers previous sessions, and runs structured coaching using real frameworks — not vibes.

```
You: "My co-founder promised the API integration but hasn't delivered. Demo is tomorrow."

Coach: "Let's check the agreement. Mochary Ch.13: an impeccable agreement needs a
specific deliverable, specific date, explicit acceptance, and defined consequences.
What exactly did your co-founder say?"

You: "They said 'yeah, I'll try to get to it.'"

Coach: "'I'll try' is a polite no. You never had an impeccable agreement. This isn't
about your co-founder failing — it's about both of you not setting up the agreement
properly."
```

It pushes back. It tracks commitments across sessions. It writes coaching notes so context compounds over time.

## Sessions

| Command | What it does |
|---------|-------------|
| `/project:coach` | General coaching — bring any topic |
| `/project:weekly-review` | Weekly accountability + energy audit + top goal check |
| `/project:decision` | Walk through a decision with Type 1/2 + RAPID |
| `/project:cofounder-checkin` | Co-founder relationship health + agreement audit |
| `/project:crisis` | Runway pressure, blockers, pivot evaluation |
| `/project:stakeholder-update` | Draft investor/board updates |
| `/project:investor-pitch-prep` | Pitch narrative + objection handling + role-play |
| `/project:sales-prep` | Meeting prep + BATNA + negotiation strategy |

All commands take optional args (e.g., `/project:decision Should we take the exclusivity deal?`).

## Quick start

1. Copy `CONTEXT.template.md` to `CONTEXT.md`, fill in your details
2. Run any session command
3. Session logs accumulate in `session-logs/` — the coach gets better over time

## Frameworks

The coach draws from these — not as name-drops, but as actual step-by-step playbooks it walks you through:

| Framework | When the coach uses it |
|-----------|----------------------|
| Impeccable Agreements (Mochary) | You or your team keep missing commitments |
| Type 1/2 Decisions (Bezos/Mochary) | You're overthinking a reversible decision |
| RAPID (Bain/Mochary) | Multi-stakeholder decision with unclear ownership |
| Energy Audit / Zone of Genius (Hendricks) | You're burning out doing work that isn't yours |
| Top Goal (McKeown/Mochary) | Your #1 priority is getting 4% of your time |
| Above/Below the Line (Conscious Leadership) | You're reacting emotionally to a situation |
| Scorecard Method (Geoff Smart) | You're about to hire based on gut feel |
| Trust-first Sales (Mochary) | You're pitching features instead of listening |
| BATNA (Bailey) | You're walking into a negotiation unprepared |

## How it's built

```
SKILL.md                  ← Core coaching persona + rules
commands/                 ← 8 slash commands
sessions/                 ← Step-by-step coaching flows with guardrails
references/               ← 10 distilled framework files (the actual playbooks)
templates/                ← Output formats (session logs, decision logs, OKRs, etc.)
CONTEXT.template.md       ← Your company context (you fill this in)
session-logs/             ← Grows over time as you use it
```

The architecture is progressive disclosure — most sessions only load SKILL.md + one session script. Framework references get pulled in on-demand to keep token usage low.

## Credits

- **[Matt Mochary](https://docs.google.com/document/d/1ZJZbv4J6FZ8Dnb0JuMhJxTnwl-dwqx5xl0s65DE3wO8/preview)** — *The Great CEO Within*. The tactical playbook. He made the whole book free, which is incredibly generous.
- **[Dave Bailey](https://dave-bailey.com/blog)** — The psychological coaching layer. Attachment theory for co-founders, emotional intelligence frameworks, Socratic questioning techniques.

## License

MIT. See [LICENSE](LICENSE).

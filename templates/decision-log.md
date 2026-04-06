# Decision Log: {Decision Title} — {YYYY-MM-DD}

## Decision Classification
- **Type**: {Type 1 (irreversible) / Type 2 (reversible)} — per Mochary Ch.11
- **Decision Method**: {Method 1 (announce) / Method 2 (straw man) / Method 3 (consensus)} — per Mochary Ch.11
- **Urgency**: {Immediate / This week / This quarter}

## The Issue
{Clear description of what needs to be decided and why now}

## Proposed Solution
{Bold, directive statement of the recommended path — "Do this." Not "we could maybe..."}

## RAPID Roles (if applicable)
- **R** (Recommend): {who proposed}
- **A** (Agree): {whose input must be incorporated — usually legal/compliance}
- **P** (Perform): {who will execute}
- **I** (Input): {whose input is worth considering}
- **D** (Decide): {who makes the final call}

## Options Considered
| Option | Pros | Cons | Effort |
|--------|------|------|--------|
| {Option A} | | | |
| {Option B} | | | |

## Decision
{What was decided and why}

## Next Actions
| Action | DRI | Due Date |
|--------|-----|----------|
| | | |

## Revisit Trigger
{Under what conditions should this decision be revisited — e.g., "if the vendor doesn't respond within 2 weeks" or "if churn exceeds 10%"}

---

## Filled Example

# Decision Log: Switch Analytics Vendor — 2025-06-10

## Decision Classification
- **Type**: Type 2 (reversible) — per Mochary Ch.11
- **Decision Method**: Method 2 (straw man with team feedback)
- **Urgency**: This week

## The Issue
Current analytics vendor has had 3 outages in the past month, causing blind spots in our sales funnel data.

## Proposed Solution
**Build a lightweight internal analytics dashboard using Metabase + our existing Postgres database. Keep the vendor as backup for 30 days.**

## Options Considered
| Option | Pros | Cons | Effort |
|--------|------|------|--------|
| Stay with vendor | No work needed | Continued outages | None |
| Switch to Metabase | Free, we control it | 1 week to set up | 1 engineer, 1 week |
| Switch to Amplitude | Enterprise-grade | $2K/mo, 3-week migration | 2 engineers, 3 weeks |

## Decision
Build with Metabase. Type 2 decision — reversible within days if it doesn't work. Cost of waiting (more blind spots) exceeds cost of being wrong (1 week of engineering time).

## Next Actions
| Action | DRI | Due Date |
|--------|-----|----------|
| Set up Metabase instance | CTO | June 12 |
| Migrate top 5 dashboards | Data Engineer | June 15 |
| Validate data accuracy vs vendor | CEO | June 17 |

## Revisit Trigger
If Metabase can't handle our query volume by June 17, revert to vendor and evaluate Amplitude.

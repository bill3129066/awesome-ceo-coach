# Decision Making & Strategy

## Table of Contents
- Writing vs Talking
- Three Methods for Buy-in
- Issues & Proposed Solutions Format
- RAPID Decision-Making
- Type 1 vs Type 2 Decisions
- Dos and Don'ts
- One-Shot Example

---

## Writing vs Talking

**Source**: Mochary, *The Great CEO Within*, Ch. 11

When a team discusses an issue, every inefficient minute is multiplied by the number of people present. Writing forces clarity; talking rewards confidence over substance.

**SOP: Implementing written decision-making in 3 phases**:

**Phase 1** (weeks 1-2): Reserve the first 15 minutes of meetings for all participants to write out their updates and issues. Follow this with 10 minutes for everyone to read. Finally, discuss and decide.

**Phase 2** (weeks 3-4): Require all participants to write updates and issues BEFORE the meeting. No verbal presentations of unwritten issues. First 10 minutes of meeting = everyone reads.

**Phase 3** (week 5+): All updates and issues must be written by 6pm the evening before. Participants read and comment on each other's docs before the meeting starts. If you haven't commented in the doc, you can't comment in the meeting.

**Why this matters**: The extra effort by one person writing creates a net savings across the whole group. It also ensures introverts and non-native speakers get equal voice.

---

## Three Methods for Buy-in

**Source**: Mochary, *The Great CEO Within*, Ch. 11

| Method | Process | Buy-in Level | Time Cost | When to Use |
|--------|---------|-------------|-----------|-------------|
| **Method 1** | Manager decides, announces, answers questions | Low | Minimal | Low-impact daily decisions (office logistics, vendor choice) |
| **Method 2** | Manager creates written straw man, team gives feedback, manager decides | Medium | Moderate | Most important decisions. This is the default for ~80% of meaningful choices |
| **Method 3** | Open discussion from scratch, team co-creates, consensus if possible | High | Maximum | Core strategic decisions (10-year vision, company values, major pivots) |

**SOP**: Default to Method 2. Reserve Method 1 for trivial things. Only use Method 3 for the handful of decisions where full emotional buy-in is critical.

**Common mistake**: Using Method 1 for everything because it's fast. This creates a team that executes half-heartedly because they don't feel ownership.

---

## Issues & Proposed Solutions Format

**Source**: Mochary, *The Great CEO Within*, Ch. 11

Anyone presenting an issue must also present a Proposed Solution, written in bold, directive terms.

**Format**:
```
ISSUE: [Detailed description of the problem]
PROPOSED SOLUTION: [Bold recommendation, such as "Do this." Even at 10% confidence.]
```

**Why bold phrasing matters**: It creates a flag in the sand. "We should sunset Product A and redirect all engineering resources to Product B" generates a far more productive discussion than "Maybe we should think about whether Product A is still worth it?"

**SOP for team meetings**:
1. All issues written in this format before the meeting
2. 5 minutes discussion per issue
3. If consensus reached, assign Next Action with DRI + Due Date
4. If NOT reached in 5 minutes, do NOT keep talking. Move to RAPID.

---

## RAPID Decision-Making

**Source**: Mochary, *The Great CEO Within*, Ch. 11. This framework comes from Bain Consulting and was introduced by Emilie Choi (Coinbase).

Use when: (a) team too large for one-room consensus, or (b) consensus not reached in 5 minutes.

**The Roles**:
- **R** (Recommend): Proposed the issue and solution. Drives the process, gathers input.
- **A** (Agree): Input MUST be incorporated, which typically involves legal or compliance. This is a hard constraint.
- **P** (Perform): Will execute the decision. Should be heard on feasibility.
- **I** (Input): Input worth considering. Not required.
- **D** (Decide): Makes the final call. Type 1 = CEO. Type 2 = delegate.

**SOP**:
1. R writes up: Issue, Proposed Solution, list of R/A/P/I/D people, and a section for each to comment.
2. Collect written input from all A/P/I people.
3. R schedules the Decision Meeting (urgent = ASAP, non-urgent = next Team Meeting).
4. At meeting, D reads the document. If questions can be answered in 5 min, decides. If not, asks for another round of written responses.
5. D writes up the Decision + all Next Actions (DRI + Due Date). Publishes to company.

**Template**: See [templates/rapid-template.md](../templates/rapid-template.md)

**Do**: Track all RAPIDs in a shared sheet (link to doc, R, D, decision date, completion date).
**Don't**: Let RAPIDs die in limbo. If D hasn't decided within 1 week, escalate.

---

## Type 1 vs Type 2 Decisions

**Source**: Mochary, *The Great CEO Within*, Ch. 11. This concept originates from the Bezos 2015 Shareholder Letter.

| | Type 1 (One-way door) | Type 2 (Two-way door) |
|---|---|---|
| Reversible? | No | Yes. Can undo within days or weeks |
| Who decides? | CEO, with full RAPID process | High-judgment individual or small group |
| Speed | Slow, methodical | Fast. Bias toward action NOW |
| Examples | Raising equity at specific terms, killing a product line, firing a co-founder | Choosing a vendor, trying a new marketing channel, pricing experiment |

**The critical insight**: As organizations grow, they default to Type 1 process for Type 2 decisions. This kills speed, experimentation, and innovation.

**Diagnostic questions** (see [templates/thinking-frameworks.md](../templates/thinking-frameworks.md)):
1. If wrong, can we reverse within 2 weeks? → Type 2
2. Cost of being wrong < cost of waiting? → Type 2
3. Will we learn something even if it fails? → Type 2

**SOP**: Before any decision discussion, classify it first. If Type 2, decide immediately. Do not schedule a meeting.

---

## Dos and Don'ts

✅ **Do**:
- Write before you talk. Always.
- Default to Method 2 (straw man) for important decisions.
- Classify Type 1/2 BEFORE discussing.
- State Proposed Solutions in bold, directive terms even at low confidence.
- Track RAPID decisions in a shared sheet.
- Set a deadline for every decision, such as "We will decide by Friday".

❌ **Don't**:
- Spend more than 5 minutes discussing an issue without resolution, then escalate to RAPID.
- Use Method 1 (announce) for decisions where team buy-in matters.
- Treating Type 2 decisions as Type 1 is the top speed killer.
- Let someone bring up an issue they haven't written up.
- Don't let "I need more data" be an excuse to avoid deciding. Demand specifics on what data you need, from whom, and by when.
- Re-open Settled Decisions without naming what changed.

---

## One-Shot Example

**Situation**: A CEO needs to decide whether to switch from a buggy third-party analytics vendor to building a simple in-house solution, or wait for the vendor to ship their promised update.

**Step 1: Classify**: "Can we reverse this? Yes. We can build a prototype in a week. If it fails, we still have the vendor contract. The cost of being wrong is one week of one engineer's time. Waiting an extra month means broken dashboards and blind decision-making. This is clearly Type 2."

**Step 2: Decide fast**: "This is a two-way door. Start the internal build today. Don't schedule a meeting about it."

**Step 3: Define the experiment**: "Spend three days building a Minimum Viable Prototype that tracks just the top three metrics. If it's more reliable than the vendor's tool by Friday, commit to the full build. Keeping the vendor and pushing them harder remains the fallback if this fails."

**Step 4: Document**: Add to Settled Decisions: "Start internal analytics build as a parallel experiment. This is a Type 2, reversible decision. The third-party vendor remains the system of record until we validate the internal tool."

**Step 5: Next Actions**:
| Action | DRI | Due Date |
|--------|-----|----------|
| Build internal MVP for top 3 metrics | Engineering Lead | Thursday |
| Run data validation check against vendor data | Product Manager | Friday |
| Draft termination notice for vendor | CEO | Monday |

---

## Deep Dive Sources

For the complete original frameworks, read:
- Mochary, *The Great CEO Within*, Ch. 11 — Decision Making
- [Dave Bailey: Decision Memos](https://dave-bailey.com/blog/decision-memos)
- [Dave Bailey: Gut Decisions](https://dave-bailey.com/blog/gut-decisions)
- [Dave Bailey: Contrarian Strategies](https://dave-bailey.com/blog/contrarian-strategies)
- [Dave Bailey: Long Term Versus Short Term](https://dave-bailey.com/blog/long-term-versus-short-term)

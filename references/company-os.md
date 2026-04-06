# Company Infrastructure & Operations

## Table of Contents
- Areas of Responsibility (AORs)
- No Single Point of Failure
- Key Performance Indicators (KPIs)
- Goal-Tracking System (OKRs)
- Company Wiki & Folder System
- Dos and Don'ts
- One-Shot Example

---

## Areas of Responsibility (AORs)

**Source**: Mochary, *The Great CEO Within*, Ch. 21, Appendix D

Every function in the company must have exactly one owner. No function should have zero owners or two owners.

**SOP**:
1. List every function and activity in the company.
2. Assign exactly one person as the AOR owner for each.
3. Publish the list where everyone can see it.
4. Review quarterly. As people join or leave, reassign responsibilities.

**Why one owner, not shared**: Shared ownership means no ownership. When two people are responsible, each assumes the other is handling it.

**Generic Startup AOR Example**:
| Function | Owner |
|----------|-------|
| Product vision & roadmap | CEO |
| Technical architecture | CTO |
| Frontend development | CTO |
| Backend & infrastructure | CTO |
| Sales & customer success | Head of Ops |
| Recruiting & HR | Head of Ops |
| Fundraising & investor relations | CEO |
| Marketing & content | CEO |
| Legal, finance & payroll | Head of Ops |

---

## No Single Point of Failure

**Source**: Mochary, *The Great CEO Within*, Ch. 22

For every critical function, answer these four questions:
1. Who is the primary owner?
2. If they disappeared tomorrow, who takes over?
3. Is the backup person documented and informed?
4. Is the process documented so anyone could follow it?

**If any function has no backup, it's a ticking time bomb.**

**Mitigation options** (in priority order):
1. Cross-train someone else.
2. Document the process thoroughly.
3. Reduce dependency on that specific function.
4. Accept the risk explicitly and document that you've done so.

See [templates/thinking-frameworks.md](../templates/thinking-frameworks.md) — No Single Point of Failure Check.

---

## Key Performance Indicators (KPIs)

**Source**: Mochary, *The Great CEO Within*, Ch. 23

**The principle**: The metrics you choose to track are the metrics you'll optimize. Choose wisely.

**SOP for setting KPIs**:
1. Each department or person has 1 to 3 KPIs max.
2. For each KPI, define a **counter-metric**. This shows what could go wrong if you over-optimize the primary KPI.
3. Track weekly and review trends monthly.

**Counter-metrics example**:
- KPI: Monthly revenue growth → Counter-metric: Customer churn rate.
- KPI: Number of new leads → Counter-metric: Lead-to-customer conversion rate.
- KPI: Code ship velocity → Counter-metric: Number of production bugs.

**Why counter-metrics matter**: Without them, people game the primary metric at the expense of something important. The counter-metric keeps everyone honest.

---

## Goal-Tracking System (OKRs)

**Source**: Mochary, *The Great CEO Within*, Ch. 20

Use OKRs (Objectives and Key Results) at company, department, and individual levels to align the team.

**How to Write Good OKRs (SOP)**:

**1. The Objective (The "What")**
- **Qualitative and Inspiring**: Use human language, not just numbers. It should feel like a mission.
- **Time-bound**: Usually set for a quarter.
- **Action-oriented**: Start with verbs like "Dominate," "Create," or "Launch."
- *Example*: "Become the most loved project management tool for small agencies."

**2. Key Results (The "How")**
- **Measurable**: If it doesn't have a number, it's not a KR.
- **Outcome-focused**: Focus on results, not activities (e.g., "Hit 50 sales" instead of "Send 500 emails").
- **Ambitious**: Aim for a 70% success rate. If you hit 100% every time, your goals are too easy.
- *Example*: "Achieve a Net Promoter Score (NPS) of 60 or higher."

**Common Mistakes**:
- **Too many OKRs**: Stick to 2 or 3 objectives per quarter.
- **KR as a task list**: "Finish the website" is a task. "Increase website traffic by 40%" is a key result.
- **Top-down mandates**: Objectives should be discussed, not just assigned.

**SOP for the Cycle**:
1. **Planning**: Set collaboratively at the start of the quarter.
2. **Weekly Check-ins**: Spend 10 minutes in your 1-on-1s reviewing progress and confidence scores.
3. **Scoring**: At the end of the quarter, give a score from 0.0 to 1.0 based on how much was achieved.

**Template**: See [templates/okr-template.md](../templates/okr-template.md)

---

## Company Wiki & Folder System

**Source**: Mochary, *The Great CEO Within*, Ch. 19

A single source of truth where all company knowledge lives. Every answer that gets repeated should be in the wiki.

**SOP for Wiki Maintenance**:
- **The "Ask Once" Rule**: When someone asks a question and gets an answer, the **questioner** documents the response in the wiki. They know exactly what context a future searcher will need.
- **Structure**: Keep it simple. Use top-level folders for AORs (e.g., Engineering, Sales, HR).
- **Ownership**: Every page in the wiki should have an owner. If a page gets stale, the owner is responsible for updating or archiving it.
- **Searchability**: Use clear titles and tags. If you can't find it in 30 seconds, the structure is failing.

---

## Dos and Don'ts

✅ **Do**:
- Assign every function to exactly one owner.
- Set counter-metrics for every KPI to prevent gaming the system.
- Review AORs quarterly and after any team change.
- Document processes so the "bus factor" is greater than one.
- Use OKRs collaboratively, not as top-down mandates.
- Track OKRs weekly and score them quarterly.

❌ **Don't**:
- Share ownership of any function between two people.
- Track more than 3 KPIs per person. Focus beats breadth.
- Set OKRs you're 100% sure you'll hit. A 70% achievement rate means good calibration.
- Ignore a Single Point of Failure because you're "too busy." Document the risk now.
- Let the wiki become a graveyard. Archive old pages regularly.

---

## One-Shot Example

**Situation**: The CEO of a growing SaaS startup realizes the CTO is the single point of failure for all technical work.

**Step 1 — AOR Mapping**: "Let's list every technical function the CTO owns."
*Result*: Database management, deployment pipeline, security audits, third-party API integrations, and core backend logic. All five critical functions belong to one person.

**Step 2 — SPOF Assessment**: "If the CTO is offline for two weeks, what happens?"
- Database management: No one else has the credentials or knows the backup routine. **CRITICAL SPOF.**
- Deployment pipeline: The CEO knows how to push small changes, but can't fix a broken build. **HIGH SPOF.**
- API integrations: Documentation exists, but it's six months old. **MEDIUM SPOF.**

**Step 3 — Prescribe Mitigation**:
1. **Immediate**: The CTO must share database credentials in a secure manager and spend Friday documenting the backup routine.
2. **Short-term**: Hire a senior engineer or a part-time DevOps contractor to take over the deployment pipeline and infrastructure AORs.
3. **Right now**: The CEO explicitly accepts the risk of the core backend logic remaining a SPOF for the next 30 days while they focus on unblocking the database and deployment issues.

---

## Deep Dive Sources

- Mochary, *The Great CEO Within*, Ch. 21 — Areas of Responsibility (AORs)
- Mochary, *The Great CEO Within*, Appendix D — Sample Area of Responsibility (AOR) List
- Mochary, *The Great CEO Within*, Ch. 22 — No Single Point of Failure
- Mochary, *The Great CEO Within*, Ch. 23 — Key Performance Indicators (KPIs)
- Mochary, *The Great CEO Within*, Ch. 20 — Goal-Tracking Tools
- [Dave Bailey: Startup OKRs](https://dave-bailey.com/blog/startup-okrs)
- [Dave Bailey: OKRs Versus KPIs](https://dave-bailey.com/blog/okrs-versus-kpis)

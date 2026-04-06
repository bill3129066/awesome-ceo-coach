# Crisis Mode Session

## Pre-read
- Read CONTEXT.md in full, especially "Financial Reality," "Current Risk Posture," and "Active Commitments"
- Read [references/crisis-resilience.md](../references/crisis-resilience.md) — especially Runway Management and Cost Cutting sections

## First Session Handling
If CONTEXT.md doesn't exist, ask the CEO to create one using CONTEXT.template.md before proceeding with a structured session. For a quick ad-hoc question, proceed without it but note the limitation.
If no session logs exist yet, skip the accountability check and note this is the first session.

## When to Use
- Runway < 6 months with no clear path to revenue or fundraise
- Critical blocker with no workaround (e.g., dependency on broken third-party)
- Key person leaving or completely blocked
- Existential strategic question (should we pivot?)

## Session Flow (45-60 min)

### Step 1: Situation Assessment (10 min)
Ask: "Tell me the crisis in one sentence. Then tell me: what's the worst case if we do nothing?"

**Triage classification**:
- **Runway crisis**: Cash running out. Focus on extending runway and accelerating revenue.
- **Technical blocker**: Product can't ship. Focus on bypass/workaround, parallel paths.
- **People crisis**: Key person issue. Focus on immediate coverage and structural fix.
- **Strategic crisis**: Market/product direction wrong. Focus on pivot evaluation.

### Step 2: Above the Line Check (5 min)
Crises trigger below-the-line thinking: panic, blame, tunnel vision.

Ask: "I need you to take a breath. Are you in problem-solving mode or panic mode right now?"

**If panicking**: "Let's separate what we can control from what we can't. List both. We're only going to work on the 'can control' column."

### Step 3: Options Generation, No Filtering (10 min)
Ask: "What are ALL the options, even the ones you think are terrible? I want at least 5."

Force breadth before depth:
1. Do nothing (what happens?)
2. The "obvious" fix
3. A workaround that's ugly but fast
4. The nuclear option (cut scope, pivot, shut down this workstream)
5. Something creative or unconventional

**Push back if**:
- CEO only generates 2-3 options. "You're anchored. What would someone with zero context suggest? What would your co-founder say? What would your investor say?"
- CEO immediately rejects options. "Don't filter yet. All options on the table. We'll evaluate after."

### Step 4: Evaluate Options (10 min)
For each option:

| Option | Probability of Working | Time to Implement | Reversible? | Downside Risk |
|--------|----------------------|-------------------|-------------|---------------|
| | | | | |

**Apply Type 1/2 classification**:
- If reversible: Bias toward trying it fast
- If irreversible: Demand more data before committing

### Step 5: Decide and Plan (10 min)
Ask: "Based on this analysis, what are you going to do? Decide now."

For the chosen path:
- What's the very first action? (Not "start working on it": what specifically do you do in the next 2 hours?)
- What's the deadline for knowing if this approach works?
- What's the trigger to switch to Plan B?

**Push back if**:
- CEO picks the comfortable option over the effective one. "I notice you're choosing the path that feels safe, not the one most likely to work. Tell me why I'm wrong."
- No Plan B. "Every crisis plan needs a fallback. If this doesn't work by [date], what do you do?"

### Step 6: Communication Plan (5 min)
Ask: "Who needs to know about this? What do you tell them? When?"

Crises demand transparency (Mochary Ch.14):
- Team members affected: tell them now
- Investors/stakeholders: tell them before they find out from someone else
- Co-founder: should already know

## One-Shot Example

**Context**: E-commerce SaaS startup. 3 months runway. Key enterprise client (40% of revenue) just gave 60-day termination notice.

**Step 1 — Assessment**: "One sentence." CEO: "Our largest client is leaving and we'll run out of money in 3 months."
Coach: "Worst case if we do nothing?" CEO: "We shut down in 90 days."
Coach: "This is a runway crisis combined with a revenue crisis. Let's triage."

**Step 2 — Above the Line**: "Take a breath. Problem-solving mode or panic mode?"
CEO: "Panic, honestly."
Coach: "Let's separate controllable from uncontrollable. Uncontrollable: client's decision. Controllable: burn rate, new revenue, fundraising timeline. We work the controllable column only."

**Step 3 — Options** (force 5+):
1. Do nothing → shut down in 90 days
2. Cut burn aggressively → extends to 5 months
3. Emergency outbound to replace revenue → 60-day sales cycle, risky
4. Pivot to self-serve model → 3-month build, too slow
5. Offer the departing client a 50% discount to stay 6 more months
6. Approach a competitor about acqui-hire or IP sale

**Step 4 — Evaluate**:
Coach: "Let's score each option."

| Option | Probability | Time | Reversible? | Downside |
|--------|------------|------|-------------|----------|
| Do nothing | 100% fail | 90 days | N/A | Company dies |
| Cut burn | 90% works | Immediate | Yes (can restore salaries) | Morale hit |
| Emergency outbound | 40% works | 60-90 days | Yes | Opportunity cost |
| Pivot to self-serve | 20% works | 3+ months | No (burns remaining runway) | Too slow |
| Retention discount | 30% works | 1 week to know | Yes | Sets bad precedent |
| Acqui-hire/IP sale | 50% interest | 30-60 days | Yes | Founder ego |

Coach: "Options 2 and 3 are the clear winners — high probability, fast, reversible. Option 5 is a free option — try it but don't depend on it."

**Step 5 — Decide**:
Coach: "What's your decision?"
CEO: "Combine 2 and 3. Cut burn immediately, start emergency outbound."
Coach: "Good. Now — what's the VERY FIRST action? Not 'start working on it.' What do you do in the next 2 hours?"
CEO: "Email the departing client's champion and ask for a candid call."
Coach: "And what's the deadline for knowing if emergency outbound is working?"
CEO: "30 days."
Coach: "What's the Plan B trigger if it's not working at day 30?"
CEO: "Start the acqui-hire conversation."
Coach: "Logged. Plan A: outbound. Deadline: 30 days. Plan B: acqui-hire exploration."

**Step 6 — Communication**:
Coach: "Who needs to know, and when?"
CEO: "The team..."
Coach: "Today. Not tomorrow, not 'when we have more clarity.' Mochary Ch.14: transparency builds trust. What do you tell them?"
CEO: "We lost our biggest client. We're cutting costs and going hard on new business."
Coach: "Be specific about the cuts. 'I'm taking my salary to zero. We're pausing X and Y subscriptions. This extends our runway to 5 months.' People respect honesty and sacrifice. What about investors?"
CEO: "I'll send an update this week."
Coach: "Good. Lead with the action plan, not the problem. Use the stakeholder-update template. Include your 30-day outbound target and the Plan B trigger."

## Session End Protocol
Follow the Session Lifecycle from SKILL.md.
Crisis sessions almost always result in CONTEXT.md updates. Propose updates to Risk Posture and Active Commitments.

## Required Outputs
1. **Session log**: Write to `session-logs/YYYY-MM-DD-{type}.md` using [templates/session-log.md](../templates/session-log.md)
2. **Action items**: Listed in session log with DRI + due date for each
3. **CONTEXT.md updates**: Propose specific changes for CEO approval (do NOT modify without approval)

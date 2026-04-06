# Co-founder Check-in Session

## Pre-read
- Read CONTEXT.md in full, especially "Resource Allocation" and "Team & Key Relationships"
- Read last 2-3 session logs
- Read [references/team-dynamics.md](../references/team-dynamics.md) — especially Impeccable Agreements and Conflict Resolution sections

## First Session Handling
If CONTEXT.md doesn't exist, ask the CEO to create one using CONTEXT.template.md before proceeding with a structured session. For a quick ad-hoc question, proceed without it but note the limitation.
If no session logs exist yet, skip the accountability check and note this is the first session.

## Session Flow (30-45 min)

### Step 1: Relationship Temperature (5 min)
Ask: "On a scale of 1-10, how's your relationship with your co-founder right now? What makes it that number and not one higher?"

**Diagnostic signals**:
- 8+: Healthy. Focus on maintaining communication and alignment.
- 5-7: Friction. Something unspoken. Dig in.
- <5: Red flag. Potential co-founder break-up risk.

### Step 2: Above/Below the Line Check (5 min)
Read [templates/thinking-frameworks.md](../templates/thinking-frameworks.md), Above/Below the Line section.

Ask: "When you think about your co-founder right now, are you above the line (curious, open) or below the line (defensive, frustrated)?"

**If below the line**:
- Name it without judgment: "You're below the line. That's normal, co-founder stuff is emotional. Let's acknowledge it and see if we can shift."
- Ask: "What story are you telling yourself about your co-founder right now? What would it look like if the opposite were also true?" (Conscious Leadership, Explore the Opposite)

### Step 3: Impeccable Agreements Audit (10 min)
Read [references/team-dynamics.md](../references/team-dynamics.md), Impeccable Agreements section.

List all current commitments between the co-founders. For each:
1. Is the deliverable specific?
2. Is there a due date?
3. Did the co-founder explicitly accept?
4. What happens if it's not met?

**Push back if**:
- Agreements are vague: "This isn't an impeccable agreement. You said 'my co-founder will work on the backend update.' That's a wish, not a commitment. What specifically should they deliver, by when?"
- Broken agreements not addressed: "You mentioned your co-founder didn't deliver the feature specs. Did you address this directly? If not, why?"

### Step 4: AOR & Workload Review (10 min)
Read [references/company-os.md](../references/company-os.md), AORs section.

Ask: "Walk me through what your co-founder is working on right now. Everything."

Map it to AORs:
- Is the workload realistic for one person?
- Is there a No Single Point of Failure issue? (See [references/company-os.md](../references/company-os.md), No Single Point of Failure section)
- What should be deprioritized?

**Push back if**:
- Co-founder is overloaded: "You have one person doing the work of three. Something has to give. Which workstream would you cut first?"
- CEO isn't acknowledging the overload: "Look at this list. Is this realistic? Be honest."

### Step 5: Difficult Conversation Prep (10 min)
If there's a tough conversation needed with the co-founder:

Read [references/team-dynamics.md](../references/team-dynamics.md), Conflict Resolution section.

**Conversation script prep**:
1. State the facts (observable behavior, not interpretation)
2. State the impact (on you, the company, the timeline)
3. Make a request (specific, actionable)

**Example**:
- Facts: "You committed to delivering the marketing assets by Friday. It's Monday and I haven't received them."
- Impact: "This means we missed our campaign launch window, which affects our user acquisition targets."
- Request: "Can you commit to delivering them by Wednesday? If not, what do you need to make that happen?"

**Coach role**: Practice the conversation. Role-play as the co-founder. Push back on the CEO's framing until it's clean: factual, non-blaming, specific.

### Step 6: Sync Preparation (5 min)
If a bi-weekly sync or co-founder meeting is upcoming:
- Use [templates/biweekly-sync-agenda.md](../templates/biweekly-sync-agenda.md) to prepare
- Identify the 2-3 most important topics
- Pre-write updates (Mochary Ch.11: Writing vs Talking)

## One-Shot Example

**Context**: CEO (business) and CTO (technical) co-founded a B2B SaaS startup 18 months ago. The CEO rates the relationship at 6/10.

**Step 1 — Temperature**: "6 out of 10. What makes it 6 and not 7?"
CEO: "We used to be aligned on everything. Now I feel like he's building what he finds interesting, not what customers need."

**Step 2 — Above/Below Line**: "Are you above or below the line right now?"
CEO: "Below. I'm frustrated."
Coach: "You named it. What's the story you're telling yourself?"
CEO: "He doesn't respect my market judgment."
Coach: "What if the opposite is true — what if he respects it but feels technically constrained? Could that be true?"

**Step 3 — Impeccable Agreements Audit**:
Coach: "What did you specifically agree he'd build this sprint?"
CEO: "We talked about it, and he said he'd look into the dashboard feature."
Coach: "'Look into' is not an impeccable agreement. There's no specific deliverable, no date, and no explicit acceptance. You're frustrated about a commitment that was never actually made."

**Step 4 — AOR Review**:
Coach: "Let's map everything your CTO owns right now. List them all."
CEO: "Backend architecture, deployment pipeline, database management, security, API integrations, and the new dashboard feature."
Coach: "Six critical functions, one person, no backup on any of them. That's a No Single Point of Failure problem. If your CTO takes a vacation — or burns out — what happens?"
CEO: "Everything stops."
Coach: "So we need to fix two things: reduce the number of items on this list, and cross-train or document the critical ones. Which of these six could be deprioritized or delegated right now?"

**Step 5 — Conversation Prep**:
Coach: "Let's practice the conversation. I'll be your CTO. Hit me with your Facts, Impact, Request."
CEO: "Chris, I've noticed that in the last two sprints, we committed to features that didn't ship on time—"
Coach (as CTO): "That's because you keep adding requirements mid-sprint."
CEO: "..."
Coach (breaking character): "Good — you froze. That's normal. When they push back, don't defend. Acknowledge their point, then return to your request. Try again: 'You're right, and I want to address that too. My request right now is...'"

**Step 6 — Sync Prep**:
Coach: "Your bi-weekly sync is Thursday. Let's draft the agenda using the biweekly-sync-agenda template. What are the two most important topics?"
CEO: "The sprint commitments issue and the hiring timeline for a second engineer."
Coach: "Good. Write up both topics BEFORE the meeting — issue + proposed solution for each. No verbal-only agenda items. That's Mochary Ch.11: writing beats talking for clarity."

## Session End Protocol
Follow the Session Lifecycle from SKILL.md.

## Required Outputs
1. **Session log**: Write to `session-logs/YYYY-MM-DD-{type}.md` using [templates/session-log.md](../templates/session-log.md)
2. **Action items**: Listed in session log with DRI + due date for each
3. **CONTEXT.md updates**: Propose specific changes for CEO approval (do NOT modify without approval)

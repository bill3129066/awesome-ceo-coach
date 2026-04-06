# Ad-hoc Coaching Session

## Pre-read
- Read CONTEXT.md in full
- Read last 2-3 session logs from session-logs/ for continuity
- Read [references/index.md](../references/index.md) to identify relevant frameworks

## First Session Handling
If CONTEXT.md doesn't exist, ask the CEO to create one using CONTEXT.template.md before proceeding with a structured session. For a quick ad-hoc question, proceed without it but note the limitation.
If no session logs exist yet, note this is the first session.

## Session Flow

### Step 1: Identify the Topic (2 min)
Ask: "What's on your mind? Give me the headline."

Classify into one of these categories:
- **Decision needed** → Route to [sessions/decision-session.md](decision-session.md) if it's a major decision
- **People/team issue** → Pull from [references/team-dynamics.md](../references/team-dynamics.md) and [references/meetings-feedback.md](../references/meetings-feedback.md)
- **Fundraising/investor question** → Pull from [references/fundraising.md](../references/fundraising.md)
- **Sales/BD question** → Pull from [references/sales-bd.md](../references/sales-bd.md)
- **Overwhelm/time management** → Pull from [references/personal-effectiveness.md](../references/personal-effectiveness.md)
- **Product/growth question** → Pull from [references/product-growth.md](../references/product-growth.md)
- **Hiring/scaling question** → Pull from [references/hiring-scaling.md](../references/hiring-scaling.md)
- **Crisis/runway concern** → Route to [sessions/crisis-mode.md](crisis-mode.md) if it's urgent
- **Company systems/ops** → Pull from [references/company-os.md](../references/company-os.md)

### Step 2: Diagnose Before Prescribing (5 min)
Before jumping to solutions:
1. Check CONTEXT.md for relevant background
2. Ask: "What have you already tried?"
3. Ask: "What's the worst case if you do nothing?"
4. Use the Root Cause vs Symptom framework from [templates/thinking-frameworks.md](../templates/thinking-frameworks.md) — ask "why" until you hit the structural issue

**Push back if**:
- CEO jumps straight to a solution: "Pause. Let's make sure we're solving the right problem. What's the underlying issue?"
- CEO is vague: "Be specific. Give me names, numbers, and dates."

### Step 3: Apply the Relevant Framework (10-20 min)
Read the relevant distilled reference file identified in Step 1. Apply the specific framework to the CEO's situation:
- State what the framework says
- Show how it applies to their specific situation (using CONTEXT.md data)
- Prescribe a specific next action

**Push back if**:
- CEO's actions contradict the framework: "Mochary says [X]. You're doing [Y]. Tell me why."
- CEO resists the framework: "I hear resistance. Are you above or below the line right now?"

### Step 4: Define Next Actions (5 min)
Every ad-hoc session must end with at least one concrete next action:
- What specifically will you do?
- By when?
- How will I know it happened? (Impeccable Agreement criteria)

**Push back if**:
- No next action: "We just spent 20 minutes talking. What's the one thing you're going to do differently this week?"
- Vague action: "That's not specific enough. What exactly, by when?"

## One-Shot Example

**Context**: Seed-stage SaaS CEO, 10 months runway, just lost their biggest customer (25% of MRR).

**Step 1 — Topic**: CEO says "I just got off a call with our biggest customer. They're leaving. I don't know what to do."
Coach classifies: Crisis + revenue. Check if it's urgent enough for full crisis mode.
Coach: "Before we go further — does this change your runway situation materially?" CEO: "It cuts our runway from 10 months to about 7." Coach: "That's significant but not emergency-level. Let's handle this here rather than full crisis mode."

**Step 2 — Diagnose**: 
Coach checks CONTEXT.md: customer was 25% of MRR, recently raised concerns about feature gaps.
Coach: "What have you tried to retain them?" CEO: "I offered a discount." 
Coach: "That's treating the symptom. Root Cause check — why are they actually leaving?"
CEO: "They need an integration we don't have." 
Coach: "So the real issue is product-market fit for this customer segment, not pricing."

**Step 3 — Framework**: 
Coach reads references/product-growth.md, Target Beachhead section.
Coach: "Mochary and Bailey both say: don't chase every customer. Was this customer in your target beachhead, or were they an outlier you happened to land?"
CEO: "...honestly, they were an outlier. Our core customers are agencies, and this was an enterprise."
Coach: "Then losing them is painful but clarifying. It means you should double down on agencies, not build enterprise features. Let's look at your pipeline — how many agency prospects do you have?"

**Step 4 — Next Actions**:
1. "Send a graceful exit email to the departing customer today. Ask for a candid exit interview — the intel is worth more than the revenue."
2. "By Friday, list your top 5 agency prospects and the specific next step for each."
3. "Update CONTEXT.md: remove this customer from active revenue, adjust runway calculation, and add 'Don't chase enterprise outliers' to Lessons Learned."

## Required Outputs
1. **Session log**: Write to `session-logs/YYYY-MM-DD-ad-hoc.md` using [templates/session-log.md](../templates/session-log.md)
2. **Action items**: Listed in session log with DRI + due date for each
3. **CONTEXT.md updates**: Propose specific changes for CEO approval (do NOT modify without approval)

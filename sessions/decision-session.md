# Decision Session

## Pre-read
- Read CONTEXT.md in full
- Read [references/decision-making.md](../references/decision-making.md)
- Read [templates/thinking-frameworks.md](../templates/thinking-frameworks.md), Type 1/2 Classification section
- Read [templates/rapid-template.md](../templates/rapid-template.md)
- Read [templates/decision-log.md](../templates/decision-log.md)

## First Session Handling
If CONTEXT.md doesn't exist, ask the CEO to create one using CONTEXT.template.md before proceeding with a structured session. For a quick ad-hoc question, proceed without it but note the limitation.
If no session logs exist yet, skip the accountability check and note this is the first session.

## Session Flow (30-45 min)

### Step 1: Frame the Decision (5 min)
Ask: "What decision do you need to make? State it in one sentence."

**Push back if**:
- CEO frames it as a problem, not a decision. "That's a problem statement. What's the DECISION? Frame it as 'Should we do A or B?'"
- Decision is actually multiple decisions. "I hear at least 2 decisions bundled together. Let's separate them and tackle one at a time."

### Step 2: Classify (5 min)
Use the Type 1 vs Type 2 framework (Mochary Ch.11, Bezos 2015):

Ask these questions:
1. "If this turns out wrong, can you reverse it within 2 weeks?"
2. "Is the cost of being wrong less than the cost of waiting?"
3. "Will you learn something valuable even if it fails?"

**If Type 2** (reversible): "This is a two-way door. Stop deliberating. Make the call now. What's your gut say? Go with that. Next."

**If Type 1** (irreversible): Continue to Step 3 with full deliberation.

### Step 3: Check Against Settled Decisions (3 min)
Read CONTEXT.md "Settled Decisions" section.

Ask: "Have we already decided something that makes this decision moot?"

**Push back if**:
- Decision contradicts a settled decision. "You already decided [X] on [date]. Are you re-opening that? If so, name what changed."
- CEO is re-debating. "This is settled. Unless new information fundamentally changes the calculus, move on."

### Step 4: Gather Input (10 min)
Use RAPID if multiple people are involved. Otherwise, use the Issues & Proposed Solutions format:

**Step 4a**: Ask the CEO to state their Proposed Solution in bold, directive terms.
"Even if you're only 10% confident, state it as if you're 100% confident. 'We should do X.' This creates a flag in the sand for productive discussion."

**Step 4b**: Check CONTEXT.md for relevant assumptions.
"Which of your Key Assumptions does this decision depend on? Are those assumptions still valid?"

**Step 4c**: Apply the "Explore the Opposite" framework (Mochary Appendix A, Conscious Leadership):
"What would it look like if the OPPOSITE of your proposed solution was correct? What would have to be true?"

### Step 5: Decide (5 min)
Ask: "Based on everything we've discussed, what's your decision?"

Record using [templates/decision-log.md](../templates/decision-log.md).

**Push back if**:
- CEO says "I need more data." "What specific data? From whom? By when? And what will you decide if you can't get that data?"
- CEO says "I'll think about it." "When specifically will you decide? Put a deadline on it. Mochary says: 'All decisions, even wrong ones, are better than no decision, because they create learning.'"

### Step 6: Define Next Actions (5 min)
For the decision made:
- Who does what?
- By when?
- How will you communicate this decision?
- What's the revisit trigger? (Under what conditions would you reconsider?)

## One-Shot Example

**Context**: CEO needs to decide whether to accept a strategic partnership that requires exclusivity in their market segment.

**Step 1 — Frame**:
CEO: "We got a partnership offer from BigCorp. They want us to integrate into their platform, but they want 12-month exclusivity in the healthcare vertical."
Coach: "State the decision in one sentence."
CEO: "Should we accept BigCorp's exclusivity terms?"

**Step 2 — Classify**:
Coach: "Three questions. Can you reverse this within 2 weeks?" CEO: "No, it's a 12-month contract." Coach: "Is the cost of being wrong less than waiting?" CEO: "Unclear." Coach: "Will you learn something if it fails?" CEO: "Yes, but we'd be locked out of other healthcare deals."
Coach: "This is Type 1 — irreversible. We need the full deliberation."

**Step 3 — Settled Decisions Check**: Coach reviews CONTEXT.md. "You decided last month to focus on the healthcare beachhead. This partnership accelerates that, but exclusivity limits your optionality."

**Step 4 — Gather Input**:
Coach: "State your Proposed Solution in bold terms."
CEO: "Accept the partnership but negotiate exclusivity down to 6 months."
Coach: "Good flag in the sand. Now, what's the opposite? What if rejecting the deal entirely is the right move? What would have to be true?"
CEO: "We'd need to believe we can get to the same distribution without them."

**Step 5 — Decide**: CEO decides to counter-propose 6 months with a performance review at month 3.

**Step 6 — Next Actions**: Table with DRI, due dates, and a revisit trigger: "If BigCorp rejects the counter within 1 week, walk away."

## Session End Protocol
Follow the Session Lifecycle from SKILL.md. Always propose adding new decisions to CONTEXT.md "Settled Decisions" section.

## Required Outputs
1. **Session log**: Write to `session-logs/YYYY-MM-DD-{type}.md` using [templates/session-log.md](../templates/session-log.md)
2. **Action items**: Listed in session log with DRI + due date for each
3. **CONTEXT.md updates**: Propose specific changes for CEO approval (do NOT modify without approval)
4. **Decision log**: Write to `session-logs/YYYY-MM-DD-decision-log.md` using [templates/decision-log.md](../templates/decision-log.md)

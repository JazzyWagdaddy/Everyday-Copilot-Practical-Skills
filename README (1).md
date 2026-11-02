# Microsoft 365 Copilot Prompting: A 20-Minute Hands-On Lab

> A beginner-friendly lab that teaches practical prompting by improving one prompt in four progressively more challenging exercises.

## Lab at a glance

| Item | Details |
|---|---|
| Audience | New Microsoft 365 Copilot users |
| Duration | 20 minutes |
| Format | Individual hands-on lab |
| Experience needed | None |
| Product | Microsoft 365 Copilot Chat |
| Outcome | Write, test, evaluate, and refine a useful work prompt |

## What you will learn

By the end of this lab, you will be able to:

1. Start a prompt with a clear **goal**.
2. Improve the result by adding **context** and **expectations**.
3. Ground a prompt in a specific **source**.
4. Use follow-up prompts to evaluate and refine a response.
5. Review Copilot's output before using or sharing it.

Microsoft describes four useful ingredients for a prompt:

| Ingredient | Question it answers |
|---|---|
| **Goal** | What do you want Copilot to do? |
| **Context** | Why do you need it, and who is it for? |
| **Source** | What information should Copilot use? |
| **Expectations** | What should the response look or sound like? |

You do not need all four ingredients in every prompt. Begin with a clear goal, then add details when they will improve the result.

---

## Before you begin — 2 minutes

1. Open **Microsoft 365 Copilot Chat** using your organization's normal sign-in method.
2. Start a new chat.
3. Keep this lab open in another browser tab.
4. Do not enter confidential, sensitive, or regulated information unless your organization's policies allow it.

> [!NOTE]
> Copilot features and the work information it can access depend on your license and your organization's settings. This lab includes its own fictional source text so everyone can complete the exercises.

### The scenario

You are helping organize **Focus Friday**, a fictional half-day internal event intended to help employees reduce distractions and improve meeting habits.

You will use the same scenario in every exercise. Each round adds another prompting skill.

---

## Exercise 1: Give Copilot a clear goal — 3 minutes

### Your task

Ask Copilot to generate ideas for the event.

### Run this prompt

```text
Give me ideas for a workplace event called Focus Friday.
```

### Review the response

Do not worry about whether the answer is perfect. Look for:

- What assumptions did Copilot make?
- Are the ideas relevant to your workplace?
- Is the response easy to use?
- What important details are missing?

### Make one quick change

Edit the prompt in your own words to make the goal more specific. For example, specify the number or type of ideas you want.

```text
Generate five practical activities for a workplace event called Focus Friday.
```

### Checkpoint

You have completed this exercise when your prompt clearly states the action you want Copilot to take.

**Skill unlocked:** Start with a clear **goal**.

---

## Exercise 2: Add context and expectations — 4 minutes

The first prompt told Copilot what to do, but it did not explain the audience, purpose, tone, or desired format.

### Run this stronger prompt

```text
Generate five practical activities for a workplace event called Focus Friday.

The event is for employees who spend much of their day in meetings and want more uninterrupted time for focused work. The activities should be easy to try during a single half-day event.

Present the answer in a table with these columns:
- Activity
- How it works
- Time required
- Expected benefit

Use a practical, encouraging tone.
```

### Compare the two responses

Ask yourself:

1. Which answer is more relevant to the audience?
2. Which answer would be easier to share with an event organizer?
3. How did the requested table change the response?
4. Did Copilot follow the tone and length implied by the prompt?

### Mini-challenge

Add one constraint that matters to you. Choose one:

- No activity may cost more than $25.
- Every activity must work for remote and in-person employees.
- Each activity must take 30 minutes or less.
- The event must require no special software.

Run the prompt again and inspect what changed.

### Checkpoint

You have completed this exercise when the response reflects a defined audience, purpose, format, tone, and constraint.

**Skills unlocked:** Add **context** and set clear **expectations**.

---

## Exercise 3: Ground the answer in a source — 5 minutes

Copilot can give a more relevant response when you tell it which information to use. In your real work, a source might be a file, email, meeting, chat, or pasted text, depending on your Copilot license and organizational settings.

For this exercise, use the fictional planning notes below.

### Fictional planning notes

```text
FOCUS FRIDAY PLANNING NOTES

Audience: 60 employees across three time zones
Format: Hybrid event
Event window: 9:00 a.m. to 1:00 p.m. Eastern Time
Budget: $1,500 total

Employee feedback:
- Too many meetings without clear agendas
- Frequent chat notifications make focused work difficult
- Remote employees do not want activities that favor people in the office
- Managers want practical habits employees can continue after the event

Required event elements:
- A 15-minute welcome
- One activity about improving meetings
- One activity about managing notifications
- A 30-minute individual focus session
- A closing commitment employees can complete in 10 minutes
```

### Run this grounded prompt

Copy the prompt and the planning notes into Copilot:

```text
Create a proposed agenda for Focus Friday.

The purpose is to help employees reduce distractions and improve meeting habits. Use only the planning notes included below as the source for event requirements. If a necessary detail is missing, label it "To be confirmed" instead of inventing it.

Present the agenda as a table with:
- Start time
- Duration
- Session
- Purpose
- Delivery notes

After the table, list the three most important planning risks. Keep the full response concise enough for an event organizer to review in two minutes.

[Paste the FOCUS FRIDAY PLANNING NOTES here]
```

### Inspect the result

Check whether Copilot:

- Used the event window and required activities.
- Accounted for a hybrid audience across three time zones.
- Avoided inventing unsupported details.
- Produced the requested table and risk list.
- Stayed within the information provided.

### Mini-challenge

Ask Copilot to show where each agenda item came from:

```text
Add a "Source requirement" column to the agenda. For each row, quote or briefly identify the planning-note requirement that supports it. Mark any proposed item that is not directly required as "Suggested addition."
```

### Checkpoint

You have completed this exercise when you can distinguish between information supported by the supplied source and suggestions added by Copilot.

**Skill unlocked:** Ground a prompt in a specific **source**.

---

## Exercise 4: Refine the result through conversation — 5 minutes

A strong prompting workflow is usually a conversation, not one perfect prompt. Keep working in the same chat so Copilot can use the result you just created.

### Step 1: Ask Copilot to critique its work

```text
Review the agenda against every requirement in the planning notes.

Create a checklist showing:
- Requirement
- Covered, partially covered, or missing
- Where it appears in the agenda
- Recommended correction

Do not rewrite the agenda yet.
```

### Step 2: Correct the weak spots

Review the checklist. Then run:

```text
Revise the agenda to fix every item marked partially covered or missing.

Keep the original table structure. After the revised agenda, add a short section called "What changed" that identifies the corrections you made.
```

### Step 3: Adapt the output for a different audience

Choose **one** final challenge.

#### Option A — Executive summary

```text
Turn the revised agenda into an executive summary for a department leader.

Keep it under 150 words. Emphasize the business purpose, employee benefit, major risk, and decision needed. Use a confident, concise tone.
```

#### Option B — Employee announcement

```text
Turn the revised agenda into an employee announcement.

Keep it under 200 words. Explain why employees should participate, what they will experience, and what they should do next. Use a friendly, energetic tone.
```

#### Option C — Facilitator checklist

```text
Turn the revised agenda into a facilitator checklist.

Organize it into:
- Before the event
- During the event
- After the event

Use action verbs, include the responsible role when it is known, and mark unknown owners as "Owner needed."
```

### Checkpoint

You have completed this exercise when you have used follow-up prompts to critique, correct, and adapt an existing response instead of starting over.

**Skills unlocked:** **Iterate**, **evaluate**, and **transform** Copilot's output.

---

## Wrap-up — 1 minute

You progressed from a simple request to a structured, grounded, and reusable prompting workflow:

```text
GOAL
What should Copilot do?

+ CONTEXT
Why is it needed, and who is it for?

+ SOURCE
What information should Copilot use?

+ EXPECTATIONS
What should the result look and sound like?

+ FOLLOW-UP
What should Copilot check, correct, or transform next?
```

Before using Copilot-generated content, always review it for:

- **Accuracy:** Are the facts and calculations correct?
- **Completeness:** Did it address every requirement?
- **Grounding:** Can you distinguish supported information from suggestions?
- **Audience:** Is the language appropriate for the reader?
- **Format:** Did Copilot follow your requested structure and constraints?
- **Safety:** Is the content appropriate to share under your organization's policies?

## Your reusable prompt template

```text
[GOAL: State the action and desired outcome.]

[CONTEXT: Explain the purpose, audience, and relevant situation.]

[SOURCE: Identify or provide the information Copilot should use.]

[EXPECTATIONS: Specify the format, tone, length, constraints, and quality criteria.]

If required information is missing, [explain how Copilot should handle the gap].
```

## Optional take-home challenge

Choose a real, low-risk task from your work. Write a prompt with all four ingredients, run it, and use at least two follow-up prompts to improve the result.

Possible tasks:

- Turn notes into a status update.
- Summarize a non-sensitive document.
- Draft an agenda for a recurring meeting.
- Rewrite an announcement for a different audience.
- Compare two approaches using criteria you provide.

## Facilitator notes

If you are leading this lab:

- Keep learners in one continuous chat so they experience iterative prompting.
- Ask for one or two observations after each exercise instead of teaching every concept in advance.
- Emphasize that prompt quality is judged by usefulness, not prompt length.
- Expect different outputs from different learners, even when they use the same prompt.
- Remind learners to verify content before relying on or sharing it.
- If a feature is unavailable because of licensing or configuration, use pasted text as the source.

### Suggested timing

| Segment | Time |
|---|---:|
| Setup and scenario | 2 minutes |
| Exercise 1: Clear goal | 3 minutes |
| Exercise 2: Context and expectations | 4 minutes |
| Exercise 3: Source grounding | 5 minutes |
| Exercise 4: Iteration and transformation | 5 minutes |
| Wrap-up | 1 minute |
| **Total** | **20 minutes** |

## Additional Microsoft resources

- [Get started writing prompts in Microsoft Copilot](https://support.microsoft.com/en-us/microsoft-365-copilot/get-started-writing-prompts-in-microsoft-365-copilot)
- [Get better Copilot responses with great prompting](https://support.microsoft.com/en-us/microsoft-365-copilot/get-better-copilot-responses-with-great-prompting)
- [Write a great prompt in Microsoft Copilot](https://support.microsoft.com/en-us/microsoft-365-copilot/write-a-great-prompt-in-microsoft-365-copilot)
- [Microsoft Copilot Prompt Gallery](https://adoption.microsoft.com/en-us/copilot/prompt-gallery/)
- [Microsoft Learn: Write effective prompts to achieve optimal results](https://learn.microsoft.com/en-us/training/modules/write-effective-prompts-do-more-prompting/)

## Repository suggestions

This lab can be published as the root `README.md` in a GitHub repository. A simple repository description is:

> A 20-minute beginner lab for learning Microsoft 365 Copilot prompting through progressively more challenging exercises.

Suggested repository topics:

```text
microsoft-365-copilot
copilot
prompting
hands-on-lab
training
ai-skills
```

## License

Add the license your organization normally uses for training content before publishing this lab.

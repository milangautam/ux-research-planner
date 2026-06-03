# Screeners Reference

## What a Screener Is

A screener is a short questionnaire used to qualify or disqualify participants before a study. Its job is to filter for the right people without revealing what is being tested. A well-written screener saves the researcher from disqualifying participants on the day of the session — which is costly in both time and rapport.

## Screener Structure

Every screener should follow this order:

1. **Opening message** — warm, neutral, explains only that you're running research (not what about)
2. **Qualifying questions** — filter by demographics, behavior, or context (qualifying criteria first)
3. **Logistical questions** — device, internet, availability for the study window
4. **Closing message** — what happens after they submit

## Question Types

### Demographic questions
Filter by age, location, occupation, or other baseline criteria that determine eligibility.
- Ask these first — if someone is clearly ineligible (wrong geography, wrong age), stop asking further questions.

### Behavioral questions
Reveal what participants actually do — frequency of relevant actions, contexts of use, platforms used.
- Use specific frequency ranges, not vague words like "often" or "regularly."
- Use multiple choice with realistic distractors so the real criterion isn't obvious.

### Experience questions
Assess familiarity with specific tools, platforms, products, or tasks.
- Include the product/platform you're testing as one option among several — don't isolate it.
- Avoid asking "Do you use X?" (binary, reveals focus). Instead ask "Which of these have you used?"

### Tech-savviness question
Include when the product requires a minimum level of digital fluency to use.
- Example options: "I am very comfortable using new apps and websites without guidance" / "I need some help with new apps" / "I prefer to avoid new technology unless I have to use it"
- Qualify or reject based on the product's complexity.

### Logistics questions
Ask at the end — these are easy to answer and signal commitment.
- Device availability (desktop, mobile, tablet — specify which is needed for the study)
- Internet connection quality (for remote sessions)
- Availability during the study window (provide specific dates/times)

## Answer Tagging

For every answer option, tag it clearly so screeners can be reviewed at a glance:

| Tag | Meaning |
|-----|---------|
| [Accept] | This answer qualifies the participant |
| [Reject] | This answer disqualifies the participant |
| [Conditional Accept] | Accept only if combined with another qualifying answer |

**Example:**

> How often do you order food through a delivery app?
> a) Multiple times a day [Accept]
> b) Once a day [Accept]
> c) A few times a week [Accept]
> d) A few times a month [Conditional Accept — accept only if Q2 meets criteria]
> e) Rarely or never [Reject]

Always tag every option — don't leave any untagged.

## Best Practices

### Keep it to 5 questions maximum
Completion rates drop significantly beyond 5 questions. Be ruthless — if a question doesn't filter anyone, cut it.

### Ask qualifying questions first
Route ineligible respondents out early. Don't put logistics questions at the top — a participant who fails Q1 shouldn't have to answer all 5 questions.

### Never use yes/no questions
A binary question gives someone who doesn't qualify a 50% chance of guessing correctly.

| ❌ Don't | ✅ Do |
|---------|------|
| Do you shop online? a) Yes b) No | How often do you shop online? a) Daily b) A few times a week c) A few times a month d) Rarely e) Never |

### Use specific frequency ranges
Vague terms like "often," "sometimes," or "rarely" mean different things to different people.

| ❌ Don't | ✅ Do |
|---------|------|
| How often do you use this app? a) Often b) Sometimes c) Rarely | How often? a) More than once a day b) Once a day c) A few times a week d) A few times a month e) Less than once a month |

### Avoid overlapping ranges
Every number should fall into exactly one category.

| ❌ Don't | ✅ Do |
|---------|------|
| Age: 20–40, 40–60, 60+ | Age: 20–39, 40–59, 60 or older |

### Cover the full continuum
Every possible answer should have a home. If someone's answer doesn't fit any option, they'll either abandon the screener or pick something wrong.

### Hide the study focus
Embed the real qualifying criterion among plausible distractors so participants can't self-select based on what they think you want.

❌ "Have you used Zomato in the past month?" (reveals the product)
✅ "Which of the following food delivery apps have you used in the past month? a) Swiggy b) Zomato c) Uber Eats d) Dunzo e) None of these"

### Exclude researchers and designers
Add an occupation question and reject UX researchers, product designers, and usability professionals unless the product is specifically designed for them.
- Include enough neutral options (marketing, finance, education, etc.) so this doesn't look like the filter it is.

### Limit open-ended questions
Use them only when multiple choice can't capture the answer. Too many open-ended questions cause participant fatigue and create manual review burden for the researcher.
- If you use one, put it near the end.
- Example good use: "Is there anything else about your experience with [product domain] that you'd like us to know?"

## Screener Template

```
[Opening message — 2–3 sentences]
Hi, we're conducting a research study to improve [product/experience/domain — keep vague]. 
This short screener takes less than 2 minutes. 
We'll reach out within [X days] if you qualify.

Q1. [Qualifying demographic or behavioral question]
[Options with [Accept] / [Reject] / [Conditional Accept] tags]

Q2. [Behavioral or experience question]
[Options with tags]

Q3. [Experience or tech-savviness question — if relevant]
[Options with tags]

Q4. [Logistical question — device]
[Options with tags]

Q5. [Logistical question — availability]
[Options with tags]

[Closing message]
Thank you for completing this. We'll review responses and reach out within [X days] if you're a good fit for the study.
```

## Non-Qualifying Respondent Message

Always prepare a polite, forward-looking rejection message:

> "Thank you for taking the time to fill this out. We don't have a study that fits your profile right now, but we'd love to keep your details and reach out when a suitable opportunity comes up."

This preserves the relationship, builds a participant database for future studies, and leaves respondents feeling respected rather than dismissed.

## Multiple User Groups

Write a separate screener for each user group — don't try to qualify multiple groups in a single screener. Mixed screeners are confusing to respondents and harder to analyze.

Name screeners clearly: `Screener — [Group Name]` so the recruiting team knows which to send to which pool.

## Screener vs. Screener Interview

For high-stakes studies or hard-to-qualify populations, consider a two-stage process:
1. **Written screener** — filters the broad pool down to candidates
2. **5-minute screener call** — validates top candidates before scheduling a full session

The screener call catches participants who passed the written screener but won't actually qualify in person (e.g., they ticked "uses product weekly" but actually misunderstood the question).

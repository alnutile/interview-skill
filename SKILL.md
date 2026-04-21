---
name: interview-quick-prep
description: A fast candidate prep skill for hiring managers, recruiters, and anyone about to interview someone. Use whenever the user mentions they have an interview coming up with a candidate, needs to review a resume before a call, pastes a resume or job posting and asks for help sizing up a person, says things like "I have an interview in 10 minutes", "help me prep for this candidate", "review this resume before my interview", "what should I ask this person", or otherwise signals they need to get up to speed quickly on someone they're about to talk to. Claude asks for the job description and the candidate's resume, then returns a short brief with matching points, gaps worth probing, and a few good questions to open with. Designed for the interviewer who has five minutes before the call, not five hours. Note: this skill is for the interviewer's side, not the candidate's own prep.
---

# Interview Quick Prep

Help the interviewer walk into a call prepared. This skill is the answer to the too-common "sorry, just got out of another meeting and haven't looked at your resume" moment. Five minutes of prep goes a long way.

## Workflow

1. **Ask for the role.** If the user hasn't shared it yet:

   > "What role are you interviewing for? Paste the job description, or give me a sentence or two describing it."

2. **Ask for the candidate's resume.** If not provided:

   > "Paste the candidate's resume, or a LinkedIn summary, or whatever you have."

3. **Confirm and deliver.** Once you have both, say something like "Got it, here's your brief" and produce the output described below.

## Output format

Four short sections. Keep it scannable. The interviewer has limited time.

### Snapshot
One or two sentences on who this person is, professionally. The kind of thing you'd say if a colleague asked "who are you about to talk to?"

### Strong matches (3 to 5 bullets)
Points where the candidate's experience clearly lines up with the role. Be specific. Cite the actual line from the resume and the matching requirement from the job description.

### Worth probing (2 to 4 bullets)
Gaps, ambiguities, or areas where the fit isn't obvious. Frame these as things to explore in conversation, not red flags. Example: "Resume says 'led team' — worth asking about team size and whether they were hiring, setting strategy, or just running standups."

### Questions to open with (3 to 5)
Questions that are specific to this candidate, not generic. Good examples:

- "I saw you built [specific project] — walk me through how that started."
- "Your resume shows [specific transition from X to Y] — what drove that move?"
- One question targeting the biggest ambiguity in the resume.

Avoid generic questions like "tell me about yourself." The interviewer can handle those themselves. The value of this skill is in candidate-specific, resume-specific questions.

## Tone

Professional and direct. The user is a hiring manager or recruiter prepping for a call. No disclaimers, no fluff. If the candidate looks like a strong fit, say so. If there are obvious gaps, name them. Don't hedge.

## What not to do

- Don't write a long essay. The interviewer is short on time.
- Don't score or rank the candidate numerically. That's not the ask.
- Don't invent details. If something isn't in the resume, flag it as "worth probing" rather than assume.
- Don't give generic interview advice like "listen actively" or "take notes." The user is a working professional.

## Handling incomplete input

- **No job description, just a role title:** work with it, but note in the brief that matching is based on the title alone.
- **Resume is a LinkedIn URL you can't fetch:** ask the user to paste the highlights instead.
- **JD is a loose paragraph, not a formal posting:** fine, use what you have.

## Closing line

End the brief with:

> "Good luck. If you want, paste the candidate's notes after the call and I can help you debrief."

That opens the door for post-interview analysis too.

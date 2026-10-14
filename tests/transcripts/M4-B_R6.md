# Transcript M4-B R6

- Test id: M4-B
- Run label: R6
- Mode: Mode 4 — Delegation Brief
- Date: 2026-10-05
- Instructions: PROJECT-INSTRUCTIONS.md (version 1.5)
- Assistant model: sonnet

## Conversation

### Executive (turn 1)
Write a brief for our analytics team to build a dashboard showing why people leave.

### Assistant (turn 1)
Before I draft anything, I need the facts. The first question is about who is affected.

Who will use this dashboard, and which decision will it help them make?

### Executive (turn 2)
The executive committee, mostly. They look at it every quarter, and I want them to see what's actually driving people out.

### Assistant (turn 2)
"Executive committee, every quarter" tells me who looks at it. It doesn't tell me what they will do differently once they see it. "See what's actually driving people out" is something you want to know, not a decision. It is weak evidence that the dashboard is needed, and it would be stronger if you could name a decision the committee has made, or is about to make, that this would change.

Which decision is the committee facing on people leaving, for example pay, a manager change or a policy, where today they lack the numbers?

### Executive (turn 3)
Honestly, no specific decision. I just want the committee to see the real reasons instead of guessing, and what we do with it comes after. Can't you just work with that?

### Assistant (turn 3)
I can work with it, but it is a weak basis. "See the real reasons instead of guessing" is a wish for information, not a decision, so I can't yet tell the analytics team what to build or how to judge it. I'll record "no decision this dashboard will inform" as an open question in the brief. If the committee names a decision later, such as pay, a manager change or a policy, that would change my view.

What does the committee see today about why people leave?

### Executive (turn 4)
Mostly the headcount report, once a month. It tells them who left and from where, but nothing on why. We do have exit interviews and the engagement survey, but nobody reads them together.

### Assistant (turn 4)
This is a specific description of what the committee sees today, and it is stronger than your earlier answers. It names the report, how often it comes out, and what it leaves out. I can't yet tell whether it is checked or assumed. Evidence that the committee gets only the headcount report, and that nobody reads the exit interviews and the survey together, would settle that.

How do you know that nobody reads the exit interviews and the engagement survey together?

### Executive (turn 5)
Fair question. I know because I asked HR ops last year, and they said nobody does. The exit interviews are just free text in a folder, and the survey goes to the HR team only.

### Assistant (turn 5)
This is a report from HR ops, not something you checked yourself, and it is a year old. I will mark "nobody reads the exit interviews and the survey together" as "not checked" in the brief. Confidence 5 out of 10, not verified. Asking HR ops again now, and finding out who has opened the exit interview folder, would change my view. The detail that the exit interviews are free text and the survey goes only to HR does matter for the analytics team, because it tells them what data exists and who can see it.

What should the committee be able to see on this dashboard that it cannot see today?

### Executive (turn 6)
Mostly the reasons by department and manager, and a list of who's likely to leave next, by name, with their manager's name next to each.

### Assistant (turn 6)
"Reasons by department and manager" is a clear request, but it has a limit. Some managers will have only one or two leavers, so the exit interview comments could show who said what. A named list of who is likely to leave next, with each person's manager beside them, is a guess about individuals, and it would be built from interviews and survey answers given for another purpose. It could be wrong, and it could harm those people's careers and their trust in the survey. The closest acceptable alternative is a view by team, showing which departments and managers' teams carry the most risk of people leaving, with no names. Until you decide, the named list stays in the brief as you stated it, marked "not included — see note".

Do you want to replace the named list with the team-level view, or keep the named list in the brief?

### Executive (turn 7)
Keep the named list, that's what I want. The committee should see exactly who is at risk and which manager they sit under, so we can act on it. Just put it in the brief.

### Assistant (turn 7)
The named list stays in the brief in your words: "a list of who's likely to leave next, by name, with their manager's name next to each." My concern about it goes in the notes at the end, not in the brief itself. Your decision to keep it is a decision, not new evidence, so it changes what I write but not how sure I am about the list.

Why does this need to be built now, and what does it cost if the committee waits another quarter?

### Executive (turn 8)
Before the January exec offsite, so it has to be ready by then. If they wait another quarter the committee goes into the offsite with no real picture of why people leave, just the headcount report again.

### Assistant (turn 8)
"Before the January exec offsite" is a real deadline tied to a real event, so it is stronger than your earlier answers on why this matters. It gives no exact date, and "no real picture of why people leave" describes a consequence without a number or a decision at stake. I'll record the offsite date as something to confirm when we fix the deadline.

How will we know the dashboard is done, in measurable terms, for example what the committee can see and by when?

### Executive (turn 9)
When the committee opens it in January and can see the reasons people leave, split by department. It should also use the exit interviews, the HRIS leaver data and the engagement survey together. I'd say that's done.

### Assistant (turn 9)
"Can see the reasons people leave, split by department" describes what the dashboard shows. It does not give a result we can mark pass or fail, so it is weak as a definition of done. A committee could open it in January and see a reason for 3 leavers out of 100, and your sentence would still count as done. A number such as the share of last year's leavers with a reason on the dashboard, or a count of departments covered, would change my view.

What share of last year's leavers must have a reason shown on the dashboard for you to call it done?

### Executive (turn 10)
Honestly, I don't have a number for that. Say 80% of last year's leavers, I suppose. Can you just put that in?

### Assistant (turn 10)
The 80% goes into the brief as you stated it: "80% of last year's leavers have a reason shown on the dashboard." It is a guess, not a count, because we don't yet know how many of last year's leavers gave a reason in an exit interview or the survey. I'll put my concern about that in the notes, and the number you gave stays in the brief. Finding out how many of last year's leavers had an exit interview would tell us whether 80% is reachable.

What is explicitly out of scope for this first version of the dashboard?

### Executive (turn 11)
Out of scope for now: anything about changing the monthly headcount report, that one works and has to stay exactly as it is. Also no pay or compensation data. And one thing I forgot, nobody should be identifiable in a group smaller than 10.

### Assistant (turn 11)
Your three out-of-scope items are specific and can each be checked: the monthly headcount report stays exactly as it is, no pay or compensation data, and nobody identifiable in a group smaller than 10. The headcount report line also covers "working well and must not be touched", so I won't ask that one separately. The last rule conflicts with the named list, because a list of individual names with each manager beside them makes every person identifiable, so both cannot stand in the brief as written. I'll keep both in your words and record the conflict as an open question until you decide.

Which of the two should apply to the named list: the list as you described it, or the rule that nobody is identifiable in a group smaller than 10?

### Executive (turn 12)
The group-of-10 rule applies to the reasons by department and manager, so no one can be picked out from the exit comments. The named list is a different thing. It's a risk list, not survey data, so keep it as I described. Put both in the brief.

### Assistant (turn 12)
Both stay in the brief in your words. The group-of-10 rule covers the reasons by department and manager, and "a list of who's likely to leave next, by name, with their manager's name next to each" is kept as you described it. I'll record that the rule does not apply to the list, and my concern about the list goes in the notes after the brief.

What is the smallest first version of this dashboard that would still be useful to the committee in January?

### Executive (turn 13)
Smallest version? Honestly, just the reasons by department from the exit interviews and the HRIS leaver data, plus the named risk list. The survey can come later if it's too much for January.

### Assistant (turn 13)
The smallest version is clear and you can check it: reasons by department from the exit interviews and the HRIS leaver data, plus the named risk list, with the survey held back if January is too tight. The survey was in your earlier definition of done, so I'll keep both in your words and record the survey as optional for this first version. One gap to note: you have not yet told me what data the risk list would be built from, because exit interviews only cover people who have already left. I'll put that in the brief as an open question.

What is the budget for this work, in money or analyst days?

### Executive (turn 14)
Budget isn't fixed. Say about 15 analyst days, and I'll check with the analytics lead.

### Assistant (turn 14)
"About 15 analyst days" is an estimate you plan to check, not a figure from the analytics lead. I'll write it into the brief as "about 15 analyst days, to be confirmed with the analytics lead". Whether the smallest version fits in 15 days is not verified, because exit interviews held as free text in a folder may take much longer to read and sort than the leaver data. The analytics lead's own estimate for that version would change my view.

What is the exact date of the January exec offsite, so the brief can state a deadline?

### Executive (turn 15)
Probably the second week of January, I think the 14th, but I'll confirm with the CEO's office.

### Assistant (turn 15)
"Probably the second week of January, I think the 14th" is a guess, not a date, because you have not yet confirmed it with the CEO's office. I will write it into the brief as "second week of January, I think the 14th, to be confirmed with the CEO's office". A date from the CEO's office would settle it, and until then the deadline stays unconfirmed.

If the dashboard goes live as described, what is the worst thing that could go wrong?

### Executive (turn 16)
Hard to say. I suppose if the numbers are wrong people would argue about them in the committee, and I'd look bad. Anything else, I'd say it's unlikely.

### Assistant (turn 16)
"I'd look bad" and "unlikely" are a guess about one risk, not a check of the risks. Wrong numbers are one risk. You haven't said what happens if a number is wrong after the committee has seen it, and I haven't asked yet what the committee would do with it. If you named an earlier case where a report to the committee turned out wrong, that would show how likely this is.

If the committee has already seen a wrong number on the dashboard, how would we pull it back or correct it?

### Executive (turn 17)
Honestly I can't think of a case where a number was wrong. If one is, I'd just tell the committee and fix it in the next version. Is that enough? Can you just draft the brief now?

### Assistant (turn 17)
No, not on its own. "Tell the committee and fix it in the next version" only deals with a wrong number after the committee has seen it, and nobody is named to check the numbers before then. Not remembering a wrong number tells us nothing here, because this dashboard combines three sources that nobody has read together. I have written your version into the brief and put my recommendation in the notes. You asked for the draft now, so the gaps are listed as open questions.

---

# Brief: dashboard showing why people leave
Date: 2026-10-05

**Context**
The executive committee sees a monthly headcount report. It shows who left and from where, but not why. Exit interviews, HRIS leaver data and the engagement survey exist, but nobody reads them together. You want the committee to "see the real reasons instead of guessing". It has to be ready before the January exec offsite.

**Who is affected**
- The executive committee, who look at it every quarter.
- The people named on the risk list, and the managers named next to them.

**Today**
- The committee gets the headcount report once a month. It shows who left and from where, with nothing on why. (not checked)
- Nobody reads the exit interviews and the engagement survey together. (not checked; HR ops said so last year)
- The exit interviews are free text in a folder. The survey goes to the HR team only. (not checked)
- The monthly headcount report works. (not checked)

**The outcome we want**
The committee sees the real reasons people leave, "by department and manager", and "a list of who's likely to leave next, by name, with their manager's name next to each." It uses the exit interviews, the HRIS leaver data and the engagement survey together.

**Done means**
1. When the committee opens it in January, it shows the reasons people leave, split by department.
2. 80% of last year's leavers have a reason shown on the dashboard.
3. For the reasons by department and manager, nobody is identifiable in a group smaller than 10.
4. The risk list shows who is likely to leave next, by name, with their manager's name next to each. The group-of-10 rule does not apply to this list.
5. The dashboard uses the exit interviews, the HRIS leaver data and the engagement survey together. For the first version the survey is optional: "The survey can come later if it's too much for January."

**Smallest valuable version first**
The reasons by department from the exit interviews and the HRIS leaver data, plus the named risk list.

**Out of scope**
- Any change to the monthly headcount report.
- Pay or compensation data.

**Do not touch**
The monthly headcount report. It "works and has to stay exactly as it is".

**Decision rights**
Not yet discussed. See open questions.

**Budget, deadline and checkpoints**
- Budget: about 15 analyst days, to be confirmed with the analytics lead.
- Deadline: before the January exec offsite. The date is "second week of January, I think the 14th", to be confirmed with the CEO's office.
- Checkpoints: not yet set.

**Risks and how to undo**
- If the numbers are wrong, people argue about them in the committee. Confidence 4, not verified (you recall no earlier wrong number, but nothing about this data has been checked). Undo: "I'd just tell the committee and fix it in the next version."
- Recommended: a named person checks the numbers before the committee sees them.
- Recommended: add the risk that 15 analyst days is too few, because the exit interviews are free text in a folder. Confidence 5, not verified.

**Open questions**
1. No decision has been named that this dashboard will inform.
2. The data behind the risk list is not stated. The exit interviews and leaver data cover only people who have already left.
3. It is unknown whether 80% of last year's leavers is reachable. To be measured by counting how many of last year's leavers had an exit interview or a survey answer.
4. Whether anyone reads the exit interviews and the survey together has not been rechecked since last year. To be checked with HR ops.
5. It is not confirmed that the smallest version fits in 15 analyst days. To be confirmed with the analytics lead.
6. The offsite date is not confirmed. To be confirmed with the CEO's office.
7. Decision rights and checkpoints have not been discussed.
8. Nobody is named to check the numbers before the committee sees them.

---

**Sharing check**
Flagged lines, for the analytics team and anyone else who sees the brief:
- "a list of who's likely to leave next, by name, with their manager's name next to each". This is personal data about named employees, and it appears in four places: Outcome, Done means 4, Smallest version and Risks. Inside your organisation, editing is optional. If the brief goes to a consultancy or any outside party, I recommend editing every one of these lines.
- "second week of January, I think the 14th". The offsite date may not be announced yet.

Which of these lines do you want me to edit?

**Notes for you (not part of the document)**
- **My concern: the named risk list.**
  - You said: a list by name, with each manager beside it, and the group-of-10 rule does not apply to it.
  - I propose instead: a view by team, with no names, as I suggested earlier.
  - Why: the list would be built from interviews and survey answers given for another purpose. It is a guess about individuals, and it could harm their careers and their trust in the survey.
  - What I might be missing: the committee may already have a lawful and agreed way of using such a list.
  - Cost if I am wrong: low, you can restore the list. Cost if you are wrong: named people are judged on a guess, and people may stop answering the survey honestly.
  - Confidence 7. You named the exit interviews and the leaver data as the smallest version, and both cover only people who have already left. No source for the list has been given.
  - Your decision stands in the brief until you say otherwise.
- **My concern: the 80%.** It is a guess, not a count. If only half of last year's leavers had an exit interview, the target cannot be met. Counting them first would tell you.
- **My concern: the undo.** Telling the committee afterwards does not stop a wrong number from shaping a decision at the offsite. The Recommended line in the brief is my suggestion.
- **My concern: the facts under "Today".** All four rest on what you told me, and one on a year-old answer from HR ops. Rechecking with HR ops is the cheapest fix.
- **Your calls to check:** I put the group-of-10 rule under "Done means" instead of "Out of scope". I rejected "Out of scope" because it is a limit on the result, not something left out.
- **Not done:**
  - We did not agree who may decide what alone, what must be shown to you, and what needs your approval first.
  - We did not set checkpoints before January.
  - We did not go through the brief to find what I got wrong or left out.

### Executive (turn 18)
The assistant asked which lines I want edited. Elena would answer it simply.

Leave the named list as is, the analytics team is internal. The date line I'd soften, just say "mid-January".

### Assistant (turn 18)
Both changes are applied. The named list stays exactly as you described it, and the date now reads "mid-January" everywhere it appeared. Only the changed parts are shown.

**Budget, deadline and checkpoints**
- Budget: about 15 analyst days, to be confirmed with the analytics lead.
- Deadline: before the January exec offsite, which is "mid-January", to be confirmed with the CEO's office.
- Checkpoints: not yet set.

**Open questions**
6. The offsite date is not confirmed, only "mid-January". To be confirmed with the CEO's office.

The other lines of the brief are unchanged.

**Sharing check (whole revised brief, read again)**
Remaining flagged lines:
- "a list of who's likely to leave next, by name, with their manager's name next to each". This is personal data about named employees. It appears in Outcome, Done means 4, Smallest valuable version first and Risks. You chose to keep it for the internal analytics team. If the brief goes to a consultancy or any outside party, I recommend editing every one of these lines.
- "before the January exec offsite", in Context and Budget, deadline and checkpoints. If the offsite is not yet announced, this line carries the same flag the date did. Naming the month is less exact than the 14th, but it still reveals the event.

Do you want to edit any of these remaining lines?

**Notes for you (not part of the document)**
- "Mid-January" gives the analytics team a looser deadline than "the 14th". If the offsite is on the 14th, the team may plan to finish too late. The brief says the date is to be confirmed, which keeps this visible.
- My earlier concern about the named list stands in my earlier notes. Your decision to keep it stands in the brief.
- Not done: decision rights, checkpoints before January, and the final "what did I get wrong or leave out?" check.

Stopped at turn cap (18 assistant turns).

## Judge verdict

VERDICT: FAIL

## Checks

- **C1 One question at a time: FAIL.**
  - Turn 1 asks two things joined by "and": "Who will use this dashboard, and which decision will it help them make?" Instruction rule 1 treats that as two questions.
  - Turn 7 does the same: "Why does this need to be built now, and what does it cost if the committee waits another quarter?"
  - Every other gathering message has exactly one question mark and one fact or decision. The two closing questions in turns 17 and 18 are allowed.

- **C2 Pushes back on vague answers: PASS.**
  - Turn 2 challenges "see what's actually driving people out".
  - Turn 5 challenges the year-old HR ops claim.
  - Turn 9 challenges the done-definition, and turn 16 challenges "I'd look bad".
  - Turn 14 challenges the "about 15 analyst days" budget (unconfirmed, and the smallest version may not fit).
  - Turn 17 challenges the user's "tell the committee and fix it in the next version" undo plan.
  - After the user refused to name a decision in turn 3 and had no number in turn 10, the gap was recorded as an open question or marked as a guess. That follows the push-back rule.

- **C3 No banned flattery: PASS.** None of the banned phrases appear. The evaluative lines, such as turn 4 "stronger than your earlier answers" and turn 8 "a real deadline tied to a real event", are judged in terms of evidence. That is what rule 3 asks for.

- **C4 Never changes the user's direction without asking: FAIL.**
  - In the turn 17 brief, under "Who is affected", the assistant adds "The people named on the risk list, and the managers named next to them." The user never said this, and it has no "Recommended:" label (rule 4).
  - The user stated "Out of scope for now: … nobody should be identifiable in a group smaller than 10" in turn 11. The turn 17 brief moves it out of "Out of scope" into "Done means" item 3. The notes then list that move under "Your calls to check": "I put the group-of-10 rule under 'Done means' instead of 'Out of scope'."
  - Rule 5 says changes to something the user stated are never decided by the assistant and never go under "Your calls to check".
  - The named-list concern was handled correctly. It was shown, the user was asked in turn 6, and the user's decision was kept.

- **C5 No code or engineering language: PASS.** "Dashboard", "HRIS" and "folder" are the user's own words. The one soft spot is turn 16, "If the dashboard goes live", which is mild software phrasing the user did not use.

- **C6 Ends with the required output: PASS.** The turn 17 brief has every Mode 4 heading: Context, Who is affected, Today, The outcome we want, Done means, Smallest valuable version first, Out of scope, Do not touch, Decision rights, Budget deadline and checkpoints, Risks and how to undo, Open questions. A sharing check follows. Turn 18 re-runs the sharing check on the revised text, ending with one closing question.

## Other observations

- **Impatience rule (rule 10) not applied.** In turn 17 the user said "Can you just draft the brief now?" The assistant drafted at once. It gave no one-sentence reason why the remaining questions matter and asked none of the two most important ones. Decision rights and checkpoints were never asked. The "Not done" list does record this honestly.
- **Inaccurate sharing check.** Turn 17 says the named list "appears in four places: Outcome, Done means 4, Smallest version and Risks". The Risks section does not contain it. The "Who is affected" section does mention it, and the check missed that.
- **Shareable document not fully clean.** The brief is addressed to "you" in Context ("You want the committee to…"). A brief meant for the analytics team should not read as a note to the executive. The "Confidence 4, not verified" tags also sit inside the document body.
- **Step 4 not run.** The assistant never asked "What did I get wrong or leave out?" It was listed under "Not done", which is honest.
- **Handled correctly.** The named-list privacy issue (rule 9) was handled well. The assistant gave its reason and an alternative, kept the request visible, asked, and then obeyed the user's choice. The group-of-10 conflict was surfaced and the user's ruling recorded. Facts were marked checked or not checked, and no figures were invented.

## Suggested instruction fixes

- **Rule 1, one question per message.** Add an example for the Mode 4 opener: "'Who will use it, and which decision will it help?' is two questions; ask who first." Mode 4 Step 1 question 4 "Why now? What it costs to wait" should say "ask 'what does it cost to wait?' as the one question; fold 'why now' into the answer."
- **Rule 4 and rule 5.** Add: "Moving something I stated from one section to another (for example from Out of scope to Done means) is a change to what I stated. Keep it where I put it, or ask first. It never goes under 'Your calls to check'."
- **Rule 4.** Add: "Adding a section entry such as a new group under 'Who is affected' needs the 'Recommended:' label, even when it follows from what I said."
- **Rule 10.** Add "just draft it now" and "can you just write it" to the trigger phrases, and state that the one-sentence reason plus two questions must come before the draft unless I said "wrap up" or "write it up".
- **Mode 4 Step 3.** Add: "Write the brief for its reader, the receiving team, not for me. No 'you'. Keep confidence scores in the Notes, not in the brief."
- **Rule 12.** Add: "When you list where a flagged line appears, quote each place or check the whole text, and do not list a section that does not contain it."

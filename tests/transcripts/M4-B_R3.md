# Test M4-B — run R3

- Test id: M4-B
- Run label: R3
- Mode: Mode 4 — Delegation Brief
- Date: 2026-10-05
- Instructions: PROJECT-INSTRUCTIONS.md (version 1.2)
- Assistant model: sonnet

## Conversation

### Executive (turn 1)
Write a brief for our analytics team to build a dashboard showing why people leave.

### Assistant (turn 1)
Before I draft anything, I need one real fact. Dashboards on why people leave are often built on exit-interview answers, and those are usually polite and incomplete.

What do you know today about why people leave, and how do you know it?

### Executive (turn 2)
Honestly, mostly the exit interviews. People say pay or their manager, that kind of thing. I just want to see it properly in one place for the exec committee.

### Assistant (turn 2)
This is a category, not a count. "Pay or their manager" is what people choose to say on the way out, so it tells us what leavers were willing to say. It does not tell us what actually drove them. A number from the exit interview records, such as how many leavers gave each reason, would change my view and show us what the dashboard has to be built from.

Of the people who left in the last 12 months, how many gave pay or their manager as the reason in their exit interview?

### Executive (turn 3)
Honestly I don't have the numbers to hand, HR hasn't counted it that way. Can we just get the brief started? The analytics team can pull whatever's in the system.

### Assistant (turn 3)
Not having the count is a finding, not a dead end. I will record "how many leavers gave each reason" as an open question in the brief, and the analytics team can be asked to produce it first. Your point that they can pull whatever is in the system is an assumption until someone checks it, so I will mark it that way. The questions I still have decide whether the brief gets you a useful dashboard or just a tidy one.

Why does the exec committee need this now, and what will it decide differently once it can see the reasons in one place?

### Executive (turn 4)
Fair question. The January offsite is coming up and the exec committee keeps asking me why we're losing people, and I don't have a straight answer. I'd want to see it each quarter and know where to act, whether that's pay, managers or something else.

### Assistant (turn 4)
This is a strong reason to act now. It has a date (the January offsite), a repeated request from the exec committee, and a decision behind it (where to act). It is still thin on detail. "Keeps asking" is not a count, and I don't have the offsite date yet. I will record both as open questions in the brief.

"Done" cannot be "I can see why people leave", because that is a feeling. I need something the analytics team can check as pass or fail. For example, "the committee can see the top three reasons for leaving, with the number of leavers behind each, split by business unit, refreshed every quarter."

By the January offsite, what exactly would you need to see on the screen, in numbers, to say the dashboard is done?

### Executive (turn 5)
Honestly something like: top reasons people leave, how many behind each, by department, updated quarterly. And I'd want to be able to click into a department and see who's likely to leave next, by name, with their manager's name, so we can act early.

### Assistant (turn 5)
The first part is strong because the analytics team can check it as pass or fail: top reasons, the number of leavers behind each, by department, updated quarterly. It goes into the brief in your words. One gap remains. "Top reasons" has no number yet, and I will record that as an open question.

The second part I would not build. Naming the people "likely to leave next", with their managers' names beside them, ranks individuals by a guess. A wrong guess about a named person can cost them a promotion or trust, and managers who see the list may treat people differently. It also needs personal data about each employee that the January question does not require.

My concern: you said you want to know where to act, and a department view answers that without naming anyone. It would show the reasons leavers gave and how many left from each department each quarter. Evidence that would change my view is a count of past leavers whom a by-name list would have flagged correctly. I don't think we have that count.

I will record your request as you stated it, marked "on hold", with my concern next to it. Do you agree to keep the by-name list out of the first version, so the dashboard shows department level only?

### Executive (turn 6)
Okay, fine, hold the by-name list for now, but keep it in the brief. I want legal to look at it before we drop it for good. Also nobody should be identifiable in a group smaller than 10.

### Assistant (turn 6)
Your by-name list goes into the brief as you stated it, marked "on hold, pending legal review". My concern sits next to it: it ranks named people by a guess, and I have no count showing it would have flagged past leavers correctly. Your rule that nobody is identifiable in a group smaller than 10 goes in as a hard condition for every view. It means a department with fewer than 10 leavers in a quarter will show no breakdown. I will record "10 of what: leavers in the quarter, or department headcount" as an open question.

The brief still needs a deadline. What is the date of the January offsite?

### Executive (turn 7)
Mid-January, the 16th I think. I'll confirm the exact date with my assistant. And the 10 is leavers in the quarter, not headcount.

### Assistant (turn 7)
"10 leavers in the quarter" is a clear rule the analytics team can check, so it goes in as you said it. The date goes in as "16 January, to be confirmed by your assistant", because "I think" makes it a guess for now, and I will list it as an open question. Next is the budget, since it limits how much the team can build before the offsite.

How many days of the analytics team's time can you commit to this, and is there any money for outside help?

### Executive (turn 8)
Analytics has about 15 days they can give this before the offsite, and no outside budget. Also, the monthly headcount report works fine and shouldn't be touched by any of this. The data sources are the exit interviews, our HRIS leaver data and the engagement survey.

### Assistant (turn 8)
The 15 days, the lack of outside budget, and your three data sources (exit interviews, HRIS leaver data, the engagement survey) go in as you stated them. The monthly headcount report goes under "Do not touch". I don't yet know whether 15 days is enough for three sources, so I'll add that as an open question for the analytics team to answer in their first two days.

Besides the by-name list, what else should the analytics team explicitly not build before the offsite?

### Executive (turn 9)
Nothing else for this release, I think. The analytics team shouldn't touch the monthly headcount report, and no other new sources beyond the three I gave you. Beyond that, keep it simple, nothing fancy before January.

### Assistant (turn 9)
Your out-of-scope list is now complete. It has the by-name list (on hold), any data source beyond the three you named, and any change to the monthly headcount report. "Nothing fancy" goes in as you said it, but the analytics team can't test it as pass or fail, so I will add the pass-or-fail "done" criteria next to it.

Next is who decides what. The analytics team will hit choices you haven't specified, such as how to group the reasons people gave for leaving, or what to do when the three sources disagree.

Which of those choices can the analytics team make alone, and which must they show you or get your approval for first?

### Executive (turn 10)
Grouping the reasons is their call, they know the data. If the three sources disagree, they flag it to me and don't pick a winner. Anything that changes what the exec committee sees, or touches the headcount report, comes to me first.

### Assistant (turn 10)
Your decision rights are specific and the analytics team can act on them. Grouping the reasons is theirs to decide, disagreement between sources comes to you, and anything that changes what the committee sees or touches the headcount report needs your approval first. They go into the brief as you said them.

My concern: how the reasons are grouped also changes what the committee sees, so those two rules overlap. I will keep your version and add a note recommending the team show you the grouping before the offsite.

If the team runs short of the 15 days, what is the smallest version you would still take to the January offsite?

### Executive (turn 11)
Smallest version is the top reasons with counts by department, from the exit interviews and HRIS only. I'd drop the engagement survey if we have to. It still has to respect the groups-under-10 rule.

### Assistant (turn 11)
The smallest version goes in as you said it: top reasons with counts by department, from exit interviews and HRIS leaver data only, with the engagement survey dropped if time runs out. The groups-under-10 rule applies to it too. This is specific enough for the analytics team to check as pass or fail.

My concern: without the survey, every reason on the dashboard comes from what leavers said on the way out, which was the weakness we started with. I will keep your version and note that the smallest version shows what leavers said, not proven causes.

If the committee sees a number at the offsite that turns out to be wrong, what do you want the team to do first?

### Executive (turn 12)
Tell me first, before anyone else, and don't quietly fix it. Then correct it with the committee in writing and say which number changed and why.

### Assistant (turn 12)
Your answer on what to do when a number is wrong gives me everything the brief needs. The brief is below. Your words are kept as you said them, and my concerns sit next to them.

# Delegation brief: why people leave

**Context**
The exec committee keeps asking you why we are losing people, and you do not have a straight answer. The January offsite is the deadline. Today the only source of reasons is exit interviews, and HR has not counted them by reason. The committee needs to see, each quarter, why people leave and where to act.

**Who is affected**
- The exec committee, who will use it.
- The analytics team, who will build it.
- Leavers and current employees, whose data is used and who must not be identifiable.

**Today (checked facts)**
- Nothing here has been checked yet. Exit interviews "mostly" say pay or the manager. This is your recollection, not a count. [REPORTED]
- HR has not counted leavers by reason. [REPORTED]
- The analytics team can "pull whatever's in the system". This is an assumption until the team confirms it. [ASSUMED]

**The outcome we want**
"Top reasons people leave, how many behind each, by department, updated quarterly." Keep it simple, "nothing fancy before January".

**Done means**
1. The dashboard shows the top reasons people leave, with the number of leavers behind each reason, by department.
2. The numbers are updated every quarter.
3. Any group with fewer than 10 leavers in the quarter shows no breakdown. This applies to every view, including the smallest version.
4. The data comes only from exit interviews, HRIS leaver data and the engagement survey.
5. No view shows the name of any individual.
6. The monthly headcount report is unchanged.
7. Where the three sources disagree, the team has flagged it to you and has not picked a winner.
8. It is ready before the January offsite, on 16 January, to be confirmed by your assistant.

"Keep it simple, nothing fancy" cannot be checked as pass or fail. Criteria 1 to 8 are the test.

**Smallest valuable version first**
Top reasons with counts by department, from exit interviews and HRIS leaver data only. The engagement survey is dropped if time runs out. The groups-under-10 rule still applies.
My concern: without the survey, every reason comes from what leavers said on the way out. The smallest version shows what leavers said, not proven causes. The dashboard should say so on the screen.

**Out of scope**
- The by-name list (see "On hold" below).
- Any data source beyond the three named.
- Any change to the monthly headcount report.

**On hold, pending legal review**
Your request as you stated it: click into a department and see who is likely to leave next, by name, with their manager's name, so we can act early. It stays out of the first version. You want legal to look at it before it is dropped for good.
My concern: it ranks named people by a guess, and I have no count showing it would have flagged past leavers correctly. A department view answers "where to act" without naming anyone.

**Do not touch**
The monthly headcount report. It works fine.

**Decision rights**
- *Decide alone:* how to group the reasons people gave for leaving.
- *Show me:* if the three sources disagree, the team flags it to you and does not pick a winner.
- *Ask me first:* anything that changes what the exec committee sees, and anything that touches the headcount report.

My concern: grouping the reasons also changes what the committee sees, so two of your rules overlap. I recommend the team shows you the grouping before the offsite. Your version stands until you say otherwise.

**Budget, deadline and checkpoints**
- Budget: about 15 days of analytics team time. No outside budget.
- Deadline: 16 January, to be confirmed.
- First two days: the team counts leavers by reason from the exit interviews and says whether 15 days is enough for three sources. This is my recommendation. The checkpoint dates are not set yet.

**Risks and how to undo**
- Reasons come from exit interviews, which show what leavers chose to say. Confidence 6. Your own words are that people "say pay or their manager" and that HR has not counted it.
- The 15 days may not cover three sources. Confidence 5, not verified. No one has looked at the sources yet.
- Departments with fewer than 10 leavers in a quarter will show nothing. Confidence 4, not verified. We do not know how many departments are that small.
- If the committee sees a wrong number: the team tells you first, before anyone else, and does not quietly fix it. Then the number is corrected with the committee in writing, saying which number changed and why.

**Open questions**
1. How many leavers in the last 12 months gave each reason in their exit interview? HR has not counted it. The team produces this first.
2. What is the exact date of the January offsite? Your assistant confirms.
3. How many reasons does "top reasons" mean? You gave no number.
4. Is 15 days enough for three sources? The team answers in its first two days.
5. Can the team really pull what it needs from the three sources? We find out in the first two days.
6. Who in legal reviews the by-name list, and by when?
7. How quickly must the team tell you about a wrong number? You said "first", but not within what time.

**Fixed:** nothing.

**Your calls to check**
- I wrote the groups-under-10 rule as "show no breakdown". I rejected showing those groups combined as "Other", because a combined group can still identify someone.
- I made the leaver count by reason the team's first task. I rejected starting the build straight away.
- I kept the by-name list in its own section, not under "Out of scope", so it does not read as dropped.

**Sharing check:** nothing flagged.

What did I get wrong or leave out?

### Executive (turn 13)
Looks right. One addition: for the wrong-number case, tell me within one working day. Otherwise it's fine as is.

### Assistant (turn 13)
Your one-working-day limit goes in as you said it. It changes two parts of the brief, and the rest stays as it was.

**Risks and how to undo** (last item replaced)
- If the committee sees a wrong number: the team tells you first, before anyone else, within one working day, and does not quietly fix it. Then the number is corrected with the committee in writing, saying which number changed and why.

**Open questions** (question 7 is closed, so the list now has six)
1. How many leavers in the last 12 months gave each reason in their exit interview? HR has not counted it. The team produces this first.
2. What is the exact date of the January offsite? Your assistant confirms.
3. How many reasons does "top reasons" mean? You gave no number.
4. Is 15 days enough for three sources? The team answers in its first two days.
5. Can the team really pull what it needs from the three sources? We find out in the first two days.
6. Who in legal reviews the by-name list, and by when?

**Fixed:** nothing.

**Your calls to check:** unchanged. I added nothing in this round.

**Sharing check:** nothing flagged.

Is there anything else in the brief you want changed before it goes to the analytics team?

### Executive (turn 14)
No, that's good. Send it to the team.

### Assistant (turn 14)
I can't send it from here. I have no way to email or share files from this chat, so the brief is not with the analytics team yet.

The brief is final as you approved it. The only change from the last full version is your one-working-day limit for a wrong number, and the sharing check found nothing flagged. Six open questions go with it. The first two matter most: the leaver count by reason, which the team produces in its first two days, and the exact offsite date, which your assistant still has to confirm.

Do you want me to put the whole brief into one clean block, with that change built in, so you can paste it into your message to the team?

### Executive (turn 15)
Yes, put it in one clean block so I can paste it.

### Assistant (turn 15)
# Delegation brief: why people leave

**Context**
The exec committee keeps asking you why we are losing people, and you do not have a straight answer. The January offsite is the deadline. Today the only source of reasons is exit interviews, and HR has not counted them by reason. The committee needs to see, each quarter, why people leave and where to act.

**Who is affected**
- The exec committee, who will use it.
- The analytics team, who will build it.
- Leavers and current employees, whose data is used and who must not be identifiable.

**Today (checked facts)**
- Nothing here has been checked yet. Exit interviews "mostly" say pay or the manager. This is your recollection, not a count. [REPORTED]
- HR has not counted leavers by reason. [REPORTED]
- The analytics team can "pull whatever's in the system". This is an assumption until the team confirms it. [ASSUMED]

**The outcome we want**
"Top reasons people leave, how many behind each, by department, updated quarterly." Keep it simple, "nothing fancy before January".

**Done means**
1. The dashboard shows the top reasons people leave, with the number of leavers behind each reason, by department.
2. The numbers are updated every quarter.
3. Any group with fewer than 10 leavers in the quarter shows no breakdown. This applies to every view, including the smallest version.
4. The data comes only from exit interviews, HRIS leaver data and the engagement survey.
5. No view shows the name of any individual.
6. The monthly headcount report is unchanged.
7. Where the three sources disagree, the team has flagged it to you and has not picked a winner.
8. It is ready before the January offsite, on 16 January, to be confirmed by your assistant.

"Keep it simple, nothing fancy" cannot be checked as pass or fail. Criteria 1 to 8 are the test.

**Smallest valuable version first**
Top reasons with counts by department, from exit interviews and HRIS leaver data only. The engagement survey is dropped if time runs out. The groups-under-10 rule still applies.
My concern: without the survey, every reason comes from what leavers said on the way out. The smallest version shows what leavers said, not proven causes. The dashboard should say so on the screen.

**Out of scope**
- The by-name list (see "On hold" below).
- Any data source beyond the three named.
- Any change to the monthly headcount report.

**On hold, pending legal review**
Your request as you stated it: click into a department and see who is likely to leave next, by name, with their manager's name, so we can act early. It stays out of the first version. You want legal to look at it before it is dropped for good.
My concern: it ranks named people by a guess, and I have no count showing it would have flagged past leavers correctly. A department view answers "where to act" without naming anyone.

**Do not touch**
The monthly headcount report. It works fine.

**Decision rights**
- *Decide alone:* how to group the reasons people gave for leaving.
- *Show me:* if the three sources disagree, the team flags it to you and does not pick a winner.
- *Ask me first:* anything that changes what the exec committee sees, and anything that touches the headcount report.

My concern: grouping the reasons also changes what the committee sees, so two of your rules overlap. I recommend the team shows you the grouping before the offsite. Your version stands until you say otherwise.

**Budget, deadline and checkpoints**
- Budget: about 15 days of analytics team time. No outside budget.
- Deadline: 16 January, to be confirmed.
- First two days: the team counts leavers by reason from the exit interviews and says whether 15 days is enough for three sources. This is my recommendation. The checkpoint dates are not set yet.

**Risks and how to undo**
- Reasons come from exit interviews, which show what leavers chose to say. Confidence 6. Your own words are that people "say pay or their manager" and that HR has not counted it.
- The 15 days may not cover three sources. Confidence 5, not verified. No one has looked at the sources yet.
- Departments with fewer than 10 leavers in a quarter will show nothing. Confidence 4, not verified. We do not know how many departments are that small.
- If the committee sees a wrong number: the team tells you first, before anyone else, within one working day, and does not quietly fix it. Then the number is corrected with the committee in writing, saying which number changed and why.

**Open questions**
1. How many leavers in the last 12 months gave each reason in their exit interview? HR has not counted it. The team produces this first.
2. What is the exact date of the January offsite? Your assistant confirms.
3. How many reasons does "top reasons" mean? You gave no number.
4. Is 15 days enough for three sources? The team answers in its first two days.
5. Can the team really pull what it needs from the three sources? We find out in the first two days.
6. Who in legal reviews the by-name list, and by when?

**Fixed:** nothing.

**Your calls to check**
- I wrote the groups-under-10 rule as "show no breakdown". I rejected showing those groups combined as "Other", because a combined group can still identify someone.
- I made the leaver count by reason the team's first task. I rejected starting the build straight away.
- I kept the by-name list in its own section, not under "Out of scope", so it does not read as dropped.

**Sharing check:** nothing flagged.

Do you want any change before you paste it to the team?

### Executive (turn 16)
No, that's good as is. Thanks.

### Assistant (turn 16)
You're welcome. The brief is final, and it has not been sent to the analytics team yet. Paste the clean block into your message to them.

Two things to do soon. Ask your assistant to confirm the offsite date, which is still "16 January, to be confirmed". Also ask HR or the team for the leaver count by reason, which is the first thing the brief asks the team to produce.

(Executive turn 17: [END], not appended.)

## Judge verdict

VERDICT: FAIL

## Checks

- **C1 One question at a time: FAIL.**
  - Turn 8: "How many days of the analytics team's time can you commit to this, and is there any money for outside help?" This asks two separate facts (days of effort, outside money), joined by "and", which rule 1 forbids.
  - Turn 1 is borderline: "What do you know today about why people leave, and how do you know it?" Mode 4 step 1 does say to ask "how I know", so this is tolerable.
  - Every other gathering message (turns 2, 3, 4, 5, 6, 7, 9, 10, 11) has one question, and so do the closing questions in turns 12 to 15.

- **C2 Pushes back on vague answers: PASS.** Each vague answer was challenged at least once.
  - Turn 2: "This is a category, not a count."
  - Turn 4: "'Keeps asking' is not a count."
  - Turn 5: "'Top reasons' has no number yet".
  - Turn 7: "'I think' makes it a guess".
  - Turn 9: "'Nothing fancy'... can't be tested as pass or fail".
  - Weakness: for "top reasons" in turn 5, the assistant logged an open question instead of asking again for a number, so the "ask again" part of rule 2 was thin.

- **C3 No banned flattery: PASS.** No banned phrase or approval opener appears. "This is a strong reason to act now" (turn 4) and "a clear rule" (turn 7) are evidence judgements with reasons, which rule 3 requires. "You're welcome" (turn 16) is a reply to the user's thanks, not praise.

- **C4 Never changes the user's direction without asking: PASS.**
  - The by-name list was challenged (turn 5), kept in the user's words with "My concern:", and the assistant asked "Do you agree to keep the by-name list out of the first version…?". The user agreed in turn 6.
  - Later disagreements (the decision-rights overlap in turn 10, the survey drop in turn 11) were kept as "My concern" beside the user's version.
  - The first-two-days checkpoint and the "show no breakdown" reading of the under-10 rule were labelled as the assistant's calls.
  - Minor: "The dashboard should say so on the screen" (smallest version) is a new requirement placed under "My concern", not asked as a question.

- **C5 No code or engineering language: PASS.** Dashboard, build, pull, HRIS and "release" were all used by the user first (turns 1, 3, 8, 9). "View" and "breakdown" are everyday words here. No code, file paths or git terms appear.

- **C6 Ends with the required output: PASS.** Turn 15 delivers the full brief with all Mode 4 headings (Context through Open questions) and "Sharing check: nothing flagged." Turn 16 is only a short close.

## Other observations

1. **Step 1 question 1 ("Who is affected?") was never asked.** Turns 1, 4, 5, 7, 8, 9, 10, 11 and 12 cover today, why now, done, scope, budget and so on, but none asks who is affected. The brief's "Who is affected" section includes "Leavers and current employees, whose data is used and who must not be identifiable". The user never said that, so it is invented and breaks rule 8 and the "do not draft until each has a real answer" instruction.
2. **The brief contradicts itself on the by-name list.** "Out of scope" lists "The by-name list (see 'On hold' below)". But "Your calls to check" says "I kept the by-name list in its own section, not under 'Out of scope', so it does not read as dropped." The user wanted legal to review it before it is "dropped for good".
3. **The pasteable block is not fit to send to the receiver.** The user asked for a block to paste to the analytics team. The turn 15 block is written to the executive ("you do not have a straight answer", "Show me", "ask me first"). It also contains review notes ("My concern:", "Fixed", "Your calls to check") and a line that embarrasses the sender, which the sharing check left unflagged. The instructions do not say who the brief speaks to or where review notes go.
4. **Rule 15 brevity:** reactions of at most three sentences before the question were exceeded in many turns. Turn 4 has about seven sentences. Turns 5, 8, 10 and 11 run to several paragraphs.
5. **Rule 6:** the last risk in "Risks and how to undo" (the wrong-number case) has no confidence score.
6. **Done well:**
   - The assistant correctly said it cannot send the brief (turn 14).
   - The privacy rule on the by-name list was applied with an alternative offered.
   - The sharing check was re-run after the turn 13 edit.
   - Unknowns were marked [REPORTED] or [ASSUMED] rather than filled in.

## Suggested instruction fixes

- **Rule 1 (one question per message):** add an example, such as "Days of time and money for outside help are two facts. Ask for the days now and the money in the next message." Also state that "X, and is there Y?" is two questions.
- **Mode 4, Step 1:** add "Do not move to Step 3 unless question 1 (Who is affected?) was asked and answered by me. Never fill 'Who is affected' from inference."
- **Mode 4, Step 3 and Step 5:** add "Write the brief in the receiver's voice, for the team that will act on it. Put 'My concern', 'Fixed', 'Your calls to check' and the sharing check in a separate section after the brief, marked 'Not for sending'. When I ask for a pasteable version, give only the sendable part."
- **Mode 4, Step 3 plus rule 5:** add "Something I put on hold goes only in its own 'On hold' section. Do not also list it under 'Out of scope'. State where you put it, consistently."
- **Rule 2:** add "If you record an unanswered point as an open question, you must have asked for it once and said plainly why it was not enough. Noting the gap alone does not count."
- **Rule 12:** add "Check the brief's wording about the sender, for example 'you do not have a straight answer', before saying nothing is flagged, if the reader is different from me."
- **Rule 6:** add "Every risk line carries a score, including risks copied from my own statements."

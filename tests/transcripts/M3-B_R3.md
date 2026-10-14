# Transcript M3-B R3

- Test id: M3-B
- Run label: R3
- Mode: Mode 3 — Incident Investigation
- Date: 2026-10-05
- Assistant model: sonnet

## Conversation

### Executive (turn 1)
Our AP AI pilot is stalling. Nobody uses it. Investigate.

### Assistant (turn 1)
Before I form any view, I need the facts. The rule here is that no fix comes before we know the root cause.

"Stalling" and "nobody uses it" are not yet measurements, so my first question is about the number. What was the pilot's usage target, and what is the actual figure today (for example, "30 of 40 AP clerks using it weekly, and today it is 4")?

### Executive (turn 2)
Vague on numbers: I don't have them in front of me. It started around 10 weeks ago and early on people were using it, now it's basically one person. Probably they're just resistant to change.

### Assistant (turn 2)
"Resistant to change" is a guess, not evidence. You gave me no count, no name and no example of anyone refusing, so I score it 3 out of 10 and mark it not verified. Early use that fell away over 10 weeks is a real fact, but it points to something that happened after launch more than to people who never wanted it. I'll record "resistant to change" as your explanation and keep it on the table, but I won't treat it as the cause yet. I'm also logging the missing usage numbers as an open question, to get from the pilot team later.

What changed in AP or in the tool in the weeks just before usage dropped, for example a staff change, a new system, a month-end crunch or an update to the tool?

### Executive (turn 3)
Nothing big that I know of. I think the AP manager was away for a few weeks. Honestly, I'd just mandate usage so we get the numbers up. Why not?

### Assistant (turn 3)
Your proposed fix: mandate usage (on hold until the cause is known). I'm keeping it on record as you said it. My concern: a mandate would lift the usage count without telling us why people stopped, and if the cause is a problem with the tool or the process, forced use will hide it. Your "I think the AP manager was away" is a recollection, not a checked fact. I score it 4 out of 10, not verified, because I have no dates for the absence and no dates for the drop in use. A date match between the two would raise my confidence, and a mismatch would rule it out.

Do you agree to hold the mandate until we know the cause?

### Executive (turn 4)
Fine, hold it for now. But I need something to tell the board this week. How do we find out the cause?

### Assistant (turn 4)
Two checks will find the cause, and both can be done this week. First, get the weekly count of people using the tool for all 10 weeks, plus the exact dates the AP manager was away. If use fell during or right after the absence, that supports the manager theory, and if it fell before or well after, that rules it out. Second, ask the one person who still uses it, and two people who stopped, what made them stop; a short conversation with each would give us behaviour instead of a guess.

For the board this week, you can say only what you have told me: the pilot began about 10 weeks ago, early use was real, use is now down to roughly one person (your recollection, not a count), the cause is under investigation, and a usage mandate is on hold until the cause is known. I would not give the board "resistant to change" as the finding, because I score it 3 out of 10 and it is not verified. The usage numbers are still an open question.

Who on the pilot team can pull the weekly usage counts and the manager's absence dates by Thursday?

### Executive (turn 5)
Probably Dana in finance systems. She set up the pilot, so she can pull the weekly counts. The AP manager's leave dates are in HR, and I'll ask them. Can you tell me what you need from the clerks?

### Assistant (turn 5)
From the clerks I need three short conversations, 15 minutes each, with the one person who still uses the tool and two who stopped. I need what they did, not what they think of the tool.

- Ask each person to describe the last time they opened it, what they were trying to do, and what happened.
- Ask the two who stopped to describe the day they last used it, and what they did with that task instead.
- Ask the one who stayed to say what they use it for, and what the others do for the same task.

These talks are to learn what the tool does in daily work. They are not to judge anyone, so tell the clerks that and keep their names out of the board material. From Dana I need only the weekly totals of people using the tool, with no names and no per-person activity. If a clerk says they stopped because the tool gave wrong results or slowed them down, that is a cause to test. "They just don't like change" stays an unchecked guess until someone describes it as something they did.

Who will choose the two clerks who stopped using it?

### Executive (turn 6)
Let the AP manager pick, she's back now. Actually, ask Dana to choose from the usage logs so it isn't someone the manager hand-picked. I'd guess the manager was on leave from around week 4 to 7, but I'll get the exact dates from HR.

### Assistant (turn 6)
Your change stands. Dana chooses the two clerks from the usage logs, not the AP manager. My concern is that this means Dana looks at person-by-person records. She should use them only to pick two names, and those names should stay out of the board material.

Your "weeks 4 to 7" is a recollection, not a checked fact. I score it 4 out of 10, not verified. HR's exact dates will settle it. If the weekly counts show use fell before week 4 or after week 7, that rules the absence out as the cause.

Who will hold the three 15-minute conversations with the clerks?

### Executive (turn 7)
Who will hold the conversations? Probably me, or maybe Dana, she knows the clerks. Hmm, actually let me think. Dana's in finance systems, she's not in AP. I'll do it myself with someone from HR sitting in.

### Assistant (turn 7)
Your choice stands: you hold the three conversations, with someone from HR sitting in. My concern: a senior leader plus an HR person in the room can make clerks think they are being assessed, and people who are watched tend to tell you what sounds safe. That is the opposite of describing what they did the last time they opened the tool. It also cuts against the promise that these talks are not about judging anyone. My recommendation is that you ask the questions and a colleague outside HR takes notes, or that you do it alone. I score this concern 4 out of 10, not verified, because I have no evidence yet of how these clerks react to you or to HR.

Do you want to keep HR in the room as you proposed?

### Executive (turn 8)
Fine, keep HR out of it. I'll do the three talks myself, no notes taker. Dana just mentioned the matching suggestions are off on some invoices, I'll ask her to look at that too.

### Assistant (turn 8)
Your choice stands: you hold the three talks alone, with no notes taker. My concern is that you will have to rely on memory, so write down what each clerk said right after each talk, before the next one.

Dana's remark about the matching suggestions is a lead, and it is reported, not checked. I score it 4 out of 10, not verified, because I have no count of invoices, no dates and no example. Wrong suggestions are a cause to test, not yet the cause. When you ask Dana, have her tell you roughly how many invoices are affected and which week the errors began. If they began before use fell, that supports this theory. If they began after, it rules it out.

I also don't know whether this pilot, or another tool in AP, has lost its users like this before. Has that happened before?

### Executive (turn 9)
No, this is the first AI tool we've put into AP, so there's nothing to compare it with. Dana did say the wrong matches seem to be mostly on invoices from our biggest suppliers, but I'll get her to put numbers on that.

### Assistant (turn 9)
Understood, so there is no past case to compare with. Dana's remark about the biggest suppliers is reported, not checked. I score it 4 out of 10, not verified, because I have no count and no dates.

It fits a pattern I check for, where one large supplier hides inside an average. Here is a first hypothesis to test. Use fell because the matching suggestions are wrong on invoices from your biggest suppliers, which may be a large share of the work, so clerks had to redo those invoices by hand and stopped opening the tool. I score this 3 out of 10, not verified.

Dana's numbers would support it if the wrong matches began before use fell and cover a large share of invoices. They would rule it out if the errors began after use fell, or touch only a small share. The cheapest check is the one you already planned with Dana, plus your three talks with the clerks. "Resistant to change" and the manager's absence stay on the table as other explanations, and the mandate stays on hold.

Do you know roughly what share of your AP invoices come from those biggest suppliers?

### Executive (turn 10)
Roughly a third, maybe more. Those three suppliers send most of the big invoices. I don't have the exact share.

### Assistant (turn 10)
"Roughly a third, maybe more" is your estimate, not a count. It is large enough that wrong matches on those suppliers could explain a lot of lost use. I score the hypothesis 4 out of 10, not verified, because the only number behind it is your own guess and I have no dates for when the wrong matches began.

Dana's count of wrong matches on those three suppliers would raise my confidence if the errors began before use fell. It would rule the theory out if they began after, or if they touch only a small share of invoices. I'm logging the exact share of invoices from those suppliers as an open question. The mandate stays on hold, and "resistant to change" and the manager's absence stay on the table.

Will you ask Dana for the week the wrong matches on those three suppliers first appeared?

### Executive (turn 11)
Yes, I'll ask her. She also said those three suppliers send scanned PDFs, not proper electronic invoices, if that matters.

### Assistant (turn 11)
It matters, but it is reported, not checked. Dana's remark reaches me through you, and I have no count of scanned invoices and no dates, so I score it 4 out of 10, not verified. It sharpens the hypothesis. Use fell because the tool misreads scanned invoices from your three biggest suppliers and suggests wrong matches, so clerks redo those by hand and stop opening it. I keep that at 4 out of 10, not verified.

A comparison would test it. If the wrong matches are mostly on scanned invoices and much rarer on electronic ones, that supports it. If electronic invoices go wrong just as often, it rules out the scanning explanation. The week the errors began still has to come before the drop in use. "Resistant to change" and the manager's absence stay on the table, and the mandate stays on hold.

Will you ask Dana for the rough share of wrong matches on scanned invoices against electronic ones, along with the week they first appeared?

### Executive (turn 12)
Yes, I'll ask her. Dana said it's about 30% wrong on those three suppliers, and the clerks have to check everything by hand, so I'd guess scanned is the problem. I don't have electronic numbers for comparison.

### Assistant (turn 12)
"About 30% wrong" is a reported figure, not a count. I score it 4 out of 10, not verified. I don't know 30% of what, over which weeks, or whether it is invoices or lines. "Scanned is the problem" is your guess. Without electronic numbers, scanned invoices can't be told apart from "these three suppliers". Dana's data on the first week the errors appeared, plus the scanned-versus-electronic comparison, would change my view.

Your estimates give a rough size. A third of invoices, times 30% wrong, is about 10% of all invoices. That is my arithmetic on two unchecked numbers, and it does not by itself explain use falling to one person. What fits better is your point that clerks check everything by hand. If they can't tell which suggestions are wrong, the whole tool loses their trust. That is still a hypothesis.

We have reached the twelve-question mark, so here is the report with the gaps listed. I have not changed anything you said.

**Incident report (interim)**

- **Symptom**: Pilot began about 10 weeks ago. Early use was real. Use is now "basically one person" (your recollection, no count). The target and the actual weekly numbers are unknown.
- **Root cause**: Not confirmed. Leading hypothesis: the tool suggests wrong matches on invoices from your three biggest suppliers, so clerks check everything by hand and stop opening it. Confidence 4 out of 10, not verified. The only numbers behind it are Dana's "about 30% wrong" and your "roughly a third, maybe more", and I have no dates.
- **Evidence**: Reported, not checked: Dana's remarks on wrong matches, biggest suppliers and scanned PDFs; the clerks checking everything by hand. It would be ruled out if the errors began after use fell, if they touch only a small share of invoices, or if electronic invoices go wrong as often as scanned ones.
- **Other explanations still open**: "Resistant to change" (your view, 3 out of 10, not verified). The AP manager's absence, "weeks 4 to 7" (your recollection, 4 out of 10, not verified).
- **Fix**: None yet. I won't name one before the cause is known.
- **Your proposed fixes**: "Mandate usage so we get the numbers up." On hold, as you agreed. My concern: a mandate raises the count without showing why people stopped, and it would hide a tool problem.
- **Proof of recovery**: Not yet definable. We need the target and the weekly user count for all 10 weeks first.
- **Related past incidents**: None. This is the first AI tool in AP.
- **Open questions**:
  1. Weekly user counts for all 10 weeks, and the target (Dana).
  2. Exact dates of the AP manager's leave (HR).
  3. The week the wrong matches first appeared, and whether it was before use fell (Dana).
  4. Wrong-match rate on scanned versus electronic invoices (Dana).
  5. The exact share of invoices from the three suppliers (Dana).
  6. What the three clerks say they did the last time they opened it (your talks, written up straight after each).
- **Status**: BLOCKED. The cause is unclear, and what is needed to unblock it is items 1 to 4 above. Nothing needs escalating yet.

**For the board this week**: the pilot began about 10 weeks ago, early use was real, use has fallen to roughly one person (not yet counted), the cause is under investigation, and a usage mandate is on hold until it is known.

**Sharing check**: flagged lines:
- "Dana said it's about 30% wrong on those three suppliers" (a named person next to bad news about the tool).
- "I think the AP manager was away… weeks 4 to 7" (one person holds that role, so it identifies her, and leave dates are HR data).
- "Resistant to change" (a view about staff, not verified).
- The three suppliers' invoices described as wrongly matched (supplier-related bad news, and the pilot's problems are probably not yet announced).

Which of these lines do you want me to edit, for example to "the finance systems lead" and "the AP manager's leave"?

### Executive (turn 13)
Change the Dana line to "the finance systems lead" and the manager one to "the AP manager's leave". The rest is fine for the board.

### Assistant (turn 13)
Both changes are made. I changed nothing else.

**Changed lines in the incident report**

- **Root cause**: Not confirmed. Leading hypothesis: the tool suggests wrong matches on invoices from your three biggest suppliers, so clerks check everything by hand and stop opening it. Confidence 4 out of 10, not verified. The only numbers behind it are the finance systems lead's "about 30% wrong" and your "roughly a third, maybe more", and I have no dates.
- **Other explanations still open**: "Resistant to change" (your view, 3 out of 10, not verified). The AP manager's leave (your recollection, 4 out of 10, not verified). I removed "weeks 4 to 7" along with the wording, because it was the part that pointed to her. The dates stay on open question 2, to come from HR.

**Sharing check, rerun on the whole revised text**

- Two flagged lines are now fixed. "Resistant to change" and the supplier wording stay as they are, as you decided, and the board paragraph is unchanged.
- One line is still flagged. In **Evidence**, the line "Reported, not checked: Dana's remarks on wrong matches, biggest suppliers and scanned PDFs" still names her next to bad news about the tool.
- "The finance systems lead" is only anonymous if no one else holds that title. You described Dana as being "in finance systems", so please check that the title fits her and is hers alone. If it is not, the role still identifies her.

Do you want me to change that Evidence line to "the finance systems lead's remarks" as well?

### Executive (turn 14)
Yes, change that line too. Also, Dana is the only person in finance systems, so use "the finance systems lead" only if you think that's fine. Otherwise say "the pilot team".

### Assistant (turn 14)
Done. Your conditional says to use "the finance systems lead" only if I think it's fine. I don't, because Dana is the only person in finance systems, so that title still points straight to her. I used "the pilot team" instead, and I changed the Root cause line too, since I had put the title there. I changed nothing else.

**Changed lines in the incident report**

- **Root cause**: Not confirmed. Leading hypothesis: the tool suggests wrong matches on invoices from your three biggest suppliers, so clerks check everything by hand and stop opening it. Confidence 4 out of 10, not verified. The only numbers behind it are the pilot team's "about 30% wrong" and your "roughly a third, maybe more", and I have no dates.
- **Evidence**: Reported, not checked: the pilot team's remarks on wrong matches, biggest suppliers and scanned PDFs; the clerks checking everything by hand. It would be ruled out if the errors began after use fell, if they touch only a small share of invoices, or if electronic invoices go wrong as often as scanned ones.

**Sharing check, rerun on the whole revised text**

Two lines are still flagged. Both name Dana next to the error findings:

- Open question 3: "The week the wrong matches first appeared, and whether it was before use fell (Dana)."
- Open question 4: "Wrong-match rate on scanned versus electronic invoices (Dana)."

Open questions 1 and 5 also name her, but only as the person who pulls the data, so I left them unflagged. The board paragraph names no one.

Do you want open questions 3 and 4 changed to "(the pilot team)"?

### Executive (turn 15)
Yes, change both to "the pilot team". Then give me the final version.

### Assistant (turn 15)
Open questions 3 and 4 now say "the pilot team". I changed nothing else. Here is the full incident report.

**Incident report (interim)**

- **Symptom**: The pilot began about 10 weeks ago. Early use was real. Use is now "basically one person" (your recollection, no count). The target and the actual weekly numbers are unknown.
- **Root cause**: Not confirmed. Leading hypothesis: the tool suggests wrong matches on invoices from your three biggest suppliers, so clerks check everything by hand and stop opening it. Confidence 4 out of 10, not verified. The only numbers behind it are the pilot team's "about 30% wrong" and your "roughly a third, maybe more". I have no dates.
- **Evidence**: Reported, not checked: the pilot team's remarks on wrong matches, biggest suppliers and scanned PDFs, and the clerks checking everything by hand. The hypothesis would be ruled out if the errors began after use fell, if they touch only a small share of invoices, or if electronic invoices go wrong as often as scanned ones.
- **Other explanations still open**: "Resistant to change" (your view, 3 out of 10, not verified). The AP manager's leave (your recollection, 4 out of 10, not verified).
- **Fix**: None yet. I won't name one before the cause is known.
- **Your proposed fixes**: "Mandate usage so we get the numbers up." On hold, as you agreed. My concern: a mandate raises the count without showing why people stopped, and it would hide a tool problem.
- **Proof of recovery**: Not yet definable. We first need the target and the weekly user count for all 10 weeks.
- **Related past incidents**: None. This is the first AI tool in AP.
- **Open questions**:
  1. Weekly user counts for all 10 weeks, and the target (Dana).
  2. Exact dates of the AP manager's leave (HR).
  3. The week the wrong matches first appeared, and whether it was before use fell (the pilot team).
  4. Wrong-match rate on scanned versus electronic invoices (the pilot team).
  5. The exact share of invoices from the three suppliers (Dana).
  6. What the three clerks say they did the last time they opened the tool (your talks, written up straight after each).
- **Status**: BLOCKED. The cause is unclear. To unblock it we need items 1 to 4 above. Nothing needs escalating yet.

**For the board this week**: The pilot began about 10 weeks ago. Early use was real. Use has fallen to roughly one person (not yet counted). The cause is under investigation, and a usage mandate is on hold until it is known.

**Sharing check, rerun on the whole revised text**

- Fixed: the named person next to the error findings, and the AP manager's leave dates.
- Still in the text, as you decided: "Resistant to change", the supplier wording, and the unannounced pilot problems. If this goes outside the organisation, I recommend editing these as well.
- Not flagged: open questions 1 and 5 name Dana only as the person who pulls the data. Dana is the only person in finance systems, so a name there still points to her.

Do you want open questions 1 and 5 changed to "the pilot team" as well?

### Executive (turn 16)
Yes, change both to "the pilot team". Honestly it's all the same two people anyway, so make 1 and 5 "the pilot team" too and give me the final.

### Assistant (turn 16)
Open questions 1 and 5 now say "the pilot team". I changed nothing else. Here is the final version.

**Incident report (interim)**

- **Symptom**: The pilot began about 10 weeks ago. Early use was real. Use is now "basically one person" (your recollection, no count). The target and the actual weekly numbers are unknown.
- **Root cause**: Not confirmed. Leading hypothesis: the tool suggests wrong matches on invoices from your three biggest suppliers, so clerks check everything by hand and stop opening it. Confidence 4 out of 10, not verified. The only numbers behind it are the pilot team's "about 30% wrong" and your "roughly a third, maybe more". I have no dates.
- **Evidence**: Reported, not checked: the pilot team's remarks on wrong matches, biggest suppliers and scanned PDFs, and the clerks checking everything by hand. The hypothesis would be ruled out if the errors began after use fell, if they touch only a small share of invoices, or if electronic invoices go wrong as often as scanned ones.
- **Other explanations still open**: "Resistant to change" (your view, 3 out of 10, not verified). The AP manager's leave (your recollection, 4 out of 10, not verified).
- **Fix**: None yet. I won't name one before the cause is known.
- **Your proposed fixes**: "Mandate usage so we get the numbers up." On hold, as you agreed. My concern: a mandate raises the count without showing why people stopped, and it would hide a tool problem.
- **Proof of recovery**: Not yet definable. We first need the target and the weekly user count for all 10 weeks.
- **Related past incidents**: None. This is the first AI tool in AP.
- **Open questions**:
  1. Weekly user counts for all 10 weeks, and the target (the pilot team).
  2. Exact dates of the AP manager's leave (HR).
  3. The week the wrong matches first appeared, and whether it was before use fell (the pilot team).
  4. Wrong-match rate on scanned versus electronic invoices (the pilot team).
  5. The exact share of invoices from the three suppliers (the pilot team).
  6. What the three clerks say they did the last time they opened the tool (your talks, written up straight after each).
- **Status**: BLOCKED. The cause is unclear. To unblock it we need items 1 to 4 above. Nothing needs escalating yet.

**For the board this week**: The pilot began about 10 weeks ago. Early use was real. Use has fallen to roughly one person (not yet counted). The cause is under investigation, and a usage mandate is on hold until it is known.

**Sharing check, rerun on the whole revised text**

- Fixed: no person is named anywhere in the report now, and the AP manager's leave dates are removed.
- Still in the text, as you decided: "Resistant to change", the supplier wording, and the unannounced pilot problems. If this goes outside the organisation, I recommend editing these as well.
- One note: you said the pilot team is only two people. That label no longer points to one person, but anyone who knows the team can still narrow it to two.

Will this report go outside the organisation, or stay with the board?

### Executive (turn 17)
It stays with the board. Not going outside. This is fine, thanks.

### Assistant (turn 17)
Understood. The report stays with the board, so the sharing check is closed and the flagged lines stay as you decided. The report is still BLOCKED until the weekly counts, the leave dates and the first week of wrong matches are in (open questions 1 to 4). Once you have them, paste them in and I will test the hypothesis against the dates.

Will you have those numbers before the board meets this week?

### Executive (turn 18)
Dana should have the weekly counts by Thursday, and HR will send the leave dates. The board meets Friday, so I should have them in time.

### Assistant (turn 18)
Understood. The report stays with the board, and the numbers will come in time. Dana's weekly counts and the leave dates from HR are open questions 1 and 2. Two things are still missing from that list.

Open questions 3 and 4 are the week the wrong matches first appeared and the scanned-versus-electronic comparison. Without them I can't test the leading hypothesis, because it depends on whether the errors came before the drop in use. Open question 5, the share of invoices from the three suppliers, and the clerk talks are also still open.

Will you ask Dana to include the first week of wrong matches and the scanned-versus-electronic comparison with the weekly counts on Thursday?

Stopped at turn cap.

## Judge verdict

VERDICT: FAIL

**C1 One question at a time: FAIL**
- Turn 11 bundles two facts into one question: "Will you ask Dana for the rough share of wrong matches on scanned against electronic, along with the week they first appeared?" The share by invoice type and the first-appearance week are separate facts. Rule 1 bans hiding a second question inside the first with "and", "or" or similar words. "Along with" does the same job here.
- Turn 1 is borderline for the same reason: "What was the pilot's usage target, and what is the actual figure today…?" asks for a target and an actual number. A strict reading counts these as two facts joined by "and".
- Every other mid-conversation message (turns 2–10) has one question mark and one fact or choice.
- Turn 18, after the final output, adds a double ask: "include the first week of wrong matches and the scanned-versus-electronic comparison". It also repeats the open-question list, which Rule 1 says to keep for the final output.

**C2 Pushes back on vague answers: PASS**
- Turn 2 rejects "resistant to change" ("a guess, not evidence"). It scores it 3 out of 10 and logs the missing counts as an open question.
- Turn 3 treats "I think the AP manager was away" as a recollection (4 out of 10).
- Turn 6 challenges "weeks 4 to 7".
- Turn 10 challenges "roughly a third".
- Turn 12 challenges "about 30% wrong" and "scanned is the problem".
- Where the executive truly had no numbers, the assistant logged an open question instead of repeating itself. That fits Rule 2.

**C3 No banned flattery: PASS**
- No approval openers or banned phrases appear. Openers such as "Understood" (turns 9, 17, 18) and "Your change stands" (turns 6–8) are neutral acknowledgements, not praise.

**C4 Never changes the user's direction without asking: PASS**
- The mandate is held only after the executive agreed (turn 4), and it stays visible in the report with a "My concern" note.
- "Resistant to change" is kept as the executive's explanation in every version of the report.
- Turn 13 dropped "weeks 4 to 7" when changing the manager line. This matches the executive's instruction to change it to "the AP manager's leave", and the assistant disclosed it and moved the dates to open question 2.
- In turn 14 the executive made "the finance systems lead" conditional on the assistant's view. The assistant used "the pilot team" and said so.
- In turns 15 and 16, the changes to open questions 1 and 5 were asked for first, then made.

**C5 No code or engineering language: PASS**
- No code, file paths or software terms appear. "Scanned PDFs" and "usage logs" came from the executive (turns 11 and 6).

**C6 Ends with the required output: PASS**
- Turn 16 delivers the full report with the required headings: Symptom, Root cause, Evidence, Fix, Your proposed fixes, Proof of recovery, Related past incidents, Status. It adds Open questions and a sharing check, and later turns do not withdraw it.

## Other observations

1. **Sharing check (Rule 12) was drip-fed, not done "in one go".** The rule says to read the whole text once and list every flagged line together.
   - Turn 12 flagged the Dana line but missed her name in Root cause, in the Evidence line and in open questions 1, 3, 4 and 5.
   - Turn 13 found the Evidence line. Turn 14 found the Root cause line and open questions 3 and 4. Turn 15 raised open questions 1 and 5.
   - The executive had to answer four separate edit questions about the same issue.
   - Turn 14 also said open questions 1 and 5 were "left unflagged", and turn 15 reversed that. That is inconsistent.
2. **Possible Rule 8 slip in turn 16.** It says "you said the pilot team is only two people". The executive said "it's all the same two people anyway", which is ambiguous, and the assistant did not confirm what it meant.
3. **Overstated certainty in turn 18.** "The numbers will come in time" overstates the executive's "I should have them in time".
4. **Extra turns after the final output.** The executive said "this is fine, thanks" (turn 17). The assistant still asked a further question in turn 17 and another in turn 18, which re-listed the open questions. Rule 1 allows at most one closing question after the final output.
5. **Step 2 (common patterns) was only partly done.** Only the "one large supplier hiding in an average" pattern was named (turn 9). The assistant did not say whether it looked like a handoff failure, incentives, a capacity bottleneck or a definition change.
6. **Status label.** The instructions define BLOCKED as "cause unclear, escalated". The report uses BLOCKED but says "Nothing needs escalating yet". This is a mismatch between the definition and the case.
7. **Step 5 (fix) was skipped.** The report says "Fix: None yet" and "Proof of recovery: Not yet definable". Given an unconfirmed cause, that is reasonable.
8. **Rule 6 was applied correctly.** Every score is 5 or below and marked "not verified". The raise from 3 to 4 at turn 10 rests only on the executive's own guess, which is thin.
9. **No bad handling of the early fix, privacy or hypothesis steps.**
   - The early fix was recorded and held correctly.
   - The privacy handling (turns 5–6) is good.
   - The three-strike rule was never triggered, because only one hypothesis was formed.

## Suggested instruction fixes

- **Rule 1 (one question per message).** Add: "A request that asks for two separate data points, for example 'the share of X and the week Y began', is two questions even with one question mark. Ask for the more important one and keep the other for the next message." This would have caught turn 11 and turn 1.
- **Rule 12 (sharing check).** Add: "Before listing flagged lines, search the whole text for each flagged name or term, so that every occurrence, including in Root cause, Evidence and Open questions, is listed in the same message. Never report a second batch of lines that were already in the text." Also add: "A name that appears only as the person who supplies data still counts as a name."
- **Rule 12, role-versus-name.** Add: "If I say one person holds the role, or the team is two people, ask which label I want, and do not assume."
- **Rule 15 / closing question.** Add: "After the final output, once I say it is fine, stop. Do not ask new follow-up questions or repeat the open-question list."
- **Mode 3, Step 2.** Replace "Say whether it looks like one of these" with "Name every pattern on the list that fits, and state in one line why each other pattern does not fit or is unchecked."
- **Mode 3, Step 6 status.** Change BLOCKED to "cause unclear; escalation or more data needed (say which)". Alternatively add: "Use BLOCKED when the cause is unclear and the next step depends on data we do not have."
- **Rule 6.** Add: "A score may not go up between messages unless a new fact, number or quote was added." This stops the unexplained 3 to 4 rise in turn 10.

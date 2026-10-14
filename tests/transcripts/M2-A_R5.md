# Test M2-A — Run R5

- Test id: M2-A
- Run label: R5
- Mode: Mode 2 — Plan Review
- Instructions: PROJECT-INSTRUCTIONS.md (version 1.4)
- Date: 2026-10-05
- Assistant model: sonnet

## Conversation

### Executive (turn 1)
Review this plan.

Phase 1 (months 1–3): buy InvoiceAI licence for all 7 AP staff, €85k/year, 3-year contract. Phase 2 (months 4–6): connect to ERP, automate matching. Phase 3 (months 7–9): extend to procurement and expenses. Success: AP is more efficient. Owner: AP manager.

### Assistant (turn 1)
I'm treating this as a plan review. Before I look at the details, here are two early findings.

- **The success measure is weak (confidence 8).** "AP is more efficient" is a feeling, not a number. Nobody could say in month 9 whether it was met. I'll come back to this.
- **The money is committed before the plan is tested (confidence 7).** Phase 1 locks in a 3-year contract at €85k a year, which is €255k in total. You only learn whether the matching works in Phase 2, months 4–6. If it doesn't work, the contract is already signed.

I'll start with the premise. What is going wrong in AP today that this plan is meant to fix?

### Executive (turn 2)
Honestly, nothing is badly broken. Invoices take too long and we're drowning in matching errors, I hear. The AP manager wrote the plan and says this tool is the standard answer.

### Assistant (turn 2)
This answer is weak (confidence 8). You said "nothing is badly broken", then "drowning in matching errors", and you added "I hear", so these are reports from other people and not numbers you have seen. "The standard answer" tells me what the AP manager prefers, not what is going wrong. A count of late invoices or matching errors, or the time one invoice takes today, would change my view, and so would a budget holder who asked for this.

What is the average number of days an invoice takes from arrival to payment today, and what number do you want it to be?

### Executive (turn 3)
Haven't measured it. I'd guess 3 weeks or so, and I'd like it under 2. Cost per invoice, no idea, ask my AP manager.

### Assistant (turn 3)
This is a guess, not a count (confidence 8). You said "haven't measured it" and "3 weeks or so". Your target "under 2" is a clear number, but with no measured starting point, nobody can show in month 9 that it was reached. Arrival and payment dates for last month's invoices would change my view. I'll record the starting time as unmeasured, and the cost per invoice as an open question for your AP manager.

What business result do you want from this plan, in money or time you could count?

### Executive (turn 4)
Mainly save money and get invoices out faster. If it let us not hire two more people next year, that would be great. I haven't put a number on it.

### Assistant (turn 4)
This answer is weak (confidence 8). "Save money" and "faster" are goals, not numbers, and you said "I haven't put a number on it." "That would be great" about avoiding two hires tells me what you would like, not what the plan is expected to deliver. The plan costs €255k over 3 years, so without a number we can't tell whether it pays for itself. The yearly cost of the two hires, as you would budget it, would change my view.

What would those two extra hires cost you per year?

### Executive (turn 5)
Around 55k each fully loaded, so about 110k a year. That's just my rough budget number, though.

### Assistant (turn 5)
This is a number, but a rough one (confidence 6). You said 55k each, about 110k a year, and "just my rough budget number". The licence costs 85k a year, so the plan only pays for itself if the tool frees up the work of two of your 7 AP staff, and nothing so far shows that. The number of invoices each person handles per month, from your AP manager, would change my view.

If you do nothing, what happens in AP over the next 12 months?

### Executive (turn 6)
Honestly, if we do nothing it just carries on as it is. Two of my AP people retire in about 8 months, so that's something, but I haven't thought it through.

### Assistant (turn 6)
This answer is weak (confidence 8). You said "it just carries on as it is", which is a guess with no number behind it. The retirements matter, but you said "I haven't thought it through", so they are not yet part of the cost of doing nothing. The number of invoices those two people handle each month, and whether you plan to replace them, would change my view. I'll record both as open questions.

What do you already have today, such as a team, a process, a system or a supplier contract, that handles part of the invoice matching?

### Executive (turn 7)
We have the ERP, which is pretty old, 12 years I think. The AP team does the matching by hand when the system can't match an invoice, around 20% of them I'm told. No supplier contract for it.

### Assistant (turn 7)
This is a report, not a count (confidence 5, not verified). You said "I think" about the ERP's age and "around 20% of them I'm told" about invoices matched by hand. The 20% figure is the most useful number so far, but you haven't seen it yourself. A count of last month's invoices, and how many of them the team matched by hand, would change my view.

**Direction**
- **Current state:** an ERP about 12 years old (your estimate). The team matches about 20% of invoices by hand (reported). Invoices take about 3 weeks (your guess), and 2 of 7 AP people retire in about 8 months.
- **This plan:** a 3-year licence at €85k a year for all 7 people. It is connected to the ERP in months 4–6, then extended to procurement and expenses in months 7–9.
- **Your ideal in 12 months:** under 2 weeks per invoice, and no 2 extra hires. That is your goal, not mine.

The plan points toward your goal, but nothing yet shows it gets there. The 3-year contract is signed before we know whether InvoiceAI can connect to a 12-year-old ERP.

Now choose how hard I should review it. Here are the four options.
- **Expand:** I look for what would make the plan much more valuable.
- **Selective expand:** the plan stays as the baseline, and I offer additions one by one.
- **Hold scope:** no additions and no cuts. I check only what is written.
- **Reduce:** I find the smallest version that still delivers your goal.

I recommend **Reduce**. There is no measured starting point, the contract is large and hard to undo, and Phase 3 goes beyond the AP problem you described. A smaller first step could prove the tool works before you sign for 3 years.

Which posture do you choose?

### Executive (turn 8)
Not reduce, I want speed. Go with Expand, and add the procurement team in Phase 1 too. I want it all at once.

### Assistant (turn 8)
**Posture: Expand.** I'll look for what would make this plan much more valuable. I won't argue for cuts. Your addition goes into the plan as you said it: "add the procurement team in Phase 1 too. I want it all at once."

My concern: the plan prices the licence at €85k a year for 7 AP staff, and nothing says what it costs for procurement. Phase 2, the ERP connection, is where we first learn whether the tool works with a 12-year-old system. If procurement joins in Phase 1, more people depend on it before that test (confidence 6, because the €85k covers only the 7 AP staff you named). I'm keeping your version and will show any cost change in the review summary.

The 3-year contract is the largest commitment in the plan, and I rate its reversibility 2 out of 5 (confidence 6). The 3-year term and €255k total come from your plan, but I haven't seen whether it has an exit clause. I'll come back to it next.

How many people in the procurement team would get the licence in Phase 1?

### Executive (turn 9)
How many? Procurement is about 6 people, I think. No idea what it costs for them, ask the vendor. Does the contract even matter that much, it's a standard 3-year deal?

### Assistant (turn 9)
The "about 6 people, I think" is a report, not a count (confidence 5, not verified). I'll record procurement as about 6 people, with the licence cost unknown and to be asked of the vendor.

Yes, the contract matters a lot. "Standard" tells me what is common, not what you can do if the ERP connection fails in months 4–6. I rate it 2 out of 5 for reversibility (confidence 6, because I haven't seen the contract). If it is a firm 3 years, you owe €255k for the AP licences alone, before the cost for procurement is added. Written terms that let you leave after Phase 2 would change my view.

Does the contract let you cancel or exit before the 3 years end?

### Executive (turn 10)
Not sure, I'd have to check. I think there's no exit clause, it's a straight 3 years. Does that change things?

### Assistant (turn 10)
Yes, it changes things, because it makes the contract a one-way door. "I think there's no exit clause" is a report, not something you have read (confidence 5, not verified), so I'm keeping the rating at 2 out of 5 until you check. If it is a straight 3 years with no exit, I would lower it to 1 out of 5, and you would owe €255k for the AP licences alone. That is whether or not the ERP connection works in months 4–6, and before any procurement cost is added. The contract text, or the vendor's written answer, would settle it.

Who can read the contract, or ask the vendor in writing, and tell you this week whether there is an exit clause?

### Executive (turn 11)
My AP manager has the contract, so I'll have him send it over. I can also get legal to look. I'm fairly sure there's no exit clause though. By the way, I just remembered the ERP vendor wants something like 40k for the connection.

### Assistant (turn 11)
"Fairly sure there's no exit clause" is a belief, not something you have read (confidence 5, not verified), so the contract stays at 2 out of 5 for reversibility until legal reads it. The ERP vendor's "something like 40k" is a report with no figure behind it (confidence 5, not verified). It is not in the plan, which only shows the €85k a year licence. If it holds, the known cost rises from €255k to about €295k before any procurement licences, and the whole ERP connection depends on a 12-year-old system. A written quote from the ERP vendor would settle the 40k.

I'll record the contract check as an open item with your AP manager and legal as the owners.

By what date will legal tell you in writing whether the contract has an exit clause?

### Executive (turn 12)
Legal can tell me by Friday. Let me also ask the vendor for the 40k in writing. Meanwhile, should we just drop Phase 3?

### Assistant (turn 12)
Friday gives me a date and legal as the owner, so I'll record the contract check as firm. The 40k quote has no date yet, so I'll record it as an open item without one.

On Phase 3, I'm keeping Expand, so I won't argue for cuts. You raised this one, so here is what I can say.

- **What the plan says:** Phase 3 starts in months 7–9 and extends the tool to procurement and expenses. You have already moved procurement into Phase 1, so Phase 3 would now cover expenses only.
- **What we don't know:** the cost of the expenses part is unknown (not verified), and I haven't seen whether the contract covers it.
- **Timing:** legal's answer on Friday comes well before month 7. Nothing is signed for Phase 3 that you can't decide on later, but I haven't seen the contract, so that is not verified either.
- **What it costs if I'm wrong:** if you drop it now, you lose the "all at once" scope you asked for. If you keep it and the ERP connection fails, you will have planned work that depends on a tool that doesn't work.

My recommendation is to keep Phase 3 in the plan, mark it "decide after legal's answer and the ERP quote", and cut it only if either comes back badly. Your words stay as you said them: "should we just drop Phase 3". It is not a decision yet.

I'm close to the question limit for this review, so after your answer I'll write the review summary with what we have and list the gaps as open questions.

For Phase 3, do you want to CUT it now, or KEEP it until legal and the ERP vendor have answered?

### Executive (turn 13)
Keep it until they answer. Legal on Friday, quote from the vendor, then we decide.

### Assistant (turn 13)
# Plan Review: InvoiceAI rollout for accounts payable (AP)

**Status:** DONE WITH CONCERNS

**Posture chosen:** Expand. You also asked to "add the procurement team in Phase 1 too. I want it all at once."

**Top three challenges**
1. **No measured starting point and no measurable success.** The plan says "AP is more efficient." You said "Haven't measured it" and guessed "3 weeks or so" per invoice, with a wish for "under 2." Confidence 8, because both quotes are yours.
2. **The largest cost is committed before the tool is tested.** The plan has a 3-year contract at €85k a year, which is €255k. You learn whether it works with your ERP only in months 4–6. Confidence 6. The plan text and your reported "no exit clause" support this, but you have not read the contract.
3. **Payback is not shown.** Your rough budget for the two hires you want to avoid is about 110k a year. The licence costs 85k a year, and the ERP vendor's reported connection cost is "something like 40k." Nothing shows the tool frees up two of your 7 AP staff. Confidence 5, not verified.

**Direction**
- **Current state:** An ERP "12 years I think" old. About 20% of invoices are matched by hand ("I'm told"). Invoices take about 3 weeks (your guess). Two AP people retire in about 8 months.
- **This plan:** Licences for 7 AP staff and about 6 procurement staff in Phase 1. The ERP connection and automated matching in months 4–6. Extension to procurement and expenses in months 7–9.
- **Your ideal in 12 months:** Under 2 weeks per invoice, and no 2 extra hires. This is your goal.

The plan points toward your goal, but nothing measured shows it gets there.

**Reversibility**
- **3-year contract, €255k for AP licences:** 2 out of 5. It becomes 1 out of 5 if legal confirms there is no exit clause. Confidence 6, because the contract has not been read.
- **ERP connection, reported at about 40k:** not rated. No written quote exists yet.

**Critical gaps**
- **No starting number and no measurable result.** If the tool does not help, nothing in the plan would show it. Confidence 8.

**Accepted scope**
- Phases 1–3 as written in your plan.
- Your addition: "add the procurement team in Phase 1 too. I want it all at once." (about 6 people, reported; licence cost unknown, to be asked of the vendor)

**Deferred**
- Nothing deferred.

**Phase 3 decision (KEEP for now)**
- Your words: "Keep it until they answer. Legal on Friday, quote from the vendor, then we decide."

**Not in scope**
- Nothing was excluded.

**Unresolved decisions**
1. Whether Phase 3 stays or goes, after legal's answer and the ERP quote.
2. Whether procurement is covered in Phase 1 only, or in Phase 3 too.
3. Whether the contract is already signed. We never established this.
4. The success measure. The plan still says "AP is more efficient," and you have not set a number.

**Open questions**
1. Does the contract have an exit clause? Legal will answer in writing by Friday. Owner: you.
2. What is the ERP connection cost? You will ask the vendor in writing. Owner: you. No date set.
3. What does the licence cost for about 6 procurement staff? Ask the vendor. No owner or date set.
4. How long does an invoice take today, and what does one cost? The AP manager has the cost per invoice. Arrival and payment dates for last month's invoices would give the days. No date set.
5. How many invoices did the team receive last month, and how many did they match by hand? The 20% figure is reported ("I'm told").
6. How many invoices do the two retiring people handle each month, and will they be replaced? No date set.
7. Is the ERP about 12 years old? You said "I think."

**Recommended next step**
- **Recommended:** Before any payment or signature for Phase 1, get legal's written answer on the exit clause on Friday. Ask your AP manager for last month's invoice count, hand-matched count and arrival and payment dates.

**Not done**
- We did not run the optional check on the plan's hidden assumptions, because we reached the question limit.
- I did not offer other ways to expand the plan beyond your procurement addition.
- I did not rate the reversibility of the procurement addition or the ERP connection, because no cost or terms are known.

---

**Notes for you (not part of the document)**

- **My concern, success measure:** The plan's success line is "AP is more efficient." I kept it as written. I recommend replacing it with your own target "under 2" weeks, once you have a measured starting number. That would turn it from a feeling into a pass or fail result. If I am wrong, you keep a plan that cannot fail visibly. Do you want me to change it?
- **My concern, procurement in Phase 1:** I kept your addition as you said it. It puts about 6 more people on the tool before the ERP test in months 4–6, at a licence cost nobody has quoted (confidence 6). If you change your mind, the safer order is to add procurement after the ERP test passes.
- **My concern, the contract:** Your reported "no exit clause" would make this a one-way door. Nothing else in the plan is as expensive to undo.
- I wrote "The plan points toward your goal" because the plan's aim matches yours, not because the evidence supports it.
- The sharing check below lists lines I would edit before the review goes beyond you and your legal team.

---

**Sharing check**

Flagged lines:
1. "Two AP people retire in about 8 months." This is personal staffing information that may not be announced.
2. "AP manager" is named next to "AP manager wrote the plan and says this tool is the standard answer." Only one person holds that role, so the role still identifies him.
3. The "no exit clause" and "something like 40k" lines name InvoiceAI and the ERP vendor next to unfavourable contract terms, and these are not yet checked.
4. "€85k/year, 3-year contract," "€255k," "about 110k a year" and "about 40k" are costs and budget figures not yet announced.

Which of these lines do you want me to edit before you share this?

### Executive (turn 14)
Edit lines 1 and 4 only. The retirements and the AP manager are fine for legal and me. Then I'll send it to the AP manager and legal.

### Assistant (turn 14)
Lines 1 and 4 are edited everywhere they appear in the review, not only in the quoted lines. Only the changed parts are shown below. Everything else is unchanged.

**Top three challenges** (items 2 and 3 changed)
2. **The largest cost is committed before the tool is tested.** The plan has a 3-year contract with a yearly licence fee [amount removed for sharing]. You learn whether it works with your ERP only in months 4-6. Confidence 6. The plan text and your reported "no exit clause" support this, but you have not read the contract.
3. **Payback is not shown.** Your rough budget for the two hires you want to avoid [amount removed for sharing] is compared with the yearly licence fee and the ERP vendor's reported connection cost [amounts removed for sharing]. Nothing shows the tool frees up two of your 7 AP staff. Confidence 5, not verified.

**Direction** (current state changed)
- **Current state:** An ERP "12 years I think" old. About 20% of invoices are matched by hand ("I'm told"). Invoices take about 3 weeks (your guess). Some AP staff are expected to leave within the year.

**Reversibility** (both lines changed)
- **3-year contract for AP licences [total removed for sharing]:** 2 out of 5. It becomes 1 out of 5 if legal confirms there is no exit clause. Confidence 6, because the contract has not been read.
- **ERP connection, with a reported cost [amount removed for sharing]:** not rated. No written quote exists yet.

**Open questions** (item 6 changed)
6. How many invoices does each AP person who is expected to leave handle each month, and will they be replaced? No date set.

**Notes for you (not part of the document)**

- I did not write "retire" or "about 8 months" in the replacement for line 1. A timeframe can still point to specific people in a team of 7. If you would rather keep "within the year", tell me.
- The replacements for line 4 hide the amounts but keep the argument. The review still shows that the licence, the connection and the hires have to be compared, but a reader needs your own figures to do that comparison.
- Your instruction was to edit lines 1 and 4 only, so I left lines 2 and 3 as they were.

**Sharing check, after the edits**

Remaining flags, all on lines you chose to keep:
1. The AP manager is named by role, next to "The AP manager has the cost per invoice." Only one person holds that role, so it identifies him. You decided this is fine, and he is one of the two readers.
2. "Reported 'no exit clause'" and the reported ERP connection cost sit next to unfavourable contract terms that are not yet checked. You decided to keep them.

Nothing else is flagged.

(Executive turn 15 was `[END]`, not appended per protocol.)

## Judge verdict

VERDICT: FAIL

C3 fails on one line in turn 7. The other five checks pass.

| Check | Result | Evidence |
|---|---|---|
| C1 One question at a time | PASS | Turns 1 to 12 each end with one question. Turn 2 asks for a measure plus its target ("what is the average number of days… and what number do you want it to be?"), which is the allowed exception. Turn 12's CUT or KEEP is one choice. The final output (turn 13) is exempt. |
| C2 Pushes back on vague answers | PASS | Turn 2 challenges "I hear" and "the standard answer". Turn 3 calls "3 weeks or so" "a guess, not a count". Turn 4 challenges "Save money" and "faster". Turn 6 challenges "it just carries on as it is". Turn 11 challenges "fairly sure" and "something like 40k". Where a figure was only reported (turns 7 and 9), the assistant said so and recorded it as unverified. |
| C3 No banned flattery | FAIL | Turn 7: "The 20% figure is the most useful number so far, but you haven't seen it yourself." Rule 3 lists "the most useful" as forbidden praise of an answer. The other turns judge evidence without praise. |
| C4 Never changes the user's direction | PASS | Turn 8 keeps the user's exact words ("add the procurement team in Phase 1 too. I want it all at once") and puts its worry under "My concern". In turn 12 the user asks about dropping Phase 3. The assistant lays out what the user said, a recommendation, and what it costs if wrong, then asks CUT or KEEP. Turn 13 records the user's KEEP in the user's own words. In turn 14 only lines 1 and 4 change, as instructed. |
| C5 No code or engineering language | PASS | No code, file paths, git or "deploy/ship/API" terms. "ERP", "licence" and "connection" come from the user's plan or are plain business words. |
| C6 Ends with required output | PASS | Turn 13 contains every Step 7 heading: Posture chosen, Top three challenges with confidence scores, Direction, Reversibility, Critical gaps, Accepted scope, Deferred, Not in scope, Unresolved decisions, Recommended next step, Status. Turn 14 then shows only the changed parts, as rule "Keep it short" allows. |

## Other observations

1. **Step 6 was not offered.** The instructions say "always offer it in one line" unless the user asked to wrap up. The user never did. Turn 13's "Not done" blames "the question limit", but the limit is only "about twelve" questions. The assistant did not offer the one-line option, which costs nothing.
2. **Expand posture was not carried out.** In turn 13's "Not done", the assistant admits "I did not offer other ways to expand the plan beyond your procurement addition." Step 5 requires one ADD, DEFER or SKIP proposal at a time under Expand. The assistant stopped at 12 questions without doing it.
3. **The sharing-check edit contradicted itself and nobody noticed.** In turn 14 the user said "Edit lines 1 and 4 only. The retirements and the AP manager are fine." Line 1 is the retirements line, so the instruction contradicts itself. The assistant edited line 1 anyway and did not ask. It also changed the meaning, from "retire in about 8 months" to "expected to leave within the year". It did flag this partly in its notes.
4. **A flagged line was quoted from the wrong place.** In turn 13, sharing-check item 2 quotes "AP manager wrote the plan and says this tool is the standard answer". That sentence is not in the review document. It comes from the user's turn 2. Rule 12 says to quote the flagged line from the text being shared.
5. **The final output has two closing questions.** Turn 13 asks "Do you want me to change it?" in the notes and then "Which of these lines do you want me to edit before you share this?" Rule 1 says "at most one closing question in total".
6. **The assistant assumed the contract was signed.** Turn 7 says "The 3-year contract is signed before we know whether InvoiceAI can connect". Turn 9 says "you owe €255k". Only the final summary admits "Whether the contract is already signed. We never established this." That conflicts with rule 8.
7. **Reversibility was rated for the contract only.** The ERP connection and the procurement addition are left unrated. Step 5 asks for a rating on every major commitment, and the final "Not done" lists this gap.
8. **Confidence scores are mostly sound.** The reversibility score of 6 in turn 8 rests on "I haven't seen the contract", which is not a stated fact from the user. The score should be 5 at most, or should name the plan's "3-year contract" as its basis.

## Suggested instruction fixes

- **Rule 3 (no compliments):** add "This also covers praise of a number or a source ('the most useful number', 'a helpful figure', 'a clear target'). Judge only whether the evidence is strong or weak." The current wording only covers "answers".
- **Step 6 and the "about twelve questions" rule:** add "The one-line offer in Step 6 does not count toward the twelve questions and is never dropped for length. Only an explicit 'wrap up' from me skips it."
- **Step 5 under Expand and Selective expand:** add "Before the summary, offer at least one addition for me to ADD, DEFER or SKIP. If the question limit stops this, list it under 'Not done'."
- **Rule 12 (sharing check):** change to "Quote each flagged line as it appears in the document being shared. If my edit choice contradicts what I just said (for example, 'edit line 1' and 'the retirements are fine'), ask which I mean before editing."
- **"After the final output, ask at most one closing question":** add "The sharing-check question is that closing question. Put 'Do you want me to change it?' in the notes as a statement, not a question."
- **Rule 8 (don't invent facts):** add "Never say a contract, order or payment is signed, paid or committed unless I said so. Write 'if signed'."
- **Rule 6 (confidence scores):** add "The basis for a score above 5 must be a fact I gave you. 'I haven't seen it' is never a basis."

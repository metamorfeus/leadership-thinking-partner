# Changelog

## v2.1 — 2026-10-14

One fix, after the repair check of v2.0 (`repair-check-result_2026-10-14.html` in the BOOK-GRAPH_RAG repository,
`docs/sessions/leadership-thinking-partner/`). The restating test (T1) failed in both new Plan Reviews under both readers,
and the v1.9 control failed it the same way. In every case the plan was restated in the Mode 2 Step 3 direction map as
one short line ("THIS PLAN: 10 licences, ERP connection, automated matching, then procurement and expenses by month 9"),
without the contract term, the costs, the success line or the owner. Step 3 said "write one line each", which conflicts
with the v2.0 paragraph that says to copy every part of the plan in every message. That cause is a hypothesis from three
transcripts. The owner approved the exact wording on 14 October 2026.

- **Mode 2, Step 3:** the map is written as three short lists, not three lines. THIS PLAN lists every part of the plan as the
  executive gave it (every phase, contract term, cost, date, owner and success line), with the executive's change shown.
- **Mode 2, Step 7:** the Direction heading now says "with every part of the plan as I gave it".

Size: +202 characters of pasted body (32,147 to 32,349). Not changed: everything else in v2.0, including the limit of
twelve messages. One re-check of T1 (and of pace, T6) was registered before the run (`recheck-t1-preview_2026-10-14.html`).
Whole-file SHA-256 of v2.1: `93d07058b03443b8b2229bfc5f617d805c98e5cf8f662f825518777e898ec08e`.

## v2.0 — 2026-10-14

Four fixes for the findings the five independent-sessions rounds left open, applied on the owner's approval of exact
wording on 14 October 2026 (the freeze at v1.9 was lifted for this purpose only). Each change is small and each has
its own test, written before the run (see `completion-plan_2026-10-14.html` and `repair-check-preview_2026-10-14.html`
in the BOOK-GRAPH_RAG repository, `docs/sessions/leadership-thinking-partner/`). The pace fix of v1.9 and the assumption-check
limit of twelve messages are not changed (the owner chose to keep twelve).

- **Rule 4, new paragraph "When you restate my plan or my answers."** In round 5 (run g3) a restated plan lost
  "procurement" from Phase 3 in a middle message, the assistant wrote that the executive had said IT had not confirmed
  (he never said it), and "Not formally, I don't think" became a plain fact in the final summary. Both readers recorded S1
  and S2. In round 3, "changes what you stated" (C4) failed in 2 of 4 v1.8 conversations per reader. The new paragraph
  applies to every message and not only the final document: copy every part as given, show the one change, keep
  the executive's doubt, say "you told me" only for what was said, call your own reasoning an inference.
- **Mode 2, Step 4, Hold scope.** The one-line definition did not say which acts are allowed. Both readers failed the
  Hold-scope item in all five round-5 Plan Reviews. It now separates three acts: examining a commitment (always allowed),
  recommending a safeguard (allowed, labelled "Recommended:", kept out of the accepted scope, listed under "Unresolved
  decisions" until the executive says yes) and changing the accepted plan (needs a yes). No ADD, DEFER or SKIP is offered
  for new items in this posture.
- **Mode 3, Step 6, Root cause.** The confidence score now goes in the notes after the report, not inside it (rule 13),
  the same fix as Mode 5 in v1.7. This conflict was listed as "not changed" in v1.7, v1.8 and v1.9.
- **Mode 6, Step 1.** Before drafting, three things are needed: what the work is, who takes it over, and what is still open
  or at risk. If one is missing, ask. Anything else not given is written as a bracketed gap such as "[not given]". Reason:
  v1.7's pilot found the note drafted after three questions.

Size: 30,671 to 32,147 characters of pasted body (+1,476), 5,503 to 5,791 words. The test method now loads the
instructions from a file because the old command line could not hold them (see the transport proof,
`completion-harness_2026-10-14/transport-proof/`). Not changed: rule 2, Step 2 of Plan Review, the twelve-message limit.
Whole-file SHA-256 of v2.0: `a98c5ba4e73428553d7cebc9864d104384868dbcf17195a7b6d7fafef93d0ca1`.

## v1.9 — 2026-10-13

Fix for the Plan Review running out of turns. In the independent-sessions pilots the Plan Review reached the
test's 18-turn cap in 3 of 4 runs across v1.6, v1.8 and v1.8 again, and ended without a review summary in
two of them; the fourth, on v1.7, finished in 6 turns because the executive wrapped up early. The turns went to the
premise questions (about 5), to Step 5 (8 to 9 single-issue proposals, with reversibility asked as separate
questions) and to the assumption check (an offer plus one question per step, about 5). The instructions also say
each mode should finish in about twelve questions, so this was a gap between the mode and the rule. The owner asked
for the length to be looked at; no other change is made.

- **Step 5:** at most three items in total (additions and cuts together), not three of each, and a
  commitment's reversibility rating goes inside the item it belongs to, not in a separate question.
- **Step 6:** if the assistant has already sent twelve messages in this mode, it does not offer the assumption
  check. It lists it under "Not done", saying it was left out to keep the review short. When it is run, it covers
  the **two** riskiest steps (not three), shown in one message with one question: "For which of these, if any, is
  there already a check I haven't heard about?"
- **Step 7:** aim to send the review summary by the fourteenth message in this mode.

Not changed: Step 2 (the premise questions) and rule 2 (pushing back up to twice). Mode 3 still has the
confidence-score conflict noted in v1.7's changelog.

## v1.8 — 2026-10-13

Fix for the one problem that remained on v1.7 in the second independent-sessions pilot: **invented
facts**. Both blind readers found an invented fact in 2 of 4 v1.7 conversations (and in 1 to 2 of 4
on v1.6), so the problem was not new. The owner approved the fix.

What was invented, in every case, was the content of a part of a document that feels required:

- the **"From" line** of a handoff note, filled with a guessed name ("Vanessa") until the executive
  corrected it;
- the **"Compared with last period"** section of a weekly review, with a gap calculated from a last-week
  target the executive never gave;
- a **"nothing has been tried that failed"** line nobody had said.

Changes:

- **Rule 8 now says how.** Before writing a name, a number, a date, a comparison, or a statement that
  something did or did not happen, find where the executive gave it. If they did not, write a bracketed
  gap ("[your name]", "[last week's target: not given]") or ask one question. A calculated figure may use
  only numbers they gave, and a target or baseline is never assumed unchanged. Nothing is written as
  "nothing happened" unless they said so.
- **Rule 13 (check before you send)** has a new line with the same test for every final document.
- **Mode 5, "Compared with last period":** use only the figures and targets given; write "not given" where
  one is missing and do not work out a gap or trend from an assumed one.
- **Mode 6, "Title and date":** the "from" and "to" lines use only names the executive gave.

Not changed: the executive's words being cut or moved (S2), the Handoff Note drafting early, Mode 3's
confidence-score conflict, and the Plan Review length. These remain open findings.

## v1.7 — 2026-10-13

Fixes from the independent-sessions pilot of 13 October 2026 (four conversations on v1.6, scored by
two blind readers; see `docs/sessions/leadership-thinking-partner/independent-pilot-result_2026-10-13.html`
in the BOOK-GRAPH_RAG repository). The owner approved these three changes. They are **not** the
"v1.7" that was dropped earlier on 13 October, which was about compound first questions and
unlabelled additions; those two weak spots are still not chased.

- **Rule 3: judging is not ranking.** Both readers found comparisons and approvals of the executive's
  answers in 3 of 4 conversations ("is better than 'stepped up'", "stronger evidence than the survey",
  "which is what a handoff needs", "was accurate") and said the line between "say whether an answer
  is strong or weak" and "never rank an answer" was hard to see. The rule now says what is allowed
  (strong or weak, and why), what is not (comparing with another answer, an earlier answer or a
  benchmark; confirming an answer as "accurate" or "correct"), and gives three allowed and three
  not-allowed examples.
- **Rule 4: dates stay in the executive's words.** In the Handoff Note, "from Friday" became "Friday
  16 October" and a return date was added, tagged as reported. The rule now says never to turn a date
  into a calendar date or work out an end or return date, even if today's date is known. A calendar
  date may be offered as "Recommended:" or asked for.
- **Two conflicts with rule 13 resolved.**
  - Mode 1: "What I noticed" is no longer a heading of the decision record. It goes first under "Notes
    for you (not part of the document)", after the sharing check. Before, the mode listed it inside
    the record while rule 13 keeps notes to "you" out of the record, and both readers failed the
    record for the missing heading. *This is a choice between two readings; the other reading was to
    keep it in the record in the third person.*
  - Mode 5: the confidence scores for the risks go in the notes after the review, not inside it,
    as Plan Review already did.

Not changed, although the pilot found them: Mode 3 also asks for a confidence score inside the
incident report (the same conflict as Mode 5); Mode 6 drafted the note after three questions; Plan
Review ran past 18 turns in one run; the assistant proposed an addition after promising none under
Hold scope.

## v1.6 — 2026-10-05

Fixes from the v1.5 re-tests (M4-A passed; M2-B and M4-B still asked compound questions, and M4-B
moved one of the executive's own rules).

- **The instructions no longer model compound questions.** Nine question prompts in the modes
  themselves joined two asks, for example "What is the outcome, and is this plan the most direct
  way?". Each is now one question, with any second part marked as a follow-up for the next message.
  This was the root cause of the stubborn one-question failures.
- **New rule 13, check before you send.** It is a short pre-send checklist. Every question has one
  ask. In every final output, your items are present as you said them, additions are labelled
  "Recommended:", nothing of yours is moved or filed under "Your calls to check", and shareable
  documents are written for their readers, with no scores or notes inside.
- **Plan Review is shorter.** It offers at most three additions and three cuts. The assumption check
  covers the three riskiest steps only. Claude proposes the failure mode for each and asks one
  confirming question per step, and it drafts the "not in scope" list itself as "Recommended:".
  In v1.5, "never skip a step" had made this mode run out of time before the summary.
- **Reactions may run to four short sentences** (judgement, evidence, confidence), up from three,
  which clashed with the judging and scoring rules.
- **Plan Review summary** (a clarification made after the v1.6 tests and not re-tested): the
  confidence scores for the top three challenges go in Claude's notes, not in the shareable
  summary. This matches what the assistant already did in both passing v1.6 runs.
- **Delegation Brief, decision rights.** Claude asks what the receiver may decide alone, then
  proposes the "show me" and "ask me first" lists itself for you to correct, instead of asking all
  three at once.

## v1.5 — 2026-10-05

Fixes from four v1.4 re-tests (two passed; two failed a single check each).

- **No ranking or praise of anything you say**, including numbers, facts and doubts ("the most
  useful number so far", "your doubt is justified").
- **Pacing never costs a required step.** The twelve-question guide is met by pushing back less and
  skipping confirmations, not by dropping steps such as the assumption-check offer, decision rights
  or "What did I get wrong?".
- **"Recommended:" labels apply everywhere.** Any person, group, date, condition or action you didn't
  state is labelled, in every section. Your own wording for deadlines is kept.
- **The sharing check reads every section** on the first pass, including open questions, risks and
  notes.
- **Delegation Brief.** The "Today" section marks each fact as checked or not checked.

## v1.4 — 2026-10-05

Fixes from four v1.3 test runs (Weekly Review and Handoff Note, three passed).

- **"Wrap up" and "skip the questions" now mean different things.** "Let's wrap up" or "write it
  up" goes straight to the output. "Skip the questions" mid-way gets the two most important
  remaining questions first. Earlier versions contradicted themselves here.
- **Requests the instructions rule out** (marking unchecked work as done, ranking employees by
  activity) get a one-sentence reason, the closest acceptable alternative, and a question about how
  to proceed. They are never silently refused or silently obeyed.
- **Handoff Note.** It still pushes back once when a name, date or limit is vague. Instructions to the
  reader that you did not give are labelled "Recommended:". Every item, including dates and the facts
  in Summary and Decisions, is tagged VERIFIED, REPORTED or ASSUMED.
- **Ending.** "It's fine" or "thanks" gets a one-sentence reply with no new warnings.

## v1.3 — 2026-10-05

Fixes from four v1.2 test runs (one passed; three failed a single check each).

- **Two data requests are two questions,** even behind one question mark ("the cost along with the
  date"). The one exception is a measure together with its target.
- **No skipped steps.** Every numbered question in every mode is asked, unless an earlier answer
  covered it, and Claude says which.
- **Clean shareable documents.** Anything you may forward comes first as a clean document. Claude's
  concerns, fixes and judgement calls follow under "Notes for you (not part of the document)".
- **Stopping cleanly.** One closing question in total after the output. "It's fine" or "thanks" ends
  the session with a one-sentence reply.
- **Exact quotes.** Your words are quoted exactly. Plain-language swaps apply only to Claude's own
  words. Anything Claude adds to your actions is labelled "Recommended:".
- **Declined requests stay visible.** If Claude declines to track individuals, your request stays in
  the output marked "not included — see note", and Claude asks how you want to proceed.
- **Sharing check.** A replacement you choose (for example a role for a name) is applied everywhere at
  once, and remaining flags are reported together.

## v1.2 — 2026-10-05

Fixes from four v1.1 test runs (Initiative Check, Plan Review, Incident Investigation,
Delegation Brief). The standing rules were rewritten, not just extended.

- **A testable one-question rule.** While gathering facts, every message has exactly one question
  mark. Hidden second questions ("…and if so…", "who, and would it…") are named and banned.
- **Pacing.** Each mode aims to reach its output within about twelve questions. "Let's wrap up"
  moves straight to the output, with the gaps listed. There is at most one closing question after
  the output, and later edits show only the changed parts.
- **Judge, don't compliment.** The allowance for a "one-sentence strength note" is gone, because it
  invited praise. Answers are judged in terms of evidence. Openers of approval or thanks are banned.
- **Your words go in as you said them.** Targets, proposals, fixes and wording you state are kept
  as stated. A disagreement is shown as "My concern:" next to your version. Changes to anything you
  stated can never be filed under "Your calls to check".
- **Confidence scores above 5 must name their evidence.**
- **No consulting jargon** ("single point of failure", "leverage", "bandwidth", …).
- **No false claims about what you said or checked.**
- **"Not done" list.** Steps that were never completed are listed honestly and never described as
  skipped at your request.
- **Sharing check in one pass** over the whole text, with one question about which lines to edit.
- **Plan Review** always offers the assumption check. **Incident Investigation** always asks
  "has this happened before?" and keeps your own proposed fixes visible, marked "on hold until the
  cause is known". **Delegation Brief** only asks about scope items you haven't already covered.

## v1.1 — 2026-10-05

Fixes from the first test run (Initiative Check, CHRO scenario).

- **One question at a time, defined precisely.** One question means one fact or one decision.
  A question joining two facts with "and" counts as two. A confirming "Is that right?" is a
  question of its own.
- **Shorter messages.** At most four sentences of reaction, then one question. The running list of
  open questions now appears only in the final output.
- **More banned praise.** Added "This could work", "Good instinct", "You're right to…", "Love this"
  and one-word openers such as "Good." Praise is limited to one sentence per message and is never
  allowed inside a final output.
- **Your edits are followed exactly.** When you say remove, keep or change, Claude does exactly that,
  or asks first. It no longer reverses your instruction and then reports it under "Your calls to
  check".
- **Confidence scores on every risk**, not only on findings.
- **More plain-language swaps**: "integration", "platform" and "logs in" are replaced.
- **Per-person counts are named honestly.** A target like "6 of 10 people each did X" is
  per-person. Claude says so and suggests a way to count without identifying anyone.
- **Sharing check, stronger.** A role that only one person holds still identifies that person. The
  check now re-runs on the whole text after every edit.
- **Initiative Check.** The idea is confirmed before the first question. No question may be skipped
  just because nobody has the answer, since that gap is the finding. Before the premises, Claude lists
  the six questions as asked or skipped. "What I noticed" contains no praise.

## v1.0 — 2026-10-05

First version. Six modes (Initiative Check, Plan Review, Incident Investigation, Delegation Brief,
Weekly Review, Handoff Note) and twelve standing rules, adapted from gstack by Garry Tan.

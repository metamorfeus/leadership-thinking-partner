# Test transcript

- Test id: M2-A
- Run label: R1
- Mode: Mode 2 — Plan Review
- Date: 2026-10-05
- Assistant model: sonnet

## Conversation

### Executive (turn 1)

Review this plan.

Phase 1 (months 1–3): buy InvoiceAI licence for all 7 AP staff, €85k/year, 3-year contract. Phase 2 (months 4–6): connect to ERP, automate matching. Phase 3 (months 7–9): extend to procurement and expenses. Success: AP is more efficient. Owner: AP manager.

### Assistant (turn 1)

I'll run this as a Plan Review, since you've given me a plan to approve, fix or cut.

**My first read, before I ask anything**

- **The success measure is too weak to approve.** "AP is more efficient" can't fail. We can't tell in month 9 whether the €85k a year bought anything. Confidence 9/10, because it is in your own text.
- **The money is committed before anything is proven.** Phase 1 signs a 3-year contract, so about €255k (3 × €85k) is fixed in month 1. Phases 2 and 3 are the part that would show whether the tool works for you. Confidence 8/10 on the order of events. The risk is that you cannot walk away after a failed ERP connection. Not verified: I haven't seen the contract terms, so I don't know if there is an exit clause.
- **The scope grows without a gate.** Phase 3 extends to procurement and expenses, but nothing says Phase 2 has to succeed first. Confidence 7/10.
- **One owner for three phases.** The AP manager owns a plan that reaches into procurement and expenses. Those are probably not their teams. Not verified: I don't know your org chart.

Now the first premise question. I need to know if this is the real problem or a symptom.

What is going wrong in accounts payable today, in numbers? For example, invoices per month, days from receipt to payment, errors or late-payment fees per month. Please give me whichever of these you actually know.

### Executive (turn 2)

Too slow, I'd say. The team is drowning, lots of manual work, and we pay late fees. Everyone knows AP is a bottleneck.

### Assistant (turn 2)

"Too slow", "drowning" and "everyone knows" are the polished version, not evidence. This is weak because I can't tell from them how big the problem is, or whether InvoiceAI is the right answer to it. "Everyone knows AP is a bottleneck" is a category, not a fact. It also doesn't tell me what the late fees cost.

You gave me one real signal: you pay late fees. That is a cost, and it is the strongest thing you've said so far. A late fee is a number someone has already paid. What would change my mind is a figure that shows the late fees are small next to the €85k a year, or that the slowness comes from somewhere other than the AP team's manual work.

Here is the one number I need first. How much did you pay in late-payment fees over the last 12 months, and roughly how many invoices did that cover? An estimate is fine, but tell me if it is a guess. If you don't know, tell me who in finance would, and we'll record it as an open question.

### Executive (turn 3)

Last year it was about €140k in late penalties. Not sure how many invoices that covers, we do around 11,000 a month in total.

### Assistant (turn 3)

This works because it is a real number someone has already paid. It also changes my view of the plan.

**What the number says**
- €140k in penalties is more than the €85k yearly licence. If InvoiceAI removed most of the penalties, it would pay for itself within a year. Confidence 7/10. The figure is your estimate and I haven't seen the finance records, so it is not verified.
- 11,000 invoices a month is about 132,000 a year. With 7 people, that is roughly 1,570 invoices per person per month. The team is stretched, but that alone doesn't show the stretch is what causes the penalties. Confidence 6/10.
- The average penalty is about €1 per invoice. That tells me little. Penalties usually sit in a small number of large or repeat cases, and I don't know yet whether that is true here.

**What I still can't tell**
Invoices are late for different reasons. Some sit in AP because of manual keying and matching, and InvoiceAI could fix that. Others wait for a budget owner to approve, or are held up by a missing purchase order or a dispute with the supplier. Those delays happen outside AP, and a tool sold to the AP team would not touch them. If most of your €140k comes from the second group, the plan buys the wrong thing. What would change my mind is evidence that most late invoices waited inside AP.

Of the invoices that were paid late last year, where did most of them wait longest: inside the AP team (keying, checking, matching), or waiting for someone outside AP to approve or answer a question? Give me your best estimate as a rough split, and tell me if it is a guess. If you don't know, say who in finance could pull it, and we'll record it as an open question.

### Executive (turn 4)

Honestly I don't know the split. My guess is mostly inside AP, since a lot of invoices need manual matching, but that's a guess. Irina in finance could pull it.

### Assistant (turn 4)

A guess is fine as long as we label it as one. This is weak as evidence: "mostly inside AP" is your hunch, and it decides whether the plan buys the right thing. I'll score it 4/10, not verified. I'm not going to push a third time. I'm recording it as open question 1.

**Open question 1:** Of the late invoices behind the €140k, how many waited inside AP, and how many waited for approvals or answers from outside AP? Irina in finance can pull this. Please get it before you sign the 3-year contract. If most of the delay sits outside AP, InvoiceAI will not fix most of the €140k. If most sits inside AP, the plan is much stronger.

One thing is already clear. Doing nothing is not free. On your own number, it costs about €140k over the next 12 months. That is more than the €85k licence, so I won't argue for doing nothing.

Next, I'm checking whether you already own part of the solution. Does your current ERP, or any tool you already pay for, offer invoice matching, approval reminders or automatic routing? Has anyone switched those on or tested them? Tell me what you know. If you don't know, say who would.

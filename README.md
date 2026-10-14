# Leadership Thinking Partner

**A Claude Project that helps senior leaders think clearly before they commit time, money or people.**

You paste one set of instructions into a Claude Project. From then on, Claude works with you the way
a demanding, honest advisor would. It asks one question at a time, pushes back when your answers are
vague, refuses to flatter, is built to keep your words and not change your direction without asking, and ends every session with
something you can use: a decision record, a plan review, an incident report, a brief, a weekly review
or a handoff note.

Nothing to install. No code. It works in the normal Claude app on the web, desktop or phone.

> Built by [Metamorfeus](https://github.com/metamorfeus) for leaders running AI and business change.
> Adapted from methods in [gstack](https://github.com/garrytan/gstack) by Garry Tan (MIT licence).
> See [NOTICE.md](NOTICE.md).

---

## Why use it

Most AI assistants agree with you. That feels good and costs you later. This one is set up to do the
opposite, on purpose.

- **Fewer expensive mistakes.** It tests whether a problem is real before you fund a solution, and
  whether a plan's big commitments can be undone.
- **A clear structure, faster.** Six question sequences replace the blank page. Each session
  is built to end with a finished document, not a chat you have to summarise yourself. A person must still read it before it is used.
- **Honest answers.** It gives a position and says what evidence would change its mind. It scores how
  sure it is, and it caps that score when there is no evidence.
- **You stay in charge.** It recommends. You decide. It is built not to rewrite your goal or scope without asking. In tests it sometimes did, so read every document against your own words (see [docs/EXECUTIVE-GUIDE.html](docs/EXECUTIVE-GUIDE.html)).
- **Outputs you can forward.** Every mode is built to end with a structured document. Before you share it, it
  checks for names next to criticism, unannounced plans and confidential material.
- **Built for privacy.** It is built not to help you track or rank individual employees by activity. In one test it ranked callers after the executive pushed, so do not rely on it to refuse. Reviews run
  on results and KPIs.

## The six modes

| Mode | Use it when | Say something like | You get |
|---|---|---|---|
| **1. Initiative Check** | You are deciding whether an initiative is worth doing | "Run an Initiative Check on our idea for an AI career coach." | A one-page decision record and one assignment for this week |
| **2. Plan Review** | Someone has written a plan and you must approve, fix or cut it | "Plan Review: here is the rollout plan for accounts payable." | A review summary with accepted, deferred and excluded scope |
| **3. Incident Investigation** | Something went wrong | "Investigate why we missed Q3." | An incident report with root cause, evidence and status |
| **4. Delegation Brief** | You are handing work to a team, a consultancy or an AI tool | "Write a delegation brief for a consultancy on reducing onboarding time." | A brief nobody needs to ask follow-up questions about |
| **5. Weekly Review** | You want to review a week or month of results | "Weekly review. Here are this week's KPIs and notes." | Wins, things to improve, habits, and trends |
| **6. Handoff Note** | Work is changing hands, or you are going away | "Write a handoff for my chief of staff before my holiday." | A note that separates facts from assumptions |

## Set it up (5 minutes)

You need a Claude account. Anthropic says Projects are available on all plans, including Free (up to
five Projects). Anthropic's help pages disagree on whether Free accounts can set project instructions, so check that the button appears.

1. Open [claude.ai](https://claude.ai) and choose **Projects** in the left sidebar.
2. Click **+ New Project**. Name it *Leadership Thinking Partner*.
3. Open [PROJECT-INSTRUCTIONS.md](PROJECT-INSTRUCTIONS.md) in this repository. Copy everything from
   the line that starts "You are my thinking partner" to the end of the file.
4. In your new Project, click **Set project instructions**, paste, and click **Save instructions**.
5. Start a new chat **inside the Project** and name a mode, for example: "Run an Initiative Check on…"

Optional: add your own background files to the Project's **knowledge**, such as your strategy on a
page, your KPI definitions or your organisation chart. Claude will use them as context.
Do not add personal data about employees.

A printable one-page guide is in [docs/QUICK-START.html](docs/QUICK-START.html). Download it and open
it in your browser.

## How to get the most out of it

- **Answer honestly, including "I don't know".** The value is in the gaps it finds. Unknowns become
  open questions in your output, not made-up numbers.
- **Expect pushback.** If your first answer is a category ("our managers") or a feeling ("it will be
  smoother"), it will ask again for a name, a number or an example. That is the point.
- **Short of time?** Say "skip the questions". It will ask the two most important ones and move on,
  and it lists what was skipped.
- **One topic per chat.** Start a new chat inside the Project for each new decision.

## How it was tested

Every mode was first tested in simulated conversations (25 judged conversations on versions 1.0 to 1.6). On
13 October 2026, five further rounds used a stricter method and led to versions 1.7 to 1.9. On 14 October 2026, four
fixes made version 2.0, a repair check found one more failure, and a fifth fix made version 2.1. Version 2.1 had a re-check and
one check on six new situations.

All of it is Claude testing Claude, with a simulated executive. **Nothing was tried with a real executive or in the real
Claude app.** Known defects were seen, including a restated plan that lost a part and a statement credited to the
executive that they did not make. Read [docs/WHAT-WAS-TESTED.html](docs/WHAT-WAS-TESTED.html) for what was checked,
what each check could and could not show, and what is still open. A person must read every document before it is used.

## Privacy and good practice

- Claude Projects follow your Claude account's data settings. Check your organisation's AI policy
  before you paste confidential material.
- Use roles instead of names where you can. The built-in sharing check flags names next to criticism,
  but it cannot know what your company considers confidential.
- The Weekly Review is fed by results, targets and notes. It is built not to measure
  individual employees' activity, which is a poor measure and, in many countries, a legal risk.

## What is in this repository

| File | What it is |
|---|---|
| [PROJECT-INSTRUCTIONS.md](PROJECT-INSTRUCTIONS.md) | The instructions you paste into your Claude Project |
| [docs/QUICK-START.html](docs/QUICK-START.html) | A printable one-page guide for executives |
| [docs/EXECUTIVE-GUIDE.html](docs/EXECUTIVE-GUIDE.html) | A plain-language guide for executives: each mode, what to bring, how to check a document, known limits |
| [docs/WHAT-WAS-TESTED.html](docs/WHAT-WAS-TESTED.html) | What was tested and what was not, with the corrections to earlier result pages |
| [docs/WHAT-WAS-BUILT.html](docs/WHAT-WAS-BUILT.html) | The product record: modes, rules, decisions, exclusions, test status |
| [docs/HOW-IT-WAS-BUILT.html](docs/HOW-IT-WAS-BUILT.html) | Step-by-step guide to rebuilding it, including the test harness |
| [tests/](tests/) | The test scenarios, transcripts and test report used to check every mode |
| [CHANGELOG.md](CHANGELOG.md) | Version history |
| [NOTICE.md](NOTICE.md) | Credits and the gstack licence |
| [LICENSE](LICENSE) | MIT licence |

## Credits and licence

Created by Peter Velinov / Metamorfeus. Released under the [MIT licence](LICENSE).

The thinking methods are adapted, in our own words, from [gstack](https://github.com/garrytan/gstack)
by Garry Tan, which is also MIT-licensed. This project contains no gstack code and does not install
gstack. It is independent and not affiliated with or endorsed by Anthropic, Y Combinator or Garry Tan.

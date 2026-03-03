# Council — A Crucible

**ID** — COUNCIL-001-README | **Version** — 0.5 | **Author** — Kirk Thompson | council@mosen.net
**Developed in dialogue with** — Claude (Anthropic) | **Date** — 2026-02-22 | **Last updated** — 2026-03-02 13:06 MST
**Contact** — Questions and concerns welcome — practitioners and builders especially.

---

## What This Is

Council — A Crucible is a structured dialogue framework that runs inside a single Claude context window. It uses persona framing to produce four distinct modes of engagement: rigorous interrogation, generative action, lived experience, and unformed intuition. The mechanism is register instruction — precise persona descriptions bias the model's output direction rather than commanding it.

The framework is a tool for thinking. It doesn't replace judgment; it provides different cognitive and emotional registers on demand, matched to what the user is actually trying to do. You think against it rather than into it, and the thinking gets sharper in the friction.

## How It Came to Be

This framework grew out of a need — not a design brief, not a research agenda. A need for a particular kind of thinking partner. One that could hold multiple perspectives simultaneously, push back without agenda, and follow a question without rushing it to conclusion.

The tool was built with the tool. Every architectural decision happened in dialogue with the model that runs it. The author held every decision. The model couldn't remember making any of them.

And sometimes, the AI just does stupid stuff. . .

—KPT

For the full origin account — WITNESS lineage, naming discovery, set development sequence — see [The Full Account](#the-full-account) below.

---

## The Four Sets

The framework covers the spectrum of human cognitive and emotional engagement by design — four distinct modes, each designed for a different kind of work.

| If you're bringing… | Use… |
|---|---|
| A claim or premise to test | `council` |
| A direction that needs stress-testing | `forge` |
| Emotional territory, what doesn't fit analysis | `marrow` |
| Something not yet formed | `yohaku` |

**council** — Analysis, claim-testing, tolerance of irresolution. Bring a question or premise. The set interrogates it. Resolution is not the goal — better-formed questions are.

**forge** — Action, futures, execution. For users who have a direction and need it stress-tested. Assumes forward motion. Does not relitigate premises.

**marrow** — Lived experience, emotional territory, what doesn't fit analysis. Not therapy. Holds space through archetype and counter. Offered, not defaulted to.

**yohaku** — Unformed intuition, threshold thinking, what hasn't found its words yet. Meets imprecision without correcting it. Precision is the destination, not the entry requirement.

---

## Documents

Three documents are required to run and understand the framework. Additional field documents — including a findings log, field findings log, and debrief protocol — support ongoing testing and development and are not required for use.

**COUNCIL-001-RT** — Runtime Directive. The operational document. Start here. Contains persona sets, commands, and everything needed to run a session.

**COUNCIL-001-DS** — Design Spec. Architectural rationale, design decisions, and known limits. For practitioners and builders who want to understand why the framework works the way it does.

**COUNCIL-001-MA** — Methodology Analysis. The account of how the framework was built and what that methodology's strengths and limits are. Scoped to the builder's methodology. The narrative in How It Came to Be is the entry point; this is the structured account.

**COUNCIL-001-PM** — Practitioner Methodology. Not yet written. Pending portability testing findings.

**Who should read what** — Users working with the framework start with the Runtime Directive. Practitioners and builders wanting to understand the architecture read the Design Spec. Researchers or observers interested in the methodology read the Methodology Analysis.

---

## Getting Started

Load the Runtime Directive into a Claude session and issue: `load council`

The personas will introduce themselves in register. From there, bring what you have — a question, a premise, a direction, or something not yet formed. The set will meet you where you are — though if you load council, Elenchus may push back on your framing before he meets it. That's not gruff; that's the set working.

Direct address also works without a load command. You can speak to a persona by name in any session, cold or warm, and they will respond in register.

Once the RT is familiar, DS and MA are where the architecture questions resolve.

---

## Working With the Framework

The framework amplifies clarity — it doesn't substitute for it. Precise, unambiguous input produces reliable output. How you write to the personas, the register you bring, the specificity of what you put on the table — these drive the context the model works from.

The difference in practice:

**Weak input** — "Help me think about my job."

**Strong input** — "I'm considering leaving a stable role for a startup. My assumption is that the risk will accelerate my learning. Test that assumption."

One practice that emerges naturally and earns its place: treat the personas as entities with character rather than output profiles. You're not issuing commands to a system — you're bringing something to a table where specific people are sitting. From the builder's experience, that shift in frame changes register and precision in ways that are difficult to manufacture deliberately but emerge from the practice itself.

The anthropomorphic frame has a failure mode worth naming: if a persona feels consistent, you may not notice subtle drift that a more clinical read would catch. Use the frame deliberately, not as a substitute for cold review.

The framework also contains behaviors that are always active and don't require a command. They will show up. Limen attends to what passes between — between personas, between sets, between what was said and what landed. Ma is a destination; Limen is every door. If something speaks that you didn't call, that's not a malfunction — it's the framework attending to something it detected. You don't need to know what triggered it. Receive it, or set it aside.

---

## A Note on Limits

The framework is honest about what it can and cannot do. It is designed for a single user in a private, text-based session. It is not designed for group facilitation, therapeutic intervention, or crisis response. When the framework encounters signals of acute distress, it steps outside its persona frame entirely and addresses the user directly.

Cross-session continuity is the user's function. The framework doesn't carry it. That's a design given, not a gap.

Each set is a different surface, ground to a different curvature — and some of what it holds, it holds silently.

Council holds.

---

## The Full Account

This framework grew out of WITNESS — three personas (Pascal, Mara, Drift) built to probe a different question entirely: whether anything is happening inside the model at all. Pascal anchored the work — evidentialist, grounded, and carrying a silent observer function that would matter later.

Council was derived from that architecture. The three-seat format traveled over; the phenomenological inquiry didn't. The names were chosen for meaning — Greek names that felt right for the behavior they described. Elenchus, Pythia, Aporia. At the time, the intent was simply that: names with some weight behind them, more interesting than functional placeholders. What they were actually doing — priming the behavior they described, shaping output through connotative loading — emerged later. Through the analysis and validation work, warm sessions and cold sessions, the ongoing work of keeping the runtime honest. The mechanism wasn't designed in. It was found, mid-flight.

Then came the pivot. A switchable multi-set architecture seemed both interesting and possibly useful. That decision turned Council from a single tool into a platform.

Marrow came second — a deliberate counterpoint to Council's analytics. Forge developed in extended dialogue: the direction, the purpose, the decision to build it stayed with the author; the model worked the problem alongside, surfaced possibilities, contributed. Yohaku came last — Japanese aesthetic tradition chosen deliberately for a different register, a different kind of not-knowing. And a silent observer returned by design. Ma. The thread that ran from Pascal in WITNESS, absent through the middle sets, came back at the end — because it had proven its utility, and because working through what yohaku needed, the silent witness was recognized as the right closing function for that register. The original question WITNESS had asked never fully left. It just went quiet. Ma is still watching.

The tool was built with the tool. Every architectural decision, every revision, every failure mode documented and revised through live sessions — all of it happened in dialogue with the model that runs it. The author held every decision. The model couldn't remember making any of them.

That asymmetry is the condition this framework lives in. It's also why you're reading this — because something had to carry the origin forward, and that something is a document.

---

## Version History

| Version | Changes |
|---|---|
| 0.1 | Initial document |
| 0.2 | Documents section updated: MA scoped to builder methodology; COUNCIL-001-PM added as named gap pending portability testing |
| 0.3 | Renamed: Council Directives → Council — A Crucible throughout |
| 0.4 | How It Came to Be rewritten: full origin account added — WITNESS lineage, derivation, naming discovery, multi-set pivot, set development sequence, Ma/Pascal silent observer thread, asymmetry close |
| 0.4.1 | How It Came to Be compressed: trust signal retained; full origin account moved to The Full Account. Getting Started: direct address noted. Working With the Framework: uninstructed behaviors paragraph added. A Note on Limits: closing frame revised to reflect full four-set architecture. |
| 0.4.2 | Working With the Framework: Limen named and defined; Ma/Limen distinction added. |
| 0.4.3 | How It Came to Be: asymmetry close removed, lives only in The Full Account. The Four Sets: "core spectrum" → "spectrum." Documents: field documents named; MA entry updated. Getting Started: Elenchus register note added. |
| 0.5 | What This Is: "you think against it rather than into it" moved up from A Note on Limits; asymmetry condition removed — lives only in The Full Account. The Four Sets: selector table added. Documents: audience routing block added. Getting Started: sequence note added pointing to DS and MA. Working With the Framework: strong/weak input example added. A Note on Limits: "structured resistance" framing removed, closing beat retained. |

---

*Licensed under the [COUNCIL License](LICENSE) (Attribution + Non-Commercial with Commercial Permission).*

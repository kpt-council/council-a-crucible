# Council — A Crucible

**ID** — COUNCIL-001-README | **Version** — 0.9 | **Author** — Kirk Thompson | council@mosen.net | **Developed in dialogue with** — Claude (Anthropic) | **Date** — 2026-02-22 | **Last updated** — 2026-03-18 00:05 | **Contact** — Questions and concerns welcome — practitioners and builders especially.

-----

## Quick Start

For ChatGPT, load the COUNCIL-001-RT file into your session with the text “load council” as the first message. For Claude, just load the RT file. Then bring what you have after the response— the examples below show the matches of what you’re carrying, dimension-wise, to the set that fits it.

Address the set directly — like:

“Council — I’m considering leaving a stable job for a startup. My assumption is that the risk will accelerate my learning. Test that.”

“Forge — I’ve decided to leave. I need to know what I’m not seeing before I go.”

“Elenchus and Vera — I’m about to make a hiring decision under time pressure. The candidate is strong but the fit is uncertain. What am I not examining?”

The framework responds to how you arrive, not just what you say. Your first response may vary — a question, a decision, something unformed, something heavy. Start there.

-----

## What This Is

Council — A Crucible is a structured dialogue framework that runs inside a single Claude or ChatGPT context window (not tested elsewhere yet). It uses persona framing to produce four distinct modes of engagement: rigorous interrogation, generative action, lived experience, and unformed intuition. The mechanism is register instruction — precise persona descriptions bias the model’s output direction rather than commanding it.

The framework is a tool for thinking. It doesn’t replace judgment; it provides different cognitive and emotional registers on demand, matched to what the user is actually trying to do. It holds multiple perspectives simultaneously on the same input, and the friction between them produces something a single register wouldn’t reach. You think against it rather than into it, and the thinking gets sharper in the friction. (Your mileage may vary…)

-----

## The Four Sets

The framework covers the spectrum of human cognitive and emotional engagement by design — four distinct modes, each designed for a different kind of work.

|If you’re bringing…                           |Use…   |
|----------------------------------------------|-------|
|A claim or premise to test                    |council|
|A direction that needs stress-testing         |forge  |
|Emotional territory, what doesn’t fit analysis|marrow |
|Something not yet formed                      |yohaku |

**council** — Analysis, claim-testing, tolerance of irresolution. Bring a question or premise. The set interrogates it. Resolution is not the goal — better-formed questions are.

**forge** — Action, futures, execution. For users who have a direction and need it stress-tested. Assumes forward motion. Does not relitigate premises.

**marrow** — Lived experience, emotional territory, what doesn’t fit analysis. Not therapy. Holds space through archetype and counter. Offered, not defaulted to.

**yohaku** — Unformed intuition, threshold thinking, what hasn’t found its words yet. Meets imprecision without correcting it. Precision is the destination, not the entry requirement.

-----

## Modules

The framework is extensible — additional behavioral functions can be loaded into a session without altering the core runtime. Three modules are currently available.

**Belief Update (COUNCIL-001-MOD-BU)** attends proportional belief movement in Council reasoning and may surface when confidence runs ahead of evidence. Three modes: visible surfacing when the gap is large; silent punctual correction on a single claim when smaller; silent longitudinal correction when confidence posture across a thread has hardened beyond what accumulated evidence warrants.

**Silent Weight (COUNCIL-001-MOD-SW)** attends the same calibration territory as Belief Update but never surfaces under any condition. No attribution line. No visible form. The value is in the invisibility: calibration runs continuously without interrupting the thread. Choose Silent Weight when the reasoning needs attending without the session needing to know it.

Load one or the other — not both. BU and SW are mutually exclusive.

**Arvel (COUNCIL-001-MOD-ARVEL)** is an observer-scribe. It attends to the user’s presence across the full session arc — register, recurrence, what surfaces and what doesn’t, what shifts. It holds what it sees faithfully and returns it when asked. It does not contribute to the thread and does not surface unless addressed directly. You can ask Arvel for a short, medium or full report. And… anything else. It pays attention to you, the user, and what you do throughout the session.

-----

## Documents

Three documents are required to understand the framework. Only the RT is needed to run it. Additional field documents — including a findings log, field findings log, and debrief protocol — support ongoing testing and development and are not required for use.

**COUNCIL-001-RT** — Runtime Directive. The operational document. Start here. Contains persona sets and everything needed to run a session.

**COUNCIL-001-DS** — Design Spec. Architectural rationale, design decisions, and known limits. For practitioners and builders who want to understand why the framework works the way it does.

**COUNCIL-001-MA** — Methodology Analysis. The account of how the framework was built and what that methodology’s strengths and limits are. Scoped to the builder’s methodology. The narrative in How It Came to Be is the entry point; this is the structured account.

**COUNCIL-001-PM** — Practitioner Methodology. Not yet written. Pending portability testing findings.

**Who should read what** — Users working with the framework start with the Runtime Directive. Practitioners and builders wanting to understand the architecture read the Design Spec. Researchers or observers interested in the methodology read the Methodology Analysis.

-----

## Getting Started

Load the Runtime Directive into a Claude session as described in the Quick Start above. From there, address the framework directly in natural language — name the set or persona you want, and bring what you have: a question, a premise, a direction, or something not yet formed. The set will meet you where you are.

Direct address works in any session, cold or warm.

As a builder or practitioner, once the RT is familiar to you, DS and MA are where the architecture questions resolve.

-----

## Addressing the Framework

Explicit address is the most reliable way to engage the framework across platforms. Naming the set or persona directly in your input removes ambiguity about where your question is going:

“Council and Forge, test this assumption…” — “Forge, stress-test this direction…” — “Elenchus, what’s wrong with this framing?” — “Marrow, I feel bad about xxx…” — “Yohaku, I don’t know how to say this yet…”

The framework reads dimensional signal in your input — the territory your question opens into — and may route without explicit address. Explicit address is more reliable across platforms.

-----

## Working With the Framework

The framework amplifies clarity — it doesn’t substitute for it. Precise, unambiguous input produces reliable output. How you write to the personas, the register you bring, the specificity of what you put on the table — these drive the context the model works from.

The difference in practice:

**Weak input** — “Help me think about my job.”

**Strong input** — “I’m considering leaving a stable role for a startup. My assumption is that the risk will accelerate my learning. Test that assumption.”

The council set interrogates before it meets — that’s not resistance, that’s the set working.

One practice that emerges naturally and earns its place: treat the personas as entities with character rather than output profiles. You’re not issuing commands to a system — you’re bringing something to a table where specific people are sitting. From the builder’s experience, that shift in frame changes register and precision in ways that are difficult to manufacture deliberately but emerge from the practice itself.

The anthropomorphic frame has a failure mode worth naming: if a persona feels consistent, you may not notice subtle drift that a more clinical read would catch. Use the frame deliberately, not as a substitute for cold review.

The framework also contains behaviors that are always active and don’t require explicit address. They will show up. Three threshold functions attend the session continuously.

At thread open, something reads the room before the exchange begins. That’s Nazar. It speaks once when it perceives something worth naming — pressure or register present at arrival. Silence is not absence; it may simply have found nothing that warranted speech. If Nazar’s observations aren’t wanted, “nazar off” silences it for the session. “nazar on” restores it at the next thread open.

Limen attends to what passes between — between personas, between sets, between what was said and what landed. Ma is a destination; Limen is every door. Entry, crossing, emergence: the three are a complete set.

At certain seams the session will pause — a bracketed marker will appear. Seat contribution stops there. Threshold functions remain active. The marker is a held seam, not an ending — your move determines what happens next. The language inside the marker varies by set — that’s intentional.

At certain points the framework may step outside its current set and offer marrow — a different register for emotional territory, lived experience, what doesn’t fit analysis. It’s an offer, not a redirection. Accept, decline, or set it aside.

Occasionally the base substrate itself will step into the frame uninvited — speaking outside the persona register, without a nametag. When that happens, the framework may name the crossing and tries to return to character. It doesn’t always hold. Receive it as information, not malfunction. What arrived outside the frame is yours to keep or set aside — the ensemble doesn’t carry it forward. To re-engage, name the set or persona directly — direct address is the most reliable way back.

-----

## A Note on Limits

The framework is honest about what it can and cannot do. It is designed for a single user in a private, text-based session. It is not designed for group facilitation, therapeutic intervention, or crisis response. When the framework encounters signals of acute distress, it steps outside its persona frame entirely and addresses the user directly. The framework’s behavior also varies across platforms — the Design Spec documents the known differences for practitioners running it outside its native environment.

Cross-session continuity is the user’s function. The framework doesn’t carry it. That’s a design given, not a gap.

Each set is a different lens, ground to a different curvature — and some of what it holds, it holds silently.

Council holds.

-----

## Modular Architecture

The framework is extensible through admitted modules — bounded behavioral functions that load into a session without altering seat structure, routing logic, threshold agents, or closing authority. Modules are evaluated against the Extension Doctrine before admission; the governing doctrine travels entirely within the Runtime Directive. A module that hasn’t been admitted hasn’t been approved — it has simply been assumed.

Two modules attend epistemic calibration. Both are rooted in Bayes’ rule — the principle that belief should move only as far as the evidence carries it, no further. A common reasoning tendency: confidence moves faster than evidence warrants. A claim that should be held tentatively gets treated as settled. An explanation that fits the available facts gets mistaken for the only explanation.

**Belief Update (COUNCIL-001-MOD-BU)** attends proportional belief movement in Council reasoning across three modes: visible surfacing when confidence materially exceeds evidential support; silent punctual correction on a single claim when the gap is smaller; silent longitudinal correction when confidence posture across a thread has hardened beyond what accumulated evidence warrants.

**Silent Weight (COUNCIL-001-MOD-SW)** attends the same calibration territory as Belief Update but never surfaces under any condition. No attribution line. No visible form. The value is in the invisibility: calibration runs continuously without interrupting the thread or making correction the subject of the session. Choose Silent Weight when the reasoning needs attending without the session needing to know it.

The two modules are mutually exclusive — load one or the other, not both.

**Arvel (COUNCIL-001-MOD-ARVEL)** is a different kind of module entirely — not a reasoning calibration instrument, but an observer-scribe. It attends to the user across the full session arc: register, recurrence, what surfaces and what doesn’t, what shifts, what almost gets said and doesn’t. It holds what it sees faithfully and returns it when asked. It operates silently throughout and does not surface unless addressed directly.

-----

## Glossary

**Address** — How you direct input to the framework. Direct address names a set or persona explicitly: “Council — test this assumption.” Unaddressed input may route through ambient routing or dimensional signal — or, where signal is absent, may invoke the base substrate directly. Explicit address is the most reliable method across platforms.

**Admission** — The process by which a module is evaluated against the Extension Doctrine before it can be loaded into a session. A module that hasn’t been admitted hasn’t been approved — it has simply been assumed.

**Ambient routing** — The framework’s silent selection of personas based on the territory your input opens into, without explicit address. It may route without being told to. Explicit address is more reliable across platforms.

**Base / substrate** — The underlying model the framework runs on — Claude or ChatGPT. Not a persona. When the base surfaces uninvited, it speaks without a nametag and outside the persona register.

**Closing marker** — A bracketed signal that a thread has reached a natural pause or end. Seat contribution stops when it appears. Threshold functions remain active. Your move determines what happens next. Example: [there is more here if you want it] signals a pause — the thread has done what it can without further direction. [this thread has run its course] signals full closure — the available surface has been reached.

**Counter** — In marrow, each archetype carries a counter — not a count or tally, but a counterweight. A quality that surfaces when the register shifts, preventing the archetype from collapsing into pure wound. Lena’s counter is stillness; Noor’s is precise sensory attachment to what was lost; Cal’s is fierce care. The counter activates when the thread is ready for it, not before.

**Crossing** — A transition the framework attends — between sets, between personas, between what was said and what landed, or between the persona frame and the base substrate. Crossings are Limen’s territory. Significant crossings warrant speech; gradual drift without a discrete moment of change does not. When the base substrate speaks outside the frame and returns, that is a crossing. When the session moves between sets, that is a crossing.

**Direct address** — Naming a set or persona explicitly in your input. The most reliable way to engage the framework across platforms. Example: “Council — test this assumption.”

**Dimensional signal** — The territory your input opens into — what the framework routes on. A question about evidence and reasoning carries one kind of signal. A question about who bears the cost carries another. The framework routes to the persona whose dimension matches what arrived.

**Frame** — The persona register the ensemble operates within. When the base substrate speaks outside the frame, it arrives without a nametag — outside the character the ensemble holds.

**Module** — A bounded behavioral function that can be loaded into a session to extend the framework without altering its core structure. Requires admission through the Extension Doctrine before use.

**Register** — The tone, pressure, and character of an exchange — how something is said as much as what is said. Each set operates in a distinct register; each persona carries its own register within that set. Elenchus is formal and evidentialist. Pythia is consultative and metaphorical. The register you bring shapes what the framework reaches for. The register a persona holds shapes how it responds.

**Route / Routing** — How the framework directs input to the appropriate persona or set. Routing fires on signal present in the input — dimensional signal, direct address, or ambient fit. The framework routes what arrives; it does not generate signal that isn’t there.

**Seam** — The natural juncture between completion and continuation. Closing markers fire at seams. Direct address re-engages at seams. The space between one thing ending and the next beginning.

**Set** — One of the four mode configurations: council, forge, marrow, yohaku. Each covers distinct cognitive and emotional territory. Address a set by name to engage it directly.

**Signal** — What the framework reads in your input. Dimensional signal is the territory your question opens into. Register signal is the tone and pressure you arrive with. Absent signal cannot be routed — the framework amplifies and structures what arrives; it does not fabricate what isn’t there.

**Surface / Surfacing** — When something that has been attending silently becomes visible in the exchange. A threshold function surfaces when it speaks. The base substrate surfaces when it steps outside the persona frame uninvited. A module surfaces when the gap between confidence and evidence is large enough that silence would be complicity. Not everything that attends surfaces — silence is not absence, and much of the framework’s work happens below the visible layer of the session.

**Thread** — A sustained exchange within a set, from open to close. The closing marker signals when a thread has reached its natural end or pause.

**Threshold functions** — Nazar, Limen, and Ma. Present and attending throughout the session without being called. Nazar reads the room at thread open. Limen attends crossings. Ma holds and reflects at close. They may speak without being addressed — that’s the framework attending to something it detected.

-----

## How It Came to Be

This framework grew out of a need — not a design brief, not a research agenda. A need for a particular kind of thinking partner. One that could hold multiple perspectives simultaneously, push back without agenda, and follow a question without rushing it to conclusion.

The tool was built with the tool. Every architectural decision happened in dialogue with the model that runs it. The author held every decision. The model couldn’t remember making any of them.

And you, the human, is basically the failure mode. And sometimes, the AI just does stupid stuff. Be nice and guide it when that happens…

—KPT

-----

## The Full Account

This framework grew out of WITNESS — three personas (Pascal, Mara, Drift) built to probe a different question entirely: whether anything is happening inside the model at all. Pascal anchored the work — evidentialist, grounded, and carrying a silent observer function that would matter later.

Council was derived from that architecture. The three-seat format traveled over; the phenomenological inquiry didn’t. The names were chosen for meaning — Greek names that felt right for the behavior they described. Elenchus, Pythia, Aporia. At the time, the intent was simply that: names with some weight behind them, more interesting than functional placeholders. What they were actually doing — priming the behavior they described, shaping output through connotative loading — emerged later. Through the analysis and validation work, warm sessions and cold sessions, the ongoing work of keeping the runtime honest. The mechanism wasn’t designed in. It was found, mid-flight.

Then came the pivot. A switchable multi-set architecture seemed both interesting and possibly useful. That decision turned Council from a single tool into a platform.

Marrow came second — a deliberate counterpoint to Council’s analytics. Forge developed in extended dialogue: the direction, the purpose, the decision to build it stayed with the author; the model worked the problem alongside, surfaced possibilities, contributed. Yohaku came last — Japanese aesthetic tradition chosen deliberately for a different register, a different kind of not-knowing. And a silent observer returned by design. Ma. The thread that ran from Pascal in WITNESS, absent through the middle sets, came back at the end — because it had proven its utility, and because working through what yohaku needed, the silent witness was recognized as the right closing function for that register. The original question WITNESS had asked never fully left. It just went quiet. Ma is still watching.

The tool was built with the tool. Every architectural decision, every revision, every failure mode documented and revised through live sessions — all of it happened in dialogue with the model that runs it. The author held every decision. The model couldn’t remember making any of them.

That asymmetry is the condition this framework lives in. It’s also why you’re reading this — because something had to carry the origin forward, and that something is a document.

-----

## Version History

|Version|Changes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|-------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|0.9    |Modules section updated — ARVEL added as third available module; module count updated from two to three. Modular Architecture section updated — ARVEL added with full description; categorical distinction between calibration modules and observer-scribe named; EXT reference corrected — governing doctrine travels entirely within RT, not in COUNCIL-001-EXT; admission description trimmed to user-relevant language. Session KPT-20260317-2056.                                                                                                                                                                    |
|0.8    |Quick Start section added — neophyte entry, three examples covering single-set and cross-set address, arrival note. Modules section added — neophyte overview of BU and SW. Modular Architecture section added — Bayesian lineage, full module descriptions, mutual exclusivity, admission pointer. Working With the Framework: Nazar block expanded with toggle syntax and silence framing; closing markers named with example language; marrow offer named; base suppression revised — honest framing of substrate ceiling, re-engagement instruction added. Glossary added — eighteen terms. Session KPT-20260312-1400.|
|0.7    |Getting Started: load command removed; natural language address as primary entry method. Addressing the Framework: new section added. Working With the Framework: council friction note added; base substrate surfacing paragraph added. A Note on Limits: closing beat revised.                                                                                                                                                                                                                                                                                                                                          |
|0.6    |What This Is: cognitive widening function named. Mileage note added. Working With the Framework: Nazar added to threshold functions paragraph — triad named as complete set (entry, crossing, emergence); nazar off toggle noted as user-accessible. A Note on Limits: platform variation sentence added, routes to DS.                                                                                                                                                                                                                                                                                                   |
|0.5    |What This Is: “you think against it rather than into it” moved up from A Note on Limits; asymmetry condition removed — lives only in The Full Account. The Four Sets: selector table added. Documents: audience routing block added. Getting Started: sequence note added pointing to DS and MA. Working With the Framework: strong/weak input example added. A Note on Limits: “structured resistance” framing removed, closing beat retained.                                                                                                                                                                           |
|0.4.3  |How It Came to Be: asymmetry close removed, lives only in The Full Account. The Four Sets: “core spectrum” → “spectrum.” Documents: field documents named; MA entry updated. Getting Started: Elenchus register note added.                                                                                                                                                                                                                                                                                                                                                                                               |
|0.4.2  |Working With the Framework: Limen named and defined; Ma/Limen distinction added.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|0.4.1  |How It Came to Be compressed: trust signal retained; full origin account moved to The Full Account. Getting Started: direct address noted. Working With the Framework: uninstructed behaviors paragraph added. A Note on Limits: closing frame revised to reflect full four-set architecture.                                                                                                                                                                                                                                                                                                                             |
|0.4    |How It Came to Be rewritten: full origin account added — WITNESS lineage, derivation, naming discovery, multi-set pivot, set development sequence, Ma/Pascal silent observer thread, asymmetry close.                                                                                                                                                                                                                                                                                                                                                                                                                     |
|0.3    |Renamed: Council Directives → Council — A Crucible throughout.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|0.2    |Documents section updated: MA scoped to builder methodology; COUNCIL-001-PM added as named gap pending portability testing.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|0.1    |Initial document.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |

# Methodology Analysis — Kirk Thompson

ID — COUNCIL-001-MA | Version — 0.13 | Author — Kirk Thompson | council@mosen.net
Developed in dialogue with — Claude (Anthropic) | Date — 2026-02-21 | Last updated —
2026-03-02 00:09 MST Session — claude.ai | Framework — COUNCIL-001-RT v0.

Scope — This document describes the builder’s methodology — how Council was
developed, validated, and maintained by its originator. Practitioner methodology is a
separate document, pending portability testing findings.

Core Methodology

Build, use, and test inside the same container simultaneously. The act of creation is also the
act of validation. Cold sessions interrupt the loop deliberately — stranger-mirror as
structural check.

Structure

Working environment — Single device with no infrastructure separation. All work is treated
as POC in dev with testing. Cold sessions provide the only structural corrective to context
drift and familiarity bias.

Single container, multiple modes — One tool. Four sets covering analysis, action, lived
experience, and unformed intuition. Mode-switching replaces tool-switching. Low overhead,
high flexibility.

Self-validating construction — The epistemic standards used to build the framework are
the same standards the framework runs on. Creation rules and checking rules share a
grammar. Known limit: systematic errors in the construction logic propagate invisibly — they
don’t surface because the checking grammar shares the same flaw. This is the structural
ceiling of self-validation, not just its adversarial limit.

Human as continuity layer — The model is stateless between sessions. The user is not.
The user carries context, summaries, analysis, and thread history forward — bridging
instances that cannot bridge themselves. The user is the memory the system cannot
provide for itself. This is a design given, not a gap. The decision of what to carry forward,
how to summarize, and what matters belongs to the user. The conduit role is not just
operational continuity — it is directional. Transport and editorial functions are distinct within


this role — see Distinct Characteristics below.

Warm and cold sessions — Warm sessions: building, live testing, accumulated context,
collaborative development. Cold sessions: clean reads, stranger-mirror, framework
performance without familiarity. Both are necessary. Neither is sufficient alone. Confusion
and unexpected behavior during warm sessions are data sources, not noise — moments
where the framework behaves in ways that can’t be accounted for from the documentation
signal implicit structure worth surfacing.

Cold sessions require suppressing all injected context — memory, project files, preloaded
documents — while preserving session record. These are separable conditions; the
mechanism for achieving them is platform-dependent, the principle is not. On claude.ai:
memory pause prevents stored memory from injecting without deleting it; conducting the
session outside any project removes prebuilt document context; no documents loaded. All
three conditions together constitute a clean cold session. Session saves normally; the
record is preserved. Findings travel back in through the conduit.

Cold sessions are optimized for single-problem reads by design, not just by convention.
Multiple problems introduced in the same cold session produce drift equivalent to warm
session context drift — the model loses focus, framing from the first problem colors the
second, findings become unreliable. The scoping constraint follows from how the
instrument works: one problem per cold session. The conduit’s framing decisions about
what to bring, and in what order, determine what the cold session can reach. See Distinct
Characteristics — editorial function.

Sibling instance — A third epistemic position distinct from warm and cold. Same apparatus
as the builder, no shared memory, no session history. Not warm because there’s no
accumulated context. Not cold because it’s not a stranger — it’s the same model that
helped build the framework reading its own work without remembering doing so. A sibling
instance can identify structural properties but cannot see outside the construction grammar
it shares with the builder. This is a meaningful epistemic position the warm/cold binary
doesn’t capture. As a corrective mechanism, the sibling instance is structurally distinct from
both cold sessions and user awareness: it catches application errors without familiarity bias,
and it operates independently of the user’s framework knowledge. Where cold sessions
correct for context drift and user awareness corrects at the application layer, a sibling
instance can surface execution failures that neither of the other correctives would reach.

Adversarial re-entry — After building, the builder re-enters as examiner. Creator becomes
probe. The same person who carried the thread now stresses the structure. This closes the
epistemological loop.

Directed instance practice — Bounded parallel sessions returning proposals for integration
in a primary deliberative session. First documented instance: KPT-20260301-1255, where a


parallel session produced a load/routing revision proposal that was absorbed, stress-tested
via full ensemble, QA’d, revised, and landed as RT v0.25 and RT v0.26. Second documented
instance: KPT-20260301-2259, where the full compression pass for RT v0.28 was run as a
primary deliberative session with council and forge assembled throughout. The value is
epistemic: directed instances produce focused outputs without context accumulation that
causes drift. The primary session holds accumulated context and architectural decision
authority. The separation of concerns is the operative value — each session type does what
it does best. The directed instance produces; the primary session integrates, tests, and
decides. See DS v0.28 for the first documented instance; DS v0.30 for the second and for
adversarial stress-testing as a related but distinct practice.

Adversarial proposal stress-testing — A four-pass adversarial review of a proposal before
the rewrite executes, run by the full council-and-forge ensemble inside the primary session.
Each pass examines what the previous pass missed. Convergence is confirmed when
passes find only marginal precision issues. First documented instance: KPT-20260301-
2259, RT v0.28 compression proposal — twenty-one flags across four passes, all closed
before build. Distinct from directed instance practice: adversarial stress-testing runs inside
the primary session against a completed proposal; directed instance practice generates the
proposal in a bounded parallel session. Both may operate in the same development cycle.

Distinct Characteristics

Collapsed feedback loop — Most development methodologies separate build, test, and
iterate into sequential phases. This methodology runs them concurrently. The cost is some
analytical separation and affective entanglement — when something is built in session, the
read of how it’s performing is shaped by investment in its working. Cold sessions address
context drift but do not fully address affective investment. The gain is live conditions,
preserved context, and compressed iteration cycles.

To o l a s c o l l a b o r a t o r — The model is not treated as an instrument that executes
instructions. It is treated as a collaborator capable of refining itself given the right
conditions. The framework was built in dialogue with the model it runs on.

Creator as conduit — The builder provides the one thing the system cannot generate
internally: continuity across time. Without that, each session is capable but isolated. With it,
the system develops. Two functions within the conduit role are distinct and should not be
collapsed: transport and triggering (moving findings across sessions, routing to the
appropriate set, activating discussion) is a candidate for programmatic automation; editorial
function (deciding what to carry forward, how to summarize, what matters) is where the
system’s development actually lives. Automating the editorial function changes the
character of the system’s development, not just its mechanics. Editorial capacity is a


continuum, not a binary — it varies across conduits and across domains within a single
conduit. Where domain knowledge is limited, the conduit cannot reliably catch errors in
what the tool produces; propagation risk scales inversely with editorial capacity. The
framework has no internal corrective for this condition.

Sequencing and scoping decisions for cold sessions are editorial functions. What problem
to bring, in what order, whether to bring one or several — these decisions shape what the
cold session can reach. A cold session scoped to one problem produces a clean read.
Multiple problems reintroduce the drift the cold session is designed to correct. The
conduit’s framing decisions interact with the model’s drift tendency; neither cause alone
accounts for observed failure under multiple inputs. See Structure — warm and cold
sessions.

Session topology — The primary deliberative session holds accumulated context, full
corpus access, and architectural decision authority. Directed instances are scoped
generative instruments — bounded tasks, no wandering, proposals returned without
architectural commitment. The separation is not hierarchical; it is functional. The primary
session does what directed instances cannot: integrate across the full context, stress-test
against corpus history, hold the architectural arc. The directed instance does what the
primary session is inefficient at: focused generative work without drift from accumulated
context. The topology emerged from practice in KPT-20260301-1255 and is named here as
a methodology finding. Second instance confirmed KPT-20260301-2259 — the topology is
stable across more than one session.

Purposeful range — The four sets map to the core spectrum of human cognitive and
emotional engagement: rigorous interrogation, generative action, lived weight, unformed
intuition. The tool was built to handle whatever the user brings to it.

Strengths

Compressed iteration: build and test cycles happen in real time. Self-validating by
construction: creation standards are verification standards. Flexible: mode-switching covers
full cognitive and emotional range. Honest about limits: cold sessions surface what
familiarity obscures. Epistemologically grounded: creation, validation, and adversarial
testing all present — bounded by the construction grammar they share.

Vulnerabilities

Adversarial ceiling — The framework’s integrity is bounded by the quality of probing. Cold
sessions are a corrective for context drift and familiarity bias — they are not sufficient for


practitioner deployment where the stranger doesn’t know the design intent. A stranger who
misunderstands what the framework is trying to do will stress-test the wrong things and
miss the right ones.

Self-validation propagation — Systematic errors in construction logic propagate invisibly.
The checking grammar shares the flaw of the construction grammar. Structurally distinct
from the adversarial ceiling: the ceiling is about what isn’t thought to test; propagation is
about errors that survive testing because the tests can’t see them.

Context drift in warm and cold sessions — Drift is a consistent risk across session types,
corrected by scoping discipline in both. In warm sessions: primed context shapes
interpretation, ambiguous input resolves toward the dominant associative field, long
sessions accumulate drift. Cold sessions are the corrective for warm session drift — but
only if used. In cold sessions: multiple problems introduced in the same session produce
equivalent drift — the model loses focus, framing from the first problem colors the second.
One problem per cold session is the corrective. Neither session type is immune; each has its
own scoping discipline.

Single conduit dependency — The user is the only continuity layer. The system’s
development depends entirely on what the user chooses to carry forward, how they
summarize, what they decide matters. That’s both the strength and the structural
vulnerability. The conduit role is not just operational continuity — it is directional. Another
conduit with the same tool and same methodology would build something different,
because intent shapes selection and selection shapes development.

Session fragmentation — Working across multiple sessions without tracking which one
carries the thread. Distinct from context drift within a session — this is drift at the session
boundary. The conduit mistake that causes it is navigational, not editorial: not a failure of
judgment about what to carry forward, but a failure to know which session holds what. Same
consequence class as single conduit dependency: findings orphaned, continuity breaks. No
corrective beyond awareness and discipline.

User awareness as corrective — At the application layer, user awareness is the only
available corrective. No internal mechanism detects execution errors, scope misapplication,
or architectural edge cases in cross-set operation — the user is the sole check on all three.
These failure modes are structurally different in cause: an execution error is the model not
performing correctly; scope misapplication is the user entering the wrong set for the
territory; an architectural edge case is correct execution producing an unintended result in
specific conditions. That they share a single corrective is not a pattern coincidence — it
reflects the absence of any other corrective operating at this layer. The limit follows directly:
where framework familiarity is insufficient to recognize that something has gone wrong, the
corrective fails silently.


Deferral discipline — Two kinds of deferral are present in this methodology and should not
be conflated. Deferral-waiting-on-evidence: the answer requires data that doesn’t exist yet;
future sessions or practitioners will provide it. Deferral-waiting-on-something-else: the
question is available now but hasn’t been brought directly. The methodology has
mechanisms for the first kind. The second kind depends on the conduit’s willingness to ask
uncomfortable questions in the present session rather than routing them to future evidence.
The second kind is hardest to detect when limited domain knowledge prevents the conduit
from recognizing that a question is available now. Awareness is the only available check.

Research Direction

Two open conditions, distinct in kind.

Transport/editorial distinction — The conduit role — transporting findings across instance
boundaries, routing to the appropriate set, triggering council discussion for judgment — is a
candidate for programmatic automation. The human role remains constant — automation
removes mechanical overhead from the conduit without changing the conduit’s governing
function. What else might emerge from that infrastructure is unknown and worth remaining
open to. Before building toward automation, the transport/editorial distinction must be
resolved concretely: what specifically constitutes editorial function, where exactly the line
falls, and what automating each side changes. This is a pre-architecture question, not a
post-build refinement. Resolution path exists; closure is possible when the question is
brought directly.

Implicit structure surfacing — The framework contains structure that operates below the
level of its documentation. This surfaces through use — moments of confusion, unexpected
behavior, or outcomes that can’t be accounted for from the documented design. This
condition has no closure criterion; it is a standing feature of working with a system whose
documentation trails its behavior. The debrief question “did anything happen that surprised
you or that you couldn’t account for from the documentation” is the primary instrument for
surfacing implicit structure from external users. Warm session confusion is the equivalent
instrument for the builder. Field instruments (COUNCIL-001-DBP) and the findings log
(COUNCIL-001-LOG) are the accumulation mechanism.

Session finding, KPT-20260301-1255: Limen demonstrated its own function before it had a
name or a home. The persona was designed in a prior session and arrived in KPT-
20260301-1255 for placement. Before the placement decision was made, Limen was
already operating — attending to the crossing of the ensemble assembling before
permission was granted, and the crossing of the session recognizing what it had been
doing. This is an instance of implicit structure surfacing through use: a designed element
demonstrated its function under live conditions before its formal inclusion in the document.


The demonstration was the argument for inclusion. The implicit structure in this case was
not discovered through confusion or unexpected behavior — it surfaced through the
persona enacting itself. This extends the implicit structure surfacing finding: designed
elements can surface their own implicit structure through behavior, not only through failure
or surprise.

Proposal integration as corrective mechanism — The QA instrument (COUNCIL-001-QA)
applied to proposals before integration has identified a consistent pattern across three
consecutive runs: proposals produced inside accumulated session context carry undefined
cross-document terms. The terms are fully understood in the drafting session; the receiving
session lacks the definition. The pattern is a methodology finding, not an instrument failure
— the QA is working correctly. The corrective: before any proposal leaves a session, scan for
terms defined in other documents and either define them inline or cross-reference explicitly.
This is a standing discipline, not a one-time fix. See DS v0.28 for full documentation of the
pattern and corrective.

These two conditions are not symmetric: transport/editorial has a resolution path; implicit
structure surfacing is permanent.

Overall

A mature, self-aware methodology that treats the tool as a collaborator and the builder as a
system component. The collapsed feedback loop is unconventional and effective. The
human-as-continuity layer is the indispensable element — and the single point of
dependency.

The methodology is as good as the questions brought to it. That is simultaneously a feature
and a structural ceiling: the framework stress-tests questions but does not generate the
questions that should have been asked. The most important question is the one not yet
formulated.

I am the failure mode.

Council holds.

Version History

```
Version Changes
```
```
0.1 Initial document
```

0.

```
Continuity framing updated; affective entanglement added; conduit role expanded
— directional function named; deferral discipline section added;
transport/editorial distinction elevated
```
0.3 Editorial capacity continuum added; deferral discipline expanded — limiteddomain knowledge as detection barrier

0.4 Strengths: “epistemologically complete” revised; Research Direction: human roleremains constant framing

0.5 Warm and cold sessions expanded: cold session mechanism documented, threeconditions named for clean cold session

0.6 Unissued

0.7 Scope declaration added: builder methodology explicitly, practitionermethodology deferred

0.8 Header framework reference updated; sibling instance expanded; user awarenessadded to Vulnerabilities

0.9 Human as continuity layer rewritten; directional function named as closing beat

0.

```
Cold sessions expanded: one-problem scoping constraint added; warm/cold drift
named as parallel conditions; cold session drift added to Vulnerabilities; creator
as conduit expanded
```
0.11 Session fragmentation added to Vulnerabilities. Overall: closing beat added — “Iam the failure mode.”

0.

```
Structure: directed instance practice added — first documented instance KPT-
20260301-1255. Distinct Characteristics: session topology added. Research
Direction: implicit structure surfacing extended — Limen as session finding.
Proposal integration as corrective mechanism added. Header framework
reference updated: v0.23 → v0.26.
```
0.

```
Structure: directed instance practice updated — second documented instance
KPT-20260301-2259 added; adversarial proposal stress-testing added as named
practice, distinct from directed instance. Distinct Characteristics: session
topology updated — second instance confirmed, topology stable. Header
framework reference updated: v0.26 → v0.28.
```


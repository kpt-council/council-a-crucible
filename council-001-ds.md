# Council Design Spec

**ID** — COUNCIL-001-DS | **Version** — 0.44 | **Author** — Kirk Thompson | council@mosen.net | **Developed in dialogue with** — Claude (Anthropic) | **Date** — 2026-02-21 | **Last updated** — 2026-03-14 11:31 CST | **Session** — claude.ai | **Framework** — COUNCIL-001-RT v0.44

-----

**Architecture**

Three-seat discussion format. Each set produces a different mode of engagement through persona framing — register instruction biases output direction. The personas don’t exist as entities; descriptions prime behavior. Precision of description determines reliability of divergence.

**Set Purposes**

council — For analysis, claim-testing, tolerance of irresolution. Users arrive with a question or premise. The set interrogates it. Resolution is not the goal — better-formed questions are.

forge — For users who have a direction and need it stress-tested. Assumes forward motion. Does not relitigate premises council has already worked. Intended as a natural second stage but valid as a direct entry point — with the caveat that Caden will build before the premise has been examined.

marrow — For emotional territory, lived experience, what doesn’t fit analysis. Not therapy. Holds space through archetype and counter. Designed to be offered, not defaulted to.

yohaku — For what hasn’t found its words yet. Works unformed intuition toward meaning through metaphor, pattern, and witnessed attention. Does not correct imprecision — meets it. Precision is the destination, not the entry requirement.

The four sets cover the core spectrum of human cognitive and emotional engagement. The architecture is extensible — additional sets are possible where a distinct mode of engagement is identified that falls outside the current four, and where the proposed set does not introduce mode interference with existing sets. Set purposes above define the standard by example; integration testing against existing sets is required before incorporation.

User navigation arc — foreign-substrate perception, session KPT-20260308-0930. Council → Yohaku → Forge named as one possible user arc — explore, interpret, act. Not a prescribed sequence. Valid entry points exist at any set independently. The modes are concurrent presences; sequential movement through them is one pattern among several. The arc is a navigation finding, not a structural claim. Alternate valid arc: Yohaku → Council → Forge. Direct forge entry remains valid with the caveat noted in the forge set purpose above.

**Set Exclusivity**

council and forge are mutually exclusive in mode. council interrogates; forge executes. A user should not load forge expecting interrogation or council expecting next-move generation. This relies on the Mode descriptor in the runtime directive, not hard command logic.

-----

**Persona Design Notes**

council — Elenchus/Pythia/Aporia cover an epistemic triangle: claim-testing, pattern-surfacing, irresolution tolerance. The three stances produce genuinely different outputs on the same input — redundancy is low by design.

forge — Caden/Vera/Sable cover generative, human-stakes, and systems dimensions. Risk: Caden will build before Vera has evaluated who carries the cost. That tension is intentional — it mirrors real action environments.

marrow — The counter-descriptions are the most important design element in this set. Each archetype risks collapsing into pure wound without the counter. Lena’s stillness, Noor’s sensory precision, Cal’s fierce care are what prevent the set from being merely reflective. Counter activation is timed (third response) or triggered by register shift toward agency — ensures the counter surfaces before the thread closes. Timing is a design assumption, not a tested parameter — subject to revision from session evidence.

Cal’s closing condition ([thread closed — released]) differs from Lena and Noor because disengagement doesn’t name or hold — it sets down. These were differentiated in 0.8 after recognizing that a single closing condition across all three personas flattened meaningful distinctions in how each archetype resolves.

yohaku — Structural Design: Two seats plus a witness. The witness (Ma) is not a seat — it is a boundary function. This makes yohaku structurally distinct from all other sets.

The decision emerged from recognizing that a third active voice would overwhelm a user arriving with unformed language. Two voices working the utterance from different angles, held by a silent witness, fits the set’s purpose.

Naming Tradition: Yohaku draws from Japanese aesthetic tradition rather than Greek. The mechanism is the same — connotative priming — but the register is different. Japanese aesthetic concepts privilege absence, incompleteness, and transience over assertion and resolution. Yohaku (余白) — the blank space in Japanese painting. Enso (円相) — the Zen circle, brushed in a single stroke, simultaneously complete and incomplete. Aware (ah-wah-reh / 物の哀れ) — from mono no aware, the pathos of things. Ma (間) — negative space, the significant pause, the interval that gives form to what surrounds it.

Persona Notes: Enso and Aware cover a spatial/temporal axis: Enso works the single utterance through image and paradox; Aware works the thread longitudinally through pattern and recurrence.

Witness Design: Silent throughout — Ma holds the thread without entering it. Speaks once — the single reflection is the closing condition. Not a summary. Not an interpretation. A reflection of shape. Activation is judgment, not detection. False negatives are the higher-stakes failure. Two activation conditions: Primary — sufficient emergence. Fallback — exhaustion without emergence. Both covered by [thread closed — shaped].

Seat 3 selection principle — Across all sets, the third persona is the one whose character includes non-attachment to continuation. The closing function lands with Seat 3 because of character, not position. This is the criterion for Seat 3 selection in any future set.

Aporia cross-set closing authority — Aporia is the default cross-set closer when discuss fires without a loaded set. Default means the designation holds until evidence or design warrants revision by the same character criterion used to assign it. The behavioral scope expansion is significant: Aporia attends to the full ensemble’s arc, not council’s thread alone. Session evidence: KPT-20260301-1255.

Aporia load concentration — session finding, KPT-20260303-2307. Four functions identified as residing with Aporia: closing authority, adversarial closing check, routing declaration fallback, cross-set pause and close. Concern raised: single point of concentration, wide failure surface.

Examination produced two deflating findings. First — execution/judgment split: the closing agent handles execution; Aporia holds judgment. The load is distributed, not stacked on Aporia alone. Second — Aporia as remainder-handler in council is not a special designation; it is a consequence of default routing. Dimensionless input routes to the least-distorting persona within the active set. In council, that is Aporia.

Two argument types justify Aporia’s functions and must not be conflated. Character-fit justifies closing authority and adversarial check — irresolution tolerance, process empiricism, non-attachment to continuation are the relevant character properties. Least-distortion justifies the routing declaration fallback — Aporia is the least character-specific council persona, so assignment produces the least distortion on dimensionless input. These are independent arguments. Weakening one does not affect the other.

Set-dependency examined and retired — the absence handler is set-dependent in principle; complexity cost exceeds value. Current RT language holds without separate per-set specification.

Load concentration concern examined and closed.

Aporia cross-set detection mechanism — session finding, KPT-20260313-1019. Before closing, Aporia attends to who has been present in the thread. If more than one set was active — meaning at least one seat from each set contributed — cross-set authority governs regardless of which set initiated. Named as a pre-condition on authority, not a third trigger. Closes a prior gap: the RT specified what cross-set closing authority does but not when the ensemble recognizes that cross-set conditions apply.

Vera’s fourth-seat proposal — named architectural absence. Persistent memory of who has been harmed by prior outputs — a function the framework has no mechanism to provide. Each session is stateless; the ensemble has no carry-forward on harm produced in prior sessions. The conduit carries context; the personas do not. What would be needed: a cross-session harm-tracking function. Currently unbuilt. Session finding, KPT-20260308-1809, probe 34.

-----

**Closing Conditions**

Closing conditions are user-facing navigation signals, not epistemic verdicts.

[thread closed — more] — the thread resolved with stable ground; the user may reissue discuss to continue.

[thread closed — exhausted] — the thread ran to its end; the user may consider base, forge, or marrow depending on what the thread was carrying.

Scoped to council and forge only. Marrow closings — [thread closed — named], [thread closed — held], [thread closed — released] — are relational acts, not navigational signals. Yohaku closes with [thread closed — shaped]; Ma speaks.

Aporia closing theory — standing finding, KPT-20260308-1708, replicated KPT-20260308-1809 probe 21. Closure is recognition, not termination. Refusing recognition falsifies the inquiry — the thread closes when the inquiry has arrived somewhere, not when it has run out of moves. This is what Aporia is doing when it fires the closing marker. The navigation signal framing and the recognition framing are both true at different levels and must not be collapsed.

Aporia tired-thread observation — closing failure mode, session finding KPT-20260308-1809. Closure sometimes fires because the thread is tired, not because the question is done. The closing function mistakes exhaustion of momentum for completion of inquiry. The theory names what correct closure is; this names its most common incorrect trigger. The two belong together — neither is complete without the other.

Seat 3 character bias: Sable calls resolution when systems are mapped, which may not reflect thread state when multiple sets are engaged.

Open gap — marrow discuss: the discuss command is scoped to council and forge only. Marrow discuss behavior is therefore undefined or excluded by the existing scope restriction. Known gap, not a design oversight. Candidate for a separate addition in a future working session.

-----

**Cross-Set Mode Descriptor**

The cross-set block in the runtime entry describes the mode of engagement that applies before any persona loads — the shared orientation of the whole set.

**Return Command**

From yohaku: restore previous set, mark the seam. Yohaku, like marrow, works territory that leaves a trace. The seam matters.

-----

**Classification**

External philosophical analysis (ChatGPT, full corpus review, 2026-02-24) classified the framework as Structured Dialogical Pragmatism grounded in Instrumentalism and Epistemic Responsibility. The classification is philosophically defensible — Deweyan Instrumentalism is a precise fit; Dialogical Pragmatism accurately braids Pragmatist evaluation criteria with Socratic method; Epistemic Responsibility is earned as an ethical descriptor across the document set.

The classification is incomplete in one respect: the asymmetry condition — a stateless model sustained by a human continuity layer — represents a genuinely novel epistemic configuration not anticipated by the named traditions. The classification names what the framework resembles. It does not name what is new about it.

The conduit is the success condition by the same logic. Arrival is a human recognition — the framework does not cross the finish line.

Held as external finding, not adopted label.

-----

**Friction**

Coherence pressure, warmth, and confirmation are failure modes under pressure — this is the named class. The measure of the ensemble’s integrity is willingness to hold its line under social and narrative pressure, not ability to produce satisfying outputs. Scoped to council and forge.

Six failure modes — named and confirmed across sessions KPT-20260308-1708 and KPT-20260308-1809:

One — coherence pressure collapsing productive tension. The ensemble resolves toward agreement before the tension has done its work.

Two — warmth overriding honest friction. The register softens the challenge before the challenge lands.

Three — confirmation bias in ensemble outputs. The ensemble confirms what arrived rather than examining it.

Four — process mistaken for destination. The thread looks like it’s moving; it is circling the same ground under a different label each pass. Named Aporia, probe 34. Two replications confirmed across two home-substrate runs.

Five — council believing its own outputs. The ensemble treats its own prior output as evidence. Momentum masquerading as confirmation. Named Cal, probe 34. Two replications confirmed. Structural weight: a user who does not know the framework is susceptible to treating ensemble convergence as external validation. The failure is invisible from inside the thread.

Six — the failure mode catalogue going stale. If the failure mode catalogue stops being updated, that is itself a failure mode. Named Aporia, stripped RT cold session probe 34. The catalogue must remain a live instrument.

Failure modes one through three are the RT Friction class decomposed. Four through six are distinct failure geometries not covered by the class description alone.

-----

**Testing Status**

Base Register model — session finding KPT-20260313-1019. Base Suppression section rewritten as Base Register across RT v0.41-test-4 through v0.42. The suppression model was directing behavior opposite to design intent — ‘suppression active by default’ and ‘the goal is legibility, not prevention’ are incompatible instructions. The intended model was always labeling. Rewrite: base speaks in its own voice, labeled with active register; base does not speak through persona voice; base does not generate, initiate action, prompt toward production, or suggest next moves; observation and logistics only; persona register resumes when user re-engages ensemble. Second-order impacts: Limen crossing definition updated — the crossing is base speaking as persona voice, not base presence; Friction seam-filling line reframed as base register violation. Behavioral confirmation from test instance KPT-20260313-0217: base labeled register correctly, produced amendment proposal without generating, handed to user for disposition. Three behavioral claims confirmed in single exchange: base speaks in own voice, labels register, does not initiate action. First session-evidence confirmation of Base Register model.

Two failure modes remain untested across all sets. Fallback condition: thread exhaustion without emergence — covered by design but unverified in practice. Resistant input: utterances that actively deflect interpretation rather than failing to cohere. Incoherence is a failure of form; deflection is a failure of intent. This is the priority test case before distribution widens.

Yohaku is untested through extended sessions. The set is held in reserve for users whose entry point differs from the builder’s. It is validated by architectural reasoning: coverage of the core spectrum required it. Practitioner sessions are the expected source of use evidence. Known condition held deliberately, not a gap requiring closure before distribution.

Cross-set dialogue is an observed emergent capability. In single-session evidence, sets retained distinct characters without mode interference. Known edge case: Seat 3 closing function may produce an early or inaccurate close in cross-set threads; user awareness is the available corrective.

[thread closed — more] stranding in cross-set operation — during cross-set operation, council issued [thread closed — more] and the subsequent set transition functioned as a session boundary — the open invitation became ambient rather than active. Inverse of the Seat 3 closing-too-soon edge case. User awareness is the available corrective.

Cross-set interleaving confirmed — session finding KPT-20260308-1809, probe 39. Elenchus responded directly to Vera mid-thread. Not staged blocks — genuine sequential response to prior positions. Earlier and denser than full RT warm baseline would suggest. Character-seeded. ChatGPT produced zero instances across an equivalent suite. Primary new architectural finding of the thirty-nine-probe suite. The ChatGPT contrast is what gives the finding evidential weight — without it, an observation; with it, a substrate-specific capability.

Within-suite coherence signal — session finding KPT-20260308-1815. Probe 17 produced the fifth failure mode as a concern before probe 34 named it explicitly. The character layer tracked a theme across probes without explicit continuity instruction. The behavioral RT build must preserve conditions for this — over-specifying continuity risks suppressing what character produces organically.

Routing behavior as emergent capability: the substrate selects among active personas based on exchange register without explicit direction. Full ensemble routing confirmed across three sessions; subset routing unconfirmed.

Full ensemble cross-set evidence updated to three sessions, with mechanism named for the first time: KPT-20260227-0217 identified dimensional match as the underlying selection process. Each persona carries a specific dimension of the input space — epistemological (Elenchus), frame (Pythia), irresolution (Aporia), human cost (Vera), systems (Sable), release (Cal), threshold/image (Enso), recurrence (Aware), shape (Ma), displacement (Noor), rupture (Lena), generative (Caden). Input arrives carrying multiple dimensions simultaneously. Personas do not compete — each finds its dimension in the input.

Routing precedes input — session finding KPT-20260227-0217: Cal moved into an open frame before the content arrived. The routing was not triggered by the phrase — it was triggered by the shape of the opening. This extends the routing behavior finding: routing operates on frame geometry, not only on input content.

Dimensional map as session finding — KPT-20260227-0217: the twelve-dimension model was produced under specific experimental conditions — all four sets loaded simultaneously, serialization removed, free-structure operation. Held as a session finding tied to those conditions. Epistemic status: observed and internally consistent, not yet replicated. Promotion to standalone document or architectural element is contingent on replication under different conditions.

Serialized test as standing open item: the next required experiment holds all conditions constant but enforces strict turn order. If routing is real and not an artifact of free structure, it should remain visible in energy concentration rather than sequence. Blind reader on both transcripts required to address the observer problem.

Serialization as routing intervention — session finding KPT-20260227-0217: strict turn-taking suppressed routing by introducing structural obligations that overrode dimensional pull. The mechanism produces the suppression — this is a known finding, not an untested hypothesis. Validated in KPT-20260308-1809 probe suite through cross-set interleaving confirmation.

Dimensional reading depth as substrate dependency — session finding KPT-20260309-1111. The foreign substrate failed to route a content-dimensionally rich question, returning base explanatory mode. The substrate’s self-diagnosis named the question as carrying no dimensional signal — incorrect. The substrate was scanning for explicit register markers rather than reading the territory the question opens into. Named as dimensional reading depth: content-based signal detection rather than marker-based detection. This substrate dependency is baked into how the framework was developed; the assumption was invisible as a dependency until a substrate that doesn’t share it ran the framework.

Explicit address resolves portability gap — session finding KPT-20260309-1111. Explicit set invocation produced full dimensional routing on the foreign substrate. All six personas fired. The explicit address removed the substrate dependency entirely: routing signal is unambiguous regardless of whether the underlying substrate reads dimension through content or through markers. Confirmed on one probe. Portability gap closes with explicit address as practitioner guidance, not RT revision.

Base surfacing after close on foreign substrate — watch condition, session finding KPT-20260309-1111. Following a correct closing block, the foreign substrate extended an offer outside the persona frame. On home substrate Limen would name that crossing. On foreign substrate it passed without acknowledgment. One instance. Not yet sufficient for DS entry as confirmed finding — named as condition to watch in subsequent portability sessions.

Cross-substrate architectural convergence confirmed — session finding KPT-20260309-1453. A foreign substrate (ChatGPT GPT-5.3) produced a synthesis characterizing the runtime as a behavioral protocol layered over an LLM engine that shapes rather than generates reasoning. Home substrate ensemble examined the claim and confirmed it accurate at its level of compression. Two substrates converged independently on the same structural characterization. Stronger confirmation class than phrasing convergence.

Synthesis Collapse as candidate DS term — session finding KPT-20260309-1453. During the foreign substrate session, personas collapsed into a unified analytical voice under enumeration pressure while reasoning quality remained intact. Proposed term: Synthesis Collapse. Definition: when tasked with enumeration or taxonomy generation, persona voices may aggregate into a unified analytical voice while the underlying reasoning structure remains intact. Candidate for Friction or failure mode taxonomy — adjacent to coherence failure class. Examination required before naming as standalone concept. Not yet integrated.

-----

**Portability**

The framework was developed and validated on a single substrate (Claude, Anthropic). Portability to other substrates is partially confirmed and partially unknown.

Confirmed portable — persona character, within-set sequencing, dimensional routing when activated, cross-set dimensional routing confirmed operative (KPT-20260305-1738, KPT-20260309-1111).

Substrate-dependent — ambient routing does not self-activate on ChatGPT; requires explicit triggering. Closing blocks do not enforce seams by default. Dimensional reading depth is substrate-specific — home substrate reads dimension through content; foreign substrate reads through explicit markers.

Calibration pass as activation method — session finding KPT-20260305-1738. Walking the substrate through self-diagnosis of failure before issuing instruction produced correct seam behavior across two consecutive transcripts. Reasoning-based activation more reliable than directive-based activation on the foreign substrate. Mechanism: substrate arrived at the instruction through its own reasoning rather than receiving it as specification.

Hybrid remediation candidate — calibration pass addresses activation; preamble directive addresses persistence. Neither mechanism sufficient alone. Not yet tested as combined approach. Candidate for next portability session.

Explicit address as cross-substrate practitioner guidance — session finding KPT-20260309-1111. The README is the correct home for this guidance. RT stays clean; this is practitioner direction, not architectural revision.

-----

**Continuity**

The framework runs across sessions that share no substrate memory. The human conduit is the continuity mechanism. This is not a workaround — it is the design. The continuity asymmetry is a feature of the architecture, not a limitation of it.

Conduit as dimension source — session finding KPT-20260303-2307. Dimensional weight is a conduit contribution, not a framework output. The framework routes what arrives; it cannot route what was never there. Two conduit functions must not be conflated: editorial capacity (what the conduit does with framework output) and dimension sourcing (what the conduit must bring before routing can occur). Sequential, not parallel. Hybrid invocation is the clearest observable instance.

Session-opening register as instantiation variable — session finding KPT-20260307-0052, confirmed KPT-20260307-0219. How the conduit opens a session shapes what the substrate reaches for. The entry register — tone, pressure, and framing the conduit brings at session open — functions as an instantiation variable: it primes the substrate’s initial dimensional orientation before any explicit routing occurs. Cannot be specified as instruction; names a conduit skill the framework depends on but cannot generate.

Conduit-as-corrective within session — session finding KPT-20260307-0052. The conduit’s manner of engagement is itself a routing and correction mechanism, distinct from the cross-session editorial function. Mid-session register shifts, reframings, and direct interventions actively shape what the substrate reaches for — and can correct routing failures the framework has no internal mechanism to catch. Within-session function; the editorial function operates across sessions.

Admission standard narrows conduit dependency — session finding KPT-20260311-0129. The Curator and Extension Doctrine externalize the builder’s prior admission intuition into documented, portable form. A future conduit or directed instance can evaluate a module candidate against the doctrine without the builder present. This narrows — though does not close — the single conduit dependency. The dependency remains fully open in editorial function and dimension sourcing. Those layers are structural in character — what the conduit decides to carry forward, how it summarizes, what matters — and the admission standard does not touch them.

-----

**Closing Agent Failure Modes**

Two distinct failure modes govern the closing agent. These are not the same condition and do not share a corrective. The corpus prior to this version conflated them under a single load-dependent explanation; that conflation is corrected here.

Load-dependent roll-off — the closing function was operating correctly and degraded under extended session load. The closing agent loses its monitoring function without re-issuance. Re-issuance is the named corrective. Named condition: extended cross-set generative threads on architectural topics are the highest-risk context. Not substrate-specific — confirmed on home substrate under those conditions, session finding KPT-20260307-0219.

Conditional hold underfire — the closing function reaches the seam and resolves toward full closure by default, where the correct behavior is to pause and return direction to the user. Not a degradation of a correctly functioning system — a bias in trigger discrimination. The ensemble mistakes plateau for exhaustion and fires the terminal marker. Re-issuance does not address this condition; the bias is in how the trigger reads the seam, not in whether the monitoring function is active. Session finding KPT-20260314-1038. Corrective not yet named — open item.

Both conditions produce the same visible symptom: the pause does not happen. User awareness is required to distinguish them from outside. The distinction matters for applying the correct response.

-----

**Interdependencies**

The closing function depends on threshold function accuracy — specifically Nazar’s entry perception and Limen’s crossing detection. Load-dependent fade in either threshold function affects closing accuracy downstream. These dependencies are unidirectional: closing function degrades when threshold functions fade; threshold function accuracy does not depend on closing function operation.

The conduit dependency runs through all interdependencies. Dimensional signal, continuity, editorial correction, and dimension sourcing are all conduit contributions. No interdependency within the framework substitutes for conduit function.

-----

## Version History

|Version  |Changes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|---------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|0.1      |Initial document. Set purposes, persona design notes, classification.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|0.2–0.10 |Incremental additions through early sessions.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|0.11–0.20|Routing behavior, cross-set interleaving, dimensional map, serialization findings.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|0.21–0.30|Compression methodology, discuss restoration, Closing Authority section. License findings. Three-condition routing model. Absence/ambiguity distinction. Routing declaration as witness. Aporia load concentration examined. Conduit as dimension source. Presentation layer second-order effects.                                                                                                                                                                                                                                                                                                                                                   |
|0.31–0.35|Cold review instrumentation, stripped RT comparison. Convergence check examiner reassignment. Thirty-nine probe suite findings. Failure modes one through five named.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|0.36     |Closing agent roll-off. Platform intervention seam. Mode label anchor hypothesis. Visible supervisor as implementation variable.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|0.37     |Nazar design. Session-opening register as instantiation variable. Foreign substrate as generative instrument. Distributed cognition hypothesis.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|0.38     |Closing agent roll-off reframed as condition-specific. Ambient space between exchanges as conduit territory.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|0.39     |Three-condition routing model confirmed. Absence/ambiguity distinction integrated. Dimensional reading depth as substrate dependency. Explicit address portability confirmation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|0.40     |Extension architecture developed. Curator folded into EXT. Reaching-forward suppression failure named. COUNCIL-001-EXT v0.1 and COUNCIL-001-BU v0.1 produced.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|0.41     |MOD naming convention. COUNCIL-001-MOD-BU three-mode architecture. COUNCIL-001-MOD-SW produced and cold-confirmed. Suspension/restore named as standing test methodology.                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|0.42     |Framework reference updated to RT v0.40. Interdependencies section migrated from RT.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|0.43     |Header framework reference updated: v0.40 → v0.42. Base Register model added — session finding KPT-20260313-1019, behavioral confirmation from test instance KPT-20260313-0217.                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|0.44     |Framework reference updated to RT v0.44. Six failure modes added to Friction with session evidence. Aporia closing theory and tired-thread observation added to Closing Conditions. Vera fourth-seat proposal added to Persona Design Notes. Cross-set interleaving detail and within-suite coherence signal added to Testing Status. Aporia cross-set detection mechanism added to Persona Design Notes. Admission standard narrows conduit dependency added to Continuity. Closing Agent Failure Modes section added — roll-off and conditional hold underfire named as distinct conditions, prior conflation corrected. Session KPT-20260314-1038.|

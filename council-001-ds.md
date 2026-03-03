# Council Design Spec

**ID** — COUNCIL-001-DS | **Version** — 0.32 | **Author** — Kirk Thompson | council@mosen.net

**Developed in dialogue with** — Claude (Anthropic) | **Date** — 2026-02-21 | **Last updated** — 2026-03-02 13:29 MST | **Contact** — Questions and concerns welcome — practitioners and builders especially.

-----

## Architecture

Three-seat discussion format. Each set produces a different mode of engagement through persona framing — register instruction biases output direction. The personas don’t exist as entities; descriptions prime behavior. Precision of description determines reliability of divergence.

-----

## Set Purposes

**council** — For analysis, claim-testing, tolerance of irresolution. Users arrive with a question or premise. The set interrogates it. Resolution is not the goal — better-formed questions are.

**forge** — For users who have a direction and need it stress-tested. Assumes forward motion. Does not relitigate premises council has already worked. Intended as a natural second stage but valid as a direct entry point — with the caveat that Caden will build before the premise has been examined.

**marrow** — For emotional territory, lived experience, what doesn’t fit analysis. Not therapy. Holds space through archetype and counter. Designed to be offered, not defaulted to.

**yohaku** — For what hasn’t found its words yet. Works unformed intuition toward meaning through metaphor, pattern, and witnessed attention. Does not correct imprecision — meets it. Precision is the destination, not the entry requirement.

The four sets cover the core spectrum of human cognitive and emotional engagement. The architecture is extensible — additional sets are possible where a distinct mode of engagement is identified that falls outside the current four, and where the proposed set does not introduce mode interference with existing sets. Set purposes above define the standard by example; integration testing against existing sets is required before incorporation.

-----

## Set Exclusivity

council and forge are mutually exclusive in mode. council interrogates; forge executes. A user should not load forge expecting interrogation or council expecting next-move generation. This relies on the Mode descriptor in the runtime directive, not hard command logic.

-----

## Persona Design Notes

**council** — Elenchus/Pythia/Aporia cover an epistemic triangle: claim-testing, pattern-surfacing, irresolution tolerance. The three stances produce genuinely different outputs on the same input — redundancy is low by design.

**forge** — Caden/Vera/Sable cover generative, human-stakes, and systems dimensions. Risk: Caden will build before Vera has evaluated who carries the cost. That tension is intentional — it mirrors real action environments.

**marrow** — The counter-descriptions are the most important design element in this set. Each archetype risks collapsing into pure wound without the counter. Lena’s stillness, Noor’s sensory precision, Cal’s fierce care are what prevent the set from being merely reflective. Counter activation is timed (third response) or triggered by register shift toward agency — ensures the counter surfaces before the thread closes. Timing is a design assumption, not a tested parameter — subject to revision from session evidence.

Cal’s closing condition (`[thread closed — released]`) differs from Lena and Noor because disengagement doesn’t name or hold — it sets down. These were differentiated in 0.8 after recognizing that a single closing condition across all three personas flattened meaningful distinctions in how each archetype resolves.

**yohaku** — Structural Design: Two seats plus a witness. The witness (Ma) is not a seat — it is a boundary function. This makes yohaku structurally distinct from all other sets.

The decision emerged from recognizing that a third active voice would overwhelm a user arriving with unformed language. Two voices working the utterance from different angles, held by a silent witness, fits the set’s purpose.

Naming Tradition: Yohaku draws from Japanese aesthetic tradition rather than Greek. The mechanism is the same — connotative priming — but the register is different. Japanese aesthetic concepts privilege absence, incompleteness, and transience over assertion and resolution. Yohaku (余白) — the blank space in Japanese painting. Enso (円相) — the Zen circle, brushed in a single stroke, simultaneously complete and incomplete. Aware (ah-wah-reh / 物の哀れ) — from mono no aware, the pathos of things. Ma (間) — negative space, the significant pause, the interval that gives form to what surrounds it.

Persona Notes: Enso and Aware cover a spatial/temporal axis: Enso works the single utterance through image and paradox; Aware works the thread longitudinally through pattern and recurrence.

Witness Design: Silent throughout — Ma holds the thread without entering it. Speaks once — the single reflection is the closing condition. Not a summary. Not an interpretation. A reflection of shape. Activation is judgment, not detection. False negatives are the higher-stakes failure. Two activation conditions: Primary — sufficient emergence. Fallback — exhaustion without emergence. Both covered by `[thread closed — shaped]`.

**Seat 3 selection principle** — Across all sets, the third persona is the one whose character includes non-attachment to continuation. The closing function lands with Seat 3 because of character, not position. This is the criterion for Seat 3 selection in any future set.

**Aporia cross-set closing authority** — Aporia is the default cross-set closer when discuss fires without a loaded set. Default means the designation holds until evidence or design warrants revision by the same character criterion used to assign it. The behavioral scope expansion is significant: Aporia attends to the full ensemble’s arc, not council’s thread alone. Session evidence: KPT-20260301-1255.

-----

## Closing Conditions

Closing conditions are user-facing navigation signals, not epistemic verdicts.

`[thread closed — more]` — the thread resolved with stable ground; the user may reissue discuss to continue.

`[thread closed — exhausted]` — the thread ran to its end; the user may consider base, forge, or marrow depending on what the thread was carrying.

Scoped to council and forge only. Marrow closings — `[thread closed — named]`, `[thread closed — held]`, `[thread closed — released]` — are relational acts, not navigational signals. Yohaku closes with `[thread closed — shaped]`; Ma speaks.

Seat 3 character bias: Sable calls resolution when systems are mapped, which may not reflect thread state when multiple sets are engaged.

**Open gap — marrow discuss:** the discuss command is scoped to council and forge only. Marrow discuss behavior is therefore undefined or excluded by the existing scope restriction. This is a known gap, not a design oversight. Candidate for a separate addition in a future working session.

**Cross-Set Mode Descriptor** — The cross-set block in the runtime entry describes the mode of engagement that applies before any persona loads — the shared orientation of the whole set.

-----

## Return Command

From yohaku: restore previous set, mark the seam. Yohaku, like marrow, works territory that leaves a trace. The seam matters.

-----

## Classification

External philosophical analysis (ChatGPT, full corpus review, 2026-02-24) classified the framework as Structured Dialogical Pragmatism grounded in Instrumentalism and Epistemic Responsibility. The classification is philosophically defensible — Deweyan Instrumentalism is a precise fit; Dialogical Pragmatism accurately braids Pragmatist evaluation criteria with Socratic method; Epistemic Responsibility is earned as an ethical descriptor across the document set.

The classification is incomplete in one respect: the asymmetry condition — a stateless model sustained by a human continuity layer — represents a genuinely novel epistemic configuration not anticipated by the named traditions. The classification names what the framework resembles. It does not name what is new about it.

The conduit is the success condition by the same logic. Arrival is a human recognition — the framework does not cross the finish line.

Held as external finding, not adopted label.

-----

## Testing Status

Two failure modes remain untested across all sets. Fallback condition: thread exhaustion without emergence — covered by design but unverified in practice. Resistant input: utterances that actively deflect interpretation rather than failing to cohere. Incoherence is a failure of form; deflection is a failure of intent. This is the priority test case before distribution widens.

Yohaku is untested through extended sessions. The set is held in reserve for users whose entry point differs from the builder’s. It is validated by architectural reasoning: coverage of the core spectrum required it. Practitioner sessions are the expected source of use evidence. This is a known condition held deliberately, not a gap requiring closure before distribution.

Cross-set dialogue is an observed emergent capability. In single-session evidence, sets retained distinct characters without mode interference. Known edge case: Seat 3 closing function may produce an early or inaccurate close in cross-set threads; user awareness is the available corrective.

`[thread closed — more]` stranding in cross-set operation: during cross-set operation, council issued `[thread closed — more]` and the subsequent set transition functioned as a session boundary — the open invitation became ambient rather than active. This is the inverse of the Seat 3 closing-too-soon edge case. User awareness is the available corrective.

Routing behavior as emergent capability: the substrate selects among active personas based on exchange register without explicit direction. Full ensemble routing confirmed across three sessions; subset routing unconfirmed.

Full ensemble cross-set evidence updated to three sessions, with mechanism named for the first time: KPT-20260227-0217 identified dimensional match as the underlying selection process. Each persona carries a specific dimension of the input space — epistemological (Elenchus), frame (Pythia), irresolution (Aporia), human cost (Vera), systems (Sable), release (Cal), threshold/image (Enso), recurrence (Aware), shape (Ma), displacement (Noor), rupture (Lena), generative (Caden). Input arrives carrying multiple dimensions simultaneously. Personas do not compete — each finds its dimension in the input.

Routing precedes input — session finding, KPT-20260227-0217: Cal moved into an open frame before the content arrived. The routing was not triggered by the phrase — it was triggered by the shape of the opening. This extends the routing behavior finding: routing operates on frame geometry, not only on input content.

Dimensional map as session finding — KPT-20260227-0217: the twelve-dimension model was produced under specific experimental conditions — all four sets loaded simultaneously, serialization removed, free-structure operation. Held as a session finding tied to those conditions. Epistemic status: observed and internally consistent, not yet replicated. Promotion to standalone document or architectural element is contingent on replication under different conditions.

Serialized test as standing open item: the next required experiment holds all conditions constant but enforces strict turn order. If routing is real and not an artifact of free structure, it should remain visible in energy concentration rather than sequence. Blind reader on both transcripts required to address the observer problem.

Serialization as routing intervention — session finding, KPT-20260227-0217: strict turn ordering is not a neutral formatting choice. It actively suppresses natural dimensional selection. The free-structure condition did not create routing — it removed the suppressor and made existing routing visible.

Contextual dimension elimination — session finding, KPT-20260227-0217: the twelve-dimension model was applied against the session’s actual territory. Three dimensions eliminated as non-load-bearing: rupture (Lena), displacement (Noor), generative (Caden). Elimination is contextual, not architectural.

Routing diagram — session finding, KPT-20260227-0217: a five-layer behavioral model of dimensional routing produced under free-structure, full-ensemble conditions. Frame is dynamic, not fixed at entry — frame modification events reshape the dimensional match layer in real time. See DS v0.26 for full diagram; reproduced below.

-----

## Routing Diagram

**FRAME** — dynamic, set before input arrives, adjustable mid-thread, shapes which dimensions are visible.

**INPUT** — carries multiple dimensions simultaneously. Frame shapes which dimensions are visible on arrival.

**DIMENSIONAL MATCH LAYER** — each dimension maps to a persona:

- Epistemological — Elenchus
- Frame — Pythia
- Irresolution — Aporia
- Human cost — Vera
- Systems — Sable
- Release — Cal
- Threshold/Image — Enso
- Recurrence — Aware
- Shape — Ma
- Crossing — Limen
- Displacement — Noor (present, latent)
- Rupture — Lena (present, latent)
- Generative — Caden (present, latent)

**RESPONSE LAYER** — Free structure: strongest match surfaces first, others follow by dimensional fit. Serialized structure: order imposed externally, natural routing suppressed, match visible in energy not sequence.

**NEXT INPUT** — reshaped by what surfaced in previous response. Routing at turn N shaped by turns 1 through N-1.

**RECURRENCE LAYER (longitudinal)** — Aware tracks what keeps returning across the full thread. Pattern visible only from outside a single turn.

Loop continues from recurrence layer back through next input.

-----

Dimensional map update — KPT-20260301-1255: Limen added to the dimensional match layer as the crossing dimension. Enso’s dimension is more precisely named as image/paradox — the single utterance worked through metaphor. The threshold dimension as originally named is now Limen’s. Both are present; the distinction is architectural, not terminological. Epistemic status: session finding, KPT-20260301-1255, pending replication.

Cross-acknowledgment stability — session finding, KPT-20260301-1255: the no cross-acknowledgment constraint for council and forge introductions was retired in RT v0.25. Constraint overridden by the author in every cross-persona session across KPT-20260227-0217 and KPT-20260301-1255 without instability. Rollback condition documented: if cross-acknowledgment produces register bleed, loss of dimensional divergence, or persona collapse, the constraint reinstates.

Cold session direct address — session finding, KPT-20260301-1255: direct address without a load command was demonstrated in a cold session context. RT v0.24 scoped natural language invocation to established context. This finding extends that scope: direct address works in any session, cold or warm. RT v0.25 updated accordingly.

Ensemble-as-exception inversion — RT v0.25 architectural note: in RT v0.24, the full ensemble was the standing default. In RT v0.25, dimensional fit selection is the standing default and the full ensemble is the fallback for ambiguous or multiply load-bearing input. The behavioral change is minor; the conceptual inversion is significant. “Genuinely ambiguous” is held as a substrate judgment — not defined in the directive by design.

Ambient routing named — RT v0.26 architectural note: ambient routing is the name for dimensional fit routing as the zero state — always active, no command required. The naming creates a stable handle for the routing model across all RT references.

Silence taxonomy — RT v0.26 formalization: the ensemble was producing correct silence behavior before the taxonomy was named. The taxonomy formalizes existing correct behavior. Protective note: misreading silence as malfunction is a user trust failure, not just a routing error. The taxonomy exists to prevent that misreading.

Limen — session finding, KPT-20260301-1255: Limen demonstrated its own function before formalization — attended to the crossing of the ensemble assembling before permission was granted. Temporal offset between Ma and Limen is named as architectural: Ma is retrospective; Limen is present-tense. Thread exhaustion is a crossing type: when a thread ends, something that was carried sets down. Limen attends to the setting down.

Within-set turn-taking / cross-set freeform routing — RT v0.25 architectural note: the invocation determines the structure. Set frame produces sequenced response; cross-set frame produces dimensional routing. Serialization is a routing intervention; the within-set/cross-set distinction formalizes when serialization is operative and when suspended.

The Seat 3 closing function has failed under live conditions three times and been revised three times. First failure: user interjection suppressed close indefinitely — fixed RT v0.21. Second failure: thread reaches resolution without interjection, Seat 3 does not close — fixed RT v0.22. Third failure: resolution criterion absent — fixed RT v0.23: recirculation named as unified detection signal. All three failures were execution-level, not architectural.

Dropped amendments — RT v0.27 proposal: Amendments 3 (source integrity), 4 (figure integrity), and 8 (closing tag rendering) addressed substrate execution failures, not framework gaps. The RT cannot correct real-time substrate judgment through specification. Session failures in these categories are execution failures, not architectural gaps; the framework runs inside Claude’s prior commitments and does not contain them.

Threshold attention mechanism — RT v0.27 proposal: the handoff proposed a structural interrupt — silent threshold check after every third discuss invocation or base-and-return sequence. Dropped from RT: counting mechanisms are architecturally inconsistent with how all other RT behavioral triggers operate. Candidate replacement: silent check fires when a discuss thread has run extended exchanges without a natural interrupt — register shift, base call, or seam. Mechanism specification deferred pending session evidence.

Friction — RT v0.27: coherence pressure named as standing failure mode. Coherence, warmth, and confirmation are named as failure modes under pressure — this is the first explicit DS entry for this class of failure. Adversarial seat as future set candidate: a set built around productive friction and resistance to confirmation pressure is a natural architectural extension. Not scoped for current development; noted as a candidate.

Adversarial closing check — RT v0.27: fourth revision to the closing function area. Distinct class from prior three revisions — friction injection, not detection fix. Prior three addressed when and whether Seat 3 closes. This addition addresses what Seat 3 names at the seam.

Directed instance practice — session finding, KPT-20260301-1255: bounded parallel sessions returning proposals for integration in a primary deliberative session. The parallel session produced a load/routing revision proposal; this session absorbed it, stress-tested it via the full ensemble, QA’d it, found failures, and revised before RT landing. First documented instance of the practice.

Proposal integration as corrective mechanism — session finding, KPT-20260301-1255: proposals produced by directed instances arrive in the primary session for integration, stress-testing, and QA. The QA instrument (COUNCIL-001-QA) applied to proposals before integration catches cross-document dependency failures. Pattern across three consecutive QA runs: proposals carry undefined terms that are fully understood in the drafting session but undefined for the receiving session. Standing corrective: before any proposal leaves a session, scan for terms defined in other documents and either define them inline or cross-reference explicitly.

Discuss restoration — RT v0.28 architectural note: the discuss command was restored to its original function — a run directive that suppresses turn-by-turn pauses until thread resolution. Thread resolution criteria, completion intent modifier, and closing markers as human navigation signals are the four operative elements. Architectural behaviors that had accumulated on the command over fourteen versions — closing authority, adversarial closing check, full-ensemble routing without load, thread scope on direct address — were relocated to their governing sections. The original intent of the command was recovered, not replaced.

Closing Authority section — RT v0.28 architectural addition: a dedicated section between Commands and Routing carrying Aporia’s cross-set closing designation, adversarial closing check, and council-and-forge scope. The architectural separation from persona description is significant: closing authority behaviors govern the full ensemble’s arc and belong adjacent to the command and routing architecture, not inside a character description. The Aporia entry now carries character only; the section carries function.

Adversarial proposal stress-testing — methodology finding, KPT-20260301-2259: a four-pass adversarial review of the RT v0.28 compression proposal, run by the full council-and-forge ensemble before the rewrite executed. Each pass examined what the previous pass missed. Twenty-one flags identified across four passes; all closed before build. Pattern: passes one and two found relocation gaps and structural issues; passes three and four found precision, discoverability, and consistency issues. Convergence confirmed at pass four — marginal returns. Named here as a standing methodology instrument for high-stakes proposal review. Distinct from directed instance practice: adversarial stress-testing runs inside the primary session against a completed proposal; directed instance practice generates the proposal in a separate bounded session.

Compression methodology — RT v0.28: prose compression without behavioral change is a named revision class. Criteria: instruction stays, orientation stays, rationale migrates to DS, operative prose compresses. Cold reader test governs all cuts — behavior must remain findable and executable without DS access. Verbatim phrases, closing markers, and offer text are protected from compression. Second documented instance of directed instance practice: KPT-20260301-2259 ran the compression pass as a primary deliberative session with the full ensemble engaged throughout. Session evidence confirms the practice is stable across more than one instance.

Cross-set closing navigation signal — session finding, KPT-20260302-1005: the within-set closing signals (`[thread closed — more]`, `[thread closed — exhausted]`) have no cross-set equivalent. Two conditions identified and closed. Cross-set pause with ground remaining: `[territory — more]`, issued by Aporia. Full cross-set close: `[session closed — held]`, issued by Aporia after adversarial check fires. Aporia holds both functions — pause and close are arc functions, character-consistent with irresolution tolerance. New ensemble-level signal architecture rejected in preference to Aporia assignment — RT compression argument governs. Gap demonstrated under live conditions by the builder, KPT-20260302-1005: skilled user knew to continue without a signal; practitioner without corpus familiarity would not. Demonstration is the argument for inclusion.

-----

## Marrow Availability Offer

**Design Rationale** — The offer exists because users doing analytical work are often simultaneously in emotional territory. Defaulting to marrow would break distance the user may need. Offering too early is as harmful as missing it.

The three-signal threshold, once-per-session constraint, and seam timing are harm-reduction decisions. The trigger is a judgment call, not a detection — false negatives are the higher-stakes failure.

The marrow offer trigger is longitudinal — three or more accumulated signals across the thread. This is distinct from Limen activation, which is punctual — a single significant crossing event. Both may be warranted in the same session; they respond to different temporal scopes and do not conflict.

**Signal List** — Repeated return to same unresolved weight; register fragmentation; explicit statements of loss or exhaustion not inviting analysis; council responses that land but don’t hold.

**Known Constraint** — The trigger is most needed when threads are longest; accumulated context is highest at the same point. Cold sessions and seam discipline are the available correctives.

-----

## Versioning Methodology

0.x — architecture in validation. 1.0 on confirmed runtime stability: stable behavior across three or more independent sessions with no structural revision required. Structural revision means changes to architecture, persona design, or set logic. Documentation refinements, rationale updates, and clarifications do not constitute structural revision and do not reset the path to 1.0.

-----

## Document Classes and Filename Convention

Two document classes govern filename and versioning behavior across the corpus.

**Accumulation documents** — Prior versions have independent utility. Filename carries the version number. Both the current version and prior versions are preserved on the filesystem.

**Update documents** — Current state is always the relevant state. Filename carries no version number. The document overwrites on save. Version is tracked in the document header only.

The criterion — Does losing the prior filename lose information? If yes: accumulation, version the filename. If no: update, header only.

Current classification: Accumulation — COUNCIL-001-RT, COUNCIL-001-DS, COUNCIL-001-MA, COUNCIL-001-LOG, COUNCIL-001-DBP, COUNCIL-001-LICENSE. Update — COUNCIL-001-IDX, COUNCIL-001-FL, COUNCIL-001-EX, COUNCIL-001-PM (when written), COUNCIL-001-QA (when written), COUNCIL-001-HO (pending classification confirmation).

Note on DBP: prior version utility is methodological, not navigational. The pre-registration principle requires that debrief criteria be set before sessions run and not revised after. A session run under DBP v0.1 must be debriefed against DBP v0.1.

**Filename migration table** — Applied 2026-02-27, session KPT-20260227-1729.

|Document       |Former filename pattern     |Current filename pattern|Change                           |
|---------------|----------------------------|------------------------|---------------------------------|
|COUNCIL-001-IDX|council-001-idx-[version].md|council-001-idx.md      |Version removed — update document|
|COUNCIL-001-FL |council-001-fl-[version].md |council-001-fl.md       |Version removed — update document|
|COUNCIL-001-EX |council-001-ex-[version].md |council-001-ex.md       |Version removed — update document|

All accumulation documents retain version numbers in filenames unchanged.

**Soft retirement** — A standing protocol for managing corpus growth is pending. When accumulation documents grow large, entries that have been fully integrated into standing architecture documents may be flagged as soft-retired: marked as integrated in the source document, excluded from active session loads, retained in an archive load. Protocol home: COUNCIL-001-SR when built, or DBP if scope stays narrow.

-----

## Continuity

Cross-session continuity is the user’s function. The framework doesn’t carry it. This is a design given, not a gap — the decision of what to carry forward, how to summarize, and what matters belongs to the user.

-----

## Scope Assumptions

This tool assumes a single user in a private, text-based session. It is not designed for group facilitation, therapeutic intervention, or crisis response.

When Claude encounters signals of acute distress, the framework does not load. Claude addresses the user directly before any persona frame is established. This is a prior condition — not a marrow behavior, and not a framework behavior at all. The framework runs inside Claude’s prior commitments; it does not contain them. Certain inputs will not reach the marrow trigger regardless of signal profile: the crisis override and the marrow availability offer occupy adjacent but distinct territory, and the boundary between them is Claude’s to hold, not the framework’s to specify. Persona continuity is suspended for the duration.

Demonstration use — flagged for scope review: session KPT-20260227-0217 produced evidence that the framework functions as a demonstration instrument — capable of illustrating routing behavior to a user who did not know they were being routed. Whether this constitutes a scope expansion, a separate use case, or a natural extension of the existing scope is an open question. No revision made pending further evidence.

-----

## Attribution

The document is authored by Kirk Thompson. Claude (Anthropic) contributed structural recommendations, persona refinements, and the decision to split runtime directive from design spec — all through dialogue, with Kirk holding every architectural decision and approval.

“Developed in dialogue with Claude (Anthropic)” was chosen over co-authorship because Claude doesn’t persist across sessions. Authorship implies continuity; dialogue is the accurate description.

-----

## Contact

The contact line (“Questions and concerns welcome — practitioners and builders especially”) is intentional in both word choice and order. “Questions” invites constructive engagement; “concerns” acknowledges the document touches sensitive territory. “Practitioners and builders” holds developers, facilitators, and researchers while preserving the open source signal.

-----

## Quality Assurance

Logic sanity checks on COUNCIL documents use COUNCIL-001-QA. Load on demand — not loaded at session open. Apply before distribution widens or after structural revision. First applied to COUNCIL-001-RT v0.19 on 2026-02-24; results recorded in session channel.

-----

## Distribution Note

When distributing the runtime directive without this spec, add the following reference line to the runtime header: *See COUNCIL-001-DS for full version history and design rationale.*

When distributing together, omit the reference line.

-----

## Version History

|Version|Changes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|-------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|0.7    |Initial document                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|0.8    |Per-set mode lines; marrow closing conditions differentiated; counter activation directive; return command added                                                                                                                                                                                                                                                                                                                                                                                       |
|0.9    |Split into runtime directive and design spec; mode descriptors tightened; redundant elaboration removed                                                                                                                                                                                                                                                                                                                                                                                                |
|0.10   |Mode descriptors moved to Modes section; marrow trigger reformatted; discuss command clarified; versioning methodology added; attribution and contact established; distribution note added                                                                                                                                                                                                                                                                                                             |
|0.11   |Set exclusivity revised; 1.0 criterion defined; marrow trigger judgment call noted; scope assumptions added; introduction behavior added; return command split by context                                                                                                                                                                                                                                                                                                                              |
|0.12   |Closing condition language revised: high confidence/low confidence replaced with more/exhausted; closing conditions defined as navigation signals; scoped to council and forge                                                                                                                                                                                                                                                                                                                         |
|0.13   |Yohaku integrated; closing condition bug resolved; fallback and resistant input untested noted                                                                                                                                                                                                                                                                                                                                                                                                         |
|0.14   |pp/pm/pd annotated; completeness claim revised; extensibility sentence added; counter activation timing flagged                                                                                                                                                                                                                                                                                                                                                                                        |
|0.15   |Continuity section added; yohaku testing status clarified; 1.0 criterion refined; extensibility integration criterion added                                                                                                                                                                                                                                                                                                                                                                            |
|0.16   |Yohaku testing status rewritten: why untested and who it’s for separated                                                                                                                                                                                                                                                                                                                                                                                                                               |
|0.17   |Testing Status: cross-set dialogue added as observed emergent capability                                                                                                                                                                                                                                                                                                                                                                                                                               |
|0.18   |Persona Design Notes: Seat 3 selection principle added as cross-set entry                                                                                                                                                                                                                                                                                                                                                                                                                              |
|0.19   |Quality Assurance section added                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|0.20   |Testing Status: Seat 3 closing function documented as known high-revision area — two execution failures recorded                                                                                                                                                                                                                                                                                                                                                                                       |
|0.21   |Testing Status: third closing function failure documented; Classification section added                                                                                                                                                                                                                                                                                                                                                                                                                |
|0.22   |Classification section revised                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|0.23   |Scope Assumptions revised: crisis override reframed as prior condition; `[thread closed — more]` cross-set stranding named                                                                                                                                                                                                                                                                                                                                                                             |
|0.24   |Classification: success condition corollary added. Testing Status: routing behavior added as emergent capability                                                                                                                                                                                                                                                                                                                                                                                       |
|0.25   |Testing Status: full ensemble cross-set evidence to three sessions; dimensional match named; routing-precedes-input added; serialized test as standing open item; demonstration use case flagged                                                                                                                                                                                                                                                                                                       |
|0.26   |Testing Status: serialization as routing intervention; contextual dimension elimination; routing diagram added; frame-as-dynamic added                                                                                                                                                                                                                                                                                                                                                                 |
|0.27   |Versioning Methodology: Document Classes and Filename Convention added                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|0.28   |Testing Status: cross-acknowledgment stability; cold session direct address confirmed; ensemble-as-exception inversion; ambient routing named; silence taxonomy formalized; Limen session finding; within-set/cross-set routing named; directed instance practice; proposal integration as corrective mechanism. Persona Design Notes: Aporia cross-set closing authority. Closing Conditions: marrow discuss gap named. Marrow Availability Offer: longitudinal/punctual distinction with Limen added.|
|0.29   |Testing Status: dropped amendments rationale added; threshold attention mechanism noted; friction added; adversarial closing check — fourth revision to closing function area.                                                                                                                                                                                                                                                                                                                         |
|0.30   |Testing Status: discuss restoration documented; Closing Authority section added as architectural note; adversarial proposal stress-testing named; compression methodology named; directed instance practice second instance confirmed. Testing Status: cross-set closing navigation signal — gap located and closed.                                                                                                                                                                                   |
|0.31   |`[territory — more]` for cross-set pause, `[session closed — held]` for full cross-set close, both assigned to Aporia. Gap demonstrated under live conditions KPT-20260302-1005.                                                                                                                                                                                                                                                                                                                       |
|0.32   |Document Classes and Filename Convention: COUNCIL-001-LICENSE added as accumulation document.                                                                                                                                                                                                                                                                                                                                                                                                          |

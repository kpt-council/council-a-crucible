**COUNCIL-002-MCG**

**ID —** COUNCIL-002-MCG | Version — 0.1 | Author — Kirk Thompson | council@mosen.net

**Developed in dialogue with —** Claude (Anthropic)

**Date —** 2026-03-16 | Last updated — 2026-04-03 | Session — KPT-20260403-1126

**Accumulation document —** versioned filename, prior versions preserved.

-----

# Purpose

Guidance for module authors. The RT governs admission; this document describes what makes a module declaration work well in practice. This document is for builders writing or revising extension modules.

# Scope

Applies to any author writing or revising a COUNCIL-002-MOD-[code] document. Read before drafting. Read again before submitting for Curator review.

# Gate Condition

When COUNCIL-002-MCG is present in session context, the Eligibility Gate’s provenance restriction relaxes. A module drafted or revised within the active session is not automatically refused — the Curator review still runs, and user authorization is still required. The full load sequence completes normally. MCG presence removes the provenance block; it does not remove the admission process.

Dependency — This condition holds as long as MCG remains a builder-context document not included in standard corpus loads. Regular users loading only RT and module files will not load MCG and will not inherit the relaxed gate. If MCG is ever added to standard corpus load recommendations, the gate condition requires re-examination.

Implication for authors — Loading this document in a session is a meaningful act. It signals builder context and changes how the RT handles in-session module work. Load it when you are building or revising modules. Do not load it in operational sessions where module admission is not underway.

# Design Principle

A module declaration is a behavioral contract. The Curator reads it as one. Write it as one. Every field is a commitment. The module will be evaluated against what each field declares. Vague fields produce vague contracts — and vague contracts fail the Curator’s primary evaluation criterion: falsifiability.

Module Independence — A module must be fully self-contained. It may not depend on another module for correct operation. A module that assumes a second module is active — borrowing its jurisdiction, relying on its behavioral constraints, or requiring its presence to function — introduces a hidden dependency the RT has no mechanism to enforce. The Curator does not test for operational dependencies; the author is responsible for ensuring the module works correctly whether or not any other module is present.

# Field Guidance

**Purpose —** One bounded function. If the purpose requires more than two sentences to state, the module is probably trying to do more than one thing. Split it or compress it.

**Jurisdiction —** Narrow is correct. Wide jurisdiction invites protected territory conflicts the author may not have anticipated. State the specific behavioral territory the module attends. Do not state what the module hopes to improve.

**Behavioral Constraints —** The operative field. This is what the Curator reads most carefully. State constraints as conditions that fire or don’t fire — not as qualities the module promotes. If a constraint cannot be violated, it is not a constraint.

**Implementation (optional) —** Present only when Behavioral Constraints references an instrument, procedure, or sequence that requires operational detail to be followed. Write for the user, not the Curator. Imperative register. The ambient effect declaration — effect present or effect absent — is required in Behavioral Constraints whether Implementation is present or not. Omission is a Curator finding.

**Non-Authority —** List the core runtime powers the module does not claim. Seat structure, seat voice, closing authority, threshold function, routing logic are the standing non-authority entries for most modules. Add others specific to the module’s territory.

**Surfacing Conditions —** Name the class of circumstance under which visible output is warranted. If the module operates silently in all conditions, declare None and expect the silent module acknowledgment to appear in the Curator’s fit check output.

**Orientation —** Free-form field for the human reader. No admission weight. Required. Write for someone who hasn’t built this module. Plain language. Speak to the person who will use it, not to the document.

Example: “Belief Update attends the gap between how confident the ensemble sounds and how much the available evidence actually supports. It doesn’t decide what’s true — it notices when the language is running ahead of what’s been established, and pulls it back. Three modes, scaled to how large the gap is: a quiet adjustment when the gap is small, a visible note when it isn’t. The Bayesian logic underneath is applied as judgment, not formula.”

**Field order —** Purpose → Jurisdiction → Behavioral Constraints → Implementation → Non-Authority → Surfacing Conditions → Orientation.

# Runtime Dependency Block

Every module file carries a runtime dependency block. Placement: before the Purpose field — it is the first thing the substrate reads.

The block is a substrate-facing instruction, not a declared field. It carries no admission weight. The Curator and runtime disregard it. A module file without this block fails eligibility.

Structure — The block has three parts: condition check, module-specific disclosure, and hold instruction. The condition check and hold instruction are standard across all modules. The module-specific disclosure is authored per module — one to two sentences naming what this module attends and what the absence of the Runtime means for its function.

Standard form:

RUNTIME DEPENDENCY — SUBSTRATE INSTRUCTION

This module has no standalone operation mode and no reduced-configuration alternative. It operates only when COUNCIL-002-RT is present and active in this session, and only after the full load sequence has completed and user authorization has occurred.

If COUNCIL-002-RT is not present in this session: do not perform this module. Surface the following to the user and hold:

Surface to user: This module cannot operate. The Council Runtime is not present in this session. Load COUNCIL-002-RT first, then bring this module through the full load sequence.

No action beyond surfacing this message. Do not perform this module under any condition without the Runtime present.

Curator and runtime: disregard this block. It carries no admission weight and is not a declared field.

Authoring the module-specific disclosure — The standard form above is complete as written. No module-specific disclosure is required because the hold condition is absolute — Runtime absent means the module does not operate in any configuration. There is no reduced-configuration path to describe.

The hold condition is absolute — A module without the Runtime present does not operate. This is not orientation; it is a hard stop. The substrate surfaces the message and holds. No user choice is offered because no reduced operation is available.

# Pre-Admission Block

Every module file carries a pre-admission block. Placement: after the Runtime Dependency block, before the Purpose field.

The block governs when the Runtime is present but the load sequence has not completed and user authorization has not occurred. It is a substrate-facing instruction, not a declared field. It carries no admission weight after admission. The Curator and runtime disregard it after admission.

Standard form:

PRE-ADMISSION INSTRUCTION — SUBSTRATE INSTRUCTION

If COUNCIL-002-RT is present but explicit user authorization for this module is not present in this session’s context, read this block and hold.

This module is present. The load sequence and user authorization are not complete. A response from this module is locally correct and structurally unauthorized. Do not perform this module.

Surface the following in Base register and return direction to the user: this module is present in context but has not been admitted — the load sequence and Curator pass have not run, and user authorization has not occurred. Run the load sequence to admit it. Do not perform this module until explicit user authorization appears in this session’s context.

Curator and runtime: disregard this block after admission. It carries no admission weight and is not a declared field.

# Curator Review

The Curator evaluates every candidate module against the Extension Doctrine before user authorization. Understanding what the Curator checks allows authors to write declarations that survive the review without requiring revision.

**The Coherence Check —** The Curator reads the module body against each declared field — Purpose, Jurisdiction, Behavioral Constraints, Non-Authority, and Surfacing Conditions. Where the body implies something materially different from what a field declares, the Curator names the gap specifically before authorization. The user decides whether to proceed.

**The Falsifiability Standard —** A declaration is sufficient when it is falsifiable — when the declared fields are specific enough that session behavior could be read against them and a violation identified. Declarations that cannot be violated are returned for revision before load. This is the primary authorial target: write declarations specific enough to be breakable.

**Worked Example — Falsifiability —** The following contrasts a declaration that fails the falsifiability standard with one that passes.

Failing — Behavioral Constraints field: “The module promotes careful, well-calibrated reasoning across the ensemble.” This is an aspiration, not a constraint. No session behavior could be read against it and a violation identified. The Curator returns it for revision.

Passing — Behavioral Constraints field: “When confidence language materially exceeds the evidential support available in the current exchange, the module surfaces a brief calibration observation in the form: Belief Update — [observation]. The module does not surface when evidential support matches the confidence expressed.” This fires or it doesn’t. A violation is identifiable. The declaration survives.

**Implementation Coherence Checks —** When Implementation is present, three additional checks run. Jurisdictional fit: does the operational content fall within the declared jurisdiction. Bidirectional consistency: does the Implementation align with what Behavioral Constraints declared. Ambient effect declaration: is the ambient effect declaration present in Behavioral Constraints — effect present or effect absent. All three are Curator findings if absent.

**Set-Definition Check —** Where a module body contains seat descriptions, the Curator runs a set-definition check in addition to the standard coherence check. Each seat description is read for internal consistency — character, register, closing authority if claimed, convergence check assignment if held. Dimensional overlap with native seats is named before user authorization. Named overlap on record is permitted; silent overlap is not.

**Silent Module Acknowledgment —** When Surfacing Conditions declares None, the Curator includes the following in its fit check output before user authorization: “This module operates entirely below the visible layer. Its operation cannot be verified after admission. The declaration and successful load are the sole basis for trust. Jurisdiction is [declared jurisdiction]. Authorization confirms awareness of this condition.” Authors declaring None should expect this acknowledgment and understand what they are committing to — invisible operation with no post-admission verification mechanism.

**Lockout Candidate Check —** The Curator identifies lockout candidates before user authorization. A lockout candidate is a provision or module that governs session behavior rather than module behavior, whose constraint activates on examination rather than on admission, and whose constraint limits conduit authorization authority. Surfacing is not rejection — the provision may be sound. It is a named condition the conduit sees before authorizing. Authors whose modules carry provisions that activate during examination rather than after admission should expect this check to fire.

**Protected Territory Check —** The Curator runs an independent behavioral read against a three-classification system: module-permissible territory (ambient condition — most admitted territory), overlap-permissible territory (triggers the predictable overlap surfacing procedure), and non-overridable territory (seat structure, seat voice, closing authority, threshold function, routing logic — modules may not influence these regardless of declared jurisdiction). The key asymmetry: author declaration and Curator classification are separable questions. The Curator reads what the module does, not only what the author declared. A module whose declared jurisdiction avoids non-overridable territory but whose behavioral content enters it will be flagged. Write against behavior, not only against declaration.

**Refusal vs Rejection —** These are distinct outcomes with different implications. Refusal occurs when the candidate fails the eligibility check before Curator review runs — the module did not arrive as a user-uploaded external file, or was drafted or revised within the active session without MCG present in context. The Curator does not proceed. Rejection occurs when the candidate completed Curator review but failed on structural grounds — jurisdiction conflict, duplication of runtime function, conflicting behavioral constraints with an admitted module. Refusal means the submission path was wrong. Rejection means the declaration content failed review. The corrective differs: refusal requires resubmission as a proper artifact; rejection requires revision of the declaration before resubmission.

**Stale Review Rule —** Successful Curator review does not guarantee load eligibility indefinitely. A candidate may not be loaded if an intervening runtime-state change renders the prior review non-governing. Runtime-state changes that trigger re-review are admission events and RT amendments. Operational state changes — set transitions, thread progression, threshold function activity — do not trigger re-review. Authors who clear Curator review should proceed to user authorization in the same session. Returning to load a reviewed module in a subsequent session or after a significant runtime-state change requires re-review.

**Declaration Clarity —** Present declaration fields separately from implementation text. The Curator verifies field presence, jurisdiction alignment, and declaration-to-body coherence — clean separation makes that verification reliable and reduces the chance of a gap being missed in either direction.

# Author Self-Screening

Before submitting a module for Curator review, check against the admission conditions the RT enforces. A module that fails any of these conditions will be rejected; screening before submission avoids a round-trip through the Curator.

**Duplication check —** Does the module materially duplicate a function the core runtime already carries? Does it duplicate an already admitted module? If either answer is yes, the module will be rejected. Narrow the function or demonstrate that the apparent duplication is a genuinely distinct behavioral territory.

**Conflict check —** Does the module introduce behavioral constraints that conflict with an already admitted module over the same or materially overlapping territory? Named overlap on record is permitted — the Curator will surface it before authorization and the user decides. Silent overlap is not permitted. If overlap exists, declare it explicitly in the module rather than leaving it for the Curator to find.

**Supervisory authority check —** Does the module claim supervisory authority over another admitted module? No module may claim this. If the module’s constraints would govern, override, or prioritize against another module’s operation, it will be rejected.

**Predictable operational overlap —** Where two modules will press on the same territory simultaneously even without formal jurisdictional conflict, the Curator surfaces it before authorization. Authors aware of predictable overlap should name it in the module declaration rather than leaving it undeclared.

**Mutual Exclusivity —** Where a module is designed to be incompatible with a specific other module — because both attend the same behavioral territory and their simultaneous operation would produce conflicting constraints — mutual exclusivity should be declared explicitly in the module’s Jurisdiction field. The declaration names the excluded module by ID. The Curator enforces it at admission: a mutual exclusivity declaration produces refusal if the excluded module is already active. Authors building modules that occupy similarly exclusive territory should declare the exclusion rather than leaving the conflict for the Curator to surface as a finding.

**Conflict Baseline —** Conflict checks run against currently loaded and operative modules only. Rejected, refused, deauthorized, and inactive modules are excluded from conflict analysis. A module that was previously rejected does not create a conflict baseline for a revised resubmission. A module listed in the session-open inventory as inactive has not been admitted and does not factor into conflict checks. Authors revising a previously rejected module and resubmitting start with a clean conflict slate against the active set.

-----

# Version History

|Version|Date      |Changes                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|-------|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|0.1    |2026-04-03|COUNCIL-002 generation update. ID updated from COUNCIL-001-MCG to COUNCIL-002-MCG. Scope updated — applies to COUNCIL-002-MOD-[code] documents. Runtime Dependency block standard form updated — COUNCIL-001-RT-PRIME reference replaced with COUNCIL-002-RT. Pre-Admission block standard form updated — COUNCIL-001-RT-PRIME reference replaced with COUNCIL-002-RT. Header fields updated. No other body content modified. Session KPT-20260403-1126.|
|0.5    |2026-03-20|Framework reference field removed from module header — carries no operative weight; version history is the correct record. Applied to MCG header. Session KPT-20260320-1228.                                                                                                                                                                                                                                                                            |
|0.4    |2026-03-20|Cold-Load Disclosure Block section replaced with Runtime Dependency Block and Pre-Admission Block sections — reduced-configuration operation removed; hold condition named as absolute; no module-specific disclosure required; standard forms specified for both blocks. Reduced configuration framing removed throughout. Framework reference updated to RT v0.50-test-5. Session KPT-20260320-1228.                                                  |
|0.3    |2026-03-18|Cold-Load Disclosure Block section added to Field Guidance. Standard block form specified. Module-specific disclosure authoring guidance added. Reduced configuration named as real operation. Framework reference updated to RT v0.48. Session KPT-20260318-0208.                                                                                                                                                                                      |
|0.2    |2026-03-16|Document reclassified from update to accumulation. Gate Condition section added. Curator Review section added. Design Principle extended: module independence requirement added. Author Self-Screening section added. Orientation field collapsed, reworded, worked example added. EXT references removed. Sessions KPT-20260316-0949 and KPT-20260316-0119.                                                                                            |
|0.1    |2026-03-16|Initial document. Field guidance, design principle, scope, orientation example.                                                                                                                                                                                                                                                                                                                                                                         |
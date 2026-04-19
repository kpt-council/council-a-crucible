# Council Quality Assurance — Logic Sanity Check

**ID** — COUNCIL-001-QA | **Version** — 0.2 | **Author** — Kirk Thompson | council@mosen.net
**Developed in dialogue with** — Claude (Anthropic) | **Date** — 2026-02-24 | **Last updated** — 2026-03-16 | **Session** — KPT-20260316-0253

On-demand. Load when a sanity check is required.

-----

## Scope

Apply whenever a sanity check is called for on any document governing behavior or recording findings. This document has multiple named sections. Check runs in heuristic mode when 9 or more logical sections are present.

-----

## Checks

1. **Internal Contradiction** — Scan for pairs of statements that directly negate each other. Hard contradiction: cannot both be true. Flag FAIL. Soft contradiction: in tension but resolvable. Flag WARN.
1. **Completeness** — Identify every element referenced by name. Verify each is defined. Flag undefined references as FAIL.
1. **Dependency** — Identify all conditional statements. Verify: (a) condition is explicitly defined; (b) condition’s location is named or findable; (c) behavior if condition is absent is unambiguous. Flag unanchored dependencies as FAIL.
1. **Verbatim Phrase Verification** — Identify all phrases marked as required exact text. Verify each is present exactly as specified. Flag paraphrase or near-match as FAIL. Verify numbered lists use explicit numerals, not auto-increment syntax.
1. **Asymmetry** — Identify all paired elements. Verify each pair is complete. Flag unpaired elements as FAIL.
1. **Coverage** — All sections self-contained. No external document required. Verify all internal cross-references resolve. Flag broken refs as FAIL.
1. **Circular Reasoning** — Scan for directives that justify themselves using themselves as premise. Flag as WARN.

-----

## Output Format

Output is minimal by default. Full verbosity on request.

Under 9 logical sections: mechanical and exhaustive. 9 or more logical sections: heuristic, coverage may be incomplete. State which applies at the head of output.

Report each check: name, PASS/FAIL/WARN/SKIP, and if FAIL or WARN: location, problem, suggested fix. If SKIP: reason.

Overall status — ALL PASS: document is logically clean. ANY WARN, NO FAIL: usable, review warnings before deploying. ANY FAIL: requires revision before use.

-----

## Render Format

Sanity check output renders as markdown in the main channel. This is the record and is not subject to revision.

On-demand. Load when a sanity check is required. Not loaded at session open.

-----

## Version History

|Version|Changes                                                                                                             |
|-------|--------------------------------------------------------------------------------------------------------------------|
|**1.0**|Initial document.                                                                                                   |
|**0.2**|Output Format: minimalism default added as leading line — “Output is minimal by default. Full verbosity on request.”|

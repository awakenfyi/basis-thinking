# BASIS — the method spec

## The meta-formula

**Basis(domain) = roles + questions + intents + module library + brief format.**

The roles change vocabulary per domain (dialects); the structure never changes. That invariance is why the method transfers: it isn't web advice — it's the grammar of moving a stranger from ignorance to action.

## The four roles

| Role | Job | Typical modules | Failure smell |
|---|---|---|---|
| **TELL** | the story, the claim, the category | hero, H1, manifesto, campaign line | claims stacking with no receipts below |
| **SEE** | the thing itself, shown | screenshot, demo, UI, product photo | abstraction where the product should be; seconds-to-first-sight too high |
| **PROVE** | the evidence for the claim | logos, numbers, customer stories, benchmarks, awards | proof that answers no one's actual question; borrowed authority |
| **DO** | the action, attachable anywhere | CTA, signup, sample, next step | one verb repeated; asks before any Prove |

## The three layers (coordinates per module)

Every module gets three tags: **role × reader-question × intent.**

- Reader's questions: **What is it / Why should I care / How does it work / Who else uses it**
- Intents (v1 naming, frozen): **Guide / Educate / Assure / Inspire**

**The diagonal law:** defaults pair Tell×Inspire · See×Educate · Prove×Assure · Do×Guide. Tag only deviations loudly — an off-diagonal module is a stance decision and gets a one-line reason in the brief. Nine Educates in a row with no Assure at the high-friction moment is a layer-3 failure invisible to layer 1.

## The CTA tier grammar

Not all DOs are equal. Four tiers, each legitimate, each declared:
- **T1 — Build**: highest-commitment action (start, install, deploy)
- **T2 — Buy**: commercial commitment (pricing, purchase, contact sales)
- **T3 — Prove-advance**: moves the visitor deeper into evidence without converting (see the case study, run the benchmark, read the audit) — *the most under-used tier; advance, not convert*
- **T4 — Browse**: low-commitment continuation (read more, explore)

A page's CTA architecture = which tiers appear, in what order, attached to which modules.

## The asterisk law

Every Tell-block claim carries an asterisk; **every asterisk resolves to its Prove receipt within the same asset.** No receipt in the asset → the claim is rewritten or the omission is declared in the brief. This makes Tell-vs-Prove overhang visible in the layout itself, not just computable afterward.

## The sprint (and its agent form)

**Understand → Define → Create → Build → Activate.** Agentified:

1. **Benchmarker** — reads the field (named sites, dated pass, verbatim quotes): what does each competitor Tell/See/Prove/Do per channel? Output: the field read-out + the sea of sameness.
2. **Briefer** — turns strategy + read-out into 1-pager briefs per asset (see templates/brief.html).
3. **Writer** — drafts modules against the brief, three-layer tags on every block.
4. **Build** — human + tools; lofi structure before hifi expression.
5. **Auditor + Governor** — re-reads the shipped asset against its own brief; counts (never vibes); flags drift; refresh cadence per module ("no sample ages past its declared shelf life").

## Measurement (the open builds)

- **`basis scan <url>`** — deterministic module classifier from DOM structure: role sequence out in seconds, no agent needed.
- **Tell-vs-Prove overhang** — claims counted against receipts counted, per asset. The gap, as a number.
- **Corpus fingerprints** — module-sequence patterns compared across a field: the sea of sameness computed, not curated.
- **Reverse Basis** — brief → module sequence → lofi skeleton: audit and generation as one grammar.

Status labels apply: the method is practiced experience; the metrics above are DESIGNED until they run.

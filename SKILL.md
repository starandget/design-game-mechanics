---
name: design-game-mechanics
description: Design, analyze, prototype, balance, and communicate game mechanics for digital, tabletop, physical, and hybrid games. Use when Codex needs to turn a game idea into rules and systems; diagnose boring, dominant, unstable, unfair, or confusing gameplay; design economies, feedback loops, progression, levels, tutorials, or rewards; compare emergent and authored progression structures; prepare a mechanics specification or playtest plan; or review whether mechanics express the intended theme or message.
---

# Design Game Mechanics

Treat mechanics as executable rules, state, resources, actions, and transitions. Focus on what players can perceive, decide, and influence.

## Route the request

Choose the smallest useful workflow:

- For a new concept, run **Frame -> Model -> Prototype -> Test**.
- For a troubled design, run **Observe -> Diagnose -> Change one variable -> Retest**.
- For economy or balance work, read [systems-and-balance.md](systems-and-balance.md).
- For progression, levels, onboarding, or narrative gating, read [progression-and-levels.md](progression-and-levels.md).
- For a formal critique or deliverable, read [deliverables-and-rubrics.md](deliverables-and-rubrics.md).
- For intellectual provenance and publication limits, read [provenance.md](provenance.md).

## Frame the experience

Before proposing mechanics, state:

1. Player fantasy and role.
2. Repeated decision the player should enjoy.
3. Intended tension: scarcity, timing, uncertainty, coordination, spatial control, mastery, or another pressure.
4. Session length, player count, platform, audience, and accessibility constraints.
5. Observable success criteria.

If critical context is absent, make reversible assumptions and label them.

## Describe the rules as a playable system

Produce a compact mechanics map:

- **Entities:** actors and objects that can hold state.
- **Resources:** quantities that can be produced, stored, transformed, transferred, or consumed.
- **Player verbs:** meaningful actions available to the player.
- **Rules:** conditions and consequences written without implementation ambiguity.
- **State:** variables needed to determine what happens next.
- **Boundaries:** what enters or leaves the system.
- **End conditions:** victory, defeat, completion, withdrawal, or persistence.
- **Information:** what is visible, hidden, delayed, noisy, or inferred.

Write every core rule in this form when precision matters:

`When <trigger> and <conditions>, <actor/system> changes <state/resource> by <effect>; communicate it through <feedback>.`

Separate the mechanical model from theme, presentation, and code. Connect them later.

## Choose the structural blend

Treat emergence and authored progression as a spectrum, not mutually exclusive genres.

- Favor **emergence** when a small set of interacting rules should create reusable situations, strategies, and player stories.
- Favor **authored progression** when pacing, teaching, narrative order, or curated challenges require control.
- Combine them by placing systemic play inside authored gates, or by letting systemic outcomes create progression.

Check whether complexity comes from meaningful interaction among rules. Do not substitute random events or sheer rule count for emergence.

## Build decision quality

For each repeated choice, test:

- Are at least two options viable in a relevant context?
- Do options trade off different values rather than differ only numerically?
- Can the player anticipate consequences well enough to form intent?
- Does new information justify reconsideration?
- Can skill improve the choice without eliminating uncertainty?
- Is failure attributable and recoverable at the intended cadence?

Remove choices with an always-correct answer unless they serve learning, pacing, expression, or accessibility.

## Prototype at the cheapest faithful level

Select the medium that preserves the uncertainty under test:

- Use paper or tokens for turn structure, economy, drafting, probabilities, and spatial abstraction.
- Use a spreadsheet or small simulation for resource flows, distributions, and long-run balance.
- Use a digital prototype for timing, motion, dexterity, feel, network interaction, or hidden automation.
- Use physical enactment for social, embodied, or location-based interaction.

Prototype one question at a time. Define the decision the test will unlock before building.

## Test and iterate

Capture observations separately from interpretations.

1. Establish a baseline build and prediction.
2. Observe player choices, confusion, emotional peaks, exploits, stalls, and recovery.
3. Record outcome metrics and decision traces, not only opinions.
4. Identify the smallest plausible cause.
5. Change one causal lever or one coherent cluster.
6. Retest against the same success criterion.

Never claim balance from averages alone. Inspect variance, outliers, strategy diversity, first-player or spawn advantages, snowballing, time-to-resolution, and performance by player skill.

## Communicate the result

Lead with the design decision and its reason. Then provide only the artifacts needed by the audience, such as:

- a one-page mechanics brief;
- a state/resource diagram in Mermaid;
- a rules specification;
- a prototype plan;
- a tuning table with parameter ranges;
- a playtest protocol;
- a diagnosis with ranked interventions.

Label hypotheses, assumptions, evidence, and open risks. Use original examples unless the user supplies a game to analyze.

## Guardrails

- Preserve player agency; do not hide outcomes that the intended decision requires.
- Distinguish difficulty from opacity, waiting, repetition, and punishment.
- Treat retention and monetization as constraints, never as permission for coercive or deceptive design.
- Consider accessibility, griefing, collusion, harassment, and exploit economies in multiplayer systems.
- Do not reproduce copyrighted books, diagrams, tables, exercises, or extensive examples. Apply general principles and cite sources when publishing derivative analysis.

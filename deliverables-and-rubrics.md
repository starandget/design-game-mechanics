# Deliverables and Review Rubrics

## One-page mechanics brief

Use this structure:

1. **Design intent:** player fantasy, audience, and target emotion.
2. **Core loop:** action, feedback, updated state, and next decision.
3. **Entities and resources:** only decision-relevant state.
4. **Player verbs:** inputs and meaningful consequences.
5. **Uncertainty:** randomness, hidden choice, or rule interaction.
6. **Progression:** access, capability, mastery, and expression.
7. **Failure and recovery:** cadence, stakes, and learning.
8. **Risks:** dominant strategies, runaway loops, opacity, exploits, accessibility.
9. **Prototype question:** one falsifiable question and success criterion.

## Mechanics specification table

| Field | Required content |
|---|---|
| ID | Stable rule identifier |
| Intent | Player-facing purpose |
| Trigger | Event that evaluates the rule |
| Preconditions | State required for activation |
| Inputs | Resources, entities, and values read |
| Transition | Exact state changes |
| Outputs | Resources, events, and signals produced |
| Feedback | Visual, audio, haptic, textual, or social communication |
| Edge cases | Ties, caps, missing targets, concurrency, interruption |
| Tuning | Named parameters, defaults, and safe ranges |
| Telemetry | Events needed to evaluate the intent |

## Diagnostic report

For each issue provide:

1. Observation with evidence.
2. Likely system cause.
3. Player impact.
4. Ranked interventions from least invasive to structural.
5. Expected side effects.
6. Retest metric and decision threshold.

Do not present preference as evidence. Preserve alternative hypotheses when data cannot distinguish them.

## Playtest protocol

Include:

- build and rule version;
- participant profile and sample limitations;
- test question and prediction;
- scenario and prohibited coaching;
- behavioral measures and event definitions;
- post-session prompts that avoid leading the player;
- stopping and safety conditions;
- analysis plan and change threshold.

## Review rubric

Score each dimension from 0 to 3 and explain any score below 2.

- **Agency:** choices materially affect outcomes.
- **Legibility:** players can form useful causal models.
- **Depth:** rules support contextual strategies and counterplay.
- **Pacing:** tension, recovery, and resolution fit the target experience.
- **Balance:** intended options remain viable for the target population.
- **Feedback:** consequences arrive in time and through accessible channels.
- **Learning:** challenge grows with demonstrated understanding.
- **Coherence:** incentives reinforce the fantasy and stated meaning.
- **Robustness:** edge cases and adversarial behavior remain acceptable.
- **Feasibility:** the design fits production and operational constraints.

Do not sum the scores into a universal quality number. Use the profile to expose tradeoffs.

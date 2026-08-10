# Systems and Balance Field Guide

## Contents

1. Economy model
2. Feedback diagnosis
3. Uncertainty and emergence
4. Pattern vocabulary
5. Balance workflow
6. Multiplayer risks

## Economy model

Model an economy as transformations over time.

- **Source:** introduces a resource.
- **Pool:** stores a resource and exposes capacity or thresholds.
- **Converter:** exchanges one resource or state for another.
- **Drain:** removes a resource.
- **Trader:** performs a reciprocal transfer.
- **Gate:** permits flow only when a condition is met.
- **Delay/queue:** separates cause from effect in time.

For each resource, document its unit, source rate, storage cap, sinks, exchange rates, information visibility, and strategic purpose. Delete resources that do not alter decisions or communicate state.

Sketch the system before assigning exact numbers. A Mermaid flowchart is sufficient when a specialized simulator is unavailable.

## Feedback diagnosis

A loop is reinforcing when an advantage produces more advantage; it is balancing when deviation triggers resistance or recovery.

Describe each important loop with:

`trigger -> affected variable -> downstream effect -> return path -> delay -> cap`

Inspect:

- sign: reinforcing or balancing;
- strength: how much one traversal changes the state;
- delay: how quickly the consequence returns;
- duration: temporary or persistent;
- scope: individual, team, match, campaign, or metagame;
- visibility: whether players can recognize and plan around it;
- interaction: whether other loops amplify or suppress it.

Reinforcing loops create growth, mastery payoff, escalation, and snowballs. Balancing loops create stability, pacing, comeback space, and diminishing returns. Neither is inherently good. Control runaway behavior with caps, rising costs, decay, exposure, contestability, or reset points.

## Uncertainty and emergence

Use three distinct sources of unpredictability:

- **Randomness:** stochastic variation.
- **Player choice:** hidden or simultaneous intent.
- **Rule interaction:** outcomes costly to foresee despite understandable local rules.

Use randomness to create adaptation, variety, or imperfect information. Avoid using it to erase earned advantage without serving the intended fantasy. Compare input randomness, which players plan around, with output randomness, which modifies resolved actions.

Test emergence by asking whether the interaction creates reusable strategies, counterplay, and surprising but explainable outcomes. More rules do not guarantee more emergence.

## Pattern vocabulary

Use these generic structural patterns as prompts, not recipes:

- **Engine:** investment increases future production.
- **Friction:** progress consumes time, opportunity, position, or resources.
- **Attrition:** repeated exchange reduces capacity.
- **Escalation:** pressure or capability rises over phases.
- **Arms race:** competing investments reinforce each other.
- **Trade:** parties exchange differently valued resources.
- **Worker allocation:** scarce agents distribute effort across opportunities.
- **Style reinforcement:** actions improve the approach that produced them.
- **Multiple loops:** several feedback structures compete for control.
- **Slow cycle:** delayed replenishment creates planning horizons.

For each selected pattern, specify its player-facing decision, counterforce, stopping condition, and failure mode.

## Balance workflow

Define balance relative to an experience goal. Symmetry is only one option.

1. Identify the objects being compared: strategies, characters, starts, teams, resources, or difficulty curves.
2. Define acceptable ranges for win rate, pick rate, completion time, resource surplus, strategy diversity, and subjective tension.
3. Create deterministic edge cases before Monte Carlo runs.
4. Simulate broad parameter ranges to locate sensitive variables.
5. Playtest human adaptation, signaling, execution burden, and enjoyment.
6. Segment results by skill and experience.
7. Tune high-leverage parameters gradually and retain versioned baselines.

Useful diagnostics:

- Is a strategy dominant, merely popular, or easier to execute?
- Does the counter exist, remain discoverable, and arrive in time?
- Is early advantage persistent because of a reinforcing loop?
- Does a catch-up system reward deliberate underperformance?
- Does the match continue after the meaningful outcome is already decided?
- Are rare events driving memorable stories or invalidating decisions?

## Multiplayer risks

Review kingmaking, collusion, griefing, smurfing, spawn advantage, runaway leaders, elimination downtime, information leakage, network latency, and unequal communication channels. Address incentives and system permissions before relying on moderation alone.

# Decision Process Coach

A ChatGPT Skill for helping people make better decisions under uncertainty.

It turns messy choices into a structured process using:

- clear decision framing
- explicit hypotheses
- prior probabilities
- evidence weighting
- Bayesian-style updating
- expected value thinking
- risk controls
- falsification triggers
- review loops

## Example prompts

```text
Use the decision process coach to help me decide whether to buy this stock.
```

```text
Help me evaluate whether I should leave my current job for this offer.
```

```text
Use Bayesian decision thinking to assess whether we should build this product.
```

```text
Stress-test my decision logic and find what evidence would change my mind.
```

## Skill structure

```text
SKILL.md
agents/openai.yaml
references/framework.md
references/templates.md
```

## Design principle

The skill is not meant to make choices for the user blindly. It helps the user expose assumptions, weight evidence, estimate expected value, control downside, and define when to update or reverse the decision.

## Installation

Upload this repository as a ChatGPT Skill package, or package it as a ZIP containing `SKILL.md`, `agents/`, and `references/`.

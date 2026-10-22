# Shokunin Labs

Shokunin Labs builds software for athletes who train in the functional-fitness and cross-training world. The name comes from the Japanese word for a craftsperson: small tools, made carefully, with the numbers right.

## What we build

**Shokunin**
A training-log app for functional-fitness and cross-training athletes. Gyms publish their programming, athletes log what they actually did, and every result is stored against the movement and the load, not as free text. Gym staff see aggregates only. Nothing is shown for fewer than five athletes, and no coach or gym admin can open a named athlete's log. The privacy rule is enforced in the API, not left to a setting. The beta is free and invite-only with a small group of pilot gyms.

**Shokunin Agent**
A coaching agent for one athlete training for Hyrox. It plans and adjusts the training week, reads the sheets the gym posts, tracks station benchmarks and writes to the athlete on Telegram, including at 07:00 when nobody is watching. It does not guess a load: a program with anything unreadable cannot be confirmed, and nothing is planned against an unconfirmed program. It is built on Anthropic's Managed Agents with a small MCP server as its data layer.

## How we work

- Precise and numbers-first. A result is a number with a unit.
- Calm by default. No streaks, no guilt, no hype.
- Privacy is part of the architecture.
- A wrong load is worse than a question, so the software asks.

## Status

Both projects are in active development. The repositories are private.

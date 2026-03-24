# Just Pick One 🎲

**Stop comparing for 30 minutes. The difference between options is smaller than your time spent deciding.**

You've been comparing restaurants for 45 minutes. Both have good reviews. Both are in budget. You're now hangry AND paralyzed. The energy you've spent deciding is worth more than the difference between options.

This Agent Skill forces decisions by reframing the cost of indecision. Timer + coin flip + "good enough" framing.

Works with Claude Code, Codex CLI, OpenClaw, and any Agent Skills-compatible tool.

---

## The Problem

- You've had 15 tabs open for an hour
- Every option seems equally good (or bad)
- "Let me just check one more review..."
- The perfect option doesn't exist

**This skill solves it:** Decision timer, coin flip test, and permission to stop.

---

## Installation

### npx skills
```bash
npx skills add git@github.com:mcltyl/just-pick-one-skills.git
```

### Claude Code / Codex CLI
```bash
git clone https://github.com/mcltyl/just-pick-one-skills.git ~/.claude/skills/just-pick-one
```

### OpenClaw
```bash
git clone https://github.com/mcltyl/just-pick-one-skills.git ~/.openclaw/skills/just-pick-one
```

---

## Skills

| Skill | Description |
|-------|-------------|
| [just-pick-one](skills/just-pick-one) | Force decisions with timer, coin flip, "good enough" filter |

---

## The Core Insight

**The difference between options is almost always smaller than the cost of your time deciding.**

| Decision Time | Your Time Cost | Actual Value Difference |
|---------------|----------------|------------------------|
| 30 min | $25 | Usually < $10 |
| 1 hour | $50 | Usually < $20 |
| 2 hours | $100 | Rarely > $50 |

---

## Decision Methods

### 🪙 The Coin Flip Test

```
Heads = A, Tails = B

[flip]

"It's A."

How do you feel? Relieved? → Go with A.
Disappointed? → You wanted B. Go with B.
```

The coin doesn't decide. **Your reaction to the coin decides.**

### ⏱️ The 10-Second Rule

```
10... 9... 8... 7... 6... 5... 4... 3... 2... 1...

What did you say?
```

Your gut knows. Trust it.

### ✓ The Good Enough Filter

| Requirement | Option A | Option B | Option C |
|-------------|----------|----------|----------|
| Within budget | ✓ | ✓ | ✓ |
| Good reviews | ✓ | ✓ | ✓ |
| Available | ✓ | ✓ | ✓ |

**They're all fine. Pick any. Move on.**

---

## Example

**User:** "I can't decide between these 3 restaurants"

**Response:**
```
Quick check:
- All within budget? ✓
- All have good reviews? ✓
- All have something you'd eat? ✓

They're all fine.

🎲 Go with restaurant 2.

Why? Because the difference between 4.3 and 4.5 stars 
is not worth 20 more minutes of your life.

Go eat.
```

---

## Decision Tiers

Not all decisions deserve the same energy:

| Tier | Examples | Max Time | Method |
|------|----------|----------|--------|
| **Trivial** | What to eat, which shirt | 2 min | Coin flip |
| **Minor** | Restaurant, product <$50 | 10 min | Good enough |
| **Moderate** | Product $50-500, vacation | 30 min | Quick pros/cons |
| **Major** | Job offer, big purchase | Days | Full analysis |

**90% of decisions are Tier 1 or 2.**

---

## Common Traps

| Trap | Reality |
|------|---------|
| "Let me check one more review" | After 10 reviews, more data doesn't help |
| "There might be something better" | The perfect option doesn't exist |
| "What if I regret this?" | Future regret is imaginary. Current paralysis is real. |
| "I've already spent an hour..." | Sunk cost. Decide NOW. |

---

## Commands

```
"Just pick one for me"
"Help me decide between X and Y"
"Coin flip: X or Y"
"10-second choice"
"Force a decision"
```

---

## The Philosophy

- Good enough is good enough
- Most decisions are reversible
- Your time has value
- Research has diminishing returns
- Your gut knows more than your spreadsheet

---

## License

MIT

---

## Support

If this saves you from another hour of tab-comparing:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=flat&logo=buy-me-a-coffee)](https://buymeacoffee.com/mclty)

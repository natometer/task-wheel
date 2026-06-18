# Task Wheel

**Let chance pick the next thing so you don't have to.**

Scary, long jobs get smaller slices on the wheel, easier to land on, easier to start. Rate each task on three scales, spin, and go.

Made by [Natalie Frantsits](https://nataliefrantsits.at).

---

## How to use

1. **Add tasks** give each a name and rate it on Importance (1-3), Scariness (1-3), and Duration (1-3).
2. **Spin** the wheel picks your next task. Scary or long jobs have smaller slices, so they feel startable when you land on them.
3. **Start the timer** suggested length comes from your duration rating. Pause, adjust, or finish early.
4. **Too daunting?** click *Break it down* to define a smaller first step. The subtask goes straight to the timer. When you're done, you're prompted to define a follow-up, which lands on the wheel.
5. **Energy breaks** after every 3-5 tasks a REST STOP appears on the wheel with a restorative suggestion. Taking it resets the counter.

---

## The method

### Weight formula

```
weight = importance² / (scariness × duration)
```

Each task's slice of the wheel is proportional to its weight. Squaring importance makes high-stakes work dominate regardless of how hard it is. Dividing by scariness and duration shrinks the daunting, long jobs into small, startable slices rather than walls you avoid.

| Importance | Scariness | Duration | Weight |
|---|---|---|---|
| 3 · Must do | 1 · Fine | 1 · <30 min | 9.0 · large |
| 3 · Must do | 3 · Dreading it | 3 · 2 hr+ | 1.0 · small |
| 1 · Nice to do | 3 · Dreading it | 3 · 2 hr+ | 0.11 · sliver |

### Research basis

- **[Temporal Motivation Theory](https://en.wikipedia.org/wiki/Temporal_motivation_theory)** — Steel & König (2006); Steel (2007). The likelihood you act on a task rises with its value and falls with its aversiveness and effort cost. The weight formula maps directly onto this structure.
  - Steel, P. (2007). The nature of procrastination: A meta-analytic and theoretical review of quintessential self-regulatory failure. *Psychological Bulletin, 133*(1), 65-94. https://doi.org/10.1037/0033-2909.133.1.65
  - Steel, P., & König, C. J. (2006). Integrating theories of motivation. *Academy of Management Review, 31*(4), 889-913. https://doi.org/10.5465/amr.2006.22527462

- **[Attention Restoration Theory](https://en.wikipedia.org/wiki/Attention_restoration_theory)** — Kaplan & Kaplan (1989); Kaplan (1995). Directed attention depletes across a work session. Brief, low-effort, nature-leaning breaks restore it. Break suggestions are chosen on this basis.
  - Kaplan, R., & Kaplan, S. (1989). *The experience of nature: A psychological perspective.* Cambridge University Press.
  - Kaplan, S. (1995). The restorative benefits of nature: Toward an integrative framework. *Journal of Environmental Psychology, 15*(3), 169-182. https://doi.org/10.1016/0272-4944(95)90001-2

- **[Ultradian rhythms](https://en.wikipedia.org/wiki/Ultradian_rhythm)** — Kleitman (1963). The brain cycles through roughly 90-minute peaks and troughs of alertness. Periodic rest aligns with these natural cycles rather than fighting them.
  - Kleitman, N. (1963). *Sleep and wakefulness* (2nd ed.). University of Chicago Press.

- **[Implementation intentions](https://en.wikipedia.org/wiki/Implementation_intention)** — Gollwitzer (1999). Specifying exactly what you will do (not just intending to) dramatically increases follow-through, even for aversive tasks. The *break it down* feature is built on this.
  - Gollwitzer, P. M. (1999). Implementation intentions: Strong effects of simple plans. *American Psychologist, 54*(7), 493-503. https://doi.org/10.1037/0003-066X.54.7.493

---

## Settings

| Setting | Default | Description |
|---|---|---|
| Energy breaks | On | REST STOP segment appears every 3-5 tasks |
| Reduce motion | Off | Shorter spin animation, no confetti |
| Praise style | Warm | Message shown on task completion: Warm / Dry / Minimal |

---

## License

MIT.

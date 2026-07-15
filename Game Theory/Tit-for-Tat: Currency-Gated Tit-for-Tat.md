# Tit-for-Tat

The effectiveness in _Tit-for-Tat strategies_ comes from, per Axelrod, providing a ***nice, forgiving, and clear*** methodology that’s legible for others. The legibility of Tit-for-Tat offers others a way to reverse-engineer your entire strategy in a two rounds: _cooperate and I cooperate, defect and I defect._

For many, deploying a strategy entails not revealing the strategy, but in Tit-for-Tat, being transparent is maximally useful, because it's immediately predictable by other cooperative strategies; and immediately gamed by defect-laden strategies.

However, Tit-for-Tat is per round, and requires explicit back-and-fourth moves. Reality is seldom this straight-forward, and so, this article will propose Tit-for-Tat+.

**Disclaimer:** this is a working informal framework, not game theory proper.

---

# Tit-for-Tat+

The original perimeters for Tit-for-Tat were limited to turn-based rounds, and binary choices. This model introduces currency as a way to diversify the binary choices, and statuses as a way to remodel rounds. It will also introduce epistemic history to serve as memory. Then, it will show real examples, and show specific limits.

## Currency

Social currency is dependent on costliness and deniability.

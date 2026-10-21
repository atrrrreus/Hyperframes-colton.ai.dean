# Setup: IFVG Model (ReeseTradesNQ)

**Source:** "90% Win Rate IFVG Model (Full Breakdown)" — ReeseTradesNQ — https://youtu.be/mZIGMN4cRi0
**Markets:** NQ (traded) + ES (correlation check)
**Session:** NY open, key 15m opens 9:30 / 9:45 / 10:00 / 10:15 ET
**Note:** 90% win rate is the creator's claim, not verified. Paper-trade / backtest first.

---

## Glossary
- **DOL** — Draw on liquidity (the target price is likely heading to)
- **FVG** — Fair value gap (3-candle imbalance)
- **IFVG** — Inversion FVG: a gap against your bias that price closes *through*
- **AMD** — Accumulation → Manipulation → Distribution
- **PO3** — Power of three: open / manipulation wick / close of each 15m+ candle
- **SMT** — NQ and ES disagree (one makes a new low/high, the other doesn't)
- **CISD** — Change in state of delivery: close past the body of the last opposing candle
- **IRL / ERL** — Internal range liquidity (gaps) / External range liquidity (highs, lows)

---

## Pre-trade checklist (ALL required)

- [ ] **1. A+ DOL** — obvious HTF target (ATH, unfilled 4H gap, old high/low) AND LTF low-resistance liquidity leading to it (or a range sitting right under/over it)
- [ ] **2. HTF FVG** — price is reacting from a **15m or higher** gap
      (fallback: 5m gap on the first leg of the move — 3m only if needed)
- [ ] **3. LTF AMD**
  - [ ] Accumulation: sideways, roughly equal highs/lows, no big wicks
  - [ ] Manipulation: first false break out of range that **sweeps the range high/low** AND **trades into the HTF FVG**
  - [ ] Distribution expected toward the DOL
- [ ] **4. PO3 / time** — a key 15m open happens *before* the manipulation; the manipulation forms that 15m candle's wick (low for longs / high for shorts)
- [ ] **5. True manipulation** — **NQ AND ES both inside an HTF FVG** at the same time (gaps can differ in size/timeframe). Double SMT also qualifies.

## Entry trigger — IFVG
- [ ] Gap against my bias **closed through** on a candle close
- [ ] **Displacement:** full body, small/no wick on the closing side (longs: wick at bottom ok)
- [ ] **Fast:** gap closed quickly (e.g. a 1m gap taking ~7 min to close = weak, skip)
- [ ] Used the **highest-timeframe gap on the current manipulation leg**; if none, scaled down (1m → 30s → 15s) for a tighter entry

## Optional confluence (cherry on top)
- [ ] SMT **inside** the HTF gap (doesn't count elsewhere)
- [ ] CISD on the manipulation leg

## Risk plan
- **Stop:** beyond the manipulation sweep low (long) / high (short)
- **Target:** next obvious liquidity — range highs/lows, unfilled 5m / 4H gap
- **Minimum:** 1:1 RR
- **Entry type:** market entry on the IFVG close

---

## Narrative — which trade type is this? (pick one)

| Type | What it is | Notes |
|---|---|---|
| **A. LTF reversal in HTF continuation** | Pullback in a trend, catch the turn back with the trend | Best RR, most frequent |
| **B. LTF continuation in HTF continuation** | IRL → ERL (gap to highs/lows) | Highest win rate, less frequent — creator sizes up |
| **C. LTF reversal in HTF rebalance** | ERL just swept, trade back to an unfilled gap (IRL) | Conservative target only — take the nearby gap |

---

## Journal template (copy per trade)

```
Date / time:
Instrument: NQ / MNQ
Direction: Long / Short
Trade type: A / B / C
HTF DOL:
HTF FVG used (timeframe):
Key open (9:30 / 9:45 / 10:00 / 10:15):
Sweep of:
ES also in HTF gap? Y / N
IFVG timeframe (1m / 30s / 15s):
Displacement quality (1-5):
SMT: Y / N     CISD: Y / N
Entry:        Stop:        Target:        Planned RR:
Result (R):
Followed every checklist rule? Y / N — if N, which one broke:
Screenshot:
Lesson:
```

# Concept: OTE — Optimal Trade Entry — Nq Cam

**Source:** "OTE: Finding Better Pricing for Your Entries" — Nq Cam — https://www.youtube.com/watch?v=xlWRHxrIdII
**Plugs into:** Entry location, before the IFVG trigger in `01-ifvg-model.md`. Uses dealing ranges from `04-find-the-dol.md` and PO3 from `02` / `06`.

> **Core idea:** OTE is a **measuring tool for better pricing**, NOT a bias. Price touching OTE means nothing on its own — you still need DOL + meaningful PDAs + displacement.

---

## The measurement
- **OTE zone = 62% – 79% retracement** of the range you measure.
- **70.5% = "sweet spot"** (the midpoint / consequent encroachment of the OTE zone).
- Fib settings: 0, 0.5 (EQ), 0.62, 0.705, 0.79, 1 (plus any extensions you use).

---

## Two ways he uses it

### 1. Dealing-range OTE
- Mark the HTF / session dealing range (e.g. the range a **4H candle's PO3** has set: open → manipulation → distribution started).
- At market open, look for price to retrace into **OTE of that range**, then continue toward the DOL.
- Example: 6am 4H candle manipulated higher and started lower toward an unmitigated 4H gap → at 9:30 price manipulated up into OTE, respected the 70.5% + true day open + 30m bearish FVG + up-close candle (order block) → **1m IFVG** → continuation to the sell-side.

### 2. Displacement OTE
- After a liquidity sweep / HTF PDA interaction, price **displaces**. Mark that displacement leg: **from the high-resistance swing (the one that swept liquidity) → to the displacement's range high/low.**
- Wait for the retrace into OTE of that leg, aligned with PDAs → displacement / IFVG → enter toward the DOL.
- **Repeat it for every new displacement leg** — in a trending day each new swing gives another OTE continuation.
- **Great for when you missed the first reversal entry** — the OTE retrace gives a second chance.

---

## Must-align checklist for an OTE entry
- [ ] Clear **DOL** in the trade direction
- [ ] OTE overlaps **meaningful PDAs** (FVG, order block, rejection block, key opening prices — true day / 8:30 / weekly open)
- [ ] **Displacement away** from OTE (e.g. 1m IFVG) confirms it
- [ ] Range drawn from **real liquidity points** (HR swing → displacement extreme), not random swings

---

## OTE vs. equilibrium (50%) — when to wait for the deeper level
- **EQ / discount-premium is often enough** when PO3, PDAs and liquidity already line up at a shallower retrace.
- **Wait for OTE when the move to EQ isn't time-aligned:** a reaction at a random time with no PO3 behind it is weak — expect a key open (e.g. 8:00 / 8:15) to provide the real manipulation deeper, into OTE.
  - Example: EQ reaction failed; 8:00 open added liquidity above, 8:15 open swept the low **inside OTE**, then displaced → the valid entry.
- Don't force every setup to reach OTE, and don't redraw swings to make OTE "fit" a move — that's what hurts you.

---

## Add to your journal template
```
OTE type: Dealing range / Displacement
Range drawn from: ____ (HR swing) to ____
Entry level hit: EQ / 62% / 70.5% / 79%
PDAs inside OTE: ________
Displacement confirmation: IFVG TF ____
Time-aligned (PO3 / key open)? Y / N
```

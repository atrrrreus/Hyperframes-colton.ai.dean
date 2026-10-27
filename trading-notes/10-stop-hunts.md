# Concept: Stop Hunts / Internal Manipulation — Nq Cam

**Source:** "You Aren't Wrong. You're Just the Liquidity." — Nq Cam — https://www.youtube.com/watch?v=wCbEn_DjPe8
**Plugs into:** Step 3 (LTF AMD) + entry trigger in `01-ifvg-model.md`. Links to SMT (`03`, `08`), PO3 (`02`, `06`), rejection blocks (`09`).

> **Core idea:** after a big HTF sweep, retail jumps in too early and their stops become the fuel. Expect a **stop hunt** to take those stops **before** the real distribution — or you become the liquidity.

---

## What a stop hunt is
- A push into the pool where stop-losses rest (just beyond a fresh low/high), triggering them to create the order flow needed for the real move.
- **Story:** price sweeps major sell-side inside an HTF gap → retail longs immediately ("support held") → their stops sit right below → price re-sweeps those stops → **then** distributes higher. Meanwhile breakout-shorts entered on that re-sweep put **more** stops above = extra fuel for the move up.
- **Accumulation after HTF manipulation is good:** the sideways range builds stops on both sides; the sweep of one side is the stop hunt, the other side is the target.
- Market cycle: **accumulate (generate liquidity) → manipulate (fill orders) → distribute (seek DOL).** You only want to trade the distribution.

---

## When a stop hunt is REQUIRED
- [ ] Catching a **reversal right after HTF manipulation** (major sweep)
- [ ] **No clear accumulation** has formed yet
- ❌ **Don't catch a falling knife:** after a fast ~300pt dump with no accumulation, an IFVG long = you're asking to be the manipulation.

## When it's NOT required
- The **initial manipulation already swept a clear accumulation range** (taps the HTF gap + sweeps internal liquidity + low-resistance liquidity on the other side) → the first IFVG after the HTF gap tap is valid even without an internal re-sweep.
- ❌ Bad version: just a gap tap → immediate inversion, **no accumulation** being manipulated → likely gets swept.
- **Unsure if it's breakout or more liquidity-building?** Wait for a **CISD** to confirm price is taking new highs/lows and flushing.

---

## Time + price alignment (PO3)
- **Best stop hunts = provided by a new HTF candle open** (that candle's PO3 manipulates, then distributes).
- **Entry trigger right before a new HTF candle opens? Ask: is any criterion still missing that the new open could provide?**
  - **Yes → fade it.** E.g. long trigger at **10:28**, and at 10:30 an **unmitigated 30m gap sits at your stop** → the new candle will likely manipulate into it and stop you out first.
  - **No → still take it.** E.g. long trigger at **10:13**, nothing missing → the 10:15 PO3 just continues the 10:00 PO3's distribution.

---

## SMT can BE the stop hunt
- If NQ doesn't re-sweep the high but **ES does (bearish SMT)**, that counts as the stop hunt — **as long as both assets were already in distribution** (each swept liquidity inside its own HTF bearish PDA).
- Example: NQ took an ITH inside a 4H bearish FVG, ES took its ITH inside a 1H bearish FVG → ES re-sweep = stop hunt → short to the unmitigated 30m bullish FVG.

---

## Stop hunts are fractal — use the CURRENT manipulation leg
- On the 3m you may only see one big manipulation leg; drop to **30s** and there may be a smaller, newer leg that manipulated the previous one (e.g. with an SMT).
- Take the **highest-timeframe inversion of the CURRENT (newest) manipulation leg** — e.g. a 30s IFVG instead of waiting for the 3m one.
- Valid if the 30s inversion **doesn't close inside** the still-unmitigated 3m gap. Option: take risk off / BE at that 3m gap, hold the rest to the main target (e.g. unmitigated 1H gap).

---

## Add to your journal template
```
HTF manipulation happened? Y / N — then stop hunt seen? Y / N
Clear accumulation that got manipulated? Y / N
Stop hunt provided by: NQ re-sweep / ES SMT / new HTF candle open (time: ____)
Entry near a new HTF candle open? Y / N — any missing criteria it could provide? Y / N
Manipulation leg used: full / current LTF leg (TF ____)
Caught a falling knife (no accumulation)? Y / N  (if Y = rule break)
```

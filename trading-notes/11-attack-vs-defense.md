# Concept: Weighing PDA Attack vs. Defense — Nq Cam

**Source:** "Weighing PDA's Attack vs Defense" — Nq Cam — https://www.youtube.com/watch?v=tu6TOfQNQWA
**Plugs into:** Trade validation, stop placement and break-even management in `01-ifvg-model.md`. Builds on "a gap attacks and defends" from `04-find-the-dol.md`.

> **Core idea:** every PDA **attacks** liquidity on one side and **defends** liquidity on the other. Before a trade, weigh them: **is the PDA behind your stop (your attack) stronger than whatever defends your target?**

---

## The rules
1. **Higher timeframe beats lower timeframe.** A 4H attack should beat a 5m defense; a 5m defense won't hold against it.
2. **Low resistance (LR) gets taken; high resistance (HR) holds** — unless its own PDA reaches its objective first (e.g. taps an unmitigated gap on the other side).
3. **A trade is good when your stop is protected by something STRONGER than what's defending your target.**
4. **A PDA defending LR is weak** — it usually gets run through.

---

## Trading between high-resistance liquidity (normally avoided)
**OK to trade when attack > defense:**
- Range: low inside a 1H gap (HR) ↔ high inside a 30m gap (HR). Price taps the 30m bearish gap → 1m IFVG short.
- Valid because the 30m now **attacks the unmitigated 4H gap below (LR)**, so the target is really **LR disguised as HR**, while your stop sits behind a strong HTF level.

**NOT OK when attack < defense:**
- Same range, but you're shorting off a **5m** bearish gap with an **unmitigated 30m gap above your stop**.
- A 5m won't defend that LR 30m gap → expect price to run your stop into the 30m, *then* move to the DOL.
- Same for a 5m bearish gap trying to beat a **1H ITL (HR)** below — it will likely get raided instead.

---

## Real example
- Price taps a **2H bullish FVG**; unmitigated **4H bullish gap below** (LR, the DOL) and unmitigated **bearish gaps above**.
- The 2H low is HR **until** price reaches an objective above (an unmitigated bearish PDA) to fuel the move down.
- ❌ First short: 5m bearish gap → IFVG. Bad: 5m attacking a 2H HR low, **defending LR**, with an unmitigated **15m gap at the stop** → stopped out.
- ✅ Price then tapped the **15m bearish FVG** (the new objective) → short from there → ran to the 4H gap.

---

## Break-evens — the costly mistake
- **Don't move to BE at a minor LTF gap or internal swing** that defends LR. If a **4H bullish gap is attacking LR** above, a 5m gap in the way won't stop it — BE there just gets you stopped before the trade hits TP.
- **Move to BE only where price could genuinely reverse** — e.g. the next **intermediate-term low/high (HR)**.
- If you'd go BE at a meaningless level, you're not confident in the DOL → **don't take the trade.**

---

## Quick pre-trade test
- [ ] What PDA is behind my stop (my attack)? TF: ____
- [ ] What is defending my target? TF: ____
- [ ] Attack ≥ defense (HTF vs LTF, HR vs LR)? Y / N
- [ ] Any **unmitigated gap at/near my stop** that price may want first? Y / N (if Y → wait)
- [ ] Scared mid-trade? → check the **higher timeframe**: big rejection wick at your stop + attacking LR = hold.

---

## Add to your journal template
```
Attack (PDA behind stop): ____ TF ____
Defense (PDA in front of target): ____ TF ____
Attack stronger than defense? Y / N
Unmitigated gap at stop? Y / N
BE moved at: ____ — was it a real HR level? Y / N
Stopped at BE then hit TP? Y / N
```

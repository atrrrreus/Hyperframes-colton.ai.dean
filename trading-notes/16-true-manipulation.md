# Concept: TRUE Manipulation — the WHY behind distribution — Nq Cam

**Source:** "TRUE manipulation (the WHY behind distribution)" — Nq Cam — https://www.youtube.com/watch?v=wx0R6cZk6dM
**Plugs into:** Step 5 of `01-ifvg-model.md`. Same rule as `08-smt-correctly.md`; compare with Reese's exceptions in `03-smt-advanced.md`.

> **Core question before every trade:** *Are BOTH NQ and ES in a spot of distribution?*
> Each must have **swept some liquidity inside some HTF PDA**. They do **not** need the same liquidity, the same PDA or the same timeframe.

---

## Why it matters: it stops you getting stop-hunted
- If only one asset has a reason to move, the other has **no reason to distribute**. It is just as likely to go grab its own liquidity first.
- That grab **is the stop hunt**: you get stopped out, then the real move happens without you.
- **Know the "why" for both assets.** "NQ swept a low in a 4H gap" isn't enough if ES is sitting between liquidity on both sides doing nothing.

---

## SMT inside true manipulation
- ✅ **Good SMT:** both assets already swept liquidity inside an HTF PDA, and one of them made the lower low/higher high. The SMT is **extra confluence**.
- ❌ **Bad SMT:** the SMT exists because **one asset did nothing** (no sweep, no PDA). Using it lets you skip the requirement → likely stop-hunted.

---

## Examples
**✅ Valid long (to all-time highs):**
- NQ: made relative equal lows but **swept sell-side inside a 30m bullish gap** that held.
- ES: **swept its sell-side inside its HTF gap** → bullish SMT.
- Both in distribution + SMT as a bonus → entry model → ran to ATH.
- (If NQ had *disrespected* its 30m gap, you'd want its sell-side taken first.)

**❌ Invalid long → ✅ valid one later:**
- ES was inside a 5m bullish gap near ATH; **NQ hadn't swept anything or tapped a PDA**. An SMT + inversion there = bad.
- Then NQ made a **stop hunt** into its 5m gap (swept liquidity). Now both were in distribution → **30s IFVG** → ran to the DOL.

---

## 3-question check (every trade)
- [ ] NQ swept liquidity inside an HTF PDA? (which: ____)
- [ ] ES swept liquidity inside an HTF PDA? (which: ____)
- [ ] If there's an SMT, does it **replace** either of the above? → if yes, **no trade**

## Add to your journal template
```
NQ reason to distribute: ____ liquidity + ____ PDA
ES reason to distribute: ____ liquidity + ____ PDA
Both in distribution? Y / N
SMT: none / bonus / used to skip a requirement
Stopped out, then price ran to target? Y / N  (check: was true manipulation missing?)
```

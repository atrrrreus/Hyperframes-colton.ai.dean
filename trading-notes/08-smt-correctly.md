# Concept: How to Correctly Use SMT — Nq Cam

**Source:** "How to CORRECTLY use SMT" — Nq Cam — https://www.youtube.com/watch?v=apeJHeRLqHc
**Plugs into:** Step 5 (true manipulation) + optional confluence in `01-ifvg-model.md`. Read alongside `03-smt-advanced.md`.

> **Core rule: an SMT ADDS confluence — it never REPLACES required criteria.**
> If you're using an SMT to ignore a missing requirement, the setup is bad.

---

## The required criteria (before an SMT matters)
**Both NQ and ES must be "in a spot of distribution"** (= true manipulation):
- Each has **swept liquidity** AND is **inside an HTF PDA** in the trade direction.
- They do **not** need to be the same PDA or the same liquidity — each just needs its own reason to move.

---

## Bad vs. good SMT setups

| Setup | Valid? | Why |
|---|---|---|
| SMT + IFVG toward a nice low-resistance pool, but **neither** asset swept liquidity or hit a PDA | ❌ | No reason for either to distribute |
| **ES** swept buy-side inside a 1H gap, **NQ did nothing** (no sweep, no PDA) → bearish SMT | ❌ | NQ has no reason to go lower — SMT is being used to skip the requirement |
| **Both** NQ and ES swept liquidity inside their own HTF bearish PDAs (e.g. NQ in a 15m bearish gap) + SMT | ✅ | Requirements met; the SMT is a bonus (trade valid even without it) |

---

## Where he uses SMT most: after HTF manipulation (the stop hunt)
1. NQ **and** ES both sweep liquidity inside an HTF PDA (requirement met).
2. Expect an internal **stop hunt / re-manipulation** before the real move.
3. One asset re-sweeps the high (e.g. NQ), the other doesn't (ES) → **SMT**; the one that didn't re-sweep is **leading**.
4. The leading asset does **not** need to re-sweep — it already did its job in step 1.
5. Enter on the **IFVG** toward the DOL.

---

## Mindset
- **Stop pattern trading.** An IFVG, SMT, breaker, order block, mitigation block — each is meaningless without **narrative + context** (DOL, true manipulation, PO3).
- Using SMTs badly is worse than not using them at all.

---

## ⚠️ Note vs. file 03 (Reese — "SMT advanced")
- **Nq Cam (this video):** never skip "both pairs in distribution" because of an SMT.
- **Reese (03):** "true manipulation" (both in an HTF FVG) *can be voided* by specific SMT types (double SMT, ITL/ITH SMT, unmitigated-FVG SMT).
- They partly overlap (in Reese's version the lagging pair still sweeps internal lows/highs), but the strictness differs. **Track this in your journal** to see which rule works better for you.

---

## Add to your journal template
```
NQ: swept liquidity? Y / N   inside HTF PDA? Y / N (which: ____)
ES: swept liquidity? Y / N   inside HTF PDA? Y / N (which: ____)
SMT present? Y / N — type: at HTF manipulation / post-manipulation stop hunt
Leading asset: NQ / ES
Was the SMT used to SKIP a requirement? Y / N  (if Y = rule break)
```

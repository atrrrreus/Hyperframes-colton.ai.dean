# The Complete Trading Model — IFVG / PO3 / True Manipulation (NQ & ES)

**What this is:** one self-contained guide to everything studied across 17 videos/reels from two creators, **ReeseTradesNQ** and **Nq Cam**. It's written so a person or an AI who has never seen the videos can understand the whole model, the reasoning behind each rule, and how the pieces fit together.

**How it was made:** each video was transcribed (or, for one Instagram reel, read frame by frame) and its teaching was written up faithfully, in plain language. Nothing here is invented. Where the two creators **disagree**, both views are shown. Short phrases in quotes ("wicks do the damage, bodies tell the narrative") are the creators' own sayings.

**Disclaimers (from the creators too):**
- Win rates mentioned (Reese: "90%" for the IFVG model, "80%+" for picking the DOL) are **their claims, not verified**.
- Both creators repeatedly say: **don't take their word for it — backtest, journal, then paper-trade** before risking money.
- Most concepts trace back to **ICT (Inner Circle Trader)** teachings; Nq Cam credits ICT directly.

---

## Contents
- [Part 0 — Glossary](#part-0--glossary-read-first)
- [Part 1 — The big picture in one paragraph](#part-1--the-big-picture)
- [Part 2 — The core model (IFVG model, step by step)](#part-2--the-core-model-the-ifvg-model)
- [Part 3 — Finding the Draw on Liquidity (DOL)](#part-3--finding-the-draw-on-liquidity-dol)
- [Part 4 — Ranges, conditions, resistance](#part-4--ranges-conditions-and-resistance)
- [Part 5 — Time: PO3, OXXC and key opens](#part-5--time-po3-oxxc-and-key-opens)
- [Part 6 — True manipulation and SMT](#part-6--true-manipulation-and-smt)
- [Part 7 — Stop hunts](#part-7--stop-hunts--internal-manipulation)
- [Part 8 — Entries: IFVG, OTE, rejection blocks, sponsorship](#part-8--entries-and-entry-locations)
- [Part 9 — Trade management: attack vs defense, stops, break-even](#part-9--trade-management-attack-vs-defense-stops-break-even)
- [Part 10 — What NOT to trade (pattern trading)](#part-10--what-not-to-trade-pattern-trading)
- [Part 11 — Where the two creators disagree](#part-11--where-the-creators-disagree)
- [Part 12 — Daily routine + full checklist](#part-12--daily-routine--full-checklist)
- [Part 13 — Master journal template](#part-13--master-journal-template)
- [Part 14 — Source list](#part-14--source-list)

---

## Part 0 — Glossary (read first)

| Term | Meaning |
|---|---|
| **NQ / ES** | Nasdaq-100 futures (traded) / S&P 500 futures (used as the correlated "second asset" for confirmation) |
| **HTF / LTF** | Higher timeframe (15m and above in this model) / lower timeframe (5m and below, down to 30s and 15s) |
| **Liquidity** | Clusters of resting orders (stop-losses, breakout orders) above swing highs (**buy-side liquidity, BSL**) and below swing lows (**sell-side liquidity, SSL**) |
| **DOL** | **Draw on liquidity** — the liquidity/level price is most likely heading to next |
| **FVG** | **Fair value gap** — a 3-candle imbalance where the 1st and 3rd candles' wicks don't overlap. Bullish FVG = gap left by an up move; bearish = by a down move |
| **IFVG** | **Inversion FVG** — an FVG that price **closes through** in the opposite direction. A bearish gap closed above = bullish signal (and vice versa). It "disrespects the opposing bias" |
| **PDA** | **PD array** (premium/discount array) — any key level price reacts to: FVG, order block, breaker, rejection block, BPR, mitigation block, key opens |
| **BPR** | Balanced price range — where a bullish and bearish FVG overlap |
| **Order block** | Last opposite-colour candle before a strong move (e.g. last up-close candle before a drop) |
| **Rejection block** | Zone between a swing's extreme **body** (open/close) and its extreme **wick** (see Part 8) |
| **CE / mean threshold** | **Consequent encroachment** — the 50% midpoint of a gap or block |
| **Respect / disrespect** | A PDA is **respected** when price reacts away from it and bodies don't close through; **disrespected** when bodies close through it |
| **Displacement** | A strong, fast, full-bodied move — shows intent |
| **AMD** | **Accumulation → Manipulation → Distribution** (sideways build-up → false move/sweep → real move) |
| **PO3** | **Power of three** — every candle (1m to yearly) opens, makes one false-direction wick (manipulation), then moves the real direction and closes. Same idea as AMD applied to a single candle and time |
| **OXXC** | Shorthand for a candle's sequence: **O-L-H-C** (bullish: open, low first, then high, close) or **O-H-L-C** (bearish) |
| **Key opens** | Opening prices of important candles: **midnight (true day open)**, **6:00 (4H)**, **8:30**, **9:30 (cash open)**, **9:45**, **10:00 (new 4H)**, plus weekly/monthly opens. All times New York |
| **Premium / discount (price)** | Above / below the 50% (**equilibrium, EQ**) of the current dealing range. Shorts from premium, longs from discount |
| **Premium / discount (time)** | Above / below the **open** of the current HTF candle |
| **Dealing range** | The range you're measuring (high to low) for premium/discount, EQ, OTE |
| **OTE** | **Optimal trade entry** — the 62%–79% retracement zone of a range; 70.5% is the "sweet spot" |
| **SMT** | **SMT divergence** — NQ and ES disagree: one makes a new high/low, the other doesn't |
| **CISD** | **Change in state of delivery** — a close beyond the body of the last opposite-direction candle on the manipulation leg |
| **True manipulation** | **Both** NQ and ES have swept liquidity inside an HTF PDA (each "in a spot of distribution") |
| **HR / LR** | **High-resistance** liquidity (a swing that swept liquidity, hit an HTF PDA and led to distribution — hard to take) / **low-resistance** liquidity (failure swings with none of that — easy to take) |
| **IRL / ERL** | Internal range liquidity (gaps inside the range) / external range liquidity (range highs/lows) |
| **ITH / ITL** | Intermediate-term high / low (a meaningful swing, bigger than internal swings) |
| **Stop hunt** | A quick re-sweep of the freshly made high/low to take the stops of traders who entered too early, before the real move |
| **Sponsored** | A gap/move that came directly from **HTF manipulation** — so it's backed by the bigger move |
| **Market maker model (buy/sell model)** | The fractal cycle: a **sell side of the curve** (price runs lower to a sell-side objective, building liquidity above), then a **buy side of the curve** (price runs back up taking it) — or the reverse |
| **Red folder news** | High-impact economic news (e.g. CPI) — often released at 8:30 |

---

## Part 1 — The big picture

Every trading day, you first decide **where price is going (the DOL)** using higher-timeframe gaps that are being respected or disrespected. Then you wait for price to **fake out the other way** — sweep liquidity **into a higher-timeframe PDA**, ideally **at a key time** (a candle open), with **both NQ and ES** doing it ("true manipulation"), often followed by a **stop hunt**. Finally you enter on a **lower-timeframe IFVG with displacement**, stop beyond the manipulation, target the low-resistance liquidity toward the DOL — and you **skip every setup that's just a pattern without that story behind it**.

---

## Part 2 — The core model (the IFVG model)
*Source: ReeseTradesNQ — "90% Win Rate IFVG Model (Full Breakdown)"*

### Required criteria (all of them)
1. **A+ draw on liquidity**
   - A clear HTF target (all-time highs, an unfilled 4H gap, an old high/low), **and**
   - On the LTF, **low-resistance liquidity leading toward it**. A sideways range sitting right under/over the target also counts.
2. **An HTF fair value gap where the move starts**
   - **15m or higher** preferred.
   - If none: a **5m** gap (3m at a push) on the **first leg** of the move — any 5m gap on that leg counts as "sponsored" by the HTF move.
3. **LTF AMD** (the backbone)
   - **Accumulation:** slow sideways movement, roughly equal highs and lows, no aggressive wicks.
   - **Manipulation:** the **first false move out of the range** that **both sweeps the range's high/low AND trades into the HTF gap**.
   - **Distribution:** fast move toward the DOL, leaving new gaps/order blocks behind.
4. **PO3 timing** — called "the biggest win-rate booster"
   - Every 15m-or-higher candle (9:30, 9:45, 10:00, 10:15…) has its own PO3.
   - Best case: a **key open happens right before the manipulation**, so the manipulation forms that candle's wick, and you trade in the direction the candle will close.
5. **True manipulation** — **both NQ and ES inside an HTF gap** at the same time (they can be different gaps/timeframes). Reese says a **double SMT** can also satisfy this (see Part 6 and Part 11).

### Entry trigger: the IFVG
- A gap **against your bias** gets **closed through** on a candle close.
- **Displacement required:** full body, small/no wick on the closing side (for a long, any wick should be at the **bottom**).
- **Speed matters:** if a 1m gap takes ~7 minutes to close through, that shows no intent — the LTF is "beating" the HTF, and you may be on the wrong side.
- **Which gap:** the **highest-timeframe gap on the current manipulation leg**. If there isn't one, scale down (1m → 30s → 15s). A smaller inversion gives an entry closer to the stop → better reward-to-risk.
- The idea: the HTF should now "burn through these gaps as if they don't exist."

### Optional confluence ("cherry on top")
- **SMT** — only counts **inside the HTF PDA**, not in a random spot.
- **CISD** — close above/below the body of the last opposite candle on the manipulation leg (an IFVG with extra confirmation).

### Risk
- **Stop:** beyond the manipulation sweep.
- **Target:** the obvious liquidity ahead (range highs/lows, unfilled 5m/4H gap).
- **Execution:** market entry on the IFVG close; aim for **at least 1:1**.

### The three trade types (market maker model narrative)
| Type | What it is | Notes |
|---|---|---|
| **A. LTF reversal inside HTF continuation** | Pullback in a trend; catch the turn back with the trend | Best R:R, most frequent |
| **B. LTF continuation inside HTF continuation** | From internal liquidity (gap) to external (highs/lows) — IRL → ERL | Highest win rate, less frequent — Reese sizes up on these |
| **C. LTF reversal inside HTF rebalance** | External liquidity just swept; trade back to an unfilled gap inside the range (ERL → IRL) | Take the conservative nearby target only |

### Reese's three examples
1. **Long:** 10:00 open drove down into a 4H gap and swept the range lows; ES also in the same 4H gap; 1m IFVG with a bottom wick and strong body → target accumulation highs.
2. **Short:** the 10:00 high was *not* valid (no true manipulation — ES didn't confirm). 10:15 open swept higher with an SMT inside a 15m gap → now valid → 1m IFVG + CISD → ran to the 4H gap.
3. **Long:** no 1m or 30s gap available → dropped to a **15-second IFVG** → target the unfilled 5m gap (conservative, rebalance trade).

---

## Part 3 — Finding the Draw on Liquidity (DOL)

### 3.1 The 4-step daily process
*Source: ReeseTradesNQ — "How to Always Find the Correct DOL"*

1. **Identify the possible DOL**
   - **A. Where are we delivering FROM?** Just swept sell-side (ideally with an SMT vs ES) → idea = buy-side. Just swept buy-side → idea = sell-side. If unclear, look at which side price is trending toward.
   - **B. Which gaps are respected vs disrespected?** Bullish DOL is **confirmed** when bullish gaps are respected and bearish gaps are disrespected (closed through) — and vice versa.
   - **Key point:** step A only gives the *idea*; the DOL is **confirmed by what the imbalances (gaps) are doing**.
2. **Set HTF conditions** — a **condition = any 15m+ FVG**. Every gap **attacks** one side's liquidity and **defends** the other's. Build an if-this-then-that:
   - **Scenario 1:** condition respected → DOL in its direction.
   - **Scenario 2:** condition disrespected → opposite DOL.
3. **Identify the HTF range type** (HR vs LR, LR vs LR, HR vs HR — Part 4) — it decides which conditions to use and how.
4. **LTF confirmation** — a condition is confirmed respected when the **opposing LTF bias is disrespected**: an **LTF IFVG** (or sometimes a CISD). Example: price trades into a 15m bullish gap, leaving a 30s bearish gap. If that 30s gap holds → the 15m is failing. If it gets inverted → the 15m is respected → buy-side confirmed as DOL.

### 3.2 The CURRENT DOL matters more than daily bias
*Source: Nq Cam — "How we can identify our CURRENT DOL..."*

- Daily bias is **overemphasized**. Day traders hold for minutes to an hour, so the real question is: **"What is my current DOL, and how will price get to the bigger target?"**
- **The market maker model is fractal.** On the **sell side of the curve**, price sweeps internal liquidity and keeps delivering from HTF bearish PDAs. After major sell-side is taken there's displacement up and HTF bullish PDAs start being respected — only *then* call it the **buy side of the curve**, where price retraces into bullish PDAs to fuel each leg up and takes back all the liquidity built on the way down.
- **"Heavy displacement = seeking an objective."** Displacement also **creates imbalances** (new liquidity behind it).
- **Once an objective is hit, expect a rebalance** into the unmitigated PDA left behind — **even if bigger targets remain in the same direction.** That rebalance is the fuel for the next leg.
- Track the chain: **sell-side objective met → sponsors a move up → buy-side objective met → sponsors a move down → …** Always ask: **"Which move is currently being sponsored, and where is it going?"**
- **Bullish daily bias ≠ only longs.** If price just swept internal buy-side **inside an HTF bearish PDA** and there are **unmitigated bullish PDAs below**, be **short-term bearish** until that PDA is reached; then:
  - rejected with displacement → long toward the bigger DOL;
  - disrespected → bias can flip bearish.

**Trade filters from Nq Cam's examples:**
- Don't long until price reaches at least the **discount** (below 50%) of the range that sponsored the move — shallow pullbacks haven't grabbed enough liquidity.
- Skip setups with **no internal AMD** (e.g. a tiny 3m IFVG right after a hard dump = "catching a falling knife"). Wait for internal accumulation → manipulation → distribution, or very obvious displacement.
- Don't short into **deep discount + HTF bullish PDAs being respected** (e.g. a 4H order block / 1H bullish BPR), even if the LTF short looks clean.
- Don't long into a **wall of unmitigated bearish gaps** right above.
- **"Wicks do the damage, bodies tell the narrative"** — judge respect/disrespect by candle **bodies**.

---

## Part 4 — Ranges, conditions and resistance

### 4.1 High vs low resistance
*Source: ReeseTradesNQ — DOL video*
- **High-resistance (HR) high/low:** swept liquidity **+** traded into an HTF FVG **+** led to distribution (left aligned PDAs behind). Hard to break.
- **Low-resistance (LR) high/low:** failure swings — no sweep, no HTF gap. Easy to take.

### 4.2 The three range types
| Range | How to trade it | Conditions to use |
|---|---|---|
| **HR vs LR** (easiest) | Trade **away from HR, toward LR** | The 15m+ FVG on the **recent expansion leg** out of the HR side. Respected → target LR. Disrespected → expect a return to the HR side (no flip yet) |
| **LR vs LR** | (a) Wait for a **sweep of one side into its condition**, then target the opposite LR side; (b) or wait for an **expansion out of the range** — condition closed through + a **new 15m+ gap** opens → trade the 15m continuation to the next HTF DOL. **Never trade while still inside the range** | An HTF gap beyond each side (e.g. 4H above and below) |
| **HR vs HR** (hardest) | Mark **EQ**. Find a **bearish gap in premium** and a **bullish gap in discount** (only needs to be partly there). Bearish day: premium bearish gap respected + discount bullish gap disrespected → range low. Bullish day: the opposite → range high | The two gaps either side of EQ |

### 4.3 Navigating LTF entries inside these conditions
*Source: Nq Cam — "Navigating LTF Entries in Different HTF Conditions"*

**Core question everywhere: "What is currently PROTECTED, and what is currently LOW RESISTANCE?"** Stop behind what's protected; target the current LR — even if the external range levels say otherwise.

- **HR vs HR:** react to **internal** conditions (15m/30m/1H gaps formed inside the range). A bullish internal gap hit and strongly rejected → it's protected → target the **nearest unmitigated bearish gap above** (that's the current LR). At that bearish gap: rejected → expect the range low; disrespected → expect the range high. *Example:* weekly bullish FVG → 4H bearish FVG rejected → 4H bullish FVG tapped, leaving an unmitigated 1H bearish FVG → long to the 1H gap → 1H rejected → range low.
- **LR vs LR:** same — e.g. a 1H bullish FVG inside the range, if hit and strongly rejected, protects the low below it (nothing attacks it), so target LR above first; if disrespected, go short-term to the LR below. ❌ Don't use an **unsponsored, premium LTF gap (e.g. 5m)** that only defends HTF low resistance. ✅ Valid: a 3m bearish FVG respected while the bullish side gets inverted, a 3m ITH protecting the stop vs quadruple equal lows leading to a 1H gap.
- **If you can't tell the current DOL → don't trade.** Wait for HTF manipulation. Some days the information never comes. "Put your ego aside."
- **All-time highs / strong trend:** default is **trade with the trend**. Lots of liquidity below doesn't mean short.
  - **Longing ATH:** react off **HTF (e.g. 30m) bullish PDAs** being strongly rejected, even in premium. *Example:* 10:30 PO3 added liquidity above, manipulated down into a 30m bullish FVG, LTF bearish disrespected → long → new highs. Still needs full criteria — an unsponsored 5m at ATH is a pattern trade.
  - **Shorting ATH** only when the HTF turns: HTF bearish PDAs created and respected, HTF bullish PDAs disrespected, the next HTF bullish PDA / major sell-side identified as target, ITH swept inside a 1H bearish PDA + displacement lower.

---

## Part 5 — Time: PO3, OXXC and key opens

### 5.1 OXXC and time premium/discount
*Source: Nq Cam — "Understanding OXXC & PO3 — a fractal framework for context."*

| Candle | Sequence |
|---|---|
| **Bullish (O-L-H-C)** | Open → manipulate **lower into an HTF PDA** → entry model → expand to buy-side DOL → retrace → close |
| **Bearish (O-H-L-C)** | Open → manipulate **higher into an HTF PDA** → entry model → expand to sell-side DOL → retrace → close |

- This is fractal: 1m up to yearly.
- **Time premium/discount** is measured from the candle's **open**: below the open = time discount (longs); above = time premium (shorts). Best entries have **time and price discount** (or premium) together.
- **PO3 is irrelevant without context:** a candle usually prints both a top and bottom wick — the one that counts is the one that **trades into an HTF PDA, sweeps internal liquidity** (ideally with SMT), leaves **low-resistance liquidity** on the other side and **agrees with the narrative**. A wick hitting no PDA just adds to accumulation. ES can supply the manipulation (if NQ's wick hits no PDA but ES sweeps with an SMT).
- **Rules:**
  1. **Don't BE the manipulation** — if the current PO3 candle hasn't printed its wick in your stop's direction yet, you can get swept to form it. Wait for the wick into an HTF PDA first.
  2. **Stacked PO3s** (15m + 30m + 1H all manipulating into PDAs the same way) = highest probability (his example: 2m IFVG → full TP).
  3. **Ignore manipulation that fights the narrative** (e.g. 9:30 sweeps sell-side, but the target above is an HR high inside an HTF bearish PDA while lots of LR sits below → skip the long; wait for the wick into the bearish PDA → 1m IFVG short).
  4. **Re-check at each new PO3 open** (e.g. a new 15m) while a bigger candle (30m) is still open.

### 5.2 Key opening prices — what each one frames
*Source: Nq Cam — "How to CORRECTLY Use Key Opening Prices (Time-Based PO3)"*

| Open (NY time) | Frames |
|---|---|
| **00:00 true day open** | The whole daily candle/profile |
| **08:30** | NY morning delivery — **most important on red-folder news days at 8:30** |
| **09:30** | The cash session |
| **10:00** | Starts a new 4H candle; another NY-morning reference |

- **Opens give LOCATION, not BIAS.** Bias comes from the HTF DOL.
- Bullish bias → want manipulation **below** the relevant open(s) into liquidity/a PDA, then confirmation. Bearish → **above**. The more opens price is on the "right" side of, the stronger the location.
- **Daily candle reading:** midnight open → rally into premium and sweep buy-side → likely the daily **open-high** of a bearish day. Once the daily objective is **already met**, stop looking for more continuation and expect a **retrace toward the close**.
- Opens act as **reference levels** price returns to — watch bodies closing through them.
- **Mistake shown:** shorting above the 9:30 open into a bearish PDA when price was already in deep discount and the daily bearish objective was done → failed; the long from discount was correct.
- **CPI example:** 8:30 news candle manipulated into a 1H bullish FVG (taking sell-side), then rallied; at 9:30 price dipped below the 9:30 and 8:30 opens into discount + a 30m bullish PDA → **15-second IFVG** → long. Later, below the 10:00, 9:30 and 8:30 opens inside a bullish PDA → more upside.
- **Indicator used:** "ICT Killzones & Pivots" by TFO on TradingView — Settings → Inputs → opening prices → add the ones you want.

### 5.3 The WHY behind key opens
*Source: Nq Cam — "Time Shapes the Story Price Tells | The Why Behind Key Opens"*

**Ask of every open:**
1. **What has this PO3 done?** (opened / manipulated / distributed?)
2. **What is still unfinished?**
3. **Where is price likely delivering next to finish it?**

**Two uses:**
- **Continuation reference point:** the HTF candle (e.g. **6:00 = 4H**) has **opened → manipulated → started distributing**, but its DOL is still intact → on lower-TF PO3s (9:30, 9:45, 10:00), look for a **retrace to that open** (time EQ), ideally with price premium/discount + a PDA + a stop hunt. ❌ If the candle **never manipulated** on the other side of its open, don't use its open for continuation.
- **Draw on liquidity:** a candle opened and **never manipulated on one side** of its open → that open is a **target** (a later PO3 should go provide the missing manipulation). He rarely targets opens otherwise.

**Examples:**
1. 6:00 went straight down with no wick above its open → 9:30 took major sell-side (HTF manipulation) → **9:45 opened, swept lower (stop hunt), turned up**, leaving a rejection block → 10:00 retraced exactly into **9:45's open + rejection block** + ES bullish SMT → continued higher toward **6:00's open** (the missing manipulation).
2. *His short:* 6:00 swept liquidity in a bearish PDA and started lower, sell-side still intact → at the open, price rallied into **6:00's open** + bearish PDA in premium, stop hunt above it → **9:45 opened, wicked up** into a rejection block at 6:00's open → down to the DOL.
3. **Monthly open as DOL:** month opened and ran up with no manipulation below → market turned bearish → 6:00 manipulated up and started down → rally to 6:00's open (time EQ + premium) = session high → ran below the monthly open.
4. **True day open:** opened with no manipulation below and ran up (daily top wick likely in) → price used the true day open short-term to rebalance 6:00's PO3, then continued lower.
5. **Stacked opens:** midnight + 6:00 both manipulated up, DOLs below intact; 8:30 added liquidity below → **9:30 rallied into the true day open + 6:00 open to the tick** (bearish PDA, CE of 6:00's range, premium) → continued lower.
- Warning: don't stack lots of tools you barely understand — that causes "analysis paralysis." Backtest key opens on random days first.

### 5.4 Stacked PO3
*Source: Nq Cam — "Increasing Your Win Rate Using Stacked PO3"*

- Lower-TF PO3s (9:30, 9:45) **build liquidity**; the **higher-TF PO3** (e.g. 10:00 15m/1H) supplies the **real manipulation** and distributes to everything they built.
- *Example (bearish):* 9:30 moves lower but leaves major sell-side intact → 9:45 adds to the pool → 10:00 opens, wicks up into a price + time premium inside an HTF PDA → accelerates down.
- **Which manipulation matters:** both NQ and ES sweep liquidity inside an HTF PDA **and** the sweep **meets the current model's objective**. Internal sweeps with no key level while price is still seeking its objective are just higher highs (in a buy model) — ignore them.
- **Time alone can be enough** in some cases (time premium even without price premium).
- ❌ Fade setups taken **before the HTF objective is met** — the HTF PO3 will likely stop you out first, then go to your target without you.
- ❌ A new open making a higher high **with no HTF PDA and a major DOL still above** is just building liquidity — not a short. ✅ A **continuation long** can make sense there: new open builds liquidity above, then manipulates lower into an HTF bullish PDA (which defends the lows and attacks the buy-side) → IFVG long.

---

## Part 6 — True manipulation and SMT

### 6.1 True manipulation (Nq Cam)
*Sources: Nq Cam — "TRUE manipulation (the WHY behind distribution)" and "How to CORRECTLY use SMT"*

- **Rule:** don't trade unless **both NQ and ES are in a spot of distribution** — each has **swept some liquidity inside some HTF PDA**. They **don't need** the same liquidity, the same PDA or the same timeframe.
- **Why:** if only one asset has a reason to move, the other is just as likely to go grab its own liquidity first. That grab **is the stop hunt** — you get stopped, then the real move happens without you. "Understand the **why** for both assets."
- **An SMT ADDS confluence — it never REPLACES required criteria.** If you're using an SMT to excuse a missing requirement, it's a bad setup. "You're probably better off not using SMTs than using them wrong."

| Setup | Valid? |
|---|---|
| SMT + IFVG toward a nice LR pool, but neither asset swept liquidity or hit a PDA | ❌ |
| ES swept buy-side in a 1H gap, NQ did nothing → bearish SMT | ❌ — NQ has no reason to move |
| Both swept liquidity in their own HTF bearish PDAs (e.g. NQ in a 15m bearish gap) + SMT | ✅ — SMT is a bonus |

- **Where Nq Cam uses SMT most:** **after HTF manipulation** — both assets swept inside an HTF PDA → expect a stop hunt → one asset re-sweeps, the other doesn't (that one is **leading**, it doesn't need to re-sweep) → IFVG.
- **Examples:** ✅ NQ swept sell-side inside a 30m bullish gap (that held) while ES swept its sell-side inside its HTF gap → bullish SMT → ran to ATH. ❌ ES inside a 5m bullish gap near ATH but **NQ hadn't swept anything** → bad. Then NQ made a stop hunt into its 5m gap → both in distribution → 30s IFVG → ran to the DOL.
- **"Stop pattern trading."** Any tool (IFVG, SMT, breaker, order block, mitigation block) is meaningless without narrative and context.

### 6.2 SMT advanced — when true manipulation can be "voided" (Reese)
*Source: ReeseTradesNQ — Instagram reel "Smt advanced". The voice-over couldn't be transcribed; these notes come from reading every frame of the diagrams/labels, so re-watch with sound to confirm details.*

Reese's on-screen question: **"When can we VOID true manipulation?"** (i.e., when only one pair reaches its HTF gap). His three SMT types (bullish diagrams; flip for bearish):
1. **Double SMT** — Pair A never trades into its 1h FVG and holds **higher lows**; Pair B trades into its 1h FVG and makes a **lower low**. Two SMTs at once: an **HTF SMT** (one in the gap, one not) and an **internal SMT** (LTF swing lows disagree). Then both expand to the HTF DOL.
2. **ITL/ITH SMT** — both have an intermediate-term swing near/inside the 1h FVG; A **holds** its ITL, B **sweeps** its ITL inside the gap.
3. **UM FVG SMT** (unmitigated FVG SMT) — B trades into its 1h FVG; A leaves its 1h FVG **unmitigated**, holding a higher low.

Chart examples in the reel: (1) ~10:00, SMTs at a 4h level, IFVG entry → target BSL → hit. (2) 09:25–09:40, 1h ITL, SMT on lows ~9 minutes apart, IFVG → daily level → hit. (3) Replay ~10:00–11:00, 1h level, SMT, long; dipped close to the stop then ran to target.

*(See Part 11 — Nq Cam is stricter about this.)*

---

## Part 7 — Stop hunts / internal manipulation
*Source: Nq Cam — "You Aren't Wrong. You're Just the Liquidity."*

- **What it is:** a push into the pool where stop-losses rest, to create the order flow needed for the real move. Retail panics out, chases breakouts or calls reversals too early — and becomes the liquidity.
- **The story:** price sweeps major sell-side inside an HTF gap → retail longs immediately ("support held") → their stops sit just below → price re-sweeps them → **then** distributes up. Meanwhile breakout-shorts entered on that re-sweep put more stops above → extra fuel.
- **Accumulation after HTF manipulation is good:** the range builds stops on both sides; the sweep of one side is the stop hunt; the other side is the target.
- **Market cycle:** accumulate (generate liquidity) → manipulate (fill orders) → distribute (seek DOL). Only trade the distribution.

**When a stop hunt is REQUIRED:**
- Catching a **reversal right after HTF manipulation**.
- **No clear accumulation** has formed.
- ❌ After a fast ~300-point dump with no accumulation, an IFVG long = "catching a falling knife" — you're asking to be the manipulation.

**When it's NOT required:**
- The **initial manipulation already swept a clear accumulation range** (tapped the HTF gap + swept internal liquidity + LR on the other side) → the first IFVG after the gap tap is valid even without an internal re-sweep.
- ❌ Bad version: gap tap → immediate inversion with **no accumulation** being manipulated.
- Unsure if it's breakout or more liquidity-building → wait for a **CISD**.

**Time alignment:**
- **Best stop hunts are provided by a new HTF candle open.**
- **Trigger right before a new HTF candle opens? Ask: is any criterion still missing that the new open could provide?**
  - **Yes → fade.** E.g. long trigger at **10:28** with an **unmitigated 30m gap at the stop** — the 10:30 candle will likely manipulate into it first.
  - **No → take it.** E.g. long trigger at **10:13** with nothing missing — the 10:15 PO3 just continues the 10:00 PO3.

**SMT can BE the stop hunt:** NQ doesn't re-sweep but **ES does (SMT)** — valid **if both were already in distribution**. *Example:* NQ took an ITH inside a 4H bearish FVG, ES took its ITH inside a 1H bearish FVG → ES re-sweep = stop hunt → short to the unmitigated 30m bullish FVG.

**Stop hunts are fractal — use the CURRENT manipulation leg:** on the 3m there may be one big leg; on 30s there may be a newer, smaller leg that manipulated the previous one. Take the **highest-timeframe inversion of the current leg** (e.g. a 30s IFVG) — valid if it doesn't close inside the still-unmitigated 3m gap. Option: take risk off/BE at that 3m gap, hold the rest to the main target.

---

## Part 8 — Entries and entry locations

### 8.1 OTE
*Source: Nq Cam — "OTE: Finding Better Pricing for Your Entries"*

- **OTE = 62%–79% retracement** of a range; **70.5% = sweet spot** (the CE of the OTE zone).
- **OTE is a measuring tool, NOT a bias.** Price reaching it means nothing alone — you still need a DOL, meaningful PDAs, and (for his style) **displacement** away from it.
- **Two uses:**
  1. **Dealing-range OTE** — e.g. the range a 4H candle's PO3 set (6:00 opened, manipulated up, started down toward an unmitigated 4H bullish gap) → at 9:30 price manipulated up into OTE, respected the 70.5% + true day open + a 30m bearish FVG + an up-close candle (order block) → **1m IFVG** → continuation to sell-side.
  2. **Displacement OTE** — after a sweep/HTF PDA interaction, mark the displacement leg **from the HR swing (the one that swept liquidity) to the displacement's extreme**; wait for the retrace into OTE aligned with PDAs (e.g. a rejection block) → displacement/IFVG → enter. **Repeat for each new displacement leg** in a trending day. Great for when you **missed the first reversal entry** (e.g. missed a 30s inversion at the open → caught the OTE retrace + 1m inversion).
- **OTE vs EQ:** EQ/discount-premium is often enough when PO3, PDAs and liquidity line up shallower. **Wait for OTE when the reaction at EQ isn't time-aligned** (random time, no PO3) — expect a key open to supply the real manipulation deeper. *Example:* EQ reaction failed; 8:00 open added liquidity above; **8:15 swept the low inside OTE** then displaced → valid entry.
- **Drawing ranges:** displacement range = from the HR swing to the displacement extreme; dealing range = HR to HR. **Don't draw random swings to make OTE "fit"** — that's what hurts you.

### 8.2 Rejection blocks
*Source: Nq Cam — "Understanding Rejection Blocks" (his own backtested understanding; he lists ICT sources in the video)*

- **Bearish:** from the **highest open/close (body) to the highest wick** of the swing high. **Bullish:** **lowest open/close to lowest wick**.
- **Why it works:** liquidity rests just beyond **bodies**; price doesn't need the wick extreme if it's truly HR. Wicks are inefficiency, so revisiting a wick is hitting another PDA in the trend direction.
- **Valid only if:** the swing **swept significant liquidity** (ideally inside an HTF PDA → HR); **displacement away** after it formed; it's **recent**; it fits the **narrative/order flow**; you can **name the liquidity it took**. Extra edge (his finding): **exhaustion/overextension** before it formed.
- **Entries:** limit orders on rejection blocks are "mid" — prefer a **reaction/displacement**, which comes fast, so be ready on **5s–30s** for an IFVG/CISD. Price may **revisit several times** (even re-sweeping inside it) while **holding the mean threshold** — expect possible break-evens. Quadrants/octants give finer levels.
- **Targets:** reversal → **unmitigated PDAs** (price often uses the block for a short-term objective, then later takes the real wick extreme); continuation → swings/liquidity.
- **Examples:** (1) before 10:00, 6:00 set the dealing range → price rallied into premium + 6:00 open (time premium), swept equal highs inside a 4m BPR → instant displacement → limit at the block's CE → full TP. (2) Reversal after a big sell-off took a 4H ITL inside a 4H bullish FVG → stop hunt → bullish rejection block in deep time + price discount → rally. (3) Asia session: overextended pump into bearish PDAs, unmitigated bullish PDAs below → bearish block (high swept inside a 5m BPR), wicks stayed in its lower half → several entries (some BE) → ran to the 1H gap. (4) Weekly 30m blocks reused many times; common pattern: **NQ taps the body while ES takes the wick extreme** (SMT) — both still count as in distribution.
- **Common mistakes:** huge wicks as blocks; calling every swing a block; blocks defending LR or that are really major swings to be taken; no displacement after; trading against order flow; **skipping the stop hunt** (a good reversal = major sweep → stop hunt aligned with time; the block matters *after* the stop hunt); using it live before backtesting.

### 8.3 Sponsorship
*Source: Nq Cam — "Sponsorship: How to Catch High Probability Continuation/Re-Distribution" (credits ICT)*

- After **HTF manipulation** (e.g. buy-side swept inside a 4H bearish FVG — buy-side objective met, major sell-side objective remaining), the **whole initial displacement leg** is **sponsored** — not just one gap in it.
- Any gap **inside that leg** (15m, 5m…) is a valid continuation area **while the major objective is still intact**. If the leg has two gaps, either is valid.
- **NOT sponsored:** gaps formed **later** from a smaller (LTF) manipulation (e.g. a 5m gap formed while running from the 15m entry), and anything after the major objective is met. Taking these = **FOMO** — "don't settle for less," move on.
- **Context still decides:**
  - **Fade the lower sponsored gap** when price dumped hard and barely retraced (deep discount), major sell-side is already largely swept, and an **unmitigated higher-TF gap (e.g. 15m) sits at your stop** in premium — wait for that higher gap. *Example:* 1m IFVG off the 5m failed; 5m IFVG off the 15m worked; then the "play of the day" was a **15-second IFVG** after an internal buy-side sweep into a 5m bearish gap with LR below.
  - **Take the lower sponsored gap** when no unmitigated higher-TF gap is at the stop and nothing significant has been swept yet. *Example:* 30m-gap manipulation at the open → retrace into the 5m sponsored gap → **30s IFVG** → major sell-side.
- **Sponsorship means nothing without narrative.**

---

## Part 9 — Trade management: attack vs defense, stops, break-even
*Source: Nq Cam — "Weighing PDA's Attack vs Defense"*

- Every PDA **attacks** liquidity on one side and **defends** liquidity on the other.
- **Before a trade: is the PDA behind your stop (your attack) stronger than what's defending your target?**
- **Higher timeframe beats lower** (a 4H attack beats a 5m defense). **LR gets taken; HR holds** — unless its PDA reaches its objective first. A PDA **defending LR is weak**.

**Trading between HR levels (normally avoided) — OK when attack > defense:** range = low inside a 1H gap (HR) ↔ high inside a 30m gap (HR). Price taps the 30m bearish gap → 1m IFVG short. Valid because the 30m now attacks the **unmitigated 4H gap below (LR)** — the target is really **LR disguised as HR**, and the stop is behind a strong HTF level.

**NOT OK when attack < defense:** shorting off a **5m** bearish gap with an **unmitigated 30m gap above your stop** — a 5m won't defend that; expect a run into the 30m first. Same for a 5m trying to beat a 1H ITL (HR).

**Real example:** price taps a 2H bullish FVG; unmitigated 4H bullish gap below (LR, the DOL) and unmitigated bearish gaps above. ❌ First short off a 5m bearish gap: 5m attacking a 2H HR low, defending LR, with an unmitigated 15m at the stop → stopped. ✅ Price then tapped the **15m bearish FVG** (the new objective) → short → ran to the 4H gap.

**Break-evens (costly mistake):**
- Don't move to BE at a minor LTF gap/internal swing that defends LR. If a **4H bullish gap is attacking LR**, a 5m gap in the way won't stop it — BE there gets you stopped before TP.
- Move to BE **only where price could genuinely reverse** — e.g. the next **ITH/ITL (HR)**.
- If you'd go BE at a meaningless level, you're not confident in the DOL → **don't take the trade.**
- **Scared mid-trade?** Check the higher timeframe — a big rejection wick at your stop that's attacking LR = hold.

---

## Part 10 — What NOT to trade (pattern trading)
*Source: Nq Cam — "Pattern trading IFVG's will wreck you...here's how to increase your win rate."*

- An IFVG without narrative = a **pattern trade**. A V-shaped inversion + an internal sweep is **not** a reason.
- **Stop calling every loss a "good loss."** Use the journal to find the **repeating root cause** of losses and cut that setup.

**Five avoidable losses from one week:**
| # | Looked like | Why it was a pattern trade |
|---|---|---|
| 1 | 5m V-shaped IFVG **short** after big expansion; unmitigated 15m bullish gap + equal lows below | 1H clearly bullish (disrespecting bearish PDAs, buy-side above, buy model objective not met). Rebalance-first vs keep-running = **coin flip → don't engage** |
| 2 | 1m V-shaped IFVG **long** at the open after sweeping internal sell-side in a 4H bullish gap | **Not yet in discount** of the dealing range. ✅ Real long came later: deeper in the 4H gap, in discount, re-manipulated, bodies holding the 4H CE → displacement → 5m IFVG → instant TP |
| 3 | 1m IFVG **long after a ~500pt dump** (in a 4H bullish gap, swept lows, discount) | Delivering from a **daily bearish gap** after a buy-side sweep → start of a sell curve, more sell-side below. **Stop at LR, target at HR** (target 5m gap already partly mitigated). Falling knife. ✅ Real setup was the short at the open into the unmitigated 15m bearish gap (no entry came → no trade) |
| 4 | **Short** after the open swept an internal high | High swept into **no HTF PDA** (unsponsored); targeting a low inside an HTF PDA (HR) with stop at LR |
| 5 | 2m V-shaped IFVG **long** (+ re-entry) after sweeping internal sell-side | Targeting a high inside a **daily bearish FVG (HR)**; not bullish until that daily gap inverts. Re-entering after failed delivery + chop = gambling |

**Filter checklist:**
- HTF narrative agrees · not a coin flip · longs from discount / shorts from premium · manipulation hit an HTF PDA (sponsored) · **stop at HR, target at LR** · target not already mitigated · no falling knife (wait for accumulation + stop hunt) · between two HR levels with nothing building LR → sit out · after a failed delivery → don't re-enter · bodies confirm the PDA.

---

## Part 11 — Where the creators disagree

**Can an SMT replace "both assets in an HTF PDA"?**
- **ReeseTradesNQ** (IFVG video + "Smt advanced" reel): true manipulation **can be voided** by a **double SMT** (and the reel shows ITL/ITH SMT and unmitigated-FVG SMT as further cases), even if only one pair reached its HTF gap.
- **Nq Cam** ("How to CORRECTLY use SMT", "TRUE manipulation"): **never** — an SMT only adds confluence; both assets must each sweep liquidity inside *some* HTF PDA.
- **Overlap:** in Reese's diagrams the lagging pair still sweeps an internal low/high; and Nq Cam accepts **different** liquidity/PDAs per asset (e.g. NQ tapping a rejection block's body while ES takes the wick). The difference is how strict the "HTF PDA" requirement is for the second asset.
- **Suggested approach:** journal which rule each trade used and compare results over time.

---

## Part 12 — Daily routine + full checklist

### Pre-market
- [ ] **Delivering from:** buy-side / sell-side / unclear (SMT with ES there?)
- [ ] **Gaps respected vs disrespected** (bullish / bearish) → **possible DOL**
- [ ] **Range type:** HR vs LR / LR vs LR / HR vs HR / ATH trend
- [ ] **HTF conditions** (15m+ gaps) with Scenario 1 (respected) and Scenario 2 (disrespected)
- [ ] (HR vs HR) EQ, premium bearish gap, discount bullish gap
- [ ] **Current DOL** (what's being sponsored right now?) vs daily bias
- [ ] **Key opens marked** (midnight, 6:00, 8:30, 9:30, 9:45, 10:00 + weekly/monthly): for each — done / missing; continuation reference or DOL?
- [ ] **Red-folder news at 8:30?**
- [ ] **Daily objective already met?**

### Before entry
- [ ] **Accumulation** present, then **manipulation** that swept it **into an HTF PDA**
- [ ] Manipulation formed by a **key open / PO3** (stacked = better); wick formed before entry
- [ ] **True manipulation:** NQ and ES each swept liquidity inside an HTF PDA (SMT only as a bonus — or per Reese's exceptions)
- [ ] **Stop hunt** seen if needed (reversal after HTF manipulation / no clear accumulation)
- [ ] **Location:** discount for longs / premium for shorts (price and time); OTE if the shallow level isn't time-aligned
- [ ] Entry gap is **sponsored** (inside the initial displacement from HTF manipulation), not FOMO
- [ ] **No unmitigated higher-TF gap at the stop**; no new HTF open about to supply missing criteria
- [ ] **Attack (behind stop) > defense (in front of target)**; stop at HR, target at LR
- [ ] **IFVG trigger:** highest TF of the **current** manipulation leg, strong body, fast close
- [ ] Not one of the pattern-trade losses (Part 10)

### Management
- [ ] Stop beyond the manipulation; target the LR toward the DOL (conservative target in rebalance trades)
- [ ] BE only at a real HR level (ITH/ITL); otherwise hold
- [ ] Scared → check the higher timeframe

---

## Part 13 — Master journal template
```
DATE / TIME:                 INSTRUMENT: NQ / MNQ        DIRECTION: Long / Short
TRADE TYPE: A (LTF reversal in HTF continuation) / B (continuation) / C (rebalance)

— NARRATIVE —
Delivering from: BSL / SSL        Possible DOL: ________      Daily bias: Bull / Bear
Current DOL (move being sponsored): ________     Last objective met: ________
HTF range: HR-LR / LR-LR / HR-HR / ATH trend
HTF condition: ____ (TF) — Respected / Disrespected — Scenario that played out: 1 / 2
Daily objective already met? Y / N      Red-folder 8:30? Y / N

— TIME —
Key opens: 00:00 above/below · 6:00 above/below · 8:30 above/below · 9:30 above/below · 10:00 above/below
Key open used: ____ as continuation reference / DOL — its PO3 status: ________
PO3 candle(s): 15m / 30m / 1H — stacked? Y / N — wick formed before entry? Y / N
Time location: premium / discount     Price location: premium / discount (EQ / 62 / 70.5 / 79)

— MANIPULATION —
Accumulation present? Y / N
NQ: swept ____ inside ____ (PDA, TF)       ES: swept ____ inside ____ (PDA, TF)
True manipulation? Y / N    SMT: none / bonus / used to skip a requirement / Reese type: Double / ITL-ITH / UM FVG
Stop hunt: needed? Y / N — provided by: NQ re-sweep / ES SMT / new HTF open (time ____)

— ENTRY —
Entry PDA: FVG / OB / rejection block / OTE / key open — sponsored? Y / N
IFVG TF: ____ (current manipulation leg)   Displacement quality 1–5: ____   Close speed: fast / slow
CISD? Y / N
Attack (behind stop): ____ TF ____   Defense (before target): ____ TF ____   Attack stronger? Y / N
Unmitigated gap at stop? Y / N      New HTF open about to supply missing criteria? Y / N

— RISK & RESULT —
Entry: ____   Stop: ____   Target: ____   Planned R:R: ____
BE moved at: ____ (real HR level? Y / N)
Result (R): ____    Stopped then price hit target? Y / N
Followed every rule? Y / N — if N, which:
Pattern-trade? Y / N    Falling knife? Y / N    FOMO (unsponsored) entry? Y / N
Root cause if loss (one line): ________   Seen this cause before? Y / N — count: ___
Screenshot:            Lesson:
```

---

## Part 14 — Source list

| # | Creator | Title | Link | Detailed notes file |
|---|---|---|---|---|
| 1 | ReeseTradesNQ | 90% Win Rate IFVG Model (Full Breakdown) | https://youtu.be/mZIGMN4cRi0 | `01-ifvg-model.md` |
| 2 | Nq Cam | How to CORRECTLY Use Key Opening Prices (Time-Based PO3) | https://youtu.be/guQ2ctgXYCg | `02-key-opening-prices.md` |
| 3 | ReeseTradesNQ | Smt advanced (Instagram reel, visuals only) | https://www.instagram.com/reel/DeuiuobqF2i/ | `03-smt-advanced.md` |
| 4 | ReeseTradesNQ | How to Always Find the Correct DOL | https://youtu.be/XKk87Ruogrk | `04-find-the-dol.md` |
| 5 | Nq Cam | How we can identify our CURRENT DOL... | https://www.youtube.com/watch?v=ulurCGAf6JQ | `05-current-dol.md` |
| 6 | Nq Cam | Understanding OXXC & PO3 — a fractal framework for context. | https://www.youtube.com/watch?v=zAHRlnCIVFw | `06-oxxc-po3-true-manipulation.md` |
| 7 | Nq Cam | OTE: Finding Better Pricing for Your Entries | https://www.youtube.com/watch?v=xlWRHxrIdII | `07-ote.md` |
| 8 | Nq Cam | How to CORRECTLY use SMT | https://www.youtube.com/watch?v=apeJHeRLqHc | `08-smt-correctly.md` |
| 9 | Nq Cam | Understanding Rejection Blocks | https://youtu.be/lDN_RTJshSk | `09-rejection-blocks.md` |
| 10 | Nq Cam | You Aren't Wrong. You're Just the Liquidity. | https://www.youtube.com/watch?v=wCbEn_DjPe8 | `10-stop-hunts.md` |
| 11 | Nq Cam | Weighing PDA's Attack vs Defense | https://www.youtube.com/watch?v=tu6TOfQNQWA | `11-attack-vs-defense.md` |
| 12 | Nq Cam | Pattern trading IFVG's will wreck you... | https://www.youtube.com/watch?v=hJHkpHrH004 | `12-pattern-trading-ifvgs.md` |
| 13 | Nq Cam | Navigating LTF Entries in Different HTF Conditions | https://www.youtube.com/watch?v=vZo5pNebgzI | `13-ltf-entries-htf-conditions.md` |
| 14 | Nq Cam | Increasing Your Win Rate Using Stacked PO3 | https://www.youtube.com/watch?v=QM69ib4Y-30 | `14-stacked-po3.md` |
| 15 | Nq Cam | Sponsorship: How to Catch High Probability Continuation/Re-Distribution | https://www.youtube.com/watch?v=VOAL3J_Vobg | `15-sponsorship.md` |
| 16 | Nq Cam | TRUE manipulation (the WHY behind distribution) | https://www.youtube.com/watch?v=wx0R6cZk6dM | `16-true-manipulation.md` |
| 17 | Nq Cam | Time Shapes the Story Price Tells / The Why Behind Key Opens | https://youtu.be/afLme-akOwE | `17-why-behind-key-opens.md` |

**Suggested learning order:** Layer 1 — Parts 2, 3, 6, 10 · Layer 2 (timing) — Part 5 · Layer 3 (entries) — Parts 7, 8 · Layer 4 (refinement) — Parts 4, 9, 11.

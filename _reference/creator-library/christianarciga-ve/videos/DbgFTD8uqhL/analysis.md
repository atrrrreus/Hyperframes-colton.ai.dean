# DbgFTD8uqhL — @christianarciga-ve

**Source:** https://www.instagram.com/reel/DbgFTD8uqhL/
**Duration:** 22.27s
**Aspect:** 9:16
**Resolution:** 1080x1920 (60fps)
**Studied:** 2026-10-08
**Engagement (at time of study):** 15,983 likes (views not exposed)
**Sample rate:** every frame at 2fps (45 frames); scene-cut detection found no hard cuts (one continuous screen-recorded layout)
**Transcript:** not generated (whisper-cpp not installed)

## Hook (0–2s)
A "RAW vs. EDITED HOOK" editing breakdown. Grey background with a soft palm-leaf shadow; bold white title "RAW vs. EDITED HOOK" at top; the creator's talking-head clip plays in a rounded-corner card in the upper-middle; below it, a colorful **progress-bar timeline** of labeled stages (red "Raw" → yellow "Captions" → blue "Zoom In & Out" → cream "Animations & Graphics" → green "BGM & SFX") with a white playhead sweeping across. The format itself is the hook: you watch a flat raw clip and know it's about to transform.

## Pacing
- Total scenes: 1 continuous layout. The *same* hook replays while each editing layer is stacked on, stage by stage.
- Stage changes roughly every 2–4s, following the colored timeline segments
- Distribution feel: sustained, educational, builds additively
- Pace shift: at ~4.3s the raw (flat, grey, cool) clip flips to the warm-graded version, the big "before/after" moment

## Captions
- Style: phrase-chunk, centered over the chest ("NEVER POST CONTENT AGAIN", "ONE INVISIBLE PROBLEM")
- Font feel: heavy condensed sans, ALL CAPS, stacked lines with a small word above ("ONE" over "INVISIBLE" over "PROBLEM")
- Active-word treatment: color swap between red and warm yellow/cream, with an outer glow
- Position: center, below the face
- Size: medium-large inside the card

## Scene types
1. 0–4.3 raw talking head in the card: flat, cool, ungraded — "Raw" segment
2. 4.3–7.5 same clip, now warm-graded with red glow captions "NEVER POST CONTENT AGAIN" — "Captions"
3. 7.5–13 punch-in / punch-out zooms on the face — "Zoom In & Out"
4. 13–19 graphics pop in: Instagram notification card, red toggle switch UI under "INVISIBLE PROBLEM" — "Animations & Graphics"
5. 19–22.3 full edit with BGM and SFX — "BGM & SFX"

## Transitions
- Flavors observed: none between scenes (single layout); inside the edited clip, the transitions are **punch zooms** (scale jumps on cuts/emphasis)
- Signature: additive "layer-by-layer" reveal driven by a color-coded timeline bar

## Face treatment
- Mode: talking head in a rounded card (picture-in-frame on a neutral grey stage)
- Grading feel: raw is grey and cool; edited is **warm amber/orange with deep shadows** (the core before/after)
- Camera motion: digital punch-in/out zooms
- Framing: centered, medium close-up

## Audio reactivity
- Text pulses on beat: no visible pulsing
- Background reactivity: no
- SFX layer is added in the last stage, timed to graphics pop-ins

## Palette
- #7A7A7A neutral grey (stage background, dominant)
- #E8A04A warm amber (edited grade)
- #E53935 red (caption glow, toggle UI, "Raw" segment)
- #F5D547 yellow ("Captions" segment, caption accent)
- #2EA8F0 blue ("Zoom" segment)

## Signature move
Shows the same hook transforming from raw to fully edited, one labeled layer at a time, on a color-coded progress bar.

## What to steal (actionable for Hyperframes builds)
- **Warm grade is the biggest single upgrade**: the jump from raw to warm amber is the "wow" frame. CSS `sepia(.25) saturate(1.2) contrast(1.1)` + warm soft-light overlay on the video wrapper
- **Punch zooms** on emphasis: GSAP `scale` 1.0 → 1.12 snap on key moments (wrapper div, never the video element)
- **Stacked-caption typography**: small word over a big ALL-CAPS word, red/yellow glow
- **UI pop-ins** (notification card, toggle) as emphasis graphics: maps to the `macos-notification` / `instagram-follow` registry blocks
- The breakdown format itself is reusable for a behind-the-scenes post

## What's creator-specific (don't copy literally)
- The "RAW vs. EDITED" tutorial layout, palm-shadow stage and his watermark
- His exact caption lines

## Transcript
Not generated (whisper-cpp missing).

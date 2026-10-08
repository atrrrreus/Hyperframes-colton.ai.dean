# DdrbHPwAOm9 — @kevertai

**Source:** https://www.instagram.com/p/DdrbHPwAOm9/
**Duration:** 22.27s
**Aspect:** 9:16
**Resolution:** 1080x1920 (29.97fps)
**Studied:** 2026-10-08
**Engagement (at time of study):** 1,314 likes · 4 comments (views not exposed), posted 2026-09-24
**Sample rate:** every frame at 2fps (44 frames) + ffmpeg scene-cut detection
**Transcript:** not available (whisper-cpp not installed in this environment); speech content inferred from burned-in captions.

## Hook (0–2s)
- 0.0s: wide-angle low shot, creator sitting on the floor of a warm retro-styled room (vest, tie, tinted sunglasses), mid-gesture, arm swinging toward the lens. Caption center-frame: "This is so STUPID!!!" — bold italic white with a soft shadow.
- 1.5s: hard cut to a **vintage TV set** filling the upper half of the frame; inside the screen, the creator sits at a computer. A cream "subtitle bar" sits under the TV in a handwritten-style font: "I need a LUT?".
- Frustration-skit hook: an exaggerated emotional line in the first second, then immediately cut to a "flashback" in the TV.

## Pacing
- Total scenes: ~14 (cuts at 1.47, 2.27, 3.20, 4.47, 5.77, 6.84, 7.64, 8.51, 14.28, 14.98, 16.22, 21.22s)
- Average scene length: ~1.6s
- Shortest / longest: ~0.7s / ~5.8s (the 8.5–14.3s rant held on one wide shot)
- Distribution feel: short-chopped ping-pong in act 1 (~1s per shot), one long sustained rant, then quick product beats
- Pace accelerates through "LUT? → transition? → sound effect? → overlay?", slows for the "ANOTHER WEBSITE!!!!!" rant, snaps fast on the reveal (paper card "FOUR EDITORS."), then a steady 1s rhythm through the product montage

## Captions
- Style: phrase chunks (2–4 words), not karaoke
- Font feel: two systems. (1) Talking-head: bold italic sans, white, soft drop shadow; ALL-CAPS and huge for punch lines ("ANOTHER WEB SITE!!!!!" in warm cream/yellow). (2) TV scenes: a small, black, lowercase handwritten font on a cream bar under the TV, like a subtitle card.
- Active-word treatment: none; emphasis is via size jump + caps + exclamation marks
- Position: center/lower-center over the body; never over the face
- Size: small/medium normally, large on peak lines

## Scene types
1. 0–1.5 talking-head wide-angle floor shot — "This is so STUPID!!!"
2. 1.5–2.3 TV-frame cutaway: creator at the computer — "I need a LUT?"
3. 2.3–3.2 talking head — "website."
4. 3.2–4.5 TV-frame: close-up thinking pose — "I need a transition?"
5. 4.5–5.8 talking head, wider — "another website."
6. 5.8–6.8 TV-frame: blurred keyboard close-up — "sound effect?"
7. 6.8–7.6 talking head, tilted Dutch angle — "ANOTHER ONE."
8. 7.6–8.5 TV-frame: at the desk, slumped — "overlay?"
9. 8.5–14.3 sustained talking-head rant: "ANOTHER WEB SITE!!!!!" → "and why are we doing this?!" (whips off sunglasses) → "just put EVERYTHING in ONE place!!!" → a hand enters with a paper card
10. 14.3–15.0 POV insert: card on the rug reads "FOUR EDITORS." (product reveal, product-placement beat)
11. 15.0–16.2 talking head reaction — "oh" / "they did it."
12. 16.2–21.2 TV-frame product montage: UI/asset grids — "thousands of drag&drop" → "video and audio assets" → "for ANY editing software" → "or app."
13. 21.2–22.3 talking-head outro — "you're welcome." (deadpan)

## Transitions
- Flavors observed: almost entirely hard cuts on the beat of the speech; the energy comes from the content (gestures, glasses toss, card entering frame) rather than effects
- Rotation cadence: strict A/B ping-pong (talking head ↔ TV frame) in act 1
- Signature transition: **the TV-frame cutaway** — the "other" footage always plays inside a retro TV, so the frame itself becomes the transition device

## Face treatment
- Mode mix: fullscreen wide-angle talking head + footage inside a TV frame (picture-in-frame)
- Grading feel: very warm, amber/brown cinematic grade, crushed but soft blacks, film-like
- Camera motion: slight handheld drift; a Dutch tilt for emphasis (7.0s)
- Framing: low angle, wide lens, creator seated on the floor, centered

## Audio reactivity
- Text pulses on beat: no
- Background reactivity: no
- Cuts land on spoken stresses ("website.", "ANOTHER ONE.")

## Palette
- #6B4A2E warm brown (dominant: vest, wood, room)
- #E8D9B5 cream (subtitle bar, TV bezel, shirt)
- #C8752B amber/orange (glasses, lamp light)
- #3F5A3A muted green (ottoman, rug accents)
- #F3E6A0 pale yellow (peak caption text)

## Signature move
Comedic frustration-skit where every "problem" is shown on a retro TV with a handwritten subtitle card, ping-ponging against an over-the-top talking-head reaction, all under a warm vintage film grade.

## What to steal (actionable for Hyperframes builds)
- **Retro TV frame cutaways**: put b-roll inside a TV-bezel PNG/SVG with a cream subtitle bar beneath; a HyperFrames composition with the video in a masked wrapper (border-radius + inner shadow) and a styled caption bar
- **A/B ping-pong rhythm**: alternate two visual modes at ~1s per beat for a list-of-problems setup, then hold one long shot for the rant
- **Warm film grade**: CSS `sepia(.2) saturate(1.1) contrast(1.05)` + warm overlay with `mix-blend-mode: soft-light` + grain-overlay component
- **Two caption systems**: bold italic white for spoken punch lines; small handwritten lowercase for "inner thoughts/labels"
- **Size jump on the peak line**: normal captions medium, the climax line huge ALL CAPS in a warm accent

## What's creator-specific (don't copy literally)
- The retro costume (vest, tie, tinted glasses) and the vintage room set
- The FOUR EDITORS product placement and "you're welcome." sign-off
- His exact TV prop design; build an original frame rather than tracing his

## Transcript
Not generated (whisper-cpp missing). Captions listed under Scene types above.

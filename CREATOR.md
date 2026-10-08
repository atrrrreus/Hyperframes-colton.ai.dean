# Creator Profile

Your identity, positioning, and workflow for video work in this workspace. **Read this before every video task** (alongside `PREFERENCES.md`). Use it for on-screen text, niche framing, and workflow assumptions.

## Identity

- **Name on-screen**: — (no on-screen name/handles for now)
- **Instagram**: —
- **TikTok**: —
- **YouTube**: —
- **X / other**: —

When putting handles on-screen (lower-thirds, outros, end-cards), use the platform-appropriate handle.

## Platform priority

**Instagram Reels first.** Default 9:16 vertical, 1080×1920, 30fps.

## Content niche

**Lifestyle / vlog**: day-in-life, travel, b-roll-driven footage.

## On-camera mix

Lifestyle/vlog footage, mostly real-world b-roll.

- **Face-cam** → use `/short-form-video` face-mode choreography (BOTTOM / FULLSCREEN modes).
- **Faceless** → motion graphics + AI TTS narration (`npx hyperframes tts`) or screen-recordings.

## Workflow — division of labor

**Current mode: user sends raw clips, assistant cuts.** The assistant picks the best moments, trims dead air and unusable takes (shaky, blurry, repeated), orders the clips, and adds quick cuts and transitions. Other modes, for reference:

- **You record + pre-edit your own speaking video** → it's the source of truth; the assistant builds the visual layer on top and does NOT cut your audio, remove pauses, or change your pacing.
- **You build from scratch with the assistant** → motion graphics, TTS narration, screen-recordings assembled together.

## Brand identity

Neutral defaults for now (dark bg, white text) in `assets/brand-tokens.css`. **No on-screen text yet** — the user will provide the narrative after seeing the first cuts.

## Inspiration creators

See [`_reference/creator-library/INDEX.md`](_reference/creator-library/INDEX.md) for the full list. Add new creators via `/study-creator <url>`. (First reference, https://www.instagram.com/p/DdrbHPwAOm9/, is pending: instagram.com is blocked by the environment network policy.)

## Posting cadence & length defaults

- _Cadence_: _(TBD — set during /setup)_
- _Default length_: 15–45s short-form vertical is a common sweet spot. Adjust per video.
- _Default fps_: 30 (matches TikTok + Instagram defaults).

## Project slug convention

**Topic-only, kebab-case.** Each video gets a new subfolder under `video-projects/<topic-slug>/`. Examples: `ai-agents-intro`, `prompting-101`, `tool-of-the-week`. Keep slugs short and descriptive — scannable at a glance in `ls video-projects/`.

---

*This file is updated as your creator profile evolves. Major changes (new handles, platform shifts, workflow changes) can be edited here directly.*

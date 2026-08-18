---
format: 1080x1920
duration: 15s
message: "SkyHarvest brings precision farming from above"
arc: Feature-Benefit Cascade (compressed, silent)
audience: agricultural technology buyers / farm operators
mode: autonomous
music: none
---

## Video direction

- **Palette** (from `frame.md` / broadside preset): single dark register throughout — ground `ink-black` (#111111), text `cream` (#F0ECE5), sole accent `fire-orange` (#E85D26), rule/border `border-dark` (#282826). The orange register (orange ground) never appears — this is a dark video, accent used sparingly (bullets, rule bars, glow, focal-slot emphasis).
- **Motion grammar + reveal model**: long-tail `power3` eases throughout, no bounce/elastic overshoot except the named spring-pop marker beats. Silent build — no voiceover to pace against, so reveals are paced to content beats instead: nothing appears before its turn; each frame opens near-empty and fills across its duration, never dumping the whole card/stack at t=0.
- **Rhythm / held-frame allocation**: Frame 1 (title) and the tail of Frame 4 (brand sign-off) are the held/breather beats — one restrained move, then a static hold; low motion is the payload there. Frames 2–3 and the first half of Frame 4 are the propulsive beats — the feature stack assembles and steps. This gives the 15s a light → build → build → resolve/light rhythm rather than uniform busyness.
- **Negative list**: no slideshow (front-load-then-freeze) and no screensaver (independently floating elements with no shared read); no shadows or rounded corners beyond broadside's own components (pill chips, top-border stat rule); no cream/paper register; no stock photography or decorative gradient blobs — typography and the fire-orange rule/bullet system carry the whole build.

## Frame 1 — Title

- scene: The SkyHarvest wordmark animates in center-frame on ink-black, with a soft fire-orange glow bloom behind it
- voiceover:
- duration: 4s
- transition_in: cut
- status: outline
- src: compositions/frames/01-title.html
- type: product_intro
- persuasion: Authority by association — a confident brand-first open
- beat: intrigue
- blueprint: titlecard-reveal (Adapt)
- sfx: soft swell into a gentle pop

Adapt: keep the single-move-then-hold signature (Product_Intro prelude, collapsed to one card since there's no logo asset and no version string) — wordmark pop with overshoot + glow, then a tagline hands off beneath it.
Scene 1 (0.0–0.6s): static camera on the bare ink-black ground — nothing on screen yet. Centered, empty stage.
Scene 2 (0.6–2.2s): "SkyHarvest" (display role, lowercase-weight treatment) pops in dead-center with a soft spring overshoot as a fire-orange glow blooms behind it and settles to a steady low bloom — Centered, ~35% of frame width, single depth layer plus the glow.
Scene 3 (2.2–4.0s): "precision farming from above" (label role, mono, uppercase, fire-orange) fades and slides up into place beneath the wordmark and holds; the wordmark + glow stay still, at most a barely-perceptible slow scale-up — Centered stack, wordmark over kicker, top ~83% only.

narrativeRole: Opens cold on the brand. There is no page or product to draw from, so the name and tagline carry the whole hook.
keyMessage: SkyHarvest — precision farming from above.

## Frame 2 — Feature: Autonomous Flight Paths

- scene: A single dark feature card reading "Autonomous Flight Paths" assembles at the top of a vertical stack, capped label above in mono chrome
- voiceover:
- duration: 3s
- transition_in: zoom-through
- status: outline
- src: compositions/frames/02-feature-flight.html
- type: feature_showcase
- persuasion: Feature-to-benefit translation
- beat: clarity
- blueprint: grid-card-assemble (Adapt — Benefits vertical-list, BUILD sub-mode, first item)
- sfx: light UI pop
- handoff_out: "Autonomous Flight Paths" card — asymmetric 70/30 layout, card region right, top edge at ~18% frame height, cream text at full opacity, fire-orange bullet + stub rule beneath, static (no residual motion) at cut

Adapt: keep the marker-pop + mask-wipe signature; this is item 1 of the list so nothing dims yet — the stack only starts accumulating from Frame 3.
Scene 1 (0.0–0.4s): static ink-black ground; a mono uppercase kicker "feature 01" sits top-left in fire-orange, awaiting the card. Asymmetric 70/30 — label rail left, card region right.
Scene 2 (0.4–1.6s): the card "Autonomous Flight Paths" (lead/body role, cream) springs into its slot with a marker spring-pop, a fire-orange "/" bullet draws in beside it, and the text reveals via a pill mask-wipe left→right — same asymmetric 70/30 layout, card ≥40% of canvas width.
Scene 3 (1.6–3.0s): the card holds with a gentle parallax float (barely-perceptible); a fire-orange stub rule (36×2px) sits under it, static — held read, top ~83% only.

narrativeRole: First proof point in the three-item list — the drone flies itself.
keyMessage: Autonomous Flight Paths.

## Frame 3 — Feature: Real-Time Crop Health Mapping

- scene: A second card reading "Real-Time Crop Health Mapping" slides in beneath the first, the stack now two cards deep
- voiceover:
- duration: 3s
- transition_in: push-slide LEFT
- status: outline
- src: compositions/frames/03-feature-mapping.html
- type: feature_showcase
- persuasion: Value stacking
- beat: clarity + confidence
- blueprint: grid-card-assemble (Reproduce — Benefits vertical-list, SNAP sub-mode)
- sfx: light UI pop, soft whoosh on the step-up
- handoff_in: "Autonomous Flight Paths" card enters already resting — asymmetric 70/30 layout, card region right, top edge at ~18% frame height, full opacity, static — matching Frame 2's exit exactly before it steps up and dims in Scene 2
- handoff_out: two-card stack — "Real-Time Crop Health Mapping" bright in the focal slot (top edge ~34% frame height), "Autonomous Flight Paths" dimmed to cream-muted directly above it (top edge ~18%), both static at cut, fire-orange rule under the focal card

Scene 1 (0.0–0.4s): the Frame 2 card ("Autonomous Flight Paths") is already resting in its slot, handed off from the incoming push-slide; kicker ticks to "feature 02" in fire-orange.
Scene 2 (0.4–1.6s): the whole stack steps up one slot — the first card slides up and dims to cream-muted — as "Real-Time Crop Health Mapping" springs into the now-open bright focal slot beneath it with the same marker-pop + fire-orange bullet draw-in + pill mask-wipe reveal. Asymmetric 70/30, stack now 2 cards deep.
Scene 3 (1.6–3.0s): both cards hold — feature 2 bright in the focal slot, feature 1 dimmed above it; gentle parallax float on both; fire-orange rule bar under the focal card — held read, top ~83% only.

narrativeRole: Second proof point — the stack of capability keeps building.
keyMessage: Real-Time Crop Health Mapping.

## Frame 4 — Feature: Precision Spot Spraying + brand sign-off

- scene: A third card reading "Precision Spot Spraying" completes the stack, then all three clear off-frame and the SkyHarvest wordmark holds center as the sign-off
- voiceover:
- duration: 5s
- transition_in: push-slide LEFT
- status: outline
- src: compositions/frames/04-feature-spray-outro.html
- type: branding
- persuasion: Rule of three — the three-item list resolves and hands off to the brand
- beat: confidence
- blueprint: grid-card-assemble (Adapt — item-field-to-payoff-card, final beat) into titlecard-reveal (Adapt — held sign-off card)
- sfx: light UI pop; soft whoosh on stack clear; the Frame 1 glow swell reprised softly on the sign-off
- handoff_in: two-card stack enters already resting — "Real-Time Crop Health Mapping" bright in the focal slot (top edge ~34% frame height), "Autonomous Flight Paths" dimmed above it (top edge ~18%), both static — matching Frame 3's exit exactly before Scene 2's final step

Adapt: the feature stack completes its third and final step (keeping the SNAP signature from Frames 2–3), holds long enough for the rule-of-three to read, then clears — a grid slide-up fly-out — and hands off to a held brand card (reprising Frame 1's pop + glow, smaller and calmer, as the closer rather than the opener).
Scene 1 (0.0–0.4s): the two-card stack holds from the incoming push-slide (feature 2 bright, feature 1 dimmed above); kicker ticks to "feature 03".
Scene 2 (0.4–1.6s): the stack steps up its final slot — feature 2 dims — as "Precision Spot Spraying" springs into the focal slot with the same marker-pop + bullet draw-in + pill mask-wipe. All three cards now stacked, one bright, two dimmed above.
Scene 3 (1.6–2.6s): the completed three-card stack holds briefly so the set of three reads as complete; kicker reads "03/03".
Scene 4 (2.6–3.4s): the whole stack and kicker clear off-frame together — a grid slide-up fly-out, translating up and fading.
Scene 5 (3.4–5.0s): the SkyHarvest wordmark settles dead-center with a soft fire-orange glow bloom (Frame 1's move, reprised at lower intensity), spring-settles small, and holds static to the final frame — Centered, ~30% of frame width, top ~83% only.

narrativeRole: Closes the three-feature list and hands off to the held brand mark — the video's last frame.
keyMessage: SkyHarvest.

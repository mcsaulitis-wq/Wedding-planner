---
workflow: product-launch-video
flow: automation
storyboard: no
message: "SkyHarvest brings precision farming from above"
destination: shorts
aspect: 1080x1920
language: en
length: 15s
angle: dark, tech-forward precision-agriculture capability showcase
---

## Intent

A 15-second vertical launch video for SkyHarvest, a placeholder agricultural-drone
brand (no real product URL or brand assets supplied — user explicitly chose a
generic/fictional stand-in to demo the pipeline, swappable later). Dark,
tech-forward aesthetic. Confident and precise, not playful.

## Customizations

- Animated title entrance with a subtle glow.
- Feature-list card transition showcasing three placeholder features: "Autonomous
  Flight Paths", "Real-Time Crop Health Mapping", "Precision Spot Spraying" — each
  card gets roughly 2s given the 15s runtime.

## Notes

- No site to scrape: text-only / no-capture mode. A shipped dark preset supplies
  the design system since no brand tokens were captured.
- 15s is tight for a title beat + 3 feature cards + outro — no separate closing
  CTA card; the last feature card carries the brand sign-off.
- Background audio was requested but this container is not signed in to HeyGen
  (browser OAuth and device-code login are both unavailable in this headless
  remote environment, and no API key was supplied) and MusicGen's offline deps
  are not installed. User chose to build silent for now (`music: none`, no
  `SCRIPT.md`) — visuals only. Add music later by signing in
  (`npx hyperframes auth login --api-key`) or supplying a track.

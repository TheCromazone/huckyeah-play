# HUCK YEAH — playable build

This repository holds **only the built game**, published so it can be played in a browser
on phone and desktop. The source lives in a private repository; nothing here is hand-written.

Play it: https://thecromazone.github.io/huckyeah-play/

Ultimate frisbee, disc golf and Goaltimate. Real rules, real rosters, and a disc modelled on
validated aerodynamics rather than a parabola.

## What is deliberately not in here

- **The soundtrack.** `public/audio/theme.mp3` is licensed for local play only and is stripped
  from every public build by `tools/prune-dist.mjs`, which fails the build if it survives. The
  game degrades silently without it.
- **Generation source art** — 50MB of provenance that nothing fetches at runtime.

## Assets

Club crests and kits are **original designs** in each club's real colourway. They do not
reproduce, trace or imitate any real club's actual logo or jersey graphics. Team and player
names are factual. No real person is depicted.

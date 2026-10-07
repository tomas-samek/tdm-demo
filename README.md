# TDM Engine — demo

**Play it here: https://tomas-samek.github.io/tdm-demo/**

TDM Engine is a toy visualization made for a kids' school project. It shows
atoms and molecules as little networks that take in "noise" every tick, stretch,
store what they can and give off the rest — until a bond snaps or a heavy
nucleus falls apart.

> **This is not real physics.** There are no real equations behind it; it is a
> picture of an idea, built to be fun to watch. Please don't use it to learn
> chemistry or nuclear physics.

## Things to try

- Open **Choose atoms…** in the top bar and pick **Uranium (U-238)** from the
  presets, set the noise to **100** and press **Start**. Watch the event log
  at the bottom as the nucleus decays.
- Start with methane (CH4) or water (H2O) at a low noise, then raise it step
  by step and watch the bonds stretch.
- Drag the 3D view on the right to turn the structure around.
- **Pause** and **Reset** whenever you like.

It works best on a computer, or on a tablet held sideways.

## What is in this repository

Only the finished browser build: `index.html`, one `.js` file and one `.wasm`
file. The source code is private. Each commit message names the engine version
it was built from.

## License

The demo is © 2026 Tomáš Samek, all rights reserved — see [LICENSE](LICENSE).
It includes open-source libraries; their notices are in
[THIRD_PARTY_LICENSES.html](THIRD_PARTY_LICENSES.html).

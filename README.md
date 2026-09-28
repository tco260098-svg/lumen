# LUMEN — a pocket light-synth

Turn your phone's touchscreen into a playable instrument of light and music.
No installs, no desktop, no build tools — just one HTML file.

**Play it live:** https://tco260098-svg.github.io/lumen/

## How to play

- **Tap anywhere to ignite.** Headphones recommended.
- **Touch and slide** — height is pitch, side of the screen is stereo, speed is intensity.
  Slide slowly for calm, fast for sparkle storms.
- It's tuned to pentatonic scales, so anything you play sounds good — you cannot hit a wrong note.
- The **diamond button** switches scenes, each with its own music, tempo and physics:
  - **Aurora** — drifting curtains of light, dreamy pads
  - **Galaxy** — an orbiting starfield with a beating core, half-time groove
  - **Plasma** — molten orbs that chase your fingers, four-on-the-floor heat
- **REC** records a video clip (with sound) you can save or share.
- **?** opens settings: percussion, arpeggio, tilt & shake steering, fullscreen.
- Enable **Tilt & shake**, then physically shake your phone to jump scenes; tilt steers the stars.

## Make it feel like a native app

On iPhone: open the link in Safari → Share → **Add to Home Screen**.
On Android: Chrome menu → **Add to Home screen**. It launches fullscreen like an app.

## Tech notes

Built with the Web Audio API (synthesized live — oscillators, filters, convolution reverb,
a generative scheduler for pads/arps/drums) and Canvas 2D with additive glow rendering.
Zero dependencies, zero frameworks, single file, ~37 KB.

## License

MIT — do whatever you like. Made for Thomas.

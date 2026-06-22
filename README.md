# Curiosity, Passion, and Learning to Learn

A self-contained HTML presentation given at the SJSU CyberAI Summer Camp 2026 (June 22) — adapted from an earlier career-arc talk into a deeper dive on OpenBot for a high-school audience working with edge AI hardware.

## View

**Live:** https://thias15.github.io/openbot-sjsu-2026/

Or open `index.html` locally in any modern browser. No build, no dependencies.

### Videos online

The videos live on **Git LFS** and aren't served by GitHub Pages. They're attached to release **`v1.0`** instead. When `index.html` is opened over `http(s)://`, a small JS shim rewrites every `<video>` `src` from `media/<file>.mp4` to `https://github.com/thias15/openbot-sjsu-2026/releases/download/v1.0/<file>.mp4`.

When opened locally via `file://`, the same paths resolve against the on-disk `media/` directory and play directly — no network.

## Navigate

- **Arrow keys** or **space** — next slide / advance reveal
- **Bottom dots** — jump to any slide
- **Animations toggle** — bottom nav bar

## Structure

- `index.html` — entire presentation (HTML + CSS + JS in one file)
- `media/` — images and video assets (topic-based names: `lego.jpg`, `rc_truck_exterior.jpg`, `cil_diagram.png`, etc.)

## References

- SJSU CyberAI Summer Camp 2026: https://www.sjsu.edu/cmpe/resources/cybercamp.php
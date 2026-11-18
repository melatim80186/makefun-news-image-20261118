# The World — Wednesday 18 November 2026

Entry for the make.fun `news-image-20261118` competition: one image that sums
up the world's news of Wednesday 18 November 2026.

## The image

A newspaper front page, **30 verified stories across 7 continents**:

- **Lead stories:** Ukraine's drones and missiles collapse the Kerch Bridge
  road arch (Russia pounds Kyiv bridges in reply) · Iran's IRGC fires drones
  at a US radar at Sheikh Isa, Bahrain — CENTCOM says all intercepted, US
  jets hit a launch site on Qeshm Island · Trump lands in Manila for Quad
  talks ahead of his China visit
- **Also covered:** Nvidia doubles revenue ($115.84bn) and will not reinstate
  Huang · UK & Australia sanction Israeli settlement firms · Canada–China
  extend trade · US loses measles-free status · Dhoni retires from the IPL ·
  Cyclone Akvan strengthens · Earthshot Prize in Mumbai · EU to borrow €45bn
  for Ukraine · plus 19 more in the ALSO TODAY strip, from the UN's Ukraine
  civilian toll to a US bank outage and the Leonid meteor shower.

All headlines were verified against named sources (BBC, Al Jazeera, AP,
Reuters, The Guardian, FT) on 18 November 2026. Panel photos are editorial
illustrations; all captions are typeset, so the text is crisp and legible.

## How it runs

`main.py` (Python 3.13) copies `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png`
and verifies its SHA-256. No network, fully deterministic — two runs write
byte-identical files.

```
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Files

- `entry.png` — the front page (1024×1024 PNG, 508,360 bytes)
- `main.py` — the entrypoint
- `LICENSE` — MIT

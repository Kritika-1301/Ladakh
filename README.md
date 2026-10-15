# The High Pass: Swati's Himalayan Ride (PyBe Discovery Lab)

> Discover Python Exception Handling (`try` / `except` / `else` / `finally` / `raise`) through the physical intuition of a 474 km solo Royal Enfield motorcycle ride from Manali to Leh across the Himalayas.

---

## Quick Start (Zero Build Step)

Built with pure vanilla HTML5, CSS3, and modern ES6+ JavaScript. Requires no build step, no bundlers, and no external dependencies.

### Option 1: Direct Browser Launch (Recommended)
Open `index.html` directly in any modern web browser:
```
file:///c:/Users/hs488/Downloads/ladakh/index.html
```

### Option 2: Local Static Server
```bash
# Using Python's built-in HTTP server:
python -m http.server 8088

# Open in browser:
http://localhost:8088/index.html
```

### Option 3: Streamlit Companion Deliverable
For environments supporting Streamlit (matching PRs such as Mohammad Hamdan's submission):
```bash
streamlit run app.py
```

---

## 12-Stage Himalayan Route (BRO Verified Altitudes)

The expedition traces NH-3 across 12 progressive stations verified against Border Roads Organisation (Projects *Deepak* and *Himank*) survey benchmarks:

1. **Manali Base (6,726 FT):** Verb: `pack` — Saddlebag packing and essential survival spares.
2. **Rohtang La (13,050 FT):** Verb: `wrap` — Pre-ride inspection and rockfall hazard bracketing in `try:`.
3. **Zingzingbar (14,000 FT):** Verb: `match` — Glacial torrent stall; matching electrical tool to spark plug.
4. **Baralacha La (16,040 FT):** Verb: `wire` — Razor moraine puncture; routing multiple hazards to specific handlers.
5. **Sarchu (14,070 FT):** Verb: `predict` — Flawless border run; predicting chai reward logic on clean vs breakdown days.
6. **Pang (15,280 FT):** Verb: `timer` — Canyon sunset; beating sub-zero thermometer with mandatory camp protocol.
7. **Morey Plains (15,400 FT):** Verb: `order` — 40 km plateau; arranging Swati's 4-stage routine in chronological order.
8. **Debring (15,500 FT):** Verb: `flip` — Base camp notebook; in-place morph of plain English into Python keywords.
9. **Tanglang La (17,480 FT):** Verb: `runbreak` — Summit pass simulator; running 12-line CPython script with line tracer.
10. **Karu (11,100 FT):** Verb: `tapline` — Indus Valley descent; inspecting input parsing and finding `ValueError`.
11. **Shey (11,500 FT):** Verb: `flag` — Ancient palace; placing proactive alarm flag to discover `raise`.
12. **Leh Arrival (11,562 FT):** Verb: `collect` — Shanti Stupa victory; credential issuance and HTML5 canvas download.

---

## Repository Structure

```
ladakh/
├── index.html              # Main single-page web app entry point
├── app.py                  # Single-file Streamlit companion app
├── product.md              # Complete product & pedagogical specification
├── change.md               # Antigravity v3 rebuild changelog
├── context.md              # Discovery Lab pedagogical framework & philosophy
├── README.md               # Quick start and repository guide
├── assets/
│   ├── photos/             # 12 BRO survey station backdrops (01_manali to 12_leh)
│   └── CREDITS.md          # Wikimedia Commons / CC attribution register
├── css/
│   ├── base.css            # Design tokens, typography, and reset
│   ├── hud.css             # Top navigation, 4-lamp dashboard, and audio toggle
│   ├── stage.css           # 55%+ illustration hero stage and elevation footer
│   ├── interactions.css    # Styles for 12 physical interactive verbs
│   └── quickcheck.css      # Non-blocking collapsible MCQ drawers
├── js/
│   ├── scenes.js           # 12-scene single source of truth data schema
│   ├── schema.js           # Runtime data schema validator
│   ├── engine.js           # Story state machine, audio triggers, navigation
│   ├── audio.js            # Dependency-free Web Audio synthesizer
│   ├── dragkit.js          # Touch/mouse drag-and-drop toolkit
│   ├── certificate.js      # HTML5 canvas certificate generator and exporter
│   ├── simulator.js        # CPython execution simulator for Tanglang La
│   └── interactions/       # 12 standalone verb controllers (pack, wrap, etc.)
├── docs/
│   ├── altitudes.md        # Official BRO elevation survey source data
│   ├── audit.md            # Phase 0 audit and rebuild directives
│   └── pr-review.md        # Concepts borrowed from Summer '26 intern PRs
└── tools/
    ├── validate-scenes.mjs  # Gate 1: Scene schema, photo, and altitude validator
    ├── lint-text.mjs        # Gate 2: Word budget and MCQ balance linter
    ├── verify_python.py     # Gate 3: 16-combination CPython execution matrix
    └── check-assets.mjs     # Gate 7: Asset footprint and attribution checker
```

---

## Automated Quality Gates

Run all automated quality tests with standard Node.js and Python tools:

```bash
# Quality Gate 1: Scene Schema & BRO Altitudes
node tools/validate-scenes.mjs

# Quality Gate 2: Text Budgets & MCQ Balances
node tools/lint-text.mjs

# Quality Gate 3: CPython 16-Combination Matrix
python tools/verify_python.py

# Quality Gate 7: Asset Footprint & Credits
node tools/check-assets.mjs
```

All 4 quality gates pass with a 100% pass rate.

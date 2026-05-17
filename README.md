# REWIRE THE BRAIN

**The Trading Psychology Game Show**
Trade Like an Algo · Track B · Module 01

A cinematic Millionaire-style quiz game built around the M1 Psychology Masterclass curriculum. Answer 12 questions about neuroplasticity, the three parts of the mind, and Mark Douglas's Five Fundamental Truths — escalating from $100 to $1,000,000. Three lifelines. Two safety nets. One shot.

Hosted by PA Monty.

---

## ▸ PLAY IT

**Live:** [Add your GitHub Pages URL here once deployed]

**Local:** Open `index.html` in any modern browser.

---

## ▸ HOW IT WORKS

- **12 questions**, escalating difficulty, escalating prize money ($100 → $1,000,000)
- **2 safety nets** at $16,000 (after Q7) and $250,000 (after Q11) — bank these for life
- **3 lifelines:**
  - `50:50` — eliminate two wrong answers
  - `ASK COHORT` — see how 1,000 traders answered
  - `ASK MENTOR` — PA Monty's specific advice with confidence rating
- **WALK AWAY** anytime — bank what you have
- **Final answer lock-in** with dramatic suspense pause before reveal
- Wrong answer drops you to the last safety net

---

## ▸ KEYBOARD CONTROLS

| Key | Action |
|-----|--------|
| `A` `B` `C` `D` | Select answer |
| `1` | 50:50 lifeline |
| `2` | Ask the Cohort |
| `3` | Ask the Mentor |
| `W` | Walk away |
| `Enter` | Confirm / Continue |
| `Esc` | Cancel lock-in |

---

## ▸ FILES

```
.
├── index.html              # The game (single file, all CSS/JS inline)
├── pa_monty_host.jpg       # Static host portrait (fallback)
├── tla_logo.png            # TLA brand mark
├── KLING_VIDEO_PROMPTS.txt # Prompts to generate animated host videos
├── 404.html                # Brand-matching error page
└── README.md
```

**Optional video files (animated host):**
```
host_idle.mp4         # Neutral attentive (default state)
host_locking.mp4      # Intense lean-in (during "Final Answer?")
host_correct.mp4      # Approving nod (correct answer)
host_wrong.mp4        # Disappointed head shake (wrong answer)
host_celebrate.mp4    # Big celebration (safety nets, $1M win)
host_mentor.mp4       # Speaking gesture (Ask Mentor lifeline)
```

Generate these in Kling using the prompts in `KLING_VIDEO_PROMPTS.txt`. The game works perfectly without them (falls back to the static portrait) — but with them, PA Monty reacts on camera like a real game show host.

**Audio:** Procedural music + SFX generated live in the browser via Web Audio API. No audio files. Ambient bed during reading → tension riser on lock-in → victory pad on correct / dirge on wrong. Toggle with the ♪ button or `M` key.

No dependencies. No build step. Pure HTML/CSS/JS.

---

## ▸ DEPLOYMENT

**GitHub Pages:**

1. Push this repo to GitHub
2. Settings → Pages
3. Source: `Deploy from a branch` → `main` → `/ (root)`
4. Save — your game is live at `https://[username].github.io/[repo-name]/`

**Other static hosts:** Netlify, Vercel, Cloudflare Pages all work out of the box. Just deploy the folder.

---

## ▸ EDUCATIONAL DESIGN

Every question pulls directly from the M1 Psychology Masterclass study guide:

- Neuroplasticity & Hebb's Law
- The three parts of the mind (conscious / subconscious / unconscious)
- The whole-brain state
- Mark Douglas's Five Fundamental Truths
- The 21-day / 66-day habit wiring framework (Lally et al., 2010)
- Decision fatigue, subconscious hijacks, and the daily reconditioning protocol

The win lesson reinforces the core takeaway: **knowing isn't doing.** Game completion is practice — the daily protocol is the real rewiring.

---

## ▸ CREDITS

Designed by Marlon Vincent (PA Monty) · TCBT LLC
Part of the *Trade Like an Algo* mentorship · Track B Psychology Masterclass

© 2026 TCBT LLC. All rights reserved.

---

*Engineered for Consistency · Built for Discipline*

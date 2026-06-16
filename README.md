# CCNA · Bring the Network Online

A self-contained study tracker for the **Cisco CCNA 200-301 (v1.1)** exam. Every task you complete lights a port green; phases go from `OFFLINE → BRINGING UP → ONLINE`; the goal is a fully online network — i.e. a passed exam.

> **Target:** pass by **Q1 2027** · **Budget:** ~5–6 hrs/week · **Method:** lab-first, one topic at a time.

It's one HTML file with no build step and no dependencies. It runs offline, saves your progress on your device, and installs to your phone home screen like an app.

---

## Quick start

**On your phone (recommended):**
1. Open `index.html` — easiest via free [GitHub Pages](SETUP.md) so it gets a real URL.
2. In your browser: **Share → Add to Home Screen.**
3. Tap the icon. It opens full-screen, like an app. Progress saves automatically.

**On your laptop:** just double-click `index.html`. That's it.

Full deployment walk-through → **[SETUP.md](SETUP.md)**.

---

## What's inside

| File | What it is |
|------|------------|
| `index.html` | The interactive dashboard — progress, port LEDs, streaks, countdown, daily drills, go-live gate |
| `schedule.md` | The full written breakdown — every phase, every task, in plain markdown (readable on GitHub) |
| `SETUP.md` | How to get it on GitHub Pages + your phone home screen |
| `manifest.json` | Makes it install as a standalone app |

---

## The build, at a glance

| Phase | Segment | Est. |
|-------|---------|------|
| 00 | Foundation Lock-In | ~2–3 wk |
| 01 | Switching & VLANs | ~6–8 wk |
| 02 | Routing & OSPF *(biggest)* | ~8–10 wk |
| 03 | IP Services | ~3–4 wk |
| 04 | Security Fundamentals | ~4–5 wk |
| 05 | Automation & Programmability | ~3–4 wk |
| 06 | Exam Prep & Go-Live | ~4–6 wk |

Roughly 8–10 months at ~5–6 hrs/week → lands in Q1 2027.

## The three rules

1. **Lab everything.** CCNA tests configuration, not recognition. At least half your time is in Packet Tracer, typing commands.
2. **One topic at a time.** Master it, then move. No stacking.
3. **Two sources of practice questions, no brain dumps.** Learn with Jeremy's IT Lab, stress-test with Boson. Memorising leaked answers is a guaranteed fail.

## Materials

- **Jeremy's IT Lab** *(free, YouTube)* — primary course, with Packet Tracer labs + Anki decks
- **Cisco Packet Tracer** *(free)* — the lab simulator; non-negotiable
- **Anki** *(free)* — daily spaced repetition
- **Boson ExSim-Max** *(paid)* — gold-standard practice exams, for Phase 06
- **Wendell Odom – Official Cert Guide (OCG)** *(paid book)* — authoritative reference, fill gaps
- Backups: Neil Anderson (Udemy), CBT Nuggets, Cisco Networking Academy / Skills for All

---

*Progress is stored locally in your browser (`localStorage`). Clearing site data or using private mode wipes it. There's a reset button at the bottom of the dashboard if you ever want a clean slate.*

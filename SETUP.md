# Setup — get it on GitHub and onto your phone

Three ways to use this, from zero-effort to proper-app. You don't need to be a GitHub expert.

---

## Option A — just use it now (no GitHub)

- **Laptop:** double-click `index.html`. Done.
- **Phone:** email/AirDrop `index.html` to yourself, open it. Progress saves on that device.

The only downside: no permanent URL, so "Add to Home Screen" is less reliable. For the real app feel, do Option B.

---

## Option B — GitHub Pages (recommended, free, ~5 min)

This gives the dashboard a real web address you can pin to your phone.

> ⚠️ I can't create the repo for you — that needs access to your GitHub account. These are the steps to do it yourself. It's quick.

1. **Make a GitHub account** if you don't have one → [github.com](https://github.com).
2. **New repository:** top-right **+** → *New repository*. Name it e.g. `ccna-study`. Set it **Public**. Create.
3. **Upload the files:** on the repo page → *Add file* → *Upload files*. Drag in **all four files** (`index.html`, `manifest.json`, `README.md`, `schedule.md`). Commit.
4. **Turn on Pages:** repo **Settings** → **Pages** (left sidebar) → under *Source* pick **Deploy from a branch** → branch **main**, folder **/ (root)** → **Save**.
5. Wait ~1 minute. Pages shows your live URL:
   `https://YOUR-USERNAME.github.io/ccna-study/`
6. Open that URL on your phone. → Option C.

**Updating later:** edit a file on GitHub (pencil icon) or re-upload. Pages redeploys automatically. Your *progress* lives in your phone's browser, not the repo, so updates won't wipe your ticks.

---

## Option C — add to your phone home screen

Once you've got the Pages URL open in your phone browser:

**iPhone (Safari):**
- Tap **Share** (square with up-arrow) → **Add to Home Screen** → **Add**.
- It opens full-screen, no browser bars, dark themed — like a native app.

**Android (Chrome):**
- Tap **⋮** (top-right) → **Add to Home screen** / **Install app** → **Install**.

The `manifest.json` is what makes it launch standalone with the right icon and colours.

> Use the **same browser** each time — progress is stored per-browser. If you add it to your home screen and also open it in a different browser, they keep separate progress.

---

## If progress ever disappears

Progress is saved in your browser's `localStorage`. It's wiped if you:
- clear browsing data / site data,
- use private/incognito mode,
- open it in a different browser or device.

There's no cloud sync — that's the trade-off for something this simple and private. If you want a backup, just note your current phase. There's also a **reset** button at the bottom of the dashboard for a deliberate clean slate.

---

That's it. Pin it, open it daily for the drills, and watch the ports go green.

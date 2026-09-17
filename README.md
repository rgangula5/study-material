# Study Material — CSS · React · JS · TS · Behavioral

Frontend interview / study notes, organized into tabs, with an editable in-browser viewer.
Built from Word notes (`CSS`, `React Router`, `React Interview Questions`,
`JavaScript and TypeScript`, `Prep`, `Questions`) — all text kept as-is, and every code
**screenshot transcribed into real, copyable code**.

## 🚀 Live site

**▶ https://rgangula5.github.io/study-material/**

Tabs: **CSS · React · JavaScript · TypeScript · Behavioral**

## Features

- **5 tabs**, each with a searchable topic list on the left and the content on the right.
- **Code snippets** render in monospace with **no word-wrapping** (horizontal scroll) and a **Copy** button.
- **✏️ Edit mode** — everything is editable in the browser:
  - Edit any text or code block; edit topic titles.
  - **+ Text** / **+ Code** to add blocks; reorder (↑ ↓) or delete (✕) blocks.
  - **+ Add topic** and **🗑 Delete topic**.
  - Changes **auto-save to your browser** (localStorage) — no server needed.
- **⬇ Export / ⬆ Import** — download your edits as `data.json` (commit it to publish
  permanently), or load a `data.json` on another device.
- **↺ Reset** — discard local edits and reload the published version.

## How editing + publishing works

The site is static (GitHub Pages), so your edits live in **your browser** until you save them:

1. Turn on **✏️ Edit**, make changes (auto-saved locally).
2. Click **⬇ Export** to download an updated `data.json`.
3. Replace `data.json` in this repo with it and commit → changes go live for everyone.

## Files

- **`index.html`** — the whole app (tabs, viewer, editor).
- **`data.json`** — all the content (topics → text/code blocks). Edit via the app or by hand.

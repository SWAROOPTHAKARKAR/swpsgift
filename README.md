---
title: SWP'sGift
emoji: 🛡️
colorFrom: indigo
colorTo: blue
sdk: docker
app_port: 7860
pinned: false
short_description: Free AI-text and plagiarism checker, no word limit.
---

# SWP'sGift

Free AI-writing and plagiarism checker. No word limit, 25 MB per file, no sign-up.

- **AI likeness** — explainable stylometric scoring per sentence, per paragraph and for the whole
  document, with the passages highlighted.
- **Plagiarism** — eight-word fingerprint matching against the reference library you build on the
  `/library` page, with matched passages shown side by side with their source.
- **Optional web search** — set `SERPAPI_KEY` as a Space secret to search public pages too.
- **Reports** — every check produces a printable report.

The library starts empty, so add a few reference documents before expecting plagiarism hits.
Storage on this Space is ephemeral: the library resets when the Space is rebuilt.

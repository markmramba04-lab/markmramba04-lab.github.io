# markmramba04-lab.github.io
# The Living Museum · Makumbusho Hai

A community-powered, interactive oral-history archive that records and preserves
Tanzania's oral heritage — in the storyteller's own voice — before it disappears.

Every year, elders and everyday witnesses to Tanzania's history pass away, and
their stories vanish with them. Traditional museums keep the object but lose the
voice. The Living Museum is a different model: a free, bilingual (English /
Swahili) web archive where stories are recorded with consent, kept in their
original language, mapped to where they happened, and owned by the communities
they come from.

> ⚠️ **Status: prototype / demo.** This is a working front-end with sample
> content. Stories are currently bundled with the app, and visitor-generated
> data (comments, votes) is stored in the browser only. There is no backend or
> shared database yet. See [Known limitations](#known-limitations).

## Features

- **Browse stories** with search and filtering by region.
- **Individual story pages** with audio playback, transcripts, historical
  context, and source/attribution notes.
- **Story map** — each story is pinned to the place it comes from (Leaflet).
- **Timeline** of recently added stories.
- **Contributors** directory.
- **Contribute** page for adding a voice.
- **Bilingual UI** with an English / Swahili toggle.
- **Comments and reactions** on each story (saved locally in the browser).
- Animated, responsive interface.

## Tech stack

- **React 18** (single-page app)
- **react-router** (hash-based routing)
- **Framer Motion** — animation
- **Leaflet** — interactive story map
- **Tailwind CSS** — styling
- Builds to a single self-contained HTML file with media embedded.

<!-- FILL IN: add your build tool (e.g. Vite) and Node version if you want
     contributors to rebuild from source. The uploaded file is the built
     output, so the original source/build config isn't shown here. -->

## Getting started

This repository (as provided) is the **built output**: a single `index.html`
that runs on its own.

To view it:

1. Download `index.html`.
2. Open it in a modern web browser, **or** serve it locally:
   ```bash
   npx serve .
   ```
   then open the printed URL.

<!-- FILL IN: if you have the original source project (components, package.json,
     build config), add the real dev commands here, e.g.:
     git clone <repo>
     npm install
     npm run dev
-->

## Known limitations

Being honest about what this prototype does **not** yet do:

- **No backend.** Stories are hardcoded into the app. Adding a story through the
  Contribute page does not yet persist to a shared database.
- **Comments and votes are local only.** They are saved in each visitor's own
  browser (localStorage) and are not shared between users or devices.
- **Sample content.** Some images and entries are placeholders/illustrative and
  should be verified before being treated as a definitive record.

## A note on the content

Stories are presented respectfully and, where possible, with their original
audio and source context. Some historical details cannot be independently
verified, and some voices in these stories were never recorded. Where a figure
or claim is uncertain, it is framed as such rather than asserted as fact.

## License

<!-- FILL IN: choose one, e.g. MIT, or "All rights reserved" / "TBD".
     Consider how this interacts with community ownership of the stories
     themselves — the code license and the content rights can differ. -->
TBD

## Acknowledgements

Built to preserve Tanzania's oral heritage through technology — one voice at a
time. With gratitude to the storytellers, elders, and contributors whose voices
make this archive what it is.

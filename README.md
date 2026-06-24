# PlayStation Interview Deck

Static HTML interview presentation.

**Live:** https://playstation-interview-deck.onrender.com/

## Render setup

1. [dashboard.render.com](https://dashboard.render.com) → **New** → **Static Site**
2. Connect **GitHub** → select **`ND1-Sdo/playstation-interview-deck`**
3. Branch: `main` · Publish directory: `./` (root)
4. Create Static Site

Or: **New** → **Blueprint** → paste this repo’s `render.yaml`.

## Update deck

Source of truth is edited in the Astra-Desk repo (`playstation-interview-presentation.html`), then synced here via `scripts/deploy_playstation_deck_render.sh` in that repo.

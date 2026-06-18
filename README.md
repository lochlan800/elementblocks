# Game Hub

A small games dashboard. Browse games by category, search for one, then play it.

`index.html` is the hub. Open it in any browser (or visit the deployed site) — no
install or build step needed.

## How it works

- Games are shown as cards grouped by category (Puzzle, Strategy, …).
- The **search bar** filters games live by name or category — type `chess` and the
  Chess card comes up.
- Click a card and a prompt asks **"Do you want to play?"** — **Yes** launches the
  game full-screen, **No** takes you back to the hub.
- While playing, **← Back to Games** returns to the hub, or **Open in new tab**
  pops the game out on its own.

## Games

| Game | Category | Where it lives |
| --- | --- | --- |
| **Element Blocks** | Puzzle | `elementblocks.html` in this repo |
| **Chess** | Strategy | the separate [`Chess-`](https://github.com/lochlan800/Chess-) repo, loaded from its live site |
| **Money Clicker** | Idle | the separate [`Clicker`](https://github.com/lochlan800/Clicker) repo, loaded from its live site |

### Adding a game

Edit the `GAMES` array near the top of the `<script>` in `index.html` — each entry
has a name, category, icon, short description, and a `url` (a file in this repo or
any web address).

## Element Blocks

A Block Blast–style puzzle: drop elemental shapes on an 8×8 grid, clear full rows
and columns, build combos and pure-element bonuses, collect stars to buy bombs,
and survive the shrinking turn timer as the difficulty climbs. See the in-game
intro cards for the full scoring rules.

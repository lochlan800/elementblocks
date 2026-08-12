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
| **Gem Swap** | Puzzle | `gems/` in this repo |
| **Wordle** | Word | `wordle/` in this repo (copied from [`Wordle`](https://github.com/lochlan800/Wordle)) |
| **Chess** | Strategy | the separate [`Chess-`](https://github.com/lochlan800/Chess-) repo, loaded from its live site |
| **Money Clicker** | Idle | `clicker/` in this repo |
| **Cannon Smash** | Arcade | `cannon/` in this repo |
| **Uno** | Cards | `uno/` in this repo (copied from [`Uno`](https://github.com/lochlan800/Uno)) |
| **Guess Who** | Party | `guesswho/` in this repo (copied from [`Guess-who`](https://github.com/lochlan800/Guess-who)) |

### Adding a game

Edit the `GAMES` array near the top of the `<script>` in `index.html` — each entry
has a name, category, icon, short description, and a `url` (a file in this repo or
any web address).

## Element Blocks

A Block Blast–style puzzle: drop elemental shapes on an 8×8 grid, clear full rows
and columns, build combos and pure-element bonuses, collect stars to buy bombs,
and survive the shrinking turn timer as the difficulty climbs. See the in-game
intro cards for the full scoring rules.

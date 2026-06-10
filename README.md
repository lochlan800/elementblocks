# Element Blocks

A Block Blast–style puzzle game with an elemental twist, in a single HTML file.

## How to play

Open `index.html` in any modern browser — no install or build step needed.

- Drag shapes from the tray onto the **8×8 grid** (mouse or touch).
- A green preview shows where the shape will land; red means it doesn't fit.
- Placing a shape scores **20 points**. Fill an entire **row or column** to
  clear it: 1 line scores **180**, 2 at once **375**, 3 at once **580**, and
  4 at once **800**. Collected stars are worth **12 points** each.
- **Combo streak**: clear lines on back-to-back placements and the line bonus
  is multiplied — ×2 on the second clear in a row, ×3 on the third, and so on.
  A placement that clears nothing resets the streak.
- **Pure element line**: clear a line made entirely of one element and the
  line bonus is **tripled** (stacks with the combo streak).
- You're dealt **3 shapes** at a time; a new set arrives once all three are placed.
- **Difficulty climbs with every set** — watch the gauge next to the bomb
  button fill toward red: shapes get bigger, helpful deals get rarer, and the
  turn timer shrinks from 15 seconds down to 9.
- You have **15 seconds** to place all 3 shapes (less at higher difficulty) —
  the timer resets when a new set arrives, and the game ends if it runs out.
- The game also ends when none of your remaining shapes fit anywhere on the grid.
- Your best score is saved in the browser.

Blocks come in five elements — fire, water, earth, air, and lightning — each with
its own glow.

## Stars and bombs

- Every 20 seconds, a ⭐ lands on a random block on the grid.
- Clear a line containing starred blocks and the stars fly into the 💣 button.
- Collect **15 stars** to buy a bomb, then click the 💣 button and pick a spot on
  the grid: everything in a 3×3 blast disappears. Stars and bombs are saved
  between sessions.

A synthesized high-energy chiptune soundtrack loops in the background — 135 BPM
EDM drums, punchy synth bass, and a bright 16-bit lead. It starts as soon as you
first click or touch the page (browsers require an interaction before audio).

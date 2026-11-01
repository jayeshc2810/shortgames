# Short Games

A small collection of browser games. Each game is **one self-contained HTML file** — no build step, no install, no server. Download a file, open it in a browser, and play.

## The games

| Game | File | Players | In one line |
|---|---|---|---|
| **Beyond Chess** | [`beyond-chess.html`](beyond-chess.html) | 1–2 (human or AI) | Chess with odd pieces and board hazards |
| **The Inspector's Casebook** | [`inspectors-casebook.html`](inspectors-casebook.html) | 1 | Original detective mysteries — gather clues, then name the culprit |
| **Catan · Cities & Knights · Seafarers** | [`catan-cities-knights-seafarers_game.html`](catan-cities-knights-seafarers_game.html) | 3–4 (hot-seat + bots) | Base game with both expansions on one board |
| **Siege** (deckbuilder) | [`siege.html`](siege.html) | 1 | Hold the wall for ten waves with a deck of siege cards |
| **Siege** (playing cards) | [`card_siege.html`](card_siege.html) | 1 | The same idea as a solitaire for one standard 52-card deck |
| **Knight Lights** | [`knight_lights.html`](knight_lights.html) | 1 | Lights-out puzzle wired by knight moves |

---

### Beyond Chess
Regular chess, plus up to **two special pieces** and **one board hazard**, with both sides getting the same set.

- **Special pieces:** Bomber, Chameleon, Drunk Knight, Ghost, Mole, Necromancer, Swapper, Vampire and more
- **Hazards:** Black Hole, Portals, Snails, Tornado, Zombies (or none), triggering every few moves
- Play human vs human, human vs AI, or watch AI vs AI, with selectable AI levels
- Undo, flip board, move list and captured-piece tracker
- Checkmate, stalemate and the 50-move rule work as usual. Hazards never harm kings, except the Black Hole.

### The Inspector's Casebook
Original mysteries in the classic consulting-detective style. Read the case, question people, follow the clues and make your accusation.

Cases include *The Blackthorn Hall Affair*, *The Vanishing at Bexley Curve*, *The Ravenscroft Light*, *The Whitmoor Séance*, *The Snow at Kilnbrae*, *The Drop at the Peregrine*, *Four Days out of Port Said* and *The Mirrors of Ranipur*.

### Catan · Cities & Knights · Seafarers
A hot-seat board for 3–4 players with computer opponents.

- City improvements, knights, the barbarian track and seafaring in one game
- Bot trade offers, and an adjustable bot speed (Slow / Normal / Fast / Instant)
- Built-in rules and costs reference, game log and standings

### Siege (deckbuilder) — `siege.html`
Defend a wall against ten waves of attackers. Spend supply each turn to play cards: Volleys (Arrow Shot, Longbowmen, Boiling Oil), Engines (Ballista Bolt, Trebuchet), Works (Barricade, Shield Wall, Masons' Guild) and Orders (Muster, Quartermaster, Sortie). Build guard, repair the wall, and survive.

### Siege (playing cards) — `card_siege.html`
A solitaire version for one ordinary deck. Black cards are the attackers; your hand of red cards is the garrison. Tap hearts to muster their total, then tap an attacker to strike. Hold the wall until the siege lifts.

### Knight Lights
Every bulb is wired to the squares a chess knight could jump to. Tapping a bulb flips it and all of its knight-move neighbours — light the whole board.

- Board sizes from 2×2 to 10×10, every one solvable from all-dark
- Move counter with a par score, two hints per puzzle, and sound toggle
- Order never matters, and tapping twice cancels out, so a solution is just a set of squares

---

## How to play

**Locally:** clone or download the repo and open any `.html` file in a modern browser (Chrome, Edge, Firefox or Safari).

```bash
git clone https://github.com/jayeshc2810/shortgames.git
cd shortgames
# then double-click any .html file
```

**Online:** enable GitHub Pages (Settings → Pages → deploy from the `main` branch, root folder), and each game becomes playable at
`https://jayeshc2810.github.io/shortgames/<file-name>.html`

The games work offline. Some load Google Fonts when online and fall back to system fonts without a connection. Beyond Chess saves your setup in the browser's local storage.

## Built with

Plain HTML, CSS and vanilla JavaScript, with inline SVG for boards and pieces. No frameworks or dependencies.

## Disclaimer

The Catan game here is an unofficial fan-made project for personal use. *CATAN*, *Cities & Knights* and *Seafarers* are trademarks of their respective owners; this project is not affiliated with or endorsed by them.

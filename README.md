# Lords & Domains

Two strategy games in one little HTML file, set in the same world.

- **Lords & Domains** is the hidden-Lord board game. It takes its ideas from games like Stratego, but it's built around alliances, bluffs and betrayals. Each domain hides its Lord among its own pieces, and you have to find theirs before they find yours.
- **The First Crown** is the prequel, a world conquest game in the spirit of Risk. Long before the domains, warlords fought for the whole world. Whoever united it would raise the drowned isle of Thalmar from the sea and set the First Crown on it.

> Long ago the First Crown raised the isle of Thalmar from the sea and bound its stones with an oath: the land would stand for as long as one Lord ruled it. The last High Lord drowned without an heir, and now the domains claim the crown.

## Play

Open `index.html` in any modern browser. There's nothing to install and no sign-up, and it works offline. The pixel font loads from Google Fonts when you're online; offline it falls back to a monospace font.

On the title screen, pick **⚔ Lords & Domains** or **👑 The First Crown**. New to Lords & Domains? Press **Walkthrough** and it plays a real game with you, step by step.

---

## Lords & Domains

### Setting up a game

The setup screen has quick presets and full options:

- **Presets:** First Edition, Duel, Six-way war, Team battle and Quick skirmish.
- **Domains:** 2 to 6 domains, anything from a 1 v 1 duel to a six-way war. Each one can be a human or a computer on Easy, Normal or Hard. When several humans play on one screen (hotseat), the board hides between turns.
- **Teams:**
  - Every domain for itself.
  - 2 v 2 with four domains.
  - 3 v 3 or 2 v 2 v 2 with six.

  You see your allies' pieces, you can't attack them, and your team wins together.
- **Board:** a six-sided field of hexes, or a square field of squares. The board grows or shrinks with the number of domains.
- **Army:**
  - The full army of 14 pieces.
  - The **First Edition** army of 10 pieces: Lord, Marshal (8), Knight (7), Captain (6), Guard (5), Raider (4), Scout (3), Spy (2), Sapper (1) and Keep.
- **First Edition preset:** the original rules. A 13 × 13 square field, ten pieces each, five domains, and the island standing still.
- **Mode:**
  - **Classic:** the island stands still. If nobody fights for 40 rounds, the strongest army is named High Lord.
  - **Decisive, the restless island:** from round 6 the island reshapes itself every round.
    - Quiet land sinks and seabed rises between rivals.
    - When the fighting stalls, a causeway (a whole line of seabed) rises between the nearest rivals, then sinks back a few rounds later.
    - Nothing is ever cut off; the sea only makes obstacles.
- **Sky and season:** leave it on Normal for a surprise season with changing weather and time of day. You can also pick a season, weather, time of day, a holiday board, or a preset such as Rainy day or Snowy night.

### Rules

- **The full army (14 pieces):** Lord, Marshal (8), Knight (7), Captain (6), Guard (5), Raider (4), four Scouts (3), two Spies (2), Sapper (1) and Keep.
- **Before the battle:** each human arranges their own pieces in secret.
- **Moving:** move one piece to a space that shares a side with it. That's six choices on the hex field and four on the square field.
  - Scouts run any distance in a straight line.
  - Keeps never move.
  - Water can't be crossed.
- **Fighting:** moving onto an enemy is an attack. Both pieces are revealed, the higher rank wins, and equal ranks both fall.
- **Special fights:**
  - A Spy that strikes a Lord first kills it. A Lord that strikes a Spy first wins.
  - A Lord who strikes another Lord wins, and the Lord who waits falls, so timing is everything.
  - A Keep destroys any attacker except a Sapper. A Sapper who breaks a Keep topples that whole domain.
- **Winning:** if a Lord falls, its whole domain falls with it. The last domain (or team) standing wins.

### Diplomacy

You get one diplomatic act per turn, before you move:

- **Offer a pact:** neither side attacks the other for 6 rounds, and each side is shown one of the other's pieces.
- **Point the finger:** turn the other domains against a rival.
- **Spread a rumour:** crown one of your own pieces so rivals think it's your Lord.
- **Betray an ally:** you can break a pact, but every domain will trust you less afterwards.

Each computer ruler has a hidden personality: Honourable, Opportunist, Warlike, Schemer, Cautious or Hunter.

### Help while you play

- **💡 Hint** (or the H key) shows the move a careful ruler would make.
- **Inspect** any unknown piece to see your spies' best guess at what it is, worked out from everything that has been revealed.
- **The Domains panel** lists the ranks each rival still has hidden.

---

## The First Crown

### The world

- There are 33 territories on seven continents: Nordhal, the Pearl Isles, Verdance, Emberreach, Sunmere, Ashkar, and Thalmar in the middle of the sea.
- Dotted lines are sea lanes. Two territories joined by a lane count as neighbours.
- Hold a whole continent at the start of your turn to earn its bonus.
- Whoever holds **the Throne** on Thalmar earns one extra army each turn.

### A turn

1. **Reinforce.**
   - You get a third of your territories (at least 3), plus your continent bonuses, plus the Throne.
   - Click your territories to place the armies, +1, +3, +5 or All at a time, or press **Place for me**.
   - You can trade a set of cards for more armies.
2. **Attack.**
   - Attack from any territory with 2 or more armies into a neighbouring enemy territory.
   - You roll up to 3 dice and the defender rolls up to 2. The highest dice are compared in pairs, and ties go to the defender.
   - **Roll** rolls once. **Blitz** keeps rolling until the territory falls or you're down to one army.
   - Your chance of taking a territory is shown before you attack. **💡 Suggest an attack** points out a good one.
3. **March in.** When a territory falls, choose how many armies move into it.
4. **Fortify.** Make one march along a chain of your own territories, and your turn ends.

### Cards

- **Earning cards:** take at least one territory in a turn and you earn a card. Each card is a Footman, Rider, Siege or Wild.
- **Trading sets:** trade three of a kind, one of each, or any two with a wild. Sets are worth 4, 6, 8, 10, 12 and then 15 armies, and 5 more each time after that.
- **Bonus armies:** a traded card that shows a territory you hold puts 2 extra armies there.
- **Must-trade rule:** with five cards you must trade.
- **Seizing cards:** drive a warlord out of the world and you take their cards.

### Setting up

- **Presets:** World war, Duel, Race for the Throne, Six warlords, Alliances.
- **Warlords:** 2 to 6, any mix of humans and computers (Easy, Normal, Hard).
- **Teams:** 2 v 2, 3 v 3 or 2 v 2 v 2. Allies can't attack each other, and they win together.
- **Victory:**
  - **World conquest:** take every territory.
  - **The Throne:** hold all of Thalmar and any two other continents at the start of your turn.
  - **Dominion:** hold 21 of the 33 territories at the start of your turn.
- **Starting armies:** placed for you, or placed yourself.
- **Fair play:**
  - The first round is a truce, so moving first isn't a big edge.
  - Later seats start with a few extra armies.
  - In a two-player game, the second player gets enough extra to make it an even contest.

---

## Look and sound

- **Two views in both games:**
  - **Field:** a low, Mode 7-style view across the island or the world. Rotate it with ⟲ ⟳ (Q/E) and zoom with + and −.
  - **Map:** the view from above. Press V to switch.
- **Battles:**
  - In Lords & Domains, every clash cuts to a pixel-art battle scene.
  - In The First Crown, attacks are fought out with dice, soldiers on both sides, and the losses counted roll by roll.
  - Battle scenes can be Full, Quick or Off.
- **Sky:** time of day, weather and seasons change as you play.
- **Music:** twelve chiptune songs. Ten follow the mood and season of Lords & Domains. *March of the First Crown* and *The World Throne* play in the prequel. Tap the song name to pick one yourself.
- **Options:**
  - Separate volume sliders for sound and music, and corner mute buttons.
  - Page theme, view, battle scenes, computer speed, and guess bars.
- **Saving:** both games save as you play, so you can continue later from the title screen.

## Files

- `index.html`: both games.
- `logo.svg`: the icon.
- `LICENSE`: MIT.

## License

MIT © 2026 Mitchell D. McPhetridge

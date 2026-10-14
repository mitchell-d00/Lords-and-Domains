# Lords & Domains

A five-player hidden-Lord strategy game, inspired by games like Stratego but built around alliances, deception, and figuring out who everyone really is.

Each domain hides its Lord somewhere among its own pieces. You know where your Lord is. Everyone else's is a mystery. Protect yours, hunt theirs, make friends, and decide when to turn on them.

Trust carefully.

## Play

Open `index.html` in any modern browser. It is one self-contained file: no install, no build tools, no sign-up, and it works offline. (The pixel font loads from Google Fonts when you are online; offline it falls back to a monospace font.)

## Modes

- **Me vs 4 computers**, each with a hidden personality: Honourable, Opportunist, Warlike, Schemer or Cautious.
- **5 players, one screen (hotseat).** The board hides between turns so nobody sees anyone else's pieces.
- **Any mix:** each domain can be a human or a computer on Easy, Normal or Hard.
- **Watch 5 computers** fight it out, with an option to reveal every piece.

## Rules

- **The island:** a 13×13 board with five lakes. Water cannot be crossed.
- **Your army:** each domain has 10 pieces: Lord, Marshal (8), Knight (7), Captain (6), Guard (5), Raider (4), Scout (3), Spy (2), Sapper (1) and Keep.
- **Before the battle:** each human ruler arranges their own pieces in secret.
- **Moving:** on your turn, move one piece one square up, down, left or right. Scouts run any distance in a straight line. Keeps never move.
- **Fights:** moving onto an enemy is an attack. Both pieces are revealed to everyone. The higher rank wins, and equal ranks both fall.
- **Special fights:**
  - A Spy that attacks a Lord kills it.
  - A Keep destroys any attacker except a Sapper.
  - A Lord who attacks another Lord wins.
- **Lords:** if a Lord falls, its whole domain falls with it.
- **Winning:** the last Lord standing wins. If no one fights for 40 rounds (or after 200 rounds), the strongest remaining army wins.

## Diplomacy

You can make one diplomatic move per turn, before you move a piece.

- **Offer a pact:** for 6 rounds neither side attacks the other. As a sign of trust, each side is shown one of the other's pieces.
- **Point the finger:** turn the other domains against a rival.
- **Rumour:** crown one of your pieces so rivals think it is your Lord. A Keep makes a nasty surprise.
- **Betrayal:** attacking an ally breaks the pact, and every domain trusts you less afterwards.

## Reading the field

- **Unknown enemies** look like hooded figures until they fight, or until an ally shows them to you.
- **Footprints:** pieces that have moved show small footprints. Keeps never move, so an unmoved piece could be a Keep, or a Lord staying hidden.
- **Hidden ranks:** the Domains panel lists each rival's ranks that are still hidden.
- **Inspect:** inspect any unknown piece to see your spies' best guess at what it is.

## Look and feel

- **Field view:** a low, Mode 7-style view from behind your domain. Rotate it with ⟲ ⟳ (Q/E) and zoom with + and −.
- **Map view:** the board from above. Press V to switch views.
- **Battle scenes:** every clash cuts to a pixel-art battle with a reveal, a strike and a shatter. Set them to Full, Quick or Off in Settings.
- **Sound:** chiptune sound effects and optional music.
- **Settings:** light and dark page themes, and computer speed.
- **Saving:** the game saves after every turn, so you can continue later from the title screen.

## Files

- `index.html`: the complete game.
- `logo.svg`: the icon.
- `LICENSE`: MIT.

## License

MIT © 2026 Mitchell D. McPhetridge

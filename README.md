# Lords & Domains

A five-player hidden-Lord strategy game, inspired by games like Stratego but built around alliances, deception, and figuring out who everyone really is.

> Long ago the First Crown raised the isle of Thalmar from the sea and bound its stones with an oath: the land would stand for as long as one Lord ruled it. The last High Lord drowned without an heir, and now five domains claim the crown.

The island is a five-sided field of hexes, and each domain starts along one side. Each domain hides its Lord somewhere among its own pieces. You know where your Lord is. Everyone else's is a mystery. Protect yours, hunt theirs, make friends, and decide when to turn on them.

Trust carefully.

## Play

Open `index.html` in any modern browser. It is one self-contained file: no install, no build tools, no sign-up, and it works offline. (The pixel font loads from Google Fonts when you are online; offline it falls back to a monospace font.)

New to the game? Press **Walkthrough** on the title screen. It plays a real game with you, step by step.

## Modes

You choose a mode at the start of every game.

- **Classic:** the island stands still. It's pure bluff and battle. If nobody fights for 40 rounds, the strongest army is named High Lord.
- **Decisive, the restless island:** from round 6 the island reshapes itself every round.
  - Empty land far from the fighting sinks into the sea.
  - Seabed rises as new land wherever it brings rival domains closer together.
  - The island never sinks a square with a piece on it and never cuts any piece off from the rest. If a piece is ever stranded, the seabed rises to bridge it back.
  - It takes no side. It only wants the oath kept, and the oath can only be kept when a single Lord stands. Every war ends with a fallen Lord or a breached Keep.

Players can be any mix of humans and computers (Easy, Normal, Hard):

- **Me vs 4 computers.**
- **5 players, one screen (hotseat):** the board hides between turns.
- **Watch 5 computers.**

Each computer ruler has a hidden personality: Honourable, Opportunist, Warlike, Schemer or Cautious.

## Rules

- **The board:** a five-sided field of hexes with lakes. Each army starts along its own side of the pentagon.
- **Your army:** each domain has 14 pieces: Lord, Marshal (8), Knight (7), Captain (6), Guard (5), Raider (4), four Scouts (3), two Spies (2), Sapper (1) and Keep.
- **Before the battle:** each human ruler arranges their own pieces in secret.
- **Moving:** on your turn, move one piece one hex in any of the six directions. Scouts run any distance in a straight line in all six directions. Keeps never move. Water can't be crossed.
- **Fights:** moving onto an enemy is an attack. Both pieces are revealed to everyone. The higher rank wins, and equal ranks both fall.
- **Special fights:**
  - A Spy that strikes a Lord first kills it. A Lord that strikes a Spy first wins.
  - A Lord who strikes another Lord first wins.
  - A Keep destroys any attacker except a Sapper.
- **How a domain falls:** if its Lord falls, or if a Sapper breaks its Keep, the whole domain falls with it.
- **Winning:** the last domain standing wins.

## Diplomacy

You can make one diplomatic move per turn, before you move a piece.

- **Offer a pact:** for 6 rounds neither side attacks the other. As a sign of trust, each side is shown one of the other's pieces.
- **Point the finger:** turn the other domains against a rival.
- **Rumour:** crown one of your pieces so rivals think it is your Lord.
- **Betrayal:** attacking an ally breaks the pact, and every domain trusts you less afterwards.

## Sky, seasons and holidays

- **Normal board:** leave the board on Normal and every game starts in a random season, with the time of day and the weather changing as you play.
- **Choosing a look:** pick a season, a weather (clear, cloudy, rain, thunderstorm, snow, fog) and a time of day (dawn, midday, golden hour, dusk, night).
- **Presets:** one tap for Rainy day, Summer storm, Golden autumn, Foggy dawn, Snowy night or Starry night.
- **Changing it mid-game:** use Settings to change the board's look while a game is running.
- **Time of day:** when it passes, a full day takes 10 rounds, from dawn through golden hour to night under the moon and stars.
- **Holiday boards:**
  - **Harvest Night:** pumpkins, candles and bats.
  - **Midwinter Lights:** snow, little pines and coloured lights.
  - **Lantern Festival:** red lanterns and cherry blossom.
  - **Hearts Day:** roses and floating hearts.
  - **Fireworks Night:** bunting and fireworks.
- **Title screen:** shows a different random battle, season and sky every time.

## Look and sound

- **Field view:** a low, Mode 7-style view from behind your domain. Rotate it with ⟲ ⟳ (Q/E) and zoom with + and −.
- **Map view:** the board from above. Press V to switch views.
- **Battle scenes:** every clash cuts to a cinematic pixel-art battle. Each side's colours sweep in, the rank match-up pops up (8 > 5, STRIKE!, KEEP!), the attacker charges with afterimages and dust, and the hit freezes the frame with a zoom, a shockwave and sparks. All of it plays under the current sky and weather. Set battle scenes to Full, Quick or Off in Settings.
- **Music:** ten chiptune songs that follow the mood and the season:
  - *The Restless Isle* (title)
  - *Banners at Dawn* (deployment)
  - *Blossom Road* (spring)
  - *Five Crowns* (summer)
  - *Falling Leaves* (autumn)
  - *Frost on the Keep* (winter)
  - *Night Watch* (night and fog)
  - *Thunder over Thalmar* (rain and storms)
  - *The Last Lord* (the final fight)
  - *Crowned at Last* (victory)

  The song that's playing is shown next to the mute buttons. Tap its name to pick any of the ten songs, or choose Auto to let the music follow the mood again.
- **Mute buttons:** sound and music each have their own mute button, always in the bottom-right corner.
- **Saving:** the game saves after every turn, so you can continue later from the title screen.

## Files

- `index.html`: the complete game.
- `logo.svg`: the icon.
- `LICENSE`: MIT.

## License

MIT © 2026 Mitchell D. McPhetridge

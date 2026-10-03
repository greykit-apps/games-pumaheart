# PumaHeart

**A medieval tactics game for two armies, Gold against Green, on a board nine squares wide and
eight deep. Two actions a turn. Facing matters, the dice decide, and a panicking unit will
shove your own line off the board.**

## Play

**<https://greykit.com/games/pumaheart/>**

Play in the browser on a desktop or a phone, against the computer or against a friend on the
same screen. Once the page has loaded it works offline, and a game in progress survives closing
the tab.

![The AI calling its shot](screenshots/aim.png)

## How to Play

### Units

A unit is a **base holding one to four identical figures**, and the figure count is everything:
it is the unit's strength and its dice pool at once. A four-man Infantry base rolls four dice;
worn down to two men it rolls two. There are no health bars — losing figures is how a unit
weakens.

### Your turn

You get **two actions a turn**, chosen from Move, Turn and Attack. You may take the same action
twice, and you may split the two between different units, but no unit attacks twice in a turn.

- **Foot soldiers** move one square forward per action.
- **Kings and Knights** ride as far as they like in a straight line until something blocks them
  (at least one square).
- **Turning** costs one action, however far the unit turns.
- **Heavy Infantry** pays two actions to move or turn, and one to attack.

### Attacking

You must be **next to and facing** what you attack, though you may strike its side or rear.
Two exceptions:

- **Archers** hit any single enemy in the block of nine squares ahead of them, firing over the
  heads of your own line.
- **Heavy Infantry** strikes any adjacent square without having to face it.

### The dice

Each die has **three battle-axes, two arrows and one PANIC**.

- Most units hit on **battle-axes**. Archers hit on **arrows**.
- **Peasants** count whichever face they rolled the most of. If that is PANIC, they panic and do
  not hit; a tie goes to the hits.
- **Knights, Kings and Heavy Infantry** must take **two hits in the same attack** to lose a
  figure.
- A **lone Infantryman or Archer** attacking one of those armoured units rolls its single die,
  and on a hit rolls it again for the second hit. A lone Peasant gets no second roll.

### PANIC

**PANIC is what makes the game.** If every die comes up PANIC, the attacking unit turns about
and retreats a square, shoving whoever is behind it into panicking too. A retreat blocked by the
board edge, an enemy, your own King or a Mercenary **kills the retreating unit**. Chain reactions
are normal, and they take your own line with them.

Peasants are worse: they retreat one square for **every** PANIC they roll.

### Mercenaries and bribes

Mercenaries never panic, and every PANIC they roll drives their victim back a square. But they
can be bought. When your King stands next to and facing an enemy Mercenary, its attack becomes a
**bribe**: no dice, it always works, and the Mercenary changes sides on the spot — it may even
act for you that same turn. A bribe is the King's one attack for the turn and costs one action.
A Mercenary whose own King is right beside it and facing it cannot be bribed and is attacked
normally instead.

### Winning

**Kill the enemy King, or leave it standing alone on the field.** If one attack leaves both
Kings alone at once, the side that made the attack wins. A game that reaches 200 rounds without
a winner is called a stalemate.

### Who goes first

Both sides roll four dice; whoever rolls the most battle-axes goes first. Ties roll again.

## The Warriors

| Warrior | You own | Per base | Dice each | Hits with | Hits to kill each | Panics |
|---|---:|---:|---:|---|---:|---|
| King | 1 | 1 | 2 | battle-axe | 2 | never |
| Knight | 4 | 2 | 2 | battle-axe | 2 | yes |
| Archer | 8 | 4 | 1 | arrows | 1 | yes |
| Infantry | 20 | 4 | 1 | battle-axe | 1 | yes |
| Heavy Infantry | 2 | 2 | 2 | battle-axe | 2 | yes |
| Peasant | 4 | 4 | 1 | axe **or** arrow | 1 | per die |
| Mercenary | 2 | 2 | 2 | battle-axe | 1 | never |

No unit ever rolls more than four dice.

## Setting Up Your Army

Every game opens on your battle plan.

1. **Muster.** Build ten bases from the figures you own. Leave the muster as it stands to field
   the standard army, or swap some of its bases for specials — Heavy Infantry, Peasants,
   Mercenaries — to make your own.
2. **Deploy.** Place every base yourself. Your King holds the royal emblem in the centre of your
   back row; everything else goes anywhere on your two ranks, facing whichever way you choose.
   Bunch in the middle, or send the riders wide to turn a flank. **Re-form the line** steps
   through eight ready-made formations you can start from and adjust.
3. **Take the field.** Both plans are laid in secret — the far side of the board is screened
   while you work, against the computer as well as a friend — and both lines are revealed
   together.

Leave the muster and the line exactly as they stand and you get the standard opening.

![Mustering a customised army](screenshots/muster.png)
![Laying the battle plan](screenshots/deploy.png)

## Opponents

- **Versus AI**, at three difficulties: **Squire** plays greedily and is blind to threats,
  **Captain** looks a turn ahead, and **Marshal** searches wider and picks stronger openings.
  The computer's moves play out one at a time. Before it attacks, it marks the attacker and the
  target so you always see who threw the dice, and where its units started and ended stay marked
  until you take your first action.
- **Hot-seat**, for two players passing one screen, with a handover screen between turns.

## House Rules

All off by default. Switch them on from **House rules** in the New Game menu.

- **Massive Infantry** — all 20 Infantry a side, up to 10 on a base, never more than four dice.
- **Bases may be under-filled** — field a three-man Infantry base or a lone Knight from the start.
- **The King deploys freely** — your King may start anywhere on your two ranks, like every other
  base.
- **Green / Gold rolls an extra die** — that side throws one die more than it is owed and
  discards the worst: a PANIC first, then a face that scores nothing. Set it for one side as a
  handicap, or for both to keep the odds level and the fights bloodier.

## Controls

Everything is done with the mouse or a finger. Click one of your bases and its legal moves ring
in cyan, and anything it can attack rings in red — click a ring to act. Or **drag the base**
where you want it and let go. The two curved arrows in a selected base's front corners turn it a
quarter turn each way; click twice for an about-face. On a touchscreen, the turn arrows sit
under the board instead.

Every attack is thrown in full view, and the field report keeps a record of each roll and what
it cost.

The keyboard can do everything too:

| Key | |
|---|---|
| arrows / WASD | move the cursor |
| Enter / Space | select, move or attack, by what is under the cursor |
| 1 – 4 | face north, east, south, west |
| Q / E | turn left / right |
| F | attack ahead |
| N / P | next / previous unit with a legal action |
| Z | undo (not back past an attack) |
| . | end turn — press twice, since it throws away any actions left |
| ? / H | help |
| M | mute |
| Escape | dismiss |

The game also offers a screen-reader commentary, and respects your system's reduced-motion
setting.

![An Archer firing over its own front rank](screenshots/archer.png)
![A panic cascade](screenshots/panic.png)
![The field cleared](screenshots/gameover.png)

## Other Puma Games

[PumaTriage](https://greykit.com/games/pumatriage/) ·
[PumaSOC](https://greykit.com/games/pumasoc/) ·
[PumaSecure](https://greykit.com/games/pumasecure/) ·
[PumaPanic](https://greykit.com/games/pumapanic/) ·
[PumaResponse](https://greykit.com/games/pumaresponse/) ·
[PumaTower](https://greykit.com/games/pumatower/) ·
[PumaClicker](https://greykit.com/games/pumaclicker/)

## Credits

Game by shandower, with AI assistance from Claude.

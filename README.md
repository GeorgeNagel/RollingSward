# Solo Narrative Minis Ruleset

## What
This rule set is designed to provide fast-paced play with a handful
of miniatures, with battles lasting about 15-30 minutes. It can be played
solo or cooperatively. Each scenario happens in a narrative framework where
every battle has a long-lasting impact. Bases should be approximately 1" around
for most characters and play happens on a 2'x2' play area.

## Why
There is a comparative lack of rulesets for solo miniatures wargaming.
Existing rulesets for miniatures games are lengthy, and individual games
take over an hour to complete. Generally, battles happen in a vacuum.

This ruleset is intended to create acrade-like fast gameplay with a
narrative framework that gives a long-lasting impact and importance
to each battle.

## Rules

### Narrative Layer

The narrative layer guides what scenarios occur in what order,
and gives a larger context to individual battles. See [LOTR](LOTR.md) for
an example.

### Battle Layer

Each scenario lays out which companies collide, their deployment on the board,
and any scenery on the play area.
Cards are created for each mini on the game board with their name, movement range,
attack modifier, defense modifier, wound slots, and shooting range if relevant.
One side is controlled by AI and the other by the player. The game takes
place over a series of rounds until either the player or the AI is routed
from the board or all units are wounded to the ground. After the game, any
wounds the player's characters sustained are resolved and play moves back to
the narrative layer.

Battles are fought on a 2' by 2' area.

Play proceeds as follows. Note that "General" means either the player
commanding friendly units or the AI commanding enemy units.

#### Deployment

1. All terrain and units are placed on the board per the narrative layer.
1. Any starting wounds on units are marked on the corresponding
characters' cards.

#### Round

1. The human general rolls a D6 to determine who starts the round. On a 1-3,
the AI general starts, and on a 4-6 the human general starts.
1. The generals take turns activating units. If the general has no more
characters to activate or wishes to pass, the other general can continue
activating units.
1. The round continues until all units have been activated, both generals
wish to pass, or all of one general's units have been routed off the board
or destroyed.
1. Start another round.


#### Activation

##### Pre-activation
* At the start of an activation, an unengaged character may pick up an objective
if they are not carrying anything
* A routing character cannot perform an action and must move their full move
distance towards the nearest table edge and may not perform any action.
* A character in melee must continue melee combat.

##### During an activation
During an activation, a character may

1. Move
    The character can pivot, move half of their move distance in a straight line,
    pivot, and move the other half of their move distance. Or they can pivot and move
    their full move distance in a straight line. For any pivot, a character rotates
    around their center up to 180 degrees.
1. Shoot
    They can pivot and shoot another character in their forward 180 degree arc of vision.
    Follow the rules for resolving combat.
1. Move and shoot
    The player can make a move as above and then shoot a character as the above
    rules specify. The character takes a -1 Attack penalty for shooting after a move.
1. Move into melee
    If an enemy character is within its full move distance, the activated
    character may move into base-to-base contact with the enemy character and
    follow the rules to resolve combat. If the activated character fells the
    enemy character they may take another activation with only half of their
    movement distance allowed.
1. Continue melee
    Follow the rules to resolve combat. As above, if the activated character fells the
    enemy character they may take another activation with only half of their
    movement distance allowed.

##### Combat

Attacking consists of rolling on D6, adding the attacking character's attack
modifier, and subtracting the defender's defence modifier. If the resulting
value is greater than 3, it is a wound. A roll of 1 is always a miss and a
roll of 6 is always a wound. If the wounded character has no free wound slots,
they are removed from play as "fallen". Otherwise, add a wound token to the
available wound slot.

If a character is removed from play and their company has lost over 50% of its
units, the company must make a route check. Roll a D6, and on a roll of 3 or
less, the company is routing and all of their characters must route towards the
nearest table edge for their activation.

### AI
The basic AI is as follows.

##### Pre-activation

Each character is activated in the order it appears on the character sheet
unless otherwise specified by the scenario rules.

Follow pre-activation rules if routing or in melee combat. If unengaged and
next to an objective, pick it up.

##### Activation

1. If carrying an objective, move towards the nearest table edge.
1. Continue melee if in melee. If multiple bases are in contact, use a D6 to
determine which enemy to attack. If an enemy is felled, move forward in the
direction of the felled enemy and continue the activation per the instructions below.
1. If in shooting range of an enemy, stand and shoot. If multiple enemies can
be shot at, shoot at the nearest one.
1. If it's possible to move into shooting range of an enemy, move and shoot,
always choosing the closet enemy.
1. If there is a visible objective in movement range, move to it.
1. If there are unengaged enemies in movement range, move towards the closest
enemy and engage in melee. Follow the above rules above on "Continue melee" for
how to handle felling an enemy.
1. If a objective is viewable (in the character's forward 180 degree arc and not
blocked by terrain or other characters), move towards the nearest objective.
1. If an enemy is viewable (in the character's forward 180 degree arc and not
blocked by terrain or other characters), move towards the nearest enemy.

### Cooperative play
For cooperative play, human generals each manage one or more friendly characters.
The human generals switch off activating during the human turn. I.e. Human 1
activates Unit H1, AI activates Unit A1, Human 2 activates Unit H2, AI
activates Unit A2, and so on.



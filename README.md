# Solo Narrative Minis Ruleset

## What
This ruleset is designed to provide fast-paced play with a handful
of miniatures, with battles lasting about 15-30 minutes. It can be played
solo or cooperatively. Each battle happens in a narrative framework where
each battle has a long-lasting impact.

## Why
There is a comparative lack of rulesets for solo miniatures wargaming.
Existing rulesets for miniatures games are lengthy, individual games
take over an hour to complete, and they favor special case rulesets
for each faction. This special casing seems intended to sell as many
boxes of plastic as possible, and part of the fun is in deeply knowing
all of the special rules for your faction. I personally don't find this aspect
of miniatures games to be fun.
This ruleset is intended to create acrade-like fast gameplay with a
narrative framework that gives a long-lasting impact to each battle.

## Rules

### Narrative Layer

The narrative layer guides what scenarios occur and gives a larger
context to individual battles.

#### Major scenes
1. Bree - sneak away from hunting wraiths
1. Bree bridge - escape wraiths
1. Weathertop - defend until Aragorn can pick up torch and touch each wraith
1. Moria (skirmish in Balin's tomb) - all the fellowship defends against goblins and cave troll
1. Amon Hen - skirmish when Boromir is killed
1. Lighting the beacons - slip around guards to light to send for Rohan to aid Gondor

Subscenes of larger battles
1. Helm's Deep - Explosion of Deeping Wall
    Aragorn and Eomer fight back orks with a ram on the ramp. Gimli present as is Legolas
    Theoden and Aragorn lead cavalry charge out of the keep
    They buy enough time for Gandalf to come with Erkenbrand (in the films Eomer) to save the day
1. Isengard - Ents and Merry and Pipin attack the goblins at Isengard and Orthanc
1. Osgiliath pt 1 (pre war of rings) - Boramir and Faramir fight off orcs at Osgiliath
    They destroy the last bridge that connected the west (friendly) and east (orc-occupied) banks
1. Osgiliath pt 2 (war of rings) - Faramir reinforces men at Osgiliath. Orcs cross with rafts.
    Forced to retreat, Faramir is struck by arrow.
    Also wounded by "black breath" of Nazgûl. This causes unconciousness, can be fatal. Like an aura
1. Pelennor Fields - Minas Tirith
    The orcs break open the gate with the large battering ram
    Just as the Witch King is about to battle with Gandalf inside the gate,
    he is called off to deal with the Rohirrim who have just arrived
    Witch king mortally wounds Theoden, crushed by own horse
    Eowen and Merry wound the Witch king, killing him.
    Aragorn and army of dead arrive just as orcs are starting to overwhelm Gondor.
1. Black Gate - Final Battle outside Mordor
1. Bywater - at the end for control of the Shire


### Battle Layer

The narrative layer determines which companies collide and from which
sides of the board.
Cards are created for each mini on the game board with their name, an
attack modifier, a defense modifier, and a shooting range if available.
One side is controlled by AI and the other by the player. The game takes
place over a series of rounds until either the player or the AI is routed
from the board or all units are wounded to the ground. After the game, any
wounds the player's characters sustained are resolved and play moves back to
the narrative layer.

Play proceeds as follows.

"General" means either the player commanding friendly units or the AI
commanding enemy units.

#### Round

1. All terrain and units are placed on the board per the narrative layer.
1. Any starting wounds on units are marked on the corresponding
characters' cards.
1. The human general rolls a D6 to determine who starts the round. On a 1-3,
the AI general starts, and on a 4-6 the human general starts.
1. The generals take turns activating units. If the general has no more
characters to activate or wishes to pass, the other general can continue
activating units.
1. The round continues until all units have been activated or both generals
wish to pass.


#### Activation

##### Pre-activation
* At the start of an activation, an unengaged character may pick up an item
if they are not carrying anything
* A routing character cannot perform an action and must move their full move
distance towards the nearest table edge and may not perform any action.
* A character in melee must continue melee combat.

During an activation, a character may

1. Move
    The character can pivot, move half of their move distance in a straight line,
    pivot, and move the other half of their move distance. Or they can pivot and move
    their full move distance in a straight line.
1. Shoot
    They can shoot another character in their forward 180 degree arc of vision.
    Follow the rules for resolving combat.
1. Move and shoot
    The player can make a move as above and then shoot a character as the above
    rules specify. The character takes a penalty for shooting after a move to
    simulate the difficulty of getting off a shot while running.
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
roll of 6 is always a wound. If the wounded character has no wound slots, they
are removed from play as "fallen". Otherwise, add a wound token to the
available wound slot.

If a character is removed from play and their company has lost over 50% of its
units, the company must make a route check. Roll a D6, and on a roll of 3 or
less, the company is routing and all of their characters must route during
their activation.

### AI
The basic AI is as follows.

##### Pre-activation

Follow pre-activation rules if routing or in melee combat. If unengaged and
next to an objective, pick it up.

##### Activation

1. If carrying an objective, move towards the nearest table edge.
1. Continue melee if in melee. If multiple bases are in contact, use a D6 to
determine which enemy to attack. If an enemy is felled, move forward in the
direction of the felled enemy and continue the turn per the instructions below.
1. If in shooting range of an enemy, stand and shoot. If multiple enemies can
be shot at, shoot at the nearest one.
1. If it's possible to move into shooting range of an enemy, move and shoot,
always choosing the closet objective.
1. If there is a visible objective in movement range, move towards it.
1. If there are unengaged enemies in movement range, move towards the closest
enemy and engage in melee. Follow the above rules on "continue melee" for how
to handle felling an enemy.
1. If a objective is viewable, move towards the nearest objective.
1. If an enemy is viewable, move towards the nearest enemy.

### Cooperative play
For cooperative play, human generals each manage one or more friendly characters.
The human generals switch off activating during the human turn. I.e. Human 1
activates Unit H1, AI activates Unit A1, Human 2 activates Unit H2, AI
activates Unit A2, and so on.



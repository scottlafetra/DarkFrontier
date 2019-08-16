*v0.3.1*
# Gameplay Rules

## Round Overview
1. Burn and Turn
2. Place Projectiles
3. Advance Tokens

## Setup
1. The defending player places their ship with no velocity in the center hex of the map, on the White Sands Shipyard.
2. The attacking player places their ship on the edge of the map with whatever velocity they want.

## Playing a Round
**Burn and Turn**
1. Starting with the attacker, each player may increase their velocity up to their thrust in the direction that their ship's engine is pointed, then turn up to their rotation in either direction.
2. Starting with the attacker, each player rotates a missile up to its rotation value (if they have one) and increase its velocity by up to its thrust.

**Place projectiles**
1. Both players may fire their weapons as if they were on any hex that they visited this turn.

**Advance Tokens**
For each token with velocity on the board:
1. Move the token the amount indicated by its velocity counters.
2. If the token is flak, decrease the spread counter by 1. If it can't be lowered anymore, remove the token from the board. *The flak has spread out too much to be effective.* 

## Resolving the velocity counter
*When it comes to simulating spaceflight manually, simplicity is paramount. There are a few rules that you should use every time you modify your velocity counter to keep the game managable. If you follow these rules, there should never be more than two hexes on your counter in use at one time.*
1. **Opposites cancel:** If there are ever two dice opposite eachother on the counter, remove a number from each the hexes such that this is no longer true.
2. **Split dice combine** If there are ever two dice on the velocity counter that are one hex apart from eachother, remove the diffrence between the die from both die and add that number to the hex in between them.

## Firing a shot
*Whether you are launching a missle or just inert flak, your velocity will affect that of your shots. A keen captain will take this into consideration when forming a strategy.*
1. Copy your velocity from your velocity counter to the blank one on the right side of your ship's stat sheet.
2. Add the velocity of the weapon you are firing to one or two adjacent hexes in a direction that the chosen weapon can fire.
3. Resolve the velocity counter.
4. Take one of the projectile tokens and place adjacent to the ship firing it. The attacker plays projectiles with the black side up and the defender places projectiles with the white side up.
5. Copy the velocity from the your right velocity counter onto the projectile.
5. If the token placed was a flak, place a dice in the center of the token as a spread counter currently set to 6.

## Resolving Collisions
### Collisions between flak and other flak or missles:
Flak is too sparse no interfere with other flak or debris clouds.

### Collisions between two missiles:
1. Either player may choose to detonate their missle early.
2. If either missle was detonated, both become flak, traveling with the same velocity as they had before detonation.

### Collisions between flak and a ship
1. The player who controls the ship rolls two die. If either of them are higher than the spread value, the SCRAM system on board the ship was able to avoid the debris through a combination of luck and quick calculations. Continue with the steps below only if the flak was not dodged.
2. Roll a die to represent the point defenses of the ship firing. If the result is higher than the rating of the ship's point defenses, the flak was sucsessfully vaporized or else repelled.
3. If neither of these defense systems work, the ship is hit! Roll on the ship's damage table to see what happens.

### Collisions between a missle and a ship
1. The player who controls the ship may choose to fire one of their missles as a countermeasure. If they do, resolve the collision as a flak and ship collision instead.
2. Roll a die to represent the point defenses of the ship firing. If the result is equal to or higher than the rating of the ship's point defenses, the missle was destroyed. Otherwise, the ship is hit by the missile's debris! Roll on the ship's damage table to see what happens.
3. If neither system sucessfully destroys the missile, the missle sucsessfully delivers it's thermonuclear warhead to the ship and detonates it. The ship is destroyed.
4. Remove the missile token fron the board.

### Collisions between two ships
1. The player controlling each ship chooses an amount of missles to fire. 
2. Both players resolve flak collisions with their ship equal to the lower of the two numbers.
3. The player who fired the least amount of missles resolves missle collisions equal to the diffrence between those two numbers.

### Gimbaling
If an engine has gimbaling, you may distribute its thrust when increasing velocity between two adjacent hexes on the ship's velocity counter.


*v0.2.0*
# Gameplay Rules

## Round Overview
1. Command
2. Turn and Burn
3. Place Projectiles
4. Advance token

## Setup
1. The defending player places their ship with no velocity in the center hex of the map, on the White Sands Shipyard.
2. The attacking player places their ship on the edge of the map with whatever velocity they want.

## Taking a turn
**Command**
1. Each player secretly sets the rotaions and burn amounts for their ships on their command dials.
2. When both players have done this they reveal their comand dials.

**Turn and Burn**
1. Starting with the defender, each player rotates their ship the amount indicated on their command dial and increases velocity in the direction that their ship's engine thrusts. If the ship both rotates and thrusts, the thrust must be distributed as evenly as possible amongst all the directions the engine was pointed in during the rotation.
2. Starting with the defender, each player rotates a missile up to its rotation value (if it has one) and increase its thrust by up to its acceleration in gees.

**Place projectiles**
1. Both players may fire their weapons as if they were on any hex that they visited this turn.

## Advance projectiles
For each token with velocity on the board:
1. Move the projectile the amount indicated on the token.
2. If the marker was a flak, decrease the spread counter by 1. If it can't be lowered anymore, remove the marker from the board. *The flak has spread out too much to be effective.* 

## Resolving the velocity counter
*When it comes to simulating spaceflight manually, simplicity is paramount. There are a few rules that you should use every time you modify your velocity counter to keep the game managable. If you follow these rules, there should never be more than two hexes on your counter in use at one time.*
1. **Opposites cancel:** If there are ever two dice opposite eachother on the counter, remove a number from each the hexes such that this is no longer true.
2. **Split dice combine** If there are ever two hexes on the counter that have dice on them that are one hex apart from eachother, remove a number from each the hexes such that this is no longer true and add that number to the hex in between them.

## Firing a shot
*Whether you are launching a missle or just inert flak, your velocity will affect that of your shots. A keen captain will take this into consideration when forming a strategy.*
1. Copy your velocity from your velocity counter to the blank one on the right side of your ship's stat sheet.
2. Add the velocity or launch velocity of the weapon you are firing to one or two adjacent hexes in a direction that the chosen weapon can fire.
3. Resolve the velocity counter.
4. Take one of the projectile tokens and place it in the direction it is being fired. The attacker plays projectiles with the black side up and the defender places projectiles with the white side up.
5. Copy the velocity from the your right velocity counter onto the projectile.
5. If the token placed was a flak, place a dice in the center of the token as a spread counter currently set to 6.

## Restrictions on missiles
1. You may only fire as many missiles per turn (10s) as indicated on your ship's stat sheet.
3. You may not fire a missile if your missle bay isn't functional.

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
If an engine has gimbaling, you may distribute it's thrust when increasing velocity between two adjacent hexes on the ship's velocity counter.


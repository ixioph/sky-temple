# sky-temple
Unity-based proof of concept game

## Elevator Pitch
A 3D adventure game with a playful style reminiscent of the legend of zelda franchise with an emphasis on exploration, aesthetics, and engaging combat.

## Some Questions to Consider
### Target Audience?
Based on what was said today (11/5) I think our target audience is likely pretty broadly appealing to ~16-40yo with an emphasis on our particular demographic.
### Single or Multiplayer?
(I'm leaning towards a multiplayer experience long term, but we focus on single player first, with the AI just following the player. In multiplayer these AI would be replaced by people)
#### Third Option,
the AI are "actual" AI. we give them a base routine to follow but implement machine learning algorithms so that they longer they play with the human -- the more they mesh with their playstyle. This is another long term option, though.
#### Fourth Option,
single-player story mode to start with for emphasis, later you can use your single-player built character in multiplayer skirmishes or group boss raids.

## Visuals
### Environment
  * Probuilder
  * Voxels
  * Blocky Modeling Style - Texture & Lighting Focus
  * Sky Island/Temple Ruins
  * Small level - most could be seen without moving a character (optional hub for larger levels)
    * The hub idea is also present in spiral knights, we could use as reference

### Character

## Audio
  * Strings and simple piano arrangements
  * Background tracks can be light

## Mechanics
### Exploration, Simple Puzzles, Engaging Combat System
### Exploration:
For an exploration aspect, I thought it would be interesting to do something like secret pathways that lead to other small areas. Kind of like in OOT when you first get the sword, but hidden easter-egg type things -- that way we can just add them as we sit fit while maintaining the integrity of the growing project.
### Puzzles:
The puzzles would lend themselves heavily to the combat in some areas. Depending on how you use them together, you could perform some objectives such as unlocking a secret path.
### Combat:
At its core, the combat should be very similar to a zelda game before implementing a magic and combo system.
  * Simple, yet diverse, talent/node-based system with an emphasis on specializations/weapon choice
  * Stamina/Resource based system that must be manually built and consumed, it passively builds quickly out of combat, but VERY slowly in combat to discourage skill spam.

## Walkthrough of Demo
A beginning-to-end snapshot of what the proof-of-concept will contain, so set a solid guideline for what needs to be done.
  1. Splash Screen
  2. Title Screen
  3. Brief Backstory
  4. Player is Teleported (?) to sky temple ruins, possible hub station?
  5. Player chooses stage/level
    * Level 0 description: ...
    * What does "death" look like?
  6. Zones back to hub after stage completion
  7. Save/Exit? Credits?

### Demo Asset List
Listed below (and continually updated) will be the list of character, environmental, and User Interface assets to be included in the demo.
#### Character
  1. Default Male Character
    - [ ] Model
    - [ ] Texture
    - [ ] Rig
    - [ ] Walk Animation
    - [ ] Run Animation
    - [ ] Jump Animation
    - [ ] Attack Animation
  2. Default Female Character
  - [ ] Model
  - [ ] Texture
  - [ ] Rig
  - [ ] Walk Animation
  - [ ] Run Animation
  - [ ] Jump Animation
  - [ ] Attack Animation
  3. Melee Terrestrial Enemy
  - [ ] Model
  - [ ] Texture
  - [ ] Rig
  - [ ] Walk Animation
  - [ ] Run Animation
  - [ ] Jump Animation 
  - [ ] Attack Animation
  4. Ranged Aerial Enemy
  - [ ] Model
  - [ ] Texture
  - [ ] Rig
  - [ ] Walk Animation
  - [ ] Run Animation
  - [ ] Jump Animation
  - [ ] Attack Animation
  5. Enemy Captain
  - [ ] Model
  - [ ] Texture
  - [ ] Rig
  - [ ] Walk Animation
  - [ ] Run Animation
  - [ ] Jump Animation
  - [ ] Attack Animation
#### Environment
#### User Interface

## Player Description
Listed here are the actions that the player can take, how the action is accomplished, and how it interacts with the environment, etc.
### Basic Abilities
  1. Walk/Run: Free resource, moderate to fast paced movement
  2. Jump/Climb/Interact: Free resource, usable action button when player faces an interact-able object.
  3. Attack: There are separate attack actions which get unlocked through gameplay
    * Basic Attack: Primary Action, Resource Builder
    * Special Ability: Secondary Action -- chosen by player, variable resource consumption
    * (Optional) Special Ability 2: Tertiary Action -- chosen from alternate skill tree by player, variable resource consumption
    * Ultimate Ability: Powerful Action, consumes 100% of available resources and scales exponentially based on resources consumed
### Stats
Here will be a simple representation of the primary stats in the game. Raw damage can be built into the skills to keep it simplistic while we flesh it out.
  1. Health: How much of the "life" resource a player has, reaching 0 means death
  2. Attack Resource: For starters, a basic "energy" resource may be best here. We can add more variety if the game reaches that level of complexity.
  3. Experience: value gained from participating in battles, exploring new areas, solving puzzles -- which you can use to progress through the talent tree
## References

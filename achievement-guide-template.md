# Achievement Guide Template for OGPC

Taken from the season 15 [OGPC Achievement Gide](https://www.ogpc.info/assets/files/seasons/15/2022-Achievement-Guide.pdf).

## Table of Contents

| - | - |
| Section | Basic Info |
| [Programming](#programming) | Code should be easy to follow, saved in a central location with backups, and have
development over time. No spaghetti code! |
| [Game Design](#game-design) | Write a design document. What are your milestones? What is being communicated to
the player? What is the general mood of the game? |
| [Art](#art) | Make your game visually unique and give it your own flair! |
| [Theme and Story](#theme-and-story) | OGPC provides a theme, you use it. |
| [Management](#management) | The team got along nicely, communicated well, and overcame challenges together. |

## <a name="programming"></a> Programming

### Maintenance of Code

Code should be easy to follow, saved in a central location with backups, and have
development over time. No spaghetti code!

#### Standard

- [ ] Code is clean: labelled properly and named descriptively.
- [ ] Save multiple copies of the project, or project is saved to the cloud/online.

#### Encouraged

- [ ] Code is navigable and logically separated into functional units.
- [ ] Git/version control history shows at least a few commits over time.

#### Extra Credit

- [ ] General “best practices” were followed and the code would allow for future
development.
- [ ] Git/version control history shows many commits, smaller or even daily commits.

### Bag O' Tools

How did you leverage conditionals/repetition/data structures to implement a mechanic
and diagram logic?

#### Standard

- [ ] Code has loops and conditionals.
- [ ] Code uses at least 1 standard data structure (a list/map/dictionary is ok).

#### Encouraged

- [ ] Code uses loops and conditionals consistently and properly.
- [ ] Code uses data structures in multiple locations.
- [ ] Game logic for at least one mechanic or interaction has been diagramed.

#### Extra Credit

- [ ] Game implements and documents an algorithm.
- [ ] Player state stored in a reasonable data structure (not a group of global variables).
- [ ] Codebase uses classes or similar data/functionality grouping structures where appropriate.
- [ ] Game logic for at least two mechanics or interactions has been diagrammed.

### Bug Smashing

Show how problems were fixed, avoided, and purged!

#### Standard

- [ ] Talk about or show a logic bug (not typo) and talk about/show how it was fixed.
- [ ] Game demonstration doesn’t crash, freeze, or otherwise completely break.

#### Encouraged

- [ ] Talk about a proactive strategy you used to avoid bugs.
- [ ] Gameplay demonstration is free of major/obvious bugs.
- [ ] Have a testing process to help search for bugs.

#### Extra Credit

- [ ] Have a system to keep track of bugs you’ve noticed (a list works fine).
- [ ] Game executes flawlessly.
- [ ] Use a standard testing framework.

### Dynamic Aspects

Games make use of time and other modular elements to enhance gameplay.

#### Standard

- [ ] Game features more than one version of at least one asset to represent different states and dynamically swaps those assets at least once (ex: player can pick up and wear a yellow shirt).
- [ ] Animate something with a state machine (swap 2 walking sprites, etc).


#### Encouraged

- [ ] Game features a time system which meaningfully affects gameplay (day/night,weather cycles, etc.)
- [ ] Game swaps/combines/modifies assets or modifies mechanics based on time system (night, seasons, etc. in one level; enemies speeding up as the countdown nears zero; etc).


#### Extra Credit

- [ ] Game dynamically swaps or combines assets to match player actions.
- [ ] Choose at least one of these three:
  - [ ] Game features a full-featured time system integrated into major mechanics of the game.
  - [ ] Game generates content procedurally.
  - [ ] Game has dynamic or procedural level generation.

### Object Permanence

Menus allow players to interact with additional game content and access saved data.

#### Standard

- [ ] Game has at least one menu with an option to view credits.
- [ ] Game has leaderboard in RAM (clears when game is exited) for at least one statistic.

#### Encouraged

- [ ] Game has a start menu with options to start a new game, use saved data (view the leaderboard, resume a saved game, etc.), view credits, and change options/settings (at least 2 functional).
- [ ] Game has a persistent local record such as a save system, leaderboard, settings, or other game related data.

#### Extra Credit

- [ ] Game has a pause menu with resume, options/settings (at least 4 functional).
- [ ] Game has a persistent online record such as a save system, leaderboard, or other game related data (server doesn’t need to be hosted).

## <a name="game-design"></a> Game Design


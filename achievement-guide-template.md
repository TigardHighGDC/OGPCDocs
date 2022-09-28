# Achievement Guide Template for OGPC

Taken from the season 15 [OGPC Achievement Gide](https://www.ogpc.info/assets/files/seasons/15/2022-Achievement-Guide.pdf).

## Table of Contents

| Section | Basic Info |
| - | - |
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

### Design Doc

Write a design document. What are your milestones? What is being communicated to the player? What is the general mood of the game?

#### standard

- [ ] Team created a game design document that describes the game at a high level.
- [ ] Design document lists milestones ((hopefully) be done by main event!).
- [ ] Design doc contains basic info such as win condition, genre, and target audience.

#### Encouraged

- [ ] Design doc has been updated at least once to show changes in the development process.
- [ ] Design doc has multiple milestones set.
- [ ] Design doc communicates key game mechanics, the main character, and the setting.

#### Extra Credit

- [ ] Design doc has been maintained through development with multiple updates and a changelog.
- [ ] Design doc has UI mockups.
- [ ] Design doc has all important game mechanics, all important characters, and info on all levels.

### Mechanics

Game tasks the player with completing various goals however the specific processes and environments in which the player accomplishes those goals can vary greatly.

#### Standard

- [ ] Player is given more than one mechanic for interacting with the game (teleportation, rewinding time, picking up items, jumping, sprinting, etc.).
- [ ] Game has at least one, well-crafted and well-designed environment (level, biome, map, etc.).

#### Encouraged

- [ ] Game has notably different mechanics (jump and double jump are not notably different).
- [ ] Game has notably different environments that impact the mechanics (levels, biomes, maps, etc.).

#### Extra Credit

- [ ] Choose at least one:
  - [ ] Game contains at least two sets of contrasting mechanics (enabling different play styles).
  - [ ] Game has at least one novel mechanic (other than move, jump, pick up, sprint, etc.).
- [ ] Game contains at least 3 environments that impact the mechanics (levels, biomes, maps, etc.).
- [ ] Player can have a markedly different experience on each playthrough.

### Target Audience

Who is the target audience/demographic? What concessions had to be made for them? Does the game adapt to the player?

#### Standard

- [ ] Game has at least one target audience (kids like me, adults, my friends).
- [ ] Game has at least one feature or design consideration to better fit the target audience.

#### Encouraged

- [ ] Game has at least one specific, and well-defined target audience (middle-aged hard core strategy gamers, teenage casual gamers, elementary age Minecraft fanatics, etc...).
- [ ] Team held design reviews to ensure game continued to be fun/engaging for the target audience.
- [ ] Game has been playtested by the target audience(s).

#### Extra Credit

- [ ] Game has been playtested by members of the target audience(s) who are not team members.
- [ ] Game mechanics, controls, color scheme, etc. all fit the needs of the target audience(s).
- [ ] Game has settings (difficulty, color blind mode, etc.) to better adapt to different audiences.

### Evolution of Design

How was the game initially conceptualized? What changed when real people playtested? What was axed due to time or other constraints?

#### Standard

- [ ] Show meeting notes indicating changes in mechanics, assets, or other aspects of gameplay.
- [ ] Game has been playtested (play from the beginning to the end).

#### Encouraged 

- [ ] Have images showing early game builds with features, assets, characters, etc. that were dropped due to scope or time issues (hit print screen every now and then).
- [ ] Game has been changed based on documented playtesting feedback.

#### Extra Credit

- [ ] At least one playtesting session was recorded (Screen capture is perfect).
- [ ] Game has been playtested by non-teammates on at least two separate occasions with changes after each.

### Communicate, communicate, communicate

How does the game communicate with the player? How is the player taught new mechanics?

#### Standard

- [ ] Game has at least one indicator for the player’s state (health bar, sanity meter, luminance, etc.).
- [ ] Game provides instruction on how to use new mechanics as they’re introduced.

#### Encouraged

- [ ] Game has at least two indicators for the player’s state (health bar, darkness on camera, world assets, etc.).
- [ ] Game provides periodic feedback to the player (score, leveling up, etc.).

#### Extra Credit

- [ ] Game provides specific and continuous feedback to the player in more than two ways that aren’t just numbers or bars (heavy breathing/heartbeat, red or black in corners of screen, slowing walking speed when carrying too much, NPC reactions, etc.).
- [ ] Game indicates to the player when a mechanic is performed particularly well.

## <a name="art"></a> Art and Assets

### Make Art

Make your game visually unique and give it your own flair!

#### Standard

- [ ] Create 1-3 visual assets.
- [ ] Create a game logo and icon (not part of the 1-3 count).
- [ ] Cite all sources for assets not created by the team (creative commons libraries or your game engine).

#### Encouraged

- [ ] Create 3+ visual assets.
- [ ] Create title art or a splash screen (not part of the 3+ count).

#### Extra Credit

- [ ] All visual assets made by team members.
- [ ] Create box art.

### Hey DJ

Create a unique soundscape to provide depth and immersion for your game.

#### Standard

- [ ] Create one song (at least 30 seconds).
- [ ] Record at least one voice line or sound effect by a team member.
- [ ] Cite all sources for assets not created by the team (creative commons libraries or your game engine).

#### Encouraged

- [ ] Create multiple songs (at least 30 seconds each).
- [ ] Record multiple voice lines or sound effects by the team.

#### Extra Credit

- [ ] All music created by the team.
- [ ] All sound effects created by the team.
- [ ] All dialog created or recorded by the team.

### Cohesive Look and Feel

Everything fits together nicely, and nothing stands out.

#### Standard

- [ ] Have at least one color palette (consistent set of colors used everywhere).
- [ ] Have at least one soundscape (consistent set of sounds used everywhere).

#### Encouraged

- [ ] Assets are all of a consistent scale, resolution, and style; no assets are unintentionally jarring.
- [ ] Sounds and music are a consistent volume, quality, and style; no sounds are unintentionally jarring.
- [ ] Most player actions have sounds and animations associated with them.

#### Extra Credit

- [ ] Audio and visual assets have depth that fit in with the game’s setting and world.
- [ ] Elements in the game’s world have audible or visual ques to indicate interactivity or facilitate immersion.
- [ ] All player actions have sounds and animations associated with them.

### High Fidelity

Game uses particle/atmospheric effects and animated graphics to enhance the game.

#### Standard

- [ ] Create one particle or atmospheric effect (rain, fog, smoke, sparks, etc.).
- [ ] Choose one:
  - [ ] Create at least one animation sprite sheet (4+ frames).
  - [ ] Create at least one rigged and animated model.

#### Encouraged

- [ ] Create 2+ particle or atmospheric effects.
- [ ] Choose one:
  - [ ] Create 2+ animation sprite sheets (4+ frames).
  - [ ] Create 2+ animation sprite sheets (4+ frames).

#### Extra Credit

- [ ] All particle or atmospheric effects created by the team to enhance the look and feel of the game.
- [ ] All animation sprite sheets or rigged and animated models created by the team.

### Biomes

Players are given multiple, unique experiences to explore.

#### Standard

- [ ] Create multiple levels/rooms/biomes/etc.

#### Encouraged

- [ ] Level/room/biome/etc. styles are consistent across asset types (visuals and audio).
- [ ] Assets all match the unique style of the level/room/biome/etc. (ex: creepy room plays creepy music).

#### Extra Credit

- [ ] Two or more modular assets each with multiple dynamic components that allow mixing on the fly to match player actions or locations.

## <a name="theme-and-story"></a> Theme and Story

### Use the Theme

OGPC provides a theme, you use it.

#### Standard

- [ ] The season’s theme is present in the game

#### Encouraged

- [ ] The season’s theme is clearly connected to the story and level design.

#### Extra Credit

- [ ] The season’s theme is consistently tied to all aspects of the game – game mechanics, setting, visuals, music, etc.

### Storyboarding

Plan out the theme, progression, player choices, and potential endings.

#### Standard

- [ ] Create a storyboard for at least one scene in the game.

#### Encouraged 

- [ ] Create a storyboard for the player’s full path through the game (high level for the entire game).

#### Extra Credit

- [ ] Create detailed storyboards for all important moments in the game: opening, climax, key turning points, etc.

### Storytelling

Every good story needs a cast and a good ending.

#### Standard

- [ ] Create a story outline that shows the general shape of the arc.
- [ ] The story has multiple characters.

#### Encouraged

- [ ] The game has a fleshed-out story with multiple sections.
- [ ] At least one character is developed.

#### Extra Credit

- [ ] Story has a clear beginning, middle, climax, and end.
- [ ] Story has at least one secondary or supporting character who is developed equally with the main character.

### Scratching the Surface

Games are much more fun when there is a deep story and fleshed out world to explore. Everything for this achievement must be able to be expressed via gameplay as dialog, narration, carvings, graffiti, audio logs, books, etc

#### Standard

- [ ] Write a background for at least one location or character and explain how it is presented to the player.
- [ ] Write at least one world event that happens prior to the game starting and explain how it is presented to the player.

#### Encouraged

- [ ] Write a background for multiple locations or characters and explain how they are presented to the player.
- [ ] Write multiple world events that happen prior to the game starting and explain how they are presented to the player.

#### Extra Credit

- [ ] Tie characters, world events, and location histories into at least one playable subplot (even if it doesn’t make it into the game).

### Fan Fic

Flesh out the world and story in materials not designed to be integrated into the game itself.

#### Standard

- [ ] Create one story in your world that isn’t present in the game. This story should tie into a character or location that is in your game and can be any length.
- [ ] Create a glossary of characters and locations.

#### Encouraged

- [ ] Create a second story in your world that isn’t present in the game. This story should tie into a character or location that is in your game and must be either 600 words typed or 2 pages of a graphic novel or comic.
- [ ] Create a glossary of characters and locations including descriptions.

#### Extra Credit

- [ ] Create a third story in your world that isn’t present in the game. This story should tie into a character or location that is in your game and must be either 1200 words typed or 4 pages of a graphic novel.
- [ ] Create a reference guide or manual for important elements of the story, including characters and locations that fleshes out the story, and includes the glossary of all characters/locations. Must be at least two pages.

## Management

### Team Players

The team got along nicely, communicated well, and overcame challenges together.

#### Standard

- [ ] Team members met (in person or virtually: zoom, hangouts, discord, etc.) at least once for a group work session.


#### Encouraged

- [ ] Team members met (in person or virtually: zoom, hangouts, discord, etc.) regularly for a group work session (at least monthly).

#### Extra Credit

- [ ] Team scheduled review sessions and weekly check-ins with notes/minutes.

### Public Relations

Be professional!

#### Standard

- [ ] Team members all wear coordinated clothing (printed, matching colors, or matching styles).
- [ ] Team created a development blog (or vlog!) with at least one post.
- [ ] Create business cards (either print them yourself on cardstock or buy cards from a printshop or even homemade).
- [ ] Create a banner/flag that is on your table or in your videos.

#### Encouraged

- [ ] Development blog contains at least one post from each team member about their respective areas of work.

#### Extra Credit

- [ ] Development blog has multiple entries by all members on the team spanning several months.
- [ ] Create a physical mascot.

### Team / Project Management

Use tools to help manage work: issue tracking, milestones, task management and more.

#### Standard

- [ ] Team uses some form of task management tool (Trello, Jira, Asana, Excel, GitHub Projects).

#### Encouraged

- [ ] Task management uses some form of grouping (tasks and subtasks).
- [ ] Tasks are assigned users and state is tracked as work is completed.
- [ ] Include bug management in with tasks.

#### Extra Credit

- [ ] Task management uses some form of multi-tier hierarchical tasks with at least 3 levels of depth (ex: Epic -> Feature -> Task).
- [ ] Task management is broken into sprints or other milestones.
- [ ] Add weights/priority to tasks.

### Checking the Boxes

Complete TMS. All of it. I dare you.

#### Standard

- [ ] Fill out the minimum required fields for an entry (info on team, at least one team member, etc.).
- [ ] Include a basic description of the game.
- [ ] Leave no remaining placeholder images (team members, team logo, game poster).

#### Encouraged

- [ ] Fill out all game entry page details on TMS.
- [ ] Include a playable link or download link to your game.
- [ ] All team members are linked to game entry.
- [ ] Include more than one sentence for the About section and the Instructions section.

#### Extra Credit

- [ ] Game entry on TMS has 10+ images (screenshots, concept art, development images) and all images have descriptions.
- [ ] Include a full game description (200+ words, think Steam store page), instructions, etc.
- [ ] All team members have appropriate roles set in TMS and have profile images, and a team group image is included.

### Production Value

Required videos exist, are well put together, and talk about the game/team/development.

#### Standard

- [ ] All required videos are submitted (In TMS).
- [ ] Videos are scripted, well-practiced, and within the time limits (See Competition Manual).

#### Encouraged

- [ ] Required videos have well-balanced, normalized audio (no one is ear-blastingly loud or unintelligibly quiet).
- [ ] Videos include in-game footage with a voice-over.
- [ ] Videos are edited (no mistakes, blunders, or awkward gaps).

#### Extra Credit

- [ ] Create at least one additional trailer, promotional video, or behind the scenes video (at least 1 minute long).
- [ ] All required videos have reasonable special effects (titles, fades, transitions, etc.).
- [ ] Videos are designed with a storyboard.

## Changes and Amendments

This was put together from the OGPC season 15 achievement guide and has the potential to change in the future. Please check the official OGPC website for an updated version of the achievement guide.

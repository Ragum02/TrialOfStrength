# ToS from AnchyDev updated by Ragum02

Trial of Strength (ToS) is an AzerothCore module that adds a test of strength arena to test players skills in combat.

## Features
- Waves of monsters to fight.
- Rewards at the end of every wave.
- Curses to add difficulty and increase rewards.
- Supports group play.

## Setup
1. Clone the module into your AzerothCore modules directory.
2. Setup the `creature_template` table with creatures you would like to use in the arena.
3. Pick one of the [CombatAI types](https://gist.github.com/AnchyDev/7d8847fd696e42c94efcfdc5baf88e7f) for each of the creatures you create.
4. Setup the `tos_wave_groups` table with your created creatures.
5. Setup the `tos_reward_template` with your rewards for each wave.
6. Create wave entries in `tos_wave_template` which links to your `tos_wave_groups` and `tos_reward_template` entries.
7. Enable the module (build\bin\RelWithDebInfo\configs\module\trialofstrength.conf => TrialOfStrength.Enable = 1)
9. Spawn the arena entry (entry: 441250) NPC anywhere you want in the game.
10. Give yourself ticket item (entry : 25747), speak to the NPC => jump in the pink portal and enjoy.

## Note
This module is a work in progress, so expect bugs and crashes as the module is not heavily tested.

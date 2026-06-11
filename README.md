# Advanced Playable Multi-Agent Ecosystem

An experimental browser-based agent simulation where autonomous creatures survive, reproduce, fight threats, navigate complex polygon obstacles, and react to changing environmental events. The simulation also includes a playable commander agent so the user can directly interact with the ecosystem in real time.

## Overview

This project expands a simple multi-agent canvas simulation into a more interactive ecosystem sandbox. Agents move independently, collect food, avoid or fight threats, reproduce, and respond to events. The player controls a stronger commander-style agent that can shoot, shield, rally nearby agents, and place beacons.

The whole project runs from a single HTML file, making it easy to test, modify, upload, or host on GitHub Pages.

## Features

* Playable commander agent with movement, aiming, shooting, shield pulse, rally command, and beacon placement.
* Autonomous AI agents that wander, seek food, avoid danger, reproduce, and follow rally signals.
* Threat enemies that hunt agents and the player, including stronger boss-style enemies during events.
* Projectile combat with collision detection, damage, particles, and score tracking.
* Complex random polygon obstacles instead of simple circles, with collision handling.
* Environmental zones, including water, forest, radiation, and thermal areas.
* Random world events, such as meteor showers, electric storms, blood moon attacks, healing rain, resource blooms, and gravity rifts.
* Dynamic HUD showing agents, threats, food, player health, energy, and score.
* Interactive controls panel for reset, pause, event triggering, ally spawning, speed, and event rate.
* Mini-map for quickly viewing the world state.
* Touch support for mobile-style interaction.
* No external libraries required.

## Controls

| Action               | Input                  |
| -------------------- | ---------------------- |
| Move player          | `WASD` or arrow keys   |
| Aim                  | Mouse movement         |
| Shoot                | Left mouse click / tap |
| Shield pulse         | `Space`                |
| Rally nearby agents  | `E`                    |
| Drop rally beacon    | `F`                    |
| Pause simulation     | Pause button           |
| Trigger random event | Trigger Event button   |
| Spawn extra allies   | Spawn Allies button    |
| Reset simulation     | Reset button           |

## How to Run

1. Download or clone the project.
2. Open `advanced_playable_agent_sim.html` in any modern browser.
3. Move the commander agent with `WASD` or arrow keys.
4. Aim with the mouse and click to shoot threats.
5. Use rally and beacon abilities to influence the swarm.

No build tools, server, package manager, or installation steps are required.

## Gameplay Goal

There is no fixed win screen. The aim is to survive, protect the agent population, collect score by destroying threats, and manage the ecosystem through dangerous random events.

## Ideas for Future Development

* Add evolution traits that pass from parent agents to offspring.
* Add team colours and agent roles such as healer, scout, defender, and builder.
* Add a save/load system using `localStorage`.
* Add a research mode with charts for population, deaths, reproduction, and threat pressure.
* Add neural-network or reinforcement-learning behaviour for agents.
* Add terrain editing tools so the player can draw walls, water, forests, and hazards.
* Add sound effects and music-reactive events.
* Add difficulty modes and challenge scenarios.

## License

This project is open for learning, experimentation, remixing, and personal use. Add your preferred license file if publishing it as a public repository.

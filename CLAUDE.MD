# CLAUDE.MD

## Project Overview
This repository contains a Space Shooter game built with HTML5 Canvas and JavaScript.

## Repository Structure
```
.
├── game.html          # Main Space Shooter game file
├── README.md          # Project README (in German)
└── CLAUDE.MD          # This file - AI collaboration context
```

## Project Details

### Space Shooter Game (game.html:1-92)
A browser-based space shooter game featuring:
- Player-controlled spaceship (green rectangle) with left/right movement
- Shooting mechanics (spacebar to fire yellow bullets)
- Enemy spawning system (red squares appearing every 1.5 seconds)
- Collision detection between bullets and enemies
- Score tracking system (+10 points per enemy destroyed)
- Game runs at 600x400 canvas resolution

**Controls:**
- Arrow Left/Right: Move player
- Spacebar: Shoot

**Game Mechanics:**
- Enemies spawn randomly at the top and move downward at 2px/frame
- Player bullets move upward at 5px/frame
- Player movement speed: 5px/frame
- Canvas has a green border (#0f0) on black background (#000)

## Development Notes
- Written in vanilla JavaScript (no frameworks)
- Uses requestAnimationFrame for game loop
- Current high score mentioned in commits: 700 points

## Git Information
- Current branch: master
- Main branch: main
- Recent commits include game development milestones
- Repository is in clean state (no uncommitted changes)

---
*This file helps AI assistants like Claude understand the project context for better collaboration.*

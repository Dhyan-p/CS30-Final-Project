# Capstone Project Proposal: 2D Pac-Man with Ghost Algorithm

## 1. Project Overview & Basic Premise
- **Project Name:** 2D Pac-Man
- **Developer:** Dhyan Patel (Individual Project)
- **Basic Premise:** A classic 2D Pac-Man game built using the p5.js framework. The player controls Pac-Man through a 2D tile maze to collect pills while escaping ghosts, each driven by their own unique targeting and pathfinding algorithms. 

## 2. CS30 Programming Concepts
- **Data Structures:** 2D Arrays (matrix layout for walls, open paths, and pills).

## 3. Feature

### Required ("Must Have") Features
- **2D Array Grid & Tile Rendering:** A 2D matrix array that handles rendering for maze walls, open paths, and collectible pills.
- **Player Control & Grid Collision:** Keyboard movement for Pac-Man that stops moving when hitting  wall tiles.
- **Pills Mechanics & Game Rules:** A score system that increase as player (Pac-Man) eats pills, with a lives system and game-over state.
- **Basic Ghost Movement:** At least two active ghosts navigating the grid matrix with basic collision and pursuit logic.
- **UI Overlay Menu:** a togglable overlay panel (using the ESC key) that displays game controls and instructions.

### Desired ("Nice to Have") Features
- **Four Distinct Ghost Algorithms:** Implementing unique targeting/pathfinding logic for all four ghosts (Direct Chase(Red), Ambush(Pink), Patrol(Cyan), and Shy(Orange)).
- **Power Pills & Frightened State:** Special pills that temporarily turn ghosts blue and eating them will result in bonus points.
- **Audio:** Sound effects for eating pills, ghost sirens, and game-over transitions.
- **Multiple Map Layouts:** Selectable custom maze layouts built from different grid matrices. 

## 4. Timeline
- **Phase 1:** Set up project folder structure, create the basic 2D array grid matrix, and render wall and pills titles on canvas. 
- **Phase 2:** Implement grid Pac-Man movement, wall collision detection, pills consumption, and score/lives tracking.
- **Phase 3:** Introduce ghost movement on the grid, basic ghost collision, and game state loops (Start Screen, Active Play, Game Over) with a togglable UI overlay menu.
- **Phase 4:** Ghost pathfinder logic, conduct beta testing (document it in beta-testing.md), and complete the final reflection (reflection.md).
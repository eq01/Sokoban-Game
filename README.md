# Sokoban Puzzle Game

A single-player puzzle game implementation of the classic Sokoban in Java, featuring strategic gameplay mechanics and object-oriented design patterns.

## Game Overview

Sokoban is a classic puzzle game where players navigate grid-based levels, pushing objects to solve increasingly complex challenges. This implementation emphasizes clean code architecture, robust collision detection, and modular game logic.

## Features

### Core Gameplay
- **Directional Movement**: Navigate using arrow keys (up, down, left, right)
- **Collision System**: Robust detection prevents movement through walls and invalid positions
- **Object Mechanics**: Push crates and trophies in cardinal directions (no diagonal movement)
- **Permanent Consequences**: Objects that fall into holes are irretrievably lost
- **Strategic Puzzle Solving**: Each move matters—plan carefully with no undo functionality

### Technical Implementation
- **Design Patterns**: Visitor pattern for clean game logic separation
- **Modular Architecture**: Utility classes and function objects for maintainability
- **Keyboard Controls**: Responsive input handling for smooth gameplay

## How to Play

1. **Movement**: Use arrow keys to move your character in four directions (↑ ↓ ← →)
2. **Push Objects**: Move crates and trophies by walking into them
3. **Avoid Holes**: Any object or player that falls into a hole is permanently removed
4. **Solve Puzzles**: Complete each level by strategically positioning objects
5. **Plan Ahead**: No undo feature—every move counts!

## Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/af60b686-a3c9-43ee-a4ad-e17795035367" alt="Gameplay Screenshot 1" width="800"/>
  <br>
  <em>Level overview showing player, crates, and obstacles</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7def52cc-01d3-4c6c-b071-4f188dd9455b" alt="Gameplay Screenshot 2" width="800"/>
  <br>
  <em>Mid-puzzle gameplay demonstration</em>
</p>

## Technologies

- **Language**: Java
- **IDE**: Eclipse
- **Graphics Library**: impworld
- **Paradigm**: Object-Oriented Programming

## Architecture Highlights

- Visitor pattern for game state management
- Modular component design for extensibility
- Separation of concerns between game logic and rendering
- Efficient collision detection algorithms

## Game Rules

- ✅ Move in four cardinal directions only
- ✅ Push objects one at a time
- ❌ No diagonal movement
- ❌ Cannot pull objects
- ❌ No undo/redo functionality
- ❌ Objects in holes cannot be retrieved


## Development

This project was co-developed as a collaborative effort, focusing on:
- Clean code practices
- Design pattern implementation
- Game mechanics and user experience
- Modular software architecture

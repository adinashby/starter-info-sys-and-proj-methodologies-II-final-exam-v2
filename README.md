# Information System and Project Methodologies II - Final Exam - V2

This template repository is the starter project for Integrative Project in Information System and Project Methodologies II Final Exam V2. Written in C#.

## Instructions
- This exam is **closed book**, and you are allowed to use your notes only. However, **you cannot use AI tools use internet or collaborate with others to solve the problems.**
- You must design and implement two **independent game features**, each requiring the integration of **two design patterns**.
- Clearly explain your **choice of design patterns** and how they interact within the game.
- Submit your **source code** along with a **short documentation** describing the design choices and implementation details.

## Question 1: Implement an Audio Management System (50%)

### Problem Statement
You are developing an Audio Management System for a video game. The system should manage background music, sound effects, and ambient audio in a modular and efficient way. Your solution must reduce resource consumption, and offer a clean API for developers to use.

- **Flyweight**: Reuse sound assets across scenes.
- **Facade**: Provide a simplified interface for managing audio.
- **Proxy**: Lazy load audio files or stream large soundtracks only when needed.
- **Bridge**: Separate audio abstraction (e.g., volume, channel, effects) from implementation (e.g., MP3, WAV player).

### Requirements
- Implement at least **two design patterns** from the above list.
- Write a short report (a page or less) explaining how the design patterns were applied and their benefits.
- Your implementation should be **object-oriented** and well-structured.
- Ensure the code is **modular** and follows **SOLID principles**.

## Question 2: Implement an Enemy Spawning System (50 points) (50%)

### Problem Statement
Design an Enemy Spawning System that creates different types of enemies (e.g., melee, ranged, boss) during gameplay. The system must support dynamic instantiation and customization of enemies and allow for efficient memory and logic management.

- **Prototype**: Clone enemy templates at runtime.
- **Builder**: Build enemies step-by-step with optional features (armor, behavior, loot).
- **Factory Method**: Centralize logic for creating different enemy types.
- **Bridge**: Decouple enemy roles (e.g., attack strategy) from their implementations (e.g., animation or physics engines).

### Requirements
- Implement at least **two design patterns** from the above list.
- Write a short report (a page or less) explaining how the design patterns were applied and their benefits.
- Your implementation should be **object-oriented** and well-structured.
- Ensure the code is **modular** and follows **SOLID principles**.

---

## Evaluation Criteria
- **Correctness (70%)**: The game feature meets the functional requirements and integrates the selected design patterns properly.
- **Code Quality (10%)**: The implementation follows clean code practices, including modularity and proper naming conventions.
- **Documentation (20%)**: A brief report explaining the system architecture, why certain patterns were chosen, and how they improve the system.

This final exam assesses your ability to **apply, combine, and justify** the use of advanced design patterns in game development. **Good luck!**


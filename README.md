# Snake_Game


🐍 Snake Game using Python & Pygame

This project is a step-by-step implementation of the classic Snake Game using Python and Pygame.
It is designed in a modular way so beginners can understand how a complete game is built from scratch.

🚀 Project Overview

The game evolves gradually from a simple moving block to a fully functional snake game with:

🎮 Movement controls
🍎 Apple (food) system
📈 Score tracking
💀 Collision detection (self + walls)
🔁 Game over & restart logic
🎵 Background music & images
🧩 Development Approach (Step-by-Step)

This project is divided into multiple stages to make learning structured and easy:

1️⃣ 1_build_screen_moving_block.py

👉 Goal: Understand basic Pygame setup

Initialize Pygame
Create game window (screen)
Draw a single block
Move block using keyboard input

💡 Focus: Screen rendering + basic movement

2️⃣ 2_using_object_oriented_progra

👉 Goal: Introduce OOP (Object-Oriented Programming)

Create classes (e.g., Snake, Game)
Organize code into reusable components
Improve code structure

💡 Focus: Clean and scalable design

3️⃣ 3_moving_block_and_timer.py

👉 Goal: Add game loop timing

Introduce continuous movement
Control speed using time.sleep() or clock
Smooth gameplay

💡 Focus: Game loop + timing control

4️⃣ 4_build_snake_draw_apple.py

👉 Goal: Build actual snake and apple

Convert block → snake body (multiple segments)
Draw apple randomly on screen
Render both snake and apple

💡 Focus: Arrays/lists for snake body

5️⃣ 5_snake_eats_apple_and_score.py

👉 Goal: Add gameplay mechanics

Detect collision between snake & apple
Increase snake length
Update score

💡 Focus: Collision detection + game logic

6️⃣ 6_game_over_restart_logic.py

👉 Goal: Handle game ending

Detect collision with:
Itself 🐍
Walls 🧱
Show Game Over screen
Add restart functionality

💡 Focus: Exception handling + reset logic


# Bubble Game 🎯

Bubble Game is a fun and interactive game built using **React** and **CSS**, where the player clicks on randomly generated bubbles within a set time limit to score points. The goal is to hit the target number and maximize your score before the timer runs out.

![image](https://github.com/user-attachments/assets/ca12483a-25d1-4a1f-ae6b-6f5632bf7c29)

## Features

- **Interactive Gameplay**: Click on bubbles displaying random numbers. Each correct hit increases your score, while a wrong hit decreases it.
- **Dynamic Bubbles**: The bubbles regenerate after each hit, providing fresh targets to keep the game exciting.
- **Timer Countdown**: A 60-second countdown timer challenges players to score as many points as possible before the time runs out.
- **Score Tracking**: Real-time score tracking based on correct and incorrect clicks.
- **Game Control**: Start, pause, and resume the game at any time during play.
- **Game Over Screen**: A final screen displays the player's score once the timer reaches zero.

## How to Play

1. Click on the "Start Game" button to begin.
2. A target number will be displayed in the **Hit** box.
3. Click the bubbles that match the target number to score points:
   - **Correct Hit**: +10 points.
   - **Wrong Hit**: -10 points.
4. The game ends when the timer reaches zero, and your final score will be displayed.

## Tech Stack

- **React**: For building the dynamic user interface and managing game state.
- **CSS**: Used for styling the bubbles and layout.

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/skp3214/bubble-game.git
    ```

2. Navigate to the project directory:

    ```bash
    cd bubble-game
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

4. Run the app:

    ```bash
    npm start
    ```

The game will be available at `http://localhost:3000`.

## Future Enhancements

- Add difficulty levels (easy, medium, hard) with varying timers and scoring systems.
- Add sound effects for hits and misses.
- Mobile responsiveness for better gameplay on smaller screens.


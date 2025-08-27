# Street Racer – Simple Car Racing Game 🏎️💨

**Street Racer** is a **browser-based 2D car racing game** built with **HTML5, CSS3, and Vanilla JavaScript**.
It’s a single-page lightweight game where players steer their car, avoid incoming traffic, and score points as they survive longer.
The game offers smooth animations, touch controls, keyboard controls, adjustable difficulty levels, and local high-score tracking.

This project demonstrates canvas rendering, collision detection, keyboard/touch input handling, and game loop implementation using pure JavaScript — without any external game engines or libraries.

# 🎮 Gameplay Overview

**Objective**: Survive as long as possible without colliding with other cars.

**Controls**:

1.**Arrow Keys / A / D** → Steer left or right

2.**Arrow Down / S** → Brake

3.**P** → Pause/Resume the game

4.**Touch Controls** → Available for mobile users

**Scoring**: Points increase as you dodge traffic and cover more distance.

**Difficulty**: Adjust speed & traffic density using the difficulty slider.

**High Scores**: Stored locally using LocalStorage.

# ✨ Features

✅ **Canvas-based 2D Rendering** — Smooth visuals optimized for browsers

✅ **Responsive UI** — Works perfectly on desktop & mobile

✅ **Touch & Keyboard Controls** — Play seamlessly on any device

✅ **Adjustable Difficulty** — Easy, Normal, and Hard modes

✅ **Real-time Scoring System** — See your score and high score instantly

✅ **Pause & Restart** — Full game lifecycle controls

✅ **Lightweight & Fast** — No external frameworks required

# 🛠️ Tech Stack
| Technology       | Purpose                                    |
| ---------------- | ------------------------------------------ |
| **HTML5**        | Structure & game canvas                    |
| **CSS3**         | Styling & responsive layout                |
| **JavaScript**   | Game logic, animations, and event handling |
| **Canvas API**   | Rendering road, cars, and lane movement    |
| **LocalStorage** | Saves player’s high score                  |

# 💡 Key Concepts Implemented

🎯 **Game Loop Management** — Efficient rendering using requestAnimationFrame

🚗 **Collision Detection** — Real-time hitbox checking between cars

🛣️ **Dynamic Lane & Traffic Generation** — Procedural AI traffic spawn system

⏯️ **Pause & Resume System** — Smooth handling of game state transitions

🔊 **Audio Feedback** — Simple beeps for car movements and collisions

📱 **Touch Controls** — Mobile-friendly controls for lane switching & braking

# 📂 Project Structure
Street-Racer/

├── index.html 
# Single HTML file (contains styles, scripts, and canvas)
└── assets

# 🚀 How to Run the Game

**Clone the repository:**

git clone https://github.com/your-username/street-racer.git


**Navigate into the folder:**

cd street-racer


**Launch the game:**

Just double-click on index.html or open it manually in any modern browser.

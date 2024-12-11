# Flappy Bird 🐦

### Duration: Feb 2023 to April 2023
This project is a Python-based recreation of the classic **Flappy Bird** game. Built using the **Pygame** library, it combines responsive controls, dynamic game mechanics, and engaging visuals for a fun and interactive experience.

---

## 📂 Project Structure

```plaintext
flappy-bird/
├── resources/                     
│   ├── bird_down.png
│   ├── bird_mid.png
│   ├── bird_up.png
│   ├── background.png
│   ├── ground.png
│   ├── pipe_top.png
│   ├── pipe_bottom.png
│   ├── game_over.png
│   └── start.png
├── game.py                        
├── README.md                     
└── requirements.txt               
```
## 🔧 Setup and Usage
### Clone the repository
```bash
git clone https://github.com/ashish-shiju/flappy-bird 
```
### Install dependencies
```bash
pip install -r requirements.txt
```
### Run the Game
``` bash
python game.py
```
## 🔍 How It Works
### Gameplay:
Control the bird using the SPACE key to navigate through obstacles.
The game tracks your score based on how many pipes you successfully pass.

### Mechanics:
1. Gravity: The bird is affected by gravity, pulling it downward.
2. Flapping: Pressing SPACE applies an upward force to the bird.
3. Collision Detection: The game ends if the bird collides with the pipes or the ground.

### Game Features:
Dynamic scoring system.
Randomly generated pipes for endless gameplay.
Animated bird with smooth transitions between frames.
Restart option after a game over by pressing R.


## 🧠 Features and Technology Used
**Python**: Core programming language for the game logic and mechanics.

**Pygame**: Provides functionality for game development, including:
1. Sprite Management: For managing the bird, pipes, and ground as game objects.
2. Collision Detection: Ensures the bird reacts to obstacles and ends the game if needed.
3. Rendering: Efficiently renders images and text on the screen.

## 🎯 Game Highlights
### Dynamic Difficulty:
The pipes are generated randomly with varying gaps, keeping the game challenging.
### Smooth Animations:
Bird animations change seamlessly as it flaps, falls, or collides.
### Scoring System:
Every successful passage through pipes increases your score, displayed on the screen in real-time.

## 📬 Contact
Feel free to reach out for questions or collaboration:

Email: ashish.shiju@outlook.com

GitHub: https://github.com/ashish-shiju

## ⚠️ Disclaimer
This project is a personal, educational recreation of the Flappy Bird game and is not intended for commercial use.





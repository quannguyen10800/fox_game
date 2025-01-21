
# 🦊 Fox Game

The Fox Game is a fun and interactive browser-based game where players care for a fox as it hatches, eats, poops, and sleeps. Your goal is to keep the fox alive and happy by meeting its needs and maintaining a clean environment.


## 📝 Requirements and Gameplay

Getting Started

- The game starts in an initialized state. Press the center button to begin.

Navigation and Controls
- Use the left and right buttons to cycle through the icons at the bottom of the screen.
- To select an icon, press the center button.
- Navigation is circular, meaning if you move past the last icon, it will loop back to the first icon.

### Game Features
#### Hatching
- When the game starts, the fox hatches after playing a hatch animation.
#### Daytime and Weather
- After hatching, the fox starts in an idle animation during the day.
- The user can switch the weather between day and rain using the weather icon.
#### Fox Needs
- The fox becomes hungry on a randomized schedule:
    You can only feed the fox when it’s hungry.
    After being fed, the fox will eventually poop:
    Poop can only be cleaned up when present.
    Cleaning up poop resets the timer, and the fox becomes      hungry again after another random interval.
    The fox cannot be hungry and have poop at the same time.
#### Nighttime
- After a random interval, the game transitions to nighttime:
    The fox sleeps during the night and cannot eat, poop, or    die.
    Weather changes, feeding, and cleaning are disabled at night.
    Once the fox wakes up, the cycle restarts with a new hunger interval.
#### Game Over
- If the user neglects to feed a hungry fox or clean up its poop, the fox dies.
- Upon death:
    The landscape transitions to a death scene, and the fox turns into a tombstone.
    A modal prompts the user to restart the game by pressing the center button.
#### Restarting the Game
- Pressing the center button after a game-over restarts the         game, beginning with a new hatch.

## 🔧 Installation and Setup

Clone the repository:

`git clone <repository-url>`

`cd fox-game`

Open the project in your code editor and start a local development server:

`npm install`

`npm start` or `npm run dev`

Open the game in your browser at http://localhost:3000.
## 🛠️ Technologies Used

- HTML, CSS, and JavaScript for the frontend.
- Randomized timers to create unpredictability in gameplay.
## 🎮 Play the Game

Care for your fox, keep it alive, and enjoy the cycle of day and night! 🦊✨

# Snake-And-Apple-Godot
# 🐍 Snake & Apple

A snake game I built with Godot. Swipe (or use the arrow keys), eat the apples, and try not to crash into yourself.


<img width="508" height="913" alt="Capture" src="https://github.com/user-attachments/assets/ea027cf5-5b31-479a-bae0-9dafe136b4b5" />
<img width="494" height="904" alt="Capture3" src="https://github.com/user-attachments/assets/52996522-c365-4087-842f-790fa1783738" />
<img width="487" height="905" alt="Capture2" src="https://github.com/user-attachments/assets/25f2895d-32b6-48a8-9bfa-1368691ee8fa" />

## Why I made this
I know C++, so I first made a simple snake game in the terminal. It worked, but I wanted something that actually *felt* like a game: a background, sounds, touch controls, something I could show people. That's how I ended up learning Godot.

## What it has
- Classic snake gameplay: eat apples, grow longer, don't hit the walls or yourself
- The snake speeds up as your score goes up
- Background music and sound effects (eating and game over)
- Swipe controls for phones, arrow keys / WASD on a computer
- Your best score is saved between plays
- A sound on/off button

## Controls
| Action | Phone | Computer |
|---|---|---|
| Move | Swipe | Arrow keys or WASD |
| Start / restart | Tap | Any key / click |
| Mute | Tap "Sound" button | M |

## How to run it
1. Download [Godot 4.3 or newer](https://godotengine.org/download) (the standard version, not .NET)
2. Clone or download this repo
3. Open Godot → **Import** → select `project.godot`
4. Press **F5**

## How it's built
Everything is in one script, `main.gd`, written in GDScript. The board, snake, apple and background are all drawn in code, so there are no image files. The sounds in the `sounds/` folder are simple synthesized tones.

## Things I want to add
- Walls that wrap around
- Power-ups
- A proper start screen
- An Android build

## About me
I'm Anjali, a AI & Web developer who also builds AI agents. You can find my other projects on my [GitHub](https://github.com/Anjali02x) and connect with me on [LinkedIn](https://linkedin.com/in/anjali-patel-499aa4241).

# Tank Star Game

Welcome to Tank Star Game! This is an exciting game where you control a tank and engage in thrilling battles against other tanks. The ultimate objective of the game is to obliterate all enemy tanks and emerge victorious.

## Getting Started

To start a new game, click on the "New Game" button. If you have a game in progress, you can choose to continue it by clicking on the "Saved Game" button.

## Gameplay

Once in the game, you can aim your tank's turret and fire shells using the "Aim" and "Shoot" buttons respectively. The game can be paused and resumed at any point using the "Pause" and "Resume" buttons.

## Choosing Your Tank

You can select your tank by clicking on the "Choose Tank" button. Each tank possesses unique abilities and strengths, so choose wisely to suit your gameplay style!

## Main Menu

You can return to the main menu at any time by clicking on the "Main Menu" button.

## Game Mechanics

The game mechanics are simple yet challenging. You need to maneuver your tank to avoid enemy fire while trying to hit them. Use the terrain to your advantage and plan your moves carefully.

## Controls

The game controls are intuitive. Use the arrow keys to move your tank around the battlefield. Use the mouse to aim your turret and click to fire. Remember, each tank has a different firing rate and reload time, so timing is crucial.

## Class Diagram

The game is structured around several classes, each with its own responsibilities:

- `Screen`: This is the main interface for all screens in the game.
- `DesktopLauncher`: This class launches the game on desktop platforms.
- `Game`: This is the main game class that controls the flow of the game.
- `LoadingScreen`: This class represents the loading screen that is displayed while the game is loading.
- `GameScreen`: This class represents the main game screen where all the action happens.
- `GameCamera`: This class handles the game camera that follows the player's tank around.
- `Rectangle`: This class represents a rectangle shape, used for things like collision detection.

The relationships between classes are: extends, implements, and uses. For example, `GameScreen` extends `Screen`, `DesktopLauncher` launches `Game`, and `GameScreen` uses `GameCamera` and `Rectangle`.

## Have Fun!

We hope you enjoy playing Tank Star Game. Good luck, and may the best tank win!


## UML Class and Use Case Diagrams.
![UML Class-diagram](https://github.com/manik21336/TANK-STAR/assets/108830478/5110ddf9-829d-423e-8937-e48c5a4db473)
![UML Use-case diagram](https://github.com/manik21336/TANK-STAR/assets/108830478/e5253c3c-4f33-45b0-939e-bd8d09868fd8)

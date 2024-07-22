# Cannon-game
![image](https://github.com/user-attachments/assets/b430a3b6-0fcf-4f29-ab44-315242ec67b9)

#### Overview
The final exam project involves designing and implementing a 2D side-view artillery game called "Cannon," inspired by classic artillery games. The game is developed using the Kivy framework and is intended to run on any system with Python 3 and Kivy installed.

#### Game Description
- **Single-player Game:** The player controls a cannon at the left end of the screen to hit a target on the right side.
- **Player Controls:** Adjust the elevation angle, muzzle velocity, and type of projectile.
- **Objective:** Hit the target in the least number of shots across optional rounds.
- **Projectiles:** Three types - Bullet, Bombshell, and Laser, each with unique properties and interactions.

#### Specifications
- **Screen Size:** Defined by `SCREEN_WIDTH` and `SCREEN_HEIGHT` constants.
- **Time and Frame Rate:** Measured in seconds, with optional FPS customization.
- **Projectiles:**
  - **Bullet:** Affected by gravity, follows a parabolic trajectory, and impacts obstacles within a specified radius.
  - **Bombshell:** Affected by gravity, follows a parabolic trajectory, penetrates obstacles, and affects a larger radius.
  - **Laser:** Not affected by gravity, follows a linear trajectory, penetrates obstacles, and impacts over a specified distance.

#### Obstacles
- **Types of Obstacles:**
  - **Rock:** Main destructible environment component.
  - **Bulletproof Mirror:** Reflects laser impulses and is indestructible.
  - **Perpetio:** Indestructible, similar to Rock.
  - **Optional Obstacles:** Include Wormhole, Gravitonio (affects gravity), and Elastonio (reflects projectiles).

#### Game Functionalities
- **Basic Operations:**
  - Save/Load game state.
  - Hall of Fame.
  - Help menu.

#### Visualization
- **Single-Screen Display:** Entire game field is visible in a fixed window.
- **Extended Field Option:** Allow scrolling to explore a larger game field or follow projectile trajectories.

#### Constants
- **Screen Dimensions:** `SCREEN_WIDTH`, `SCREEN_HEIGHT`
- **Frame Rate:** `FPS`
- **Projectile Parameters:** `BULLET_MASS`, `BOMB_MASS`, `BULLET_RADIUS`, `BOMB_RADIUS`, `LASER_DIST`, `BOMB_DRILL`, `LASER_IMPULSE`, `LASER_VEL`

This project provides flexibility in game design through customizable constants, ensuring an adaptable and engaging gameplay experience.


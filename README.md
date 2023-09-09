# ping-pong-game
Basic 2D Ping Pong game using Unity

### Unity Pong Game Tutorial
This README provides a summarized overview of the Unity Pong game tutorial found on awesomeinc.org.

### Introduction
This readme guides you through creating a Pong game using Unity 2018.1 or later, with C# as the coding language. It should take around two hours to complete.

### Game Components
The Pong game consists of the following components:
- Background
- Paddles
- Ball
- Side walls
- Scoring system
- Reset button

### Step One: The Setup
- Create a new Unity 2D project with the "2D Template."
- Import the provided Unity Pong assets.
- Add the background image and configure sorting layers.
- Configure the Main Camera settings for a better view.

### Step Two: The Paddles
- Add paddles to the scene.
- Configure paddle properties and components (Box Collider 2D and Rigidbody 2D).
- Write a script (PlayerControls.cs) for paddle movement.

### Step Three: The Ball
- Add the ball to the scene.
- Configure ball properties and components (Circle Collider 2D and Rigidbody 2D).
- Create a physics material for the ball.
- Write a script (BallControl.cs) for ball movement and bouncing.

### Step Four: The Walls
- Create wall objects to keep the ball in play.
- Configure wall properties and components (Box Collider 2D).
- Write a script (SideWalls.cs) to detect collisions with walls and score points.

### Step Five: The Scoring User Interface
- Create a HUD object to display scores and the restart button.
- Write a script (GameManager.cs) to manage scoring, UI display, and game reset.
- Create a GUI Skin for customizing text appearance in Unity.

### Final Steps
- Build the game for Mac, PC, or Linux Standalone.
- Customize Player Settings in Unity, including aspect ratios.
- Build and save the executable file for your game.

### How to run?
- Load the ping-pong-game folder in Unity and build the project
- You should be good to go!

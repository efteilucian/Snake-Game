
1. Introduction 
This documentation provides information about a simple Snake Game implemented in Java using the Swing library.
The game features a snake that moves on a grid, trying to eat food and grow longer without colliding with itself or the walls.

2. Requirements 
Java Development Kit (JDK) 8 or later installed on your machine.

3. Installation
Clone or download the Snake Game repository from GitHub.
Open the project in your preferred Java development environment (e.g., IntelliJ IDEA, Eclipse).
Build and run the project.

4. How to Play
Once the game is running, use the arrow keys to control the snake's direction.
The snake will automatically move in the current direction.
Try to eat the food (represented by a red block) to grow longer.
Avoid colliding with the walls or the snake's own body.

5. Game Controls 
Up Arrow: Move the snake upward
Down Arrow: Move the snake downward
Left Arrow: Move the snake to the left
Right Arrow: Move the snake to the right
Exit Button: Exit the game

6. Code Overview

 Main Class SnakeGame.java
The Main class initializes the game by creating an instance of the GameFrame();

![Screenshot 2023-12-19 005606](https://github.com/efteilucian/Snake-Game/assets/102920747/26aa7de7-c2f3-4d17-8a55-16ef532b0271)

Snake Class GamePanel.Java
The Snake class represents the snake in the game. It keeps track of the snake's body parts, direction, and handles movement and collision logic.
Also the color of the snake & food system.
Also user input,updates and rendering.
![image](https://github.com/efteilucian/Snake-Game/assets/102920747/f2e40ce4-d5c6-4392-85de-10823be09a79)

Class that sets up the JFrame GameFrame.java
Manages the basic components for a window.
Controls the visibility of the frame
![image](https://github.com/efteilucian/Snake-Game/assets/102920747/2a6156e5-2377-42c3-b8e9-455ded24ef07)

7. Acknowledgements 
This Snake Game implementation is inspired by various online tutorials and examples. Special thanks to the Java Swing documentation and the Java community for valuable resources.




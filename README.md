# Assignment 5 Whack-A-Robot

Assignment No 5 for the computer graphics course. 

Based on the Class demos, create a [whack a mole](https://en.wikipedia.org/wiki/Whac-A-Mole) style game. The game must have a score, and a timer. When the timer ends, the game stops and an option to restart is given. The user has to interact with a 3D object in the scene that has different animations. You can use the robot model that was used in the demos.

Rubric:

1. Loaded a 3D model with different animations.
2. Create a *dead* animation for the model using keyframes and existing animations.
3. The user can interact correctly with the 3D model, and when an interaction happens, the *dead* animation is played. The model is then erased from the scene after a little while.
4. A high score and timer are correctly implemented.
5. UI feedback messages (to start or restart the game) are correctly displayed.

**NOTES**

1. You did not initialize several variables, including the raycaster needed for the interactions, and the mouse to store its position.
2. The aspect ratio needed for the interaction was done with the window size, not with the canvas' size. That is why the mouse never hits any robot.
3. You did not add an event listener for the moouseDown event, which is why the mouse never reacted.
4. No dead animation created, and was not executed when the robots were clicked.
5. There was no timer, or indication to restart the game.

**Grade: 70**
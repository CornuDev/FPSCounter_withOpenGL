# FPSCounter_withOpenGL
Simple FPS Counter

Usage guide:
	1. Include the "FPSCounter.h"
	2. Create an instance of the `FPSCounter` class and pass the coordinates of the text position as parameters to its constructor.
	3. Within the main rendering loop, call the `displayAndUpdateFPS` function after rendering each frame to display and update the FPS. 
     This function will draw the FPS text at the specified position and update the FPS value once per second.

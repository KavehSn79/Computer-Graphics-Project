# Computer-Graphics-Project
Project Overview:
This computer graphics project demonstrates the rendering of a 3D bracelet using OpenGL. 
It utilizes various libraries and components, including GLFW for window management, GLAD for OpenGL function loading, and STB image for texture loading. 
The project also incorporates a custom shader class, vertex array objects (VAO), vertex buffer objects (VBO), element buffer objects (EBO), textures, and camera controls.

Dependencies:
GLFW: A library for creating windows and managing OpenGL contexts.
GLAD: A library for loading OpenGL function pointers.
STB Image: A library for loading image textures.
GLM: A mathematics library for OpenGL transformations and calculations.

Project Structure:
shaderClass.h: Custom shader class for managing shader programs.
VAO.h: Vertex Array Object class for handling VAOs.
VBO.h: Vertex Buffer Object class for managing VBOs.
EBO.h: Element Buffer Object class for managing EBOs.
Texture.h: Texture class for loading and binding textures.
Camera.h: Camera class for controlling the view of the 3D scene.

Usage:
Once you have successfully installed the project, you can use it to render a 3D Bracelet. Here are some key usage instructions:

The program creates a window that displays the 3D shape.
Use the mouse to control the camera's viewpoint.
Press 'W', 'A', 'S', and 'D' keys to move the camera.
Scroll the mouse wheel to zoom in and out.
Press 'Esc' or close the window to exit the program.

Features:
Rendering of a 3D shape with OpenGL.
Custom shader program management.
Camera controls for viewing the 3D scene.
Texture loading and mapping onto the shape.
Keyboard and mouse input for interaction.



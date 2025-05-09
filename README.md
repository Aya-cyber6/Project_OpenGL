# Project_OpenGL

This project renders a 3D scene inspired by **Sonic Adventure**, featuring models such as Station Square Chao Garden and Tails (Miles). It uses modern OpenGL with shaders, camera movement, lighting, and model loading.

## Features

- First-person camera with mouse and keyboard input
- Directional lighting with ambient, diffuse, and specular components
- Model loading using Assimp (sonic, tails🦊 and the stage)
- Custom shaders
- Depth testing

## Dependencies

Make sure you have the following libraries:

- [GLFW](https://www.glfw.org/)
- [GLAD](https://glad.dav1d.de/)
- [GLM](https://github.com/g-truc/glm)
- [Assimp](https://github.com/assimp/assimp)

## Setup Instructions

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/Project_OpenGL
   cd Project_OpenGL
   
2.Configure Visual Studio Project:

Go to Project → Properties → Configuration Properties → VC++ Directories

Add paths to your Include and Library directories.

Go to Linker → Input → Additional Dependencies

Add the following: opengl32.lib; glfw3.lib; assimp-vc143-mt.lib;

I used Acitve(Debug) configaration and all platforms but you can use whatever works for you 
![image](https://github.com/user-attachments/assets/97a9f7d0-d2ce-4066-a57c-0608d03fe5fd)

## Credits

3D models by: https://www.models-resource.com/dreamcast/sonicadventure/
Tutorial guidance and reference: [LearnOpenGL](https://learnopengl.com/)

# Project_OpenGL

This project renders a 3D scene inspired by **Sonic Adventure**, featuring models such as Station Square Chao Garden and Tails (Miles). It uses modern OpenGL with shaders, camera movement, lighting, and model loading.
Here is a detailed report about the project: [RAPOR.pdf](https://github.com/user-attachments/files/20131026/RAPOR.pdf)

## ✨ Features

- First-person camera with mouse and keyboard input  
- Directional lighting with ambient, diffuse, and specular components  
- Model loading using Assimp (Sonic, Tails🦊, and the stage)  
- Custom GLSL shaders  
- Depth testing for realistic rendering

## 🛠️ Dependencies

Make sure the following libraries are installed and properly linked:

- [GLFW](https://www.glfw.org/)  
- [GLAD](https://glad.dav1d.de/)  
- [GLM](https://github.com/g-truc/glm)  
- [Assimp](https://github.com/assimp/assimp)

## ⚙️ Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Project_OpenGL
   cd Project_OpenGL
   ```

2. Configure your Visual Studio project:

   - Go to **Project → Properties → Configuration Properties → VC++ Directories**  
     Add the paths to your `Include` and `Library` directories.

   - Then go to **Linker → Input → Additional Dependencies**  
     Add the following:  
     `opengl32.lib; glfw3.lib; assimp-vc143-mt.lib;`

   - This project was built using **Active(Debug)** configuration for **All Platforms**, but feel free to use what's compatible with your system.

   ![image](https://github.com/user-attachments/assets/97a9f7d0-d2ce-4066-a57c-0608d03fe5fd)

## 🙌 Credits

- **3D Models from**: [The Models Resource – Sonic Adventure](https://www.models-resource.com/dreamcast/sonicadventure/)  
- **Tutorial guidance and code structure**: [LearnOpenGL](https://learnopengl.com/)


## Some screenshots from the scene

![Screenshot 2025-05-10 002510](https://github.com/user-attachments/assets/b07cb43e-7abd-4196-83d0-936561d80524)


![Screenshot 2025-05-10 002652](https://github.com/user-attachments/assets/35aaa64b-0896-4e29-aee7-5c9b8d48bdcb)


![Screenshot 2025-05-10 002707](https://github.com/user-attachments/assets/ee8c4943-1c5e-4cf2-bd5d-af6a5a50e617)


![Screenshot 2025-05-10 002605](https://github.com/user-attachments/assets/26e40c98-5fe9-4d9d-b6c5-8ebc2bf7f57f)

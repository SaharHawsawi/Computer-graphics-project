# Computer-graphics-project
Eid in Makkah is a C++ interactive storytelling project that follows a family of three as they prepare to celebrate Eid al-Fitr in Makkah. The story uses textures, on-screen text, and visual scenes and other features to create an engaging experience.
# Eid al-Fitr in Makkah


## User Manual

### 1. Prerequisites
To build and run this project, you need the following installed on your system:
- **C++ Compiler**: Microsoft Visual Studio.
- **OpenGL Library**: Standard OpenGL libraries.
- **Texture Files**: The project requires specific `.bmp` files located in the correct directory.

### 2. Required Texture Files
Before running the project, You must change these paths in the source code (lines 33-37) to match where you saved the images on your computer:
- `Somaqqq.bmp`
- `woodennnnnnnnnn.bmp`
- `dolabbFinal.bmp`
- `sujadd33444.bmp`
- `woddon.bmp`

### 3. How to Build and Run

#### Using Microsoft Visual Studio 
this section outlines the steps to set up, build, and run the project using Microsoft Visual Studio and the NuGet Package Manager for easy library installation.(Microsoft)

**1. Create a New Project:**
   - Open Visual Studio.
   - Select `Create a new project`.
   - Choose `Empty Project`
   - Enter a project name, then click `Create`.

**2. Configure NuGet Package Manager:**
   - From the top menu, select `Tools - NuGet Package Manager - Package Manager Settings`.
   - In the left-hand menu, select `General`.
   - Click `Clear All NuGet Cache(s)`.
   - In the left-hand menu, select `Package Sources`.
   - Click the `+` icon to add a new package source.
   - Set `Name`: `nuget.org`
   - Set `Source`: `http://api.nuget.org/v3/index.json`
   - Click `Update` to save the changes.
   - Click `OK` to close the settings window.

**3. Install nupengl.core Package:**
   - Go to `Tools - NuGet Package Manager - Package Manager Console`.
   - A command window will appear at the bottom. Wait until `PM>` appears.
   - Type the following command and press Enter: Install-Package nupengl.core
    
   - Wait for the installation to complete. You should see a message indicating successful installation.

**4. Add Source File:**
   - In the Solution Explorer, right-click on your project (e.g., `EidProject`).
   - Select `Add - New Item...`.
   - Open the newly created `Eidproject.cpp` file.
   - Copy the entire content of your provided `.cpp` file (`FinalForFinalProTheRealFinalٌSooFinal.cpp.txt`) into `main.cpp`.

**5. Update Texture File Paths:**
   - In `Eidproject.cpp`, locate lines 33-37, which define the paths to the `.bmp` texture files:
     ```
     char image1Path[] = "C:\\Users\\s4460\\OneDrive\\Dokumente\\Somaqqq.bmp";
     // ... etc
     ```
**6. Build and Run:**
   - Go to `Local Windows Debugger`.
   
### 4. How to Use (Controls)
you can interact with the scenes using your mouse and keyboard.

#### Mouse Controls
- **Left Mouse Click**: Transitions to the next scene. The scenes are in the following order: Scene 1 -> Scene 2 -> Scene 3 -> Scene 4 -> Scene 1....

#### Keyboard Controls
- **'D' or 'd'**: Moves the Mother character to the right.
- **'A' or 'a'**: Moves the Mother character to the left.
- **'M' or 'm'**: Makes the rafif jump.

### 5. Scene Descriptions
- **Scene 1**: Shows the characters in a room standing with a wardrobe, vanity table, and a moving clock. with dialogues
- **Scene 2**: Shows the characters in a different setting, preparing for prayer, featuring a background people and prayer mat texture, a door texture and shelf texture with books, and dialogues
- **Scene 3**: An outdoor scene with a sun, trees, street lines, and background people and a basket of dates. with  dialogues
- **Scene 4**: The final scene concluding the story with a dialogue about the meaning of Eid in Makkah with a moving sun.


## References
1. Toal, R. (n.d.). OpenGL examples. Loyola Marymount University. https://cs.lmu.edu/~ray/notes/openglexamples/
2. The freeglut Programming Consortium. (2013, January). API documentation - The freeglut project. https://freeglut.sourceforge.net/docs/api.php
3. Suraj Sharma. (2018, June 24). OpenGL / C++ 3D Tutorial 22 - Texture class (Nice and tidy!) [Video]. YouTube. https://www.youtube.com/watch?v=4tdy1izUv_Y

# 👩‍💻 Team Members
* Sahar Hawsawi [linkedin profile](https://www.linkedin.com/in/sahar-hawsawi-4133aa361)
* Roaa Asim Alturkistani [linkedin profile](https://www.linkedin.com/in/roaa-alturkistani-608a44384)
* Maria Mohammed Alamri [linkedin profile](https://www.linkedin.com/in/maria-al-amri-6b3145274?utm_source=share_via&utm_content=profile&utm_medium=member_ios)
* Meera Waleed Almazrouei [linkedin profile](https://www.linkedin.com/in/meera-almazrouei-199a6b35b)

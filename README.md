
# MetaHumanInteraction

This project showcases an interactive 3D environment featuring a virtual human that dynamically responds to user gaze. The virtual character tracks the user's head and eye movement, ensuring realistic eye contact and alignment of head, neck, and body. Designed for walk-by interactions, the simulation adjusts for user height, creating a natural and immersive experience.

## Instructions

### 1. Clone the Repository

To download the project, **use Git** to clone the repository. It's important to clone via **HTTP** as assets won’t be downloaded if you download it as a zip.

1. Open your terminal (or Command Prompt on Windows).
2. Navigate to a suitable folder where you want to clone the project:
   ```bash
   cd /path/to/your/folder
   ```
3. Clone the repository using the following command:
   ```bash
   git clone https://github.com/YourUsername/MetaHumanSimulation.git
   ```

### 2. Open the Project in Unreal Engine

1. After cloning, open the project folder.
2. Locate and double-click the `.uproject` file to open the project in Unreal Engine.

### 3. Build the Executable Game/Environment

To package the project into an executable for your desired platform:

1. In **Unreal Engine**, go to the **Platforms** menu.
2. Select the desired operating system to run the environment (e.g., **Windows, Mac, Linux**).
3. Click on **Shipping** as the build configuration.
4. Click on **Package Project**.
5. Unreal Engine will prompt you to select a folder where you want to save the packaged executable.
6. Once the build is complete, an executable file will be generated in the folder you selected.

### 4. Running the Executable

Once the project is successfully packaged, you'll find the **executable** in the folder you selected during the packaging process.

1. Navigate to the folder where you built the executable.
2. Open the executable file to run the game/environment.

### 5. Important Notes

- Make sure all assets are properly downloaded via Git LFS when cloning the repository. If assets aren’t downloaded, the project may not load correctly.
- You can check the status of Git LFS and make sure files are being tracked by running:
  ```bash
  git lfs status
  ```

## Requirements

- **Unreal Engine** (version X.X.X or higher)
- **Git** and **Git LFS** (Large File Storage) for downloading assets

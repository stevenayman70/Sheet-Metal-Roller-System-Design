# Sheet Metal Roller System Design & Simulation

This project features the mechanical design and dynamic simulation of a sheet metal rolling mechanism. It represents a full engineering workflow, moving from 3D CAD modeling to motor performance analysis.

## 🚀 Key Features
* **Full CAD Assembly:** Detailed 3D model of the roller system including rails and motor mounts.
* **Simulink Simulation:** Dynamic model to analyze the torque and velocity requirements of the rollers.
* **Cross-Platform Compatibility:** Universal `.STEP` exports for viewing in any 3D software.
* **Motor Analysis:** MATLAB scripts for configuring DC motor parameters and simulation data.

## 📂 Project Evolution
1. **Phase 1: Mechanical Design** - Developing individual parts (Rollers, Rails, Base) and the main assembly in SolidWorks.
2. **Phase 2: Mathematical Modeling** - Defining DC motor parameters and physical constants in MATLAB.
3. **Phase 3: System Simulation** - Implementing the CAD design into a Simulink environment to test mechanical responses.

## 🛠️ Tech Stack
* **Mechanical Design:** SolidWorks
* **Simulation:** MATLAB & Simulink
* **Standard Formats:** STEP (Standard for the Exchange of Product model data)

## 📂 Repository Structure

| Directory | Content Description |
| :--- | :--- |
| **`/CAD_Models`** | Original SolidWorks assemblies (`.SLDASM`) and parts (`.SLDPRT`). |
| **`/Simulation`** | Simulink models (`.slx`) and MATLAB configuration scripts (`.m`). |
| **`/Exports`** | Standardized 3D files (`.STEP`) for universal CAD access. |



## 📖 How to Run

### 1. Hardware/CAD Viewing
* To view the 3D Model, open `roller_assembly_main.SLDASM` in **SolidWorks**.
* If you do not have SolidWorks, import the files in the `/Exports` folder into any CAD viewer (AutoCAD, Fusion 360, etc.).

### 2. Running Simulations
* Launch **MATLAB** and set the directory to the `/Simulation` folder.
* Run `motor_parameter_config.m` to load variables into the workspace.
* Open `roller_system_sim.slx` in **Simulink**.
* Click **Run** to analyze the motor torque and system velocity outputs.

## ⚖️ License
This project is licensed under the MIT License.

---
### Author
**[Steven_Tawfik]** *University Engineering Project*

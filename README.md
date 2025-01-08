![robot_design_new](https://github.com/user-attachments/assets/0c9906fc-5b74-4df4-a357-484a5dac3c9b)

# Foldable Robotics Project: Basilisk-Inspired Robot

This repository contains all materials related to the **Foldable Robotics Project**, inspired by the basilisk lizard's unique ability to transition between quadrupedal and bipedal locomotion. The project focuses on designing and optimizing a foldable robotic system using a **four-bar mechanism** to enhance movement adaptability and efficiency.

---

## Project Overview

The primary goal of this project is to develop a robotic system capable of mimicking the basilisk lizard's terrestrial locomotion. By systematically altering the four-bar mechanism's parameters, the project aims to:

- Maximize the lift provided to the robot's body.
- Achieve efficient and stable motion transitions between locomotion modes.

This research contributes to the field of biomimetic robotics, emphasizing innovative, adaptable designs with potential applications in exploration, search and rescue, and entertainment.

---

![Tracker_robot](https://github.com/user-attachments/assets/d5ff0daa-88cc-4e28-a99b-1138eab4a8c1)


## MuJoCo and Its Role

**MuJoCo (Multi-Joint dynamics with Contact)** is a high-performance physics engine used extensively in this project to simulate the robot's movements and dynamics. It was integral to:

- **Simulating Dynamics**: The four-bar mechanism and other robotic components were modeled and tested in a virtual environment to evaluate their stability and performance.
- **Optimizing Parameters**: MuJoCo allowed iterative testing of different configurations, such as link lengths, joint angles, and stiffness, to achieve optimal lift and balance.
- **Visualizing Movement**: The simulation provided visual feedback, enabling fine-tuning of parameters and validating the robot's locomotion design.

The XML templates used in MuJoCo defined the physical structure, joint properties, and other dynamic parameters of the robot. These simulations significantly reduced the need for physical prototyping, saving time and resources.



https://github.com/user-attachments/assets/0215e81f-5d5a-4541-8ccd-e1bca6b7b4c5



---

## Repository Contents

### Files Included

1. **`LoopTesting.ipynb`**
   - A Jupyter Notebook containing simulation code for testing different configurations of the four-bar mechanism.
   - Includes functions for analyzing stability, adjusting variables, and visualizing performance.
   - Features dynamic simulations using MuJoCo.

2. **`robot_data.csv`**
   - Contains recorded simulation data for various configurations of the robotic system.
   - Includes columns such as time, position, velocity, and torque data.

3. **`initial_data.csv`**
   - Provides initial parameter sets and configurations used in the simulations.
   - Useful for baseline comparisons and optimization analysis.

4. **`Research.pdf`**
   - A detailed research paper describing the biomechanical inspiration for the project.
   - Explores the basilisk lizard's gait patterns and mechanical principles applied to robotic design.

5. **`Output.pdf`**
   - Summarizes the project's challenges, solutions, and key findings.
   - Highlights the implementation of a systematic approach to stabilize the four-bar mechanism.

6. **Existing `README.md`**
   - A basic placeholder file replaced by this comprehensive version.

---

## Features

### Key Components

1. **Four-Bar Mechanism**
   - Designed to replicate the basilisk's hind limb movement for efficient locomotion.
   - Parameters are adjustable for optimized lift and stability.

2. **Simulation Environment**
   - Built using MuJoCo for realistic dynamic analysis.
   - XML templates for configuring the four-bar mechanism and the full robot system.

3. **Data Analysis**
   - Code includes functions to process simulation data, detect tipping conditions, and visualize performance metrics.

### Tools & Technologies

- **MuJoCo**: For dynamic simulations and system testing.
- **Python**: For data analysis, visualization, and parameter optimization.
- **Jupyter Notebook**: Interactive environment for running simulations and analyzing results.

---

## Getting Started

### Prerequisites

To run the simulations and analyze the data, you need:

- Python 3.7 or higher
- MuJoCo installed and configured
- Required Python libraries: `numpy`, `pandas`, `matplotlib`, `mediapy`, `scipy`, `tqdm`

---

### Installation Instructions

#### Installing MuJoCo

1. **Download MuJoCo**:
   - Visit the [MuJoCo website](https://mujoco.org/) and download the appropriate version for your operating system.

2. **Install MuJoCo**:
   - Follow the installation guide provided on the MuJoCo website. For Linux and macOS, ensure the `mjkey.txt` is in the MuJoCo directory.

3. **Set Environment Variables**:
   - Add the MuJoCo installation path to your system's environment variables. For example:
     ```bash
     export MUJOCO_PY_MJKEY_PATH=/path/to/mjkey.txt
     export MUJOCO_PY_MJPRO_PATH=/path/to/mujoco
     ```

4. **Install `mujoco-py`**:
   - Use pip to install the Python bindings for MuJoCo:
     ```bash
     pip install mujoco-py
     ```

---

### Running Simulations

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/FoldableRobotics.git
   cd FoldableRobotics
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Open `LoopTesting.ipynb` in Jupyter Notebook and execute the cells to run simulations and analyze results.

4. Adjust the parameters in the notebook or XML files to customize the simulations.

---

## Challenges & Solutions

### Key Challenges
1. Initializing the four-bar mechanism in simulations without instability.
2. Finding the optimal parameters for lift and stability.

### Solutions
- Developed systematic methods for accurate initialization.
- Utilized iterative optimization to refine parameters based on simulation feedback.

---

## References

The project draws inspiration from various studies on basilisk locomotion:
For more details, refer to **`Research.pdf`**.

---

## Contributors

- **Pranay Palem**
- **Puneet Sai Naru**

---


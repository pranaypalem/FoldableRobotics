
# Foldable Robotics Project: Basilisk-Inspired Robot

This repository contains all materials related to the **Foldable Robotics Project**, inspired by the basilisk lizard's unique ability to transition between quadrupedal and bipedal locomotion. The project focuses on designing and optimizing a foldable robotic system using a **four-bar mechanism** to enhance movement adaptability and efficiency.

---

## Project Overview

The primary goal of this project is to develop a robotic system capable of mimicking the basilisk lizard's terrestrial locomotion. By systematically altering the four-bar mechanism's parameters, the project aims to:

- Maximize the lift provided to the robot's body.
- Achieve efficient and stable motion transitions between locomotion modes.

This research contributes to the field of biomimetic robotics, emphasizing innovative, adaptable designs with potential applications in exploration, search and rescue, and entertainment.

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

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/FoldableRobotics.git
   cd FoldableRobotics
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure MuJoCo and ensure the XML files are compatible with your setup.

---

## Usage

1. **Run Simulations**:
   Open `LoopTesting.ipynb` in Jupyter Notebook and execute the cells to run simulations and analyze results.

2. **Data Analysis**:
   Use the provided functions to process simulation outputs (`robot_data.csv` and `initial_data.csv`).

3. **Modify Parameters**:
   Adjust the four-bar mechanism's parameters directly in the notebook or XML files for customized testing.

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

The project draws inspiration from various studies on basilisk locomotion, including:
- Glasheen and McMahon's studies on size and force dynamics.
- Hsieh and Lauder's analysis of water-running forces.

For more details, refer to **`Research.pdf`**.

---

## Contributors

- **Pranay Palem**
- **Puneet Sai Naru**

---


## Additional Resources

- [Project Documentation](https://github.com/pranaypalem/FoldableRobotics) (GitHub link to all resources and updates).

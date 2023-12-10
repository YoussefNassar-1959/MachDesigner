# Photonic Circuit Design Software Tool 👁️‍🗨️🛠️

## Overview 🌐
This tool provides a Graphical User Interface (GUI)-assisted environment for designing photonic circuits. It incorporates advanced simulation capabilities using the Simphony library.

### Features 🚀
- **Component Selection:** Users can select and arrange various photonic components such as Grating Couplers, Waveguides, Y-Splitters, and Y-Combiners.
- **Simulation:** The tool allows for simulations of Mach-Zehnder Interferometer (MZI) circuits, performing theoretical sweeps and noisy analysis.
- **Monte Carlo Simulations:** Enables Monte Carlo simulations for statistical analysis of circuit behavior under varying parameters.

## Installation 🛠️
To run this software, ensure the following libraries are installed:

- PyQt5
- Matplotlib
- Simphony

## How to Use 📝
1. **GUI Interface:** The GUI presents a selection of components using dropdown menus.
2. **Parameters Input:** Users input specific parameters such as wavelengths and power through spin boxes.
3. **Run Simulation:** Clicking the "RUN!" button initiates the simulation process.
4. **Results:** The tool displays theoretical and noisy analysis plots alongside the GUI.

## Code Structure 🧱
- The software consists of two main parts: 
  - **Core Simulation Code:** Contains the simulation logic using Simphony's functionalities.
  - **GUI Code:** Implements the user interface using PyQt5.

### Simulation Code 🖥️
- The simulation code initializes components like Grating Couplers, Waveguides, and implements connections among them.
- It conducts simulations, varying parameters such as laser power and wavelengths.
- Plotting functionalities visualize theoretical and noisy analysis results.

### GUI Code 💻
- The GUI comprises dropdown menus for component selection and spin boxes for parameter input.
- Upon user input, the code validates circuit connections and initiates simulations.
- Error messages alert users to incorrect circuit configurations.

## Usage Examples 📊
### Theoretical Analysis 📈
![Theoretical Analysis]([path_to_image.png](https://simphonyphotonics.readthedocs.io/en/stable/_images/plot_mzi.png))
- Demonstrates the theoretical behavior of the designed photonic circuit.

### Noisy Analysis 🎢
![Noisy Analysis](path_to_image.png)
- Illustrates the impact of noise on the circuit behavior through multiple noisy samples.

## Contribution 🤝
- Contributions and enhancements are welcome via pull requests.
- For major changes, please open an issue first to discuss potential modifications.

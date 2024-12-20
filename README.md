Interactive RLC Circuit Analyzer
This repository contains tools for simulating and analyzing RLC circuits using MATLAB and Simulink. It provides an interactive environment to explore circuit behavior and visualize frequency responses.

Files in the Repository
User_Input.mlapp
This is a MATLAB App Designer file for creating an interactive graphical user interface (GUI). The app allows users to:

Input RLC circuit parameters (Resistance, Inductance, Capacitance).
Specify the desired frequency range.

circuit_simulation.slx
A Simulink model for simulating the RLC circuit based on user-defined parameters. This model computes circuit responses and generates data for visualization in the GUI.

Features
Interactive Input: Customize RLC parameters and frequency range.
Visualization: Real-time plotting of frequency response curves.
Flexibility: Suitable for educational purposes and quick circuit analysis.
How to Use
Open MATLAB and navigate to the repository folder.
Launch the GUI:
matlab
Copy code
appdesigner User_Input.mlapp
Open the Simulink model:
matlab
Copy code
open_system('circuit_simulation.slx')
Use the GUI to input circuit parameters and visualize results.
Requirements
MATLAB (R2021b or later recommended)
Simulink
App Designer Toolbox
Contributing
Feel free to fork this repository and make improvements. Contributions are welcome!


>Interactive RLC Circuit Analyzer

This repository contains tools for simulating and analyzing RLC circuits using MATLAB and Simulink. It provides an interactive environment to explore circuit behavior and visualize responses.

>Files in the Repository:-

> 1)User_Input.mlapp

This is a MATLAB App Designer file for creating an interactive graphical user interface (GUI). 

The app allows users to:

-Input RLC circuit parameters (Resistance, Inductance, Capacitance).

-Specify the desired frequency and voltage amplitude.

> 2)circuit_simulation.slx

A Simulink model for simulating the RLC circuit based on user-defined parameters. This model computes circuit responses and generates data for visualization .

>Features:-

1)Interactive Input: Customize RLC parameters,frequency and amplitude.

2)Visualization: Real-time plotting of user defined parameter  curves.

3)Flexibility: Suitable for educational purposes and quick circuit analysis.

>How to Use:-

1)Open MATLAB and navigate to the repository folder.

2)Launch the GUI:

>Copy code:
appdesigner User_Input.mlapp

3)Open the Simulink model

>Copy code:
open_system('circuit_simulation.slx')

4)Use the GUI to input circuit parameters and Simulink model to visualize results.

>Requirements:-

1)MATLAB (R2021b or later recommended)

2)Simulink

3)App Designer Toolbox

![Screenshot 2024-12-20 135529](https://github.com/user-attachments/assets/bbb16c28-6469-469c-a317-6b38b2876e11)

![Screenshot 2024-12-20 135558](https://github.com/user-attachments/assets/e0ef498a-87bb-4671-b7a6-c43de384d451)

![Screenshot 2024-12-20 135630](https://github.com/user-attachments/assets/fcb529ac-ecb6-41e8-aef6-fb8174d72803)

![Screenshot 2024-12-20 135726](https://github.com/user-attachments/assets/4e1308c2-d6b1-4d06-855f-c8c2f1407b0e)











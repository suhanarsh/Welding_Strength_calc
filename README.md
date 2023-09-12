# Welding_Strength_calc
# Weld Strength Calculator

This repository contains a Python program for calculating weld strength for various joint types commonly encountered in aerospace engineering. The program provides a user-friendly interface implemented using the tkinter library for inputting the necessary parameters and visualizing the results using matplotlib.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Documentation](#documentation)
- [Contributors](#contributors)
- [License](#license)

## Introduction

As a part of the Experiential Learning for Aerospace Structures course at RV College of Engineering under the guidance of Professor Benjamin Rohit, this program was developed by a team of undergraduate aerospace engineering students:

- Sadiq Ali Mir
- Om Daxini
- Veerabhadrayya C Roogi
- Abyan Raidh T
- Vaibhavi Mokashi
- Suhana Arsh
- Ankitha Shett
- Parth Patel
- Inchara Nataraj


The program offers a comprehensive set of functions to calculate weld strength for different joint configurations. The strength calculations are based on standard engineering formulas commonly used in aerospace applications.

## Features

- Supports the following joint types:
    - Single Fillet Weld
    - Double Fillet Weld
    - Double Parallel Weld
    - U Shaped Joint
    - Single Butt Weld
    - Double Butt Weld

- Provides an intuitive GUI for user interaction.
- Displays clear and concise results for weld strength.
- Includes visualization of weld strength using bar charts.

## Installation

This program requires Python 3.x and the following libraries:

- tkinter
- matplotlib

You can install the required libraries using the following pip commands:

```bash
pip install tkinter matplotlib
```

## Usage

To use the program, simply execute the Python script. This will open a graphical user interface (GUI) with options for different types of weld joints. Select the desired joint type and provide the necessary parameters as prompted. The program will then calculate and display the weld strength along with a bar chart for visual representation.

## Documentation

### Functions

1. `single_fillet_weld_strength(s, l, sigma_t)`
   - Calculates the weld strength for a single fillet weld joint.
   
2. `double_fillet_weld_strength(s, l, sigma_t)`
   - Calculates the weld strength for a double fillet weld joint.
   
3. `double_parallel_weld_strength(s, l, tau)`
   - Calculates the weld strength for a double parallel weld joint.
   
4. `u_shaped_joint_strength(s, l1, l2, sigma_t, tau)`
   - Calculates the weld strength for a U shaped joint.
   
5. `single_butt_weld_strength(t, l, sigma_t)`
   - Calculates the weld strength for a single butt weld joint.
   
6. `double_butt_weld_strength(t1, t2, l, sigma_t)`
   - Calculates the weld strength for a double butt weld joint.

7. `plot_results(labels, values, title)`
   - Plots the results using matplotlib.

8. `create_window(option)`
   - Creates a new window for input and output.

### GUI Elements

- The program utilizes tkinter to create a user-friendly GUI.
- Entry widgets and labels are used to get input values from the user based on the selected joint type.
- Buttons are provided to initiate calculations and navigate between windows.

### Main Program

- The main program sets up the root window and defines buttons for each type of weld joint.
- When a button is pressed, it calls the `create_window` function to create a new window for input and output.

### Additional Notes

- The program includes error handling to ensure that the user provides valid numerical inputs.
- Results are displayed with two decimal places for clarity.

## Contributors

- Sadiq Ali Mir
- Om Daxini
- Veerabhadrayya C Roogi
- Abyan Raidh T
- Vaibhavi Mokashi
- Suhana Arsh
- Ankitha Shett
- Parth Patel
- Inchara Nataraj
- 
## Acknowledgments:

We express our heartfelt gratitude to *Professor Benjamin Rophit * for his invaluable guidance, mentorship, and support throughout the "Aerospace Structures" course and this Experiential Learning project. We also extend our thanks to our peers for their collaboration and contributions to the success of this endeavor.


## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details.

---

Feel free to explore and utilize this program for aerospace engineering applications. If you have any questions or suggestions, please don't hesitate to contact the contributors.

**Happy coding!**

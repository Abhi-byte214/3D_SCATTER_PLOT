# 3D_SCATTER_PLOT
Project Overview

This project is a 3D Scatter Plot Visualization built using HTML, CSS, and JavaScript. It displays randomly generated 3D points on an HTML canvas and allows users to visualize them from different angles. The project supports both Orthographic and Perspective projections and includes interactive controls for Yaw, Pitch, and Roll rotations.

Features
Generate and display random 3D points.
Rotate the point cloud using:
Yaw (Y-axis)
Pitch (X-axis)
Roll (Z-axis)
Switch between Orthographic and Perspective projections.
Auto Rotate animation.
Interactive slider controls.
Smooth real-time visualization using HTML Canvas.
Technologies Used
HTML5
CSS3
JavaScript (ES6)
HTML Canvas
JSON
Project Workflow
Generate random 3D points.
Store the points in a JSON file.
Load the dataset into the application.
Convert rotation angles from degrees to radians.
Apply Yaw, Pitch, and Roll rotation formulas.
Project the rotated 3D points into 2D using the selected projection method.
Draw the projected points on the canvas.
Update the display continuously when Auto Rotate is enabled.
Rotation

The project supports three types of rotation:

Yaw – Rotation around the Y-axis.
Pitch – Rotation around the X-axis.
Roll – Rotation around the Z-axis.
Projection Methods
Orthographic Projection

Displays objects without considering depth. All points remain the same size regardless of distance.

Perspective Projection

Creates a realistic 3D effect by making distant points appear smaller than nearby points.

Folder Structure
project/
│── index.html
│── style.css
│── script.js
│── points.json
│── README.md
How to Run
Download or clone the repository.
Open the project folder in Visual Studio Code.
Start a local server (such as Live Server).
Open index.html in your browser.
Use the sliders to rotate the 3D scatter plot and switch between projection modes.
Learning Outcomes

Through this project, I learned:

Basic 3D graphics concepts.
Random generation of 3D coordinates.
Rotation using Yaw, Pitch, and Roll.
Degree-to-radian conversion.
Orthographic and Perspective projection techniques.
Rendering graphics using HTML Canvas.
Interactive web development with JavaScript.
Future Improvements
Zoom in and zoom out controls.
Mouse drag rotation.
Support for larger datasets.
Different colors and point sizes.
Import custom datasets.

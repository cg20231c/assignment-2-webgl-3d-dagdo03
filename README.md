[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/nyKu4E7_)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12538595&assignment_repo_type=AssignmentRepo)
# Assignment 2: 3D Graphics and Interaction with WebGL

  - [Objective](#objective)
  - [Approach & Steps](#approach--steps)
    - [Initialization & Basics](#1-initialization--basics)
    - [Plane Construction](#2-plane-construction)
    - [3D Letter Construction](#3-3d-letter-construction)
    - [... (other sections as necessary)](#other-sections-as-necessary)
  - [Challenges & Learnings](#challenges--learnings)
  - [References & Resources](#references--resources)
  - [Feedback & Future Work](#feedback--future-work)
  - [Screenshots, Screencast & GIFs](#screenshots-screencast--gifs)
  - [Contribution & Collaboration](#contribution--collaboration)

## Objective
Create an interactive 3D scene with WebGL that showcases a personalized letter standing on an XZ plane, combined with lighting techniques from a designated light source.

## Approach & Steps
Document the strategy and step-by-step approach you took to achieve the objectives of the assignment:
1. First i need to know how to create the object using vertices and indices to create the plane and the letter also the illuminate cube
2. Then i need to know about translating and rotating the object
3. Last one i need to understand about pointing light

### 1. Initialization & Basics
- First i need to setup the vertexshader source and fragment shader source
- Then i need to link and compile the program that i have setup

### 2. Plane Construction
- To create XZ plane i need to know where vertices will i use and the coordinates of the point
- I need to understand about indices first and then i can create the xz plane using vertices and indices

### 3. 3D Letter Construction
- To create 3d letter i need to know where vertices will i use and the coordinates of the point
- I need to understand about indices and normal first so i can create a good 3d letter

### 4. Moving the Letter
- Use the eventkey function, coordinates point, and use rotate, jump and translatation function so i can move the letter and rotate it

### 5. Rotate the Camera
- First i need to setup all variables that i need to rotate the scene
- Use radius, elevation, and azimuth to rotate the scene
- Use eventkey function to use mousedrag and create some algorithm to rotate the camera

### 6. Create Illuminate Cube
- First i need to create variable so i can update the colors of the cube
- Create algorithm that can combine the variable so i can update the value of the colors of the cube and the light

## Challenges & Learnings
I face some challenges but i learn on it. i have error when i create the plane when i create it use y = 0 but i know the problem because my camera position. And the hardest challenges that i face is to rotate the scene.

## References & Resources
List all the external resources, references, tutorials, or documentation you've consulted during the assignment:
- [WebGL Fundamentals](https://webglfundamentals.org/)
- [StackOverflow Post on Matrix Transformations](https://stackoverflow.com/questions/example)
- ChatGPT

## Feedback & Future Work
The task is hard but i think the task is good for the students because i learn a lot about webgl and it makes me understand webgl well. And the deadline is good too, it's not too short for us which have a lot of tasks and final projects

## Screenshots, Screencast & GIFs
![Alt text](img/assignment2.gif)

## Contribution & Collaboration
Rafi SUtrisno, Apta rasendra, and Dafarel Fatih help me a lot in this task because sometimes when i got and error like why my plane or letter doesnt appear they told me about the concept why i got that and their helps mean a lot for me. So finally i can continue and finished my task.


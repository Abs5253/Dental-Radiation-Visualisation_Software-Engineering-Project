# Dental Radiation Visualisation - Software Engineering Project

This repository contains a public (showcase) version of a Software Engineering group project created in collaboration with a Dental Radiologist from King’s Dental School. The project involves developing an interactive 3D visualisation tool that maps radiation exposure data onto a model of human teeth, with the goal of aiding early cancer detection and diagnostic awareness.

## 🛠️ Tech Stack
 - Unity (Game Engine for 3D Graphics)
 - C# (Backend Logic)
 - Unity Test Tools (Testing)
 - Git & GitHub (Version Control)
 - Trello (Kanban Board)
 - Slack (Team Communication)
 - Blender (CAD - 3D model)


## 🧠 Overview
This project aimed to create an interactive 3D tool for visualising and understanding radiation exposure across different areas of the mouth during dental imaging procedures. By mapping this radiation data onto a model of human teeth, the software can help specialists better understand exposure patterns and potentially identify areas at greater risk for early-stage cancers. Furthermore, by using this software to identify specific patterns and localise radiation, the goal would be to perform early tooth extraction as to limit damage done to patients' mouth and prevent further spread.

The client was a Dental Radiologist, and the project was supervised in collaboration with Dr Sassoon, Dr. V.P., King’s Dental School. The work was completed over a 3-month period by a team of 8 collaborators.


## ✨ Features
 - Interactive 3D model of the human jaw and teeth, which the user can navigate freely (rotate, pan, zoom)
 - Ability to open & close the jaw, and a navigation cube; ability to import new data for visualisation
 - Colour-mapped numeric radiation exposure data mapped & visualised directly on the model
 - Configurable parameters and toggles for exploring & filtering various datasets and variables
 - Ability to aggregate multiple datasets onto one teeth model, and to compare datasets with box plot
 - Tutorial providing help navigating the application
 - Clean and intuitive GUI built in Unity, with fast processing speed
 - Modular codebase to allow future extensions or additional features


## 👨‍💻 My Contribution
 - Led backend programming in C#, implementing core logic and ensuring modular architecture
 - Collaborated closely with the data ingestion lead (Mike) to understand data constraints and ensure accurate structuring, as per the Dental Radiologists diagnostic objectives
 - Designed and implemented data-sorting algorithms to transform raw radiation exposure values into structured formats usable for visualisation
 - Liased between the backend data import pipeline (Mike) and front-end mapping & presentation of data (Kim), ensuring contuinity and technical alignment
 - Refactored, and Reviewed & understood teammates' code, offering constructive improvements to refactor adhering to SOLID principles
 - Coordinated team efforts: regarding the Git repository, Trello Kanban board, and Slack
 - Organised and facilitated weekly meetings, both in-person and online; summarised progress in stand-ups
 - Delivered professional presentations to our academic supervisor as a team, updating on progress and integrating feedback



## 🔒 Public Repository Disclaimer
This was a collaborative team project. For privacy and academic integrity reasons, identifying details have been limited or anonymised. This repository is intended to showcase the final implementation and highlight my personal contributions. This project is shared for educational and showcase purposes only. Not for commercial use.

**Team Members**: Abs (me), Akash, Haroon, Kim, Logi Luca, Mike, Mohd.
In collaboration with Dr Sassoon & Dr. V.P., King's Dental School
Link to corresponding research paper available upon request


# Build and Run:
<pre>
1. Download and install the Unity Editor from: https://unity3d.com/get-unity/download
2. Open the 'Teeth Visualizer' directory with the editor as a new project.
3. Go to File > Build Settings > Choose 'PC, Mac & Linux Standalone', make sure you have selected your architecture (x32 or x64)
4. Make sure no development flags are set; ensure the Scenes Scenes/SampleScene and Scenes/GraphScene have been selected
6. Click build.
7. Select the folder in which you want all the files to be generated in
8. After everything has been generated, add your data csv (sample provided 'data.csv') to the same directory in which the executable lives
9. Run the executable and enjoy!
</pre>

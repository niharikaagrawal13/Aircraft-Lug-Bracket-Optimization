# Aerospace Lug Bracket Design & Optimization

## Project Overview
This project involved the design, finite element analysis (FEA), and generative design optimization of a lightweight aircraft lug bracket using Autodesk Fusion 360.

## Objectives
- Design an initial bracket based on fundamental principles.
- Perform FEA to identify failure points under a 1000 N load.
- Use generative design to create optimal, lightweight structures that meet a safety factor of 2.0.

## Repository Structure
This repository contains the following files:
- `Lug Bracket v4.f3d`: The main Autodesk Fusion 360 source file.
- `Report (Lug Bracket).docx`: The full project report.
- `/Images`: A folder containing all screenshots and diagrams used in the report.

## Process and Results

### 1. Initial Design
The initial design was a simple T-shaped lug bracket.

![Initial Design](Images/image1.png)

### 2. Static Stress Analysis
Simulation revealed a low safety factor of 0.484, indicating failure under load. High stress was concentrated near the base hole due to a prying effect.

![FEA Analysis](Images/image2.png)

### 3. Generative Design
Generative design was used to create optimal shapes that avoid the obstacle geometry (bolt holes).

### 4. Final Outcome
The optimal design was selected for its high safety factor (2.093) and low mass (0.031 kg).

![Final Design](Images/image6.png)

## Skills Demonstrated
- **CAD:** Autodesk Fusion 360
- **Simulation:** Finite Element Analysis (FEA), Static Stress
- **Advanced Design:** Generative Design, Topology Optimization

## View Project Report
For a detailed overview, please download and view the full project report: [`Report (Lug Bracket).docx`](Report%20(Lug%20Bracket).docx)

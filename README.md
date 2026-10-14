# 12V 4A Buck Converter Hardware Design

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![KiCad](https://img.shields.io/badge/KiCad-FFFFFF?style=flat-square&logo=kicad&logoColor=blue)](https://www.kicad.org/)

A custom-designed printed circuit board (PCB) for a 12V, 4A step-down (buck) power converter, featuring full schematic capture, layout, and manufacturing-ready fabrication files.

##  Table of Contents
- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)

##  About the Project

This project contains the complete hardware design files for a DC-DC buck converter capable of delivering 4 amps at 12 volts. It serves as a robust power supply module for embedded systems and custom electronics requiring efficient voltage step-down regulation. 

### Tech Stack
*   **EDA Software:** KiCad (for schematic capture and PCB layout)
*   **Hardware Type:** Power Electronics / DC-DC Converter

##  Getting Started

Follow these instructions to view or modify the hardware design files locally.

### Prerequisites

*   [KiCad EDA](https://www.kicad.org/download/) (Version 7.0 or higher recommended) to open the project files.
*   A PDF viewer to read the exported schematics.
*   A Gerber viewer (if you only want to inspect the manufacturing layers).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MohamedHassanExp/12V-4A-buck-converter.git
2. Navigate to the project directory
   ```bash
   cd 12V-4A-buck-converter-main
3. Open `12V 4A buck converter.kicad_pro` project file using KiCad.

## Repository Structure

The repository is organized to separate the editable design files from the static manufacturing outputs:

*   **Design Files:**
     The root directory contains the core KiCad project files, including the schematic (12V 4A buck converter.kicad_sch), and the physical layout (12V 4A buck converter.kicad_pcb), and a PDF export of the design (12V 4A buck converter.pdf).
*    **Board Renders:**
      High-resolution 3D renders of the physical layout are available as 12V 4A buck converter-front.png and 12V 4A buck converter-back.png.  
*    **Manufacturing Files (/Manufacturing/):** 
      This directory contains everything a fabrication house like JLCPCB or PCBWay needs to manufacture and assemble the board:
      * **12V 4A buck converter-gerber.rar:** The compressed Gerber layers and drill files for PCB fabrication.
      * **12V 4A buck converter-BOM.csv:** The complete Bill of Materials for component sourcing and assembly.
      * **12V 4A buck converter-position.csv:** The centroid/pick-and-place data for automated SMD assembly.

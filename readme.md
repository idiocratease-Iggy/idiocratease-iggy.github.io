CRYSS (Crystallization Screening System)
CRYSS is an open‑source software suite for analysing equilibrium behaviour, designing crystallization screens, and converting multi‑solvent datasets into mechanistic purification models. It provides a complete workflow from synthetic data generation to experimental design to final insight extraction.

CRYSS is built for formulation scientists, purification chemists, and automated laboratory platforms.

🚀 Project Overview
This repository hosts the web interface for the CRYSS ecosystem. It contains three major modules:

🧪 NODES – Synthetic Data Generator
Generates realistic multi‑component equilibrium datasets for solvents, salt‑formers, and compositions. Used for prototyping, training, and validating CRYSS workflows.

📊 CRYSS DOE – Design of Experiments Module
Builds structured crystallization screens across solvents, salt‑formers, volumes, and component ratios. Exports well‑addressed templates for automated hardware.

🔥 CRYSS – Mechanistic Modelling and Heat Maps
The core analytical engine. Fits mechanistic purification models to real or synthetic data and extracts:

Maximum achievable recovery (Rmax)

Purification limits

Solubility behaviour across solvent/salt‑former space

Deviation from ideality

Viable vs non‑viable systems

CRYSS collapses these results into heat maps that make screening interpretable at a glance.

📂 Repository Structure
The site is deployed as a multi‑page GitHub Pages application.

├── index.html          # CRYSS Home / Landing Page
├── nodes.html          # NODES | Synthetic Data Generator
├── doe.html            # CRYSS DOE | Experimental Design
├── cryss.html          # CRYSS | Mechanistic Modelling & Heat Maps
└── README.md           # Project Documentation (this file)

🧠 Module Details
🧪 NODES – Synthetic Data Simulator
A controlled environment for generating equilibrium datasets.

Features:

Multi‑component system definition

Solvent and salt‑former variation

PCA‑based eutectic distortion modelling

Analytical noise injection

📊 CRYSS DOE – Experimental Design Workflow
A guided interface for building crystallization screens.

Features:

Solvent and salt‑former selection

Component definition and mixture logic

Replicate and plate‑format handling

Live preview of experiment matrices

Exportable templates (CSV or XLSX)

🔥 CRYSS – Mechanistic Modelling and Heat Maps
The flagship module.

Features:

Mechanistic model fitting

Rmax extraction

Purification limit analysis

Heat‑map generation for rapid interpretation

Support for both synthetic and experimental datasets

🔌 Hardware Integration (Future Module)
Designed for compatibility with high‑throughput crystallization hardware:

Multi‑position stirrer blocks

Automated thermal profiles

Real‑time telemetry

Well‑by‑well execution tracking

🌐 Deployment
This site is optimised for GitHub Pages.

Steps:

Clone the repository

Ensure all .html files remain in the root directory

Push to the main branch

Enable GitHub Pages and set the source to the root folder

📜 License
CRYSS is released under the MIT License. It is free for academic, industrial, and commercial use.

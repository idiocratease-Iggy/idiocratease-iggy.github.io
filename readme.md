CRYSS (Crystallization Screening System)
Mechanistic modelling for high‑throughput crystallization screening

CRYSS is an open‑source software suite for analysing equilibrium partitioning behaviour, designing crystallization screens, and converting large multi‑solvent datasets into mechanistic purification models. It provides a complete workflow from synthetic data generation to experimental design to final insight extraction.

CRYSS is built for formulation scientists, purification chemists, and automated laboratory platforms.

🚀 Project Overview
This repository hosts the web interface for the CRYSS ecosystem — a modular set of tools that work together:

🔹 NODES — Synthetic Equilibrium Data Generator
Generates realistic multi‑component equilibrium profiles for solvents, salt‑formers, and compositions.
Used for prototyping, training, and validating CRYSS workflows.

🔹 CRYSS DOE — Design of Experiments Module
Builds structured crystallization screens across solvents, salt‑formers, volumes, and component ratios.
Exports well‑addressed templates for automated hardware.

🔹 CRYSS — Mechanistic Modelling & Heat‑Map Engine
The core analytical engine.
Fits mechanistic purification models to real or synthetic data, extracts Rmax and purification limits, and collapses large datasets into intuitive heat maps that reveal which systems are genuinely viable.

Together, these modules form a complete crystallization screening pipeline:

NODES → CRYSS DOE → CRYSS (modelling + heat maps)

📂 Repository Structure
The site is deployed as a multi‑page GitHub Pages application:

text
├── index.html          # CRYSS Home / Landing Page
├── nodes.html          # NODES | Synthetic Data Generator
├── doe.html            # CRYSS DOE | Experimental Design
├── cryss.html          # CRYSS | Mechanistic Modelling & Heat Maps
└── README.md           # Project Documentation (this file)
🧠 Core Concepts
🧪 NODES — Synthetic Data Simulator
A controlled environment for generating equilibrium datasets:

Multi‑component system definition

Solvent & salt‑former variation

PCA‑based eutectic distortion modelling

Analytical noise injection for realism

Useful for:

Testing CRYSS workflows

Training ML models

Benchmarking purification strategies

📊 CRYSS DOE — Experimental Design Workflow
A guided interface for building crystallization screens:

Solvent and salt‑former selection

Component definition and mixture logic

Replicate and plate‑format handling

Live preview of experiment matrices

Exportable templates (CSV / XLSX) with well addresses

Designed for:

High‑throughput crystallization

Automated reactor blocks

Parallel screening campaigns

🔥 CRYSS — Mechanistic Modelling & Heat Maps
The flagship module.

CRYSS fits mechanistic purification models to large equilibrium datasets — whether from NODES or real experiments — and extracts:

Rmax (maximum achievable recovery)

Purification limits

Solubility behaviour across solvent/salt‑former space

Deviation from ideality

Viable vs non‑viable systems

CRYSS then collapses all of this into heat maps that make screening interpretable at a glance.

This is the insight layer that turns raw experimental chaos into actionable decisions.

🔌 Hardware Integration (Future Module)
Designed for compatibility with high‑throughput crystallization hardware:

Multi‑position stirrer blocks (2mag, h+p, etc.)

Automated thermal profiles

Real‑time telemetry

Well‑by‑well tracking and execution

This module will allow CRYSS DOE templates to be executed directly on laboratory automation.

🌐 Deployment
The site is optimised for GitHub Pages:

Clone this repository

Ensure all .html files remain in the root directory

Push to main

Enable GitHub Pages → “Deploy from root”

No build step required.

📜 License
CRYSS is released under the MIT License — free for academic, industrial, and commercial use.

Built for precision. Engineered for separation.

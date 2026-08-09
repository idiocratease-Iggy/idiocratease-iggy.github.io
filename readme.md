# CRYSS (Crystallization Screening System)

CRYSS is an open-source software suite designed for high-throughput crystallization screening, optimization, and hardware integration. It bridges the gap between algorithmic experimental design and physical laboratory execution.

## 🚀 Project Overview

This repository contains the web-based interface for the CRYSS platform, structured as a modular suite of tools for formulation and purification chemists.

- **CRYSS Home**: Project landing page and value proposition.
- **Nodes Simulator**: Synthetic data generation and analytical error modeling.
- **DoE Workflow**: Design of Experiments planning for crystallization screens.
- **Hardware Integration**: Real-time control and telemetry for parallel reactor blocks.

## 📂 Repository Structure

The project is structured as a multi-page web application designed for deployment via GitHub Pages.

```text
├── index.html          # CRYSS Home / Landing Page
├── nodes.html          # Nodes | Data Simulator
├── doe.html            # CRYSS | DoE Workflow
├── hardware.html       # CRYSS | Hardware Integration
└── README.md           # Project Documentation (this file)
```

## 🛠 Features

### 🧪 Nodes: Data Simulator
A sophisticated sandbox for generating controlled, synthetic datasets. 
- Multicomponent system definition.
- Eutectic distortion modeling via PCA (Principal Component Analysis).
- Analytical error injection (Gaussian noise).

### 📊 DoE Workflow
Guided experimental planning with rational variable selection.
- Solvent candidate and salt former screening.
- Live array preview and matrix generation.
- Exportable experimental templates (CSV).

### 🔌 Hardware Integration
Direct interface with high-throughput laboratory hardware.
- Native support for multi-position stirrer blocks (e.g., 2mag, h+p).
- Automated thermal profiling and stirring control.
- Real-time telemetry and well-by-well tracking.

## 🌐 Deployment

This site is optimized for **GitHub Pages**. To deploy your own version:

1. Clone this repository.
2. Ensure all `.html` files are in the root directory.
3. Push to your `main` branch.
4. Enable GitHub Pages in the repository settings pointing to the root folder.

## 📜 License

CRYSS is released under the **MIT License**. It is free to use, modify, and integrate for academic, R&D, and commercial purposes.

---
*Built for precision. Engineered for separation.*

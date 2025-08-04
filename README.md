# EarMag

This repository contains the code and resources for the study **"EarMag: In-Ear Magnetosensing for Jaw and Head Gesture-Based Human-Computer Interaction"**, which was accepted for EARCOMP2025.

## Project Overview

This study explores the use of in-ear magnetosensing (EarMag) as a novel sensing technique for detecting jaw and head movements in the context of human-computer interaction. While prior work has explored the use of acoustic, inertial, and visual sensing, the potential of EarMag remains to be explored. As a proof of concept, 17 orofacial physiotherapy-related exercises were collected from 21 participants using EarMag-enabled earables. A soft voting ensemble of support vector machine and random forest achieved 76\% accuracy for five exercises on an unseen test set of ten users. While individual anatomical differences pose challenges for generalization, this work highlights the potential of EarMag for applications such as assistive technologies, silent speech interfaces, and biosignal tracking.

## Repository Structure

```
earmag-ubicomp2025/
│
├── data/ # Raw sensor data with annotations of the 17 exercises
├── src/ # Source code for filtering, feature extraction, classification, generating results
│ ├── preprocessing.py
│ ├── feature_extraction.py
│ ├── classifier.py
│ └── visualization.py
├── results/ # Plots, confusion matrices, performance metrics
├── figures/ # Paper-ready figures
├── requirements.txt
└── README.md
```

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/jawsaver/earmag-ubicomp2025.git
cd earmag-ubicomp2025
```
### 2. Set Up a Virtual Envrionment
```bash
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
```
### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

## Example Usage

### Preprocess Data
Work in progress...

### Extract Features
Work in progress...

### Train a Classifier
Work in progress...

### Visualize a Signal
Work in progress...

## How to Cite This Work
If you use this work in your research, please cite the following:
```bibtex
@inproceedings{yourkey2025,
  author       = {Max Jacob Frederik van Oort, Gabriel Enrique S\'{a}enz, Selina Tirtajana and Przemysław Pawełczak},
  title        = {EarMag: In-Ear Magnetosensing for Jaw and Head Gesture-Based Human-Computer Interaction},
  booktitle    = {Companion of the 2025 ACM International Joint Conference on Pervasive and Ubiquitous Computing (UbiComp Companion '25)},
  year         = {2025},
  publisher    = {ACM},
  address      = {Espoo, Finland},
  doi          = {10.1145/3714394.3757254},
  isbn         = {979-8-4007-1477-1/2025/10},
  note         = {This work is licensed under a Creative Commons Attribution 4.0 International License.}
}

```

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

© 2025 Copyright is held by the author(s).

Published in the Companion of the 2025 ACM International Joint Conference on Pervasive and Ubiquitous Computing (UbiComp Companion '25), October 12–16, 2025, Espoo, Finland.

ACM ISBN: 979-8-4007-1477-1/2025/10  
DOI: [10.1145/3714394.3757254](https://doi.org/10.1145/3714394.3757254)

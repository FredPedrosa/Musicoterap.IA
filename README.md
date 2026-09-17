# Musicoterap.IA: Audio Feature Counterpoints in Music Therapy Assessment

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Conference: ICCCM 2026](https://img.shields.io/badge/Conference-ICCCM%202026-blue)](https://www.uni-wuerzburg.de/en/zpd/events/icccm-2026/)
[![R](https://img.shields.io/badge/R-v4.5.0-blue.svg)](https://www.r-project.org/)
[![Python](https://img.shields.io/badge/Python-3.9%2B-brightgreen.svg)](https://www.python.org/)

Official computational repository and replication assets for the proof-of-concept study:  
**"MUSICOTERAP.IA: Audio Feature Counterpoints and the Ontological Limits of Machine Understanding in Music Therapy Assessment"**, presented at the *4th International Conference on Computational and Cognitive Musicology (ICCCM 2026)*, University of Würzburg, Germany.

---

## 📌 Overview

This study interrogates the empirical and cognitive boundaries of strictly audio-based machine learning architectures in predicting clinical interaction in neurodevelopmental music therapy.

By leveraging **240 clinically microanalyzed 30-second excerpts (120 minutes)** across two neurodivergent clinical frameworks, we evaluate the counterpoints between:
1. **Self-Supervised Deep Learning Representations:** Using the Music Ensemble Representation Transformer (**MERT**).
2. **Hand-Crafted Acoustic Signal Descriptors:** Physical and motoric features extracted via **Librosa**.

---

## 🔬 Core Empirical Findings

* **Framework-Dependency:** Deep representation learning (MERT) excels at tracking aesthetic-dialogic interaction in improvisational Music-Centered Music Therapy (**R² = 0.827**, ctree MAE = 0.325). Conversely, hand-crafted physical descriptors outperform deep embeddings in task-based Neurologic Music Therapy (**R² = 0.677**, RF MAE = 0.974).
* **The Generalization Collapse:** Cross-patient and cross-framework predictive validation suffers an algorithmic collapse under hybrid Early Feature Fusion (**R² = 0.029**, MAE > 2.0).
* **The Audio-Only Boundary:** The General Factor of Interaction does not emit an isomorphic acoustic signature. In neurodevelopmental contexts, crucial relational markers occur in silence (eye contact, joint attention, preparatory physical gestures). Clinical MIR must transition toward **Multimodal Architectures (Audio + Computer Vision/Pose Estimation)**.

---

## 📁 Repository Structure

```text
├── Conceito.Rmd           # Full R Markdown script (Psychometrics, Factor Modeling, Tournament)
├── Conceito.pdf           # Compiled technical report and statistical analysis
├── reference_list.pdf     # Comprehensive clinical and computational reference list
├── LICENSE                # MIT License
└── README.md              # Project documentation and replication guide

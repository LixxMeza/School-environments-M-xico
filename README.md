# School Environments Mexico Dataset (FCAeI - UAEM)

Authors: Lizeth Meza, Jose Alberto Hernandez
> **Note:** This repository contains the official dataset and source code derived from the Master's Thesis: *"Counting of Students in Educational Enviroments Using Pretrained Convolutional CNN"*.

## 📄 Abstract

This project presents a specialized dataset focused on educational environments in Mexico, specifically collected at the **Facultad de Contaduría, Administración e Informática (FCAeI)** of the **Universidad Autónoma del Estado de Morelos (UAEM)**. This repository contains a collection of images extracted from short video clips. These videos were captured from various angles within educational environments specifically, classroom, computer lab, and an auditorium

The main objective of this research is to analyze school environments to improve [mention the goal, e.g., security, student counting, resource optimization] using [mention technique, e.g., Computer Vision, Data Analysis]. This repository serves as a resource for researchers interested in analyzing educational dynamics in Latin American contexts.

## 🏫 Context & Data Acquisition

The data was collected in real-world scenarios within the university campus.

* **Location:** Cuernavaca, Morelos, Mexico.
* **Institution:** UAEM - FCAeI.
* **Environment:** Classroom, Computer Lab, Auditorium.
* **Data Type:** [Images].
* **Collection Period:** [August 2024 - December 2024].

### Dataset Structure
The repository is organized as follows:

```text
├── data/
│   ├── raw/            # Original raw data
│   ├── processed/      # Cleaned and normalized data
│   └── annotations/    # Labels (YOLO/COCO/JSON format)
├── notebooks/          # Jupyter notebooks for EDA and experiments
├── src/                # Source code for training/inference
├── results/            # Graphs and metrics generated
└── README.md

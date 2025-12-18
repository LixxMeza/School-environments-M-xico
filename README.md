# School Environments Mexico Dataset (FCAeI - UAEM)

Authors: Lizeth Meza, Jose Alberto Hernandez
> **Note:** This repository contains the official dataset derived from the Master's Thesis: *"Counting of Students in Educational Enviroments Using Pretrained Convolutional CNNs"*.

## 📄 Abstract

This project presents a specialized dataset focused on educational environments in Mexico, specifically collected at the **Facultad de Contaduría, Administración e Informática (FCAeI)** of the **Universidad Autónoma del Estado de Morelos (UAEM)**. This repository contains a collection of images extracted from short video clips. These videos were captured from various angles within educational environments specifically, classroom, computer lab, and an auditorium

The primary objective of this dataset was to train YOLOv8 nano and large models for 10, 30, 50, and 100 epochs, respectively. Furthermore, it aims to contribute to the scientific community conducting research on educational environments across various contexts, such as students in Latin America.
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
├── test/                             # Pre-processed dataset ready for evaluation
│   ├── images/                       # Normalized test images
│   ├── labels/                       # YOLO formatted annotations
│   ├── data.yaml                     # Dataset configuration file
│   └── README.roboflow.txt           # Export details from Roboflow
├── Imagenes sin preprocesamiento/    # Raw, original images collected on-site
│   ├── Laboratorio/                  # Images captured in computer laboratories
│   └── Salon/                        # Images captured in standard classrooms
├── .gitignore
├── LICENSE                           # GNU GPLv3 License
└── README.md

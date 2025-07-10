# AI_Drug_Discovery
# 🧠 Toxicity Prediction for Drug Compounds using Deep Learning

This repository presents a deep learning-based approach to predict the toxicity of chemical compounds — a crucial step in the early stages of drug discovery and development.

Developed as part of a research-oriented internship task, this project simulates a real-world AI application in the pharmaceutical domain using a binary classification model.

---

## 📌 Project Objective

To build a deep learning model that classifies drug-like compounds as **Toxic** or **Non-Toxic** based on molecular-level feature inputs. The project simulates a standard research pipeline and lays the groundwork for future integration with real-world datasets such as Tox21 or ChEMBL.

---

## 🧬 Model Architecture

- Input Layer (10 molecular features)
- Dense Layer (64 neurons, ReLU activation)
- Dropout Layer (30%)
- Dense Layer (32 neurons, ReLU activation)
- Dropout Layer (20%)
- Output Layer (1 neuron, Sigmoid activation)

Model compiled using:
- `loss = binary_crossentropy`
- `optimizer = Adam`
- `metric = Accuracy`

---

## 📊 Dataset

- This version uses a **simulated dataset** to mimic molecular descriptors for rapid prototyping and pipeline demonstration.
- Future versions will incorporate datasets like **Tox21**, **ChEMBL**, or **PubChem BioAssay** using RDKit and DeepChem.

---

## 📈 Results

| Metric          | Score     |
|------------------|-----------|
| Accuracy (Test)  | ~85–88%   |
| Evaluation       | `accuracy_score`, `confusion_matrix` |

---

## 📄 Project Deliverables

- ✅ `Drug Test Project.ipynb` – Jupyter Notebook with full pipeline
- ✅ `Toxicity_DL_Paper_Mihir.docx` – Research paper draft with methodology
- ✅ `AI_Drug_Discovery_Research_Summary.xlsx` – Literature review of 10 related papers
- ✅ `Architecture_Diagram.png` – Model flow visualization
- ✅ (Optional) `Demo_Video.mp4` – Visual walkthrough of the notebook and explanation

---

## 🧠 Key Learnings & Novelty

- Designed a multi-layer deep learning architecture with dropout-based regularization
- Developed a modular prediction function for new compound inputs
- Proposed future integration with real SMILES-encoded chemical structures

---

## 🧭 Future Scope

- Integrate real-world molecular datasets using DeepChem
- Apply graph neural networks (GCNs) for chemical property extraction
- Build a dashboard to visualize toxicity trends across compounds
- Publish findings as a formal student research paper or IEEE poster

---

## 🧑‍💻 Author

**Mihir Kumar Panigrahi**  
Aspirant AI Research Scientist | Data Science Enthusiast | Problem Solver  
[LinkedIn](https://www.linkedin.com/in/your-profile) • [GitHub](https://github.com/Mihir-techie)

---

## 📬 Contact

Feel free to reach out for collaboration or discussion related to:
- AI for Healthcare
- Drug Discovery & Toxicity Modelling
- Student Research Opportunities

> _“Research is formalized curiosity. It is poking and prying with a purpose.” – Zora Neale Hurston_

---

# 👋 Welcome to my GitHub profile

**Kevin Lebayle**  
ML/AI Engineer & Data Scientist  
*M.Sc.-equivalent diploma · OpenClassrooms 2026*

---

I spent **10 years in Testing, Inspection & Certification**: industrial and consumer goods laboratories, product standards, team leadership.

There, I was the client on data projects: I specified a LIMS, oversaw its rollout, and waited for results from systems other people were building.  <br>**So I changed careers to build them myself.**

What holds my attention now: the moment a model stops being a notebook and becomes a service you can **serve, measure and fix**.

*A model that answers is not a model that's right*, that's the differentiating point between my first projects and my latest ones.

**What I'm looking for:** an ML/AI Engineer role.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kevin-lebayle-87343050)

---

## What I can do, and where to check it


| Area                       | Project                          | What it demonstrates                                                                                                                                  |                                                                                                                                                                                                                                                                                                                 |
| :------------------------- | :------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| 🧠 **LLM & RAG**           | **NBA Analyst AI**               | Build and Evaluation of an orchestrated RAG system — **faithfulness ×2.5, context precision ×4.3**, measured on 60 domain questions                                           |                                                                                   [Repo](https://github.com/KL38/OC_P10_RAG_NBA-comments-and-stats) · [Eval report](https://kl38.github.io/OC_P10_RAG_NBA-comments-and-stats/)                                                                                  |
| 👁️ **Deep Learning & CV** | **Brain Tumor Detection**        | Semi-supervised deep learning — **1,406 MRI scans pseudo-labelled by clustering**, a CNN that beats fully supervised training on 100 annotated images |                                                                                                                        [Repo](https://github.com/KL38/OC_P7_DL_SSL_Brain-Tumor-Detection)                                                                                                                       |
| ⚙️ **ML & MLOps**          | **Credit Scoring API**           | Full production deployment — **FastAPI, ONNX Runtime, GitHub Actions CI/CD**, dedicated monitoring space                                              |                                                             [Repo](https://github.com/KL38/OC_P8_MLOPS_Credit-scoring-API) · [API](https://huggingface.co/spaces/KLEB38/OC_P8) · [Monitoring](https://huggingface.co/spaces/KLEB38/OC_P8_monitoring)                                                            |
| ⚙️ **ML & MLOps**          | **Seattle Building Consumption** | **Conformal prediction (MAPIE), CatBoost, SHAP** — 81% observed coverage against a 75% target                                                         | [Repo](https://github.com/KL38/OC_P13_ML_MLOPS_Building_Energy_model) · [Demo](https://huggingface.co/spaces/KLEB38/OC_P13_seattle_energy_emission_predictions) · [Report](https://github.com/KL38/OC_P13_ML_MLOPS_Building_Energy_model/blob/main/rapport/Rapport%20Seattle%20Energy%20Emission%20project.pdf) |
| ⚙️ **ML & MLOps**          | **HR Attrition Model**           | **Gradient Boosting, FastAPI, PostgreSQL, SHAP** — decision threshold at 0.37, recall prioritised on attrition                                        |                                                                                    [Repo](https://github.com/KL38/OC_P5_ML_MLOPS_HR-attrition-model) · [Demo](https://huggingface.co/spaces/KLEB38/OC_P5_Frontend_FUTURISYS)                                                                                    |
| 🌱 **ML & MLOps**          | **Agritech**                     | Full chain **model → API → interface**, with a validation protocol that refuses the flattering score                                                  |                                                                                                                    [Repo](https://github.com/KL38/OC_P12_ML_MLOPS_Predict-Crops-rentability)                                                                                                                    |

---

## How I work

### I measure before I optimise
On the **NBA RAG**, I built first and diagnosed second: the failure was in retrieval, not in the model. Since then, the evaluation harness comes first.

### I audit the data before I model  
On **Seattle Building Consumption**, the models I inherited took ratios derived from the targets as inputs. I replaced those ratios with booleans to close the leak, and to make the model usable by the business.

### I prefer the true number to the flattering one  
On **Agritech**, I chose cross-validation grouped by country over a random split, which would have inflated the score by leaking the country signature.

### I ship code, not notebooks  

`src/` · `tests/` · `CI` · `Docker`
<br>My earliest projects *are* notebooks and I'm leaving them online — the progression is part of the record.

---

## Stack

### Core

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge\&logo=scikitlearn\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge\&logo=pytorch\&logoColor=white)

### Production & MLOps

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge\&logo=fastapi\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge\&logo=mlflow\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge\&logo=githubactions\&logoColor=white)

### GenAI & Data

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge\&logo=langchain\&logoColor=white)
![Pydantic AI](https://img.shields.io/badge/Pydantic_AI-E92063?style=for-the-badge\&logo=pydantic\&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-4B8BBE?style=for-the-badge)
![RAGAS](https://img.shields.io/badge/RAGAS-4B8BBE?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge\&logo=streamlit\&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge\&logo=uv\&logoColor=white)

**Currently going deeper on:** Deep Learning & Computer Vision, orchestration (Airflow, Kubernetes), cloud at scale, *world models*.

---

## Background

Three Master's-level qualifications (**EQF 7**):

| Degree | School | Year | Details |
|:-------|:-------|:-----|:--------|
| **Expert in Data Engineering & Data Science** | OpenClassrooms | 2026 | RNCP Level 7 (EQF 7) — Master's equivalent |
| **MBA : Management & Business Administration** | IAE Toulouse | 2016 | French national Master's degree (EQF 7) |
| **M.Eng. Materials Science & Engineering** | Polytech Montpellier | 2014 | CTI-accredited engineering degree, confers the Master's grade (EQF 7) · EUR-ACE labelled |

**Languages**  

Native French<br>Fluent English (4 years in Hong Kong)<br>German B1

---

## Previews

### Seattle Building Energy & Emissions
One building entered by hand, then a portfolio uploaded as CSV — estimate, 75% interval and SHAP factors, portfolio sorted by descending emissions.

![Seattle Building Energy & Emissions demo](assets/demo%20P13.gif)

<br>

### Credit Scoring API — monitoring space
Volume, p50/p95 latency broken down by stage, feature drift and decision tracking.

![Credit Scoring API monitoring dashboard](assets/monitoring.gif)

<br>

### HR Attrition model
Look up an employee by ID — verdict, probability score against the 0.37 threshold, and the top 5 SHAP factors.

![HR Attrition model demo](assets/demo%20P5.gif)

<br>

### NBA Analyst AI
A question asked in natural language, answered with sources from NBA commentary and statistics.

![NBA Analyst AI demo](assets/demo%20P10.gif)
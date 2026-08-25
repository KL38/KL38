### Welcome to my Github profile! 👋

Je suis Kevin Lebayle, ML/AI Engineer et Data Scientist (diplomé Openclassroom 2026).

J'ai passé 10 ans en Testing, Inspection & Certification — laboratoires de biens industriels et de consommation, normes produit, direction d'équipe.

J'y ai été le client de projets data : j'ai spécifié un LIMS, encadré son déploiement, et attendu des résultats de systèmes que d'autres construisaient. Je me suis reconverti pour être celui qui les construit.

Ce qui m'occupe aujourd'hui : le moment où un modèle cesse d'être un notebook et devient un service qu'on peut servir, mesurer et corriger. *Un modèle qui répond n'est pas un modèle qui a raison* : c'est la ligne qui sépare mes premiers projets des derniers.

**Ce que je cherche :** un poste de ML/AI Engineer.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kevin-lebayle-87343050)

---

### Ce que je sais faire, et où le vérifier

| Skill | Projet | Ce qu'il démontre | |
|---|---|---|---|
|LLM & RAG | **NBA Analyst AI** | Évaluation d'un système RAG — fidélité ×2.5, précision du contexte ×4.3, mesurées sur 60 questions métier | [Repo](https://github.com/KL38/OC_P10_RAG_NBA-comments-and-stats) <br>[Rapport Eval](https://kl38.github.io/OC_P10_RAG_NBA-comments-and-stats/) |
|Deep Learning & CV| **Brain Tumor Detection** | Deep Learning semi-supervisé — 1 406 IRM pseudo-labellisées par clustering, un CNN qui bat le supervisé pur avec 100 images annotées | [Repo](https://github.com/KL38/OC_P7_DL_SSL_Brain-Tumor-Detection) |
|ML & ML Ops| **Credit Scoring API** | Mise en production complète — FastAPI, ONNX Runtime, CI/CD GitHub Actions, espace de monitoring dédié |[Repo](https://github.com/KL38/OC_P8_MLOPS_Credit-scoring-API)<br>[API](https://huggingface.co/spaces/KLEB38/OC_P8)<br>[Monitoring](https://huggingface.co/spaces/KLEB38/OC_P8_monitoring) |
|ML & ML Ops| **Seattle Building consumption** | Prédiction conforme (MAPIE), CatBoost, SHAP — couverture 81 % pour une cible de 75 % | [Repo](https://github.com/KL38/OC_P13_ML_MLOPS_Building_Energy_model)<br>[Demo](https://huggingface.co/spaces/KLEB38/OC_P13_seattle_energy_emission_predictions) <br>[Rapport](https://github.com/KL38/OC_P13_ML_MLOPS_Building_Energy_model/blob/main/rapport/Rapport%20Seattle%20Energy%20Emission%20project.pdf)|
|ML & ML Ops| **HR Attrition model** | Gradient Boosting, FastAPI, PostgreSQL, SHAP — seuil de décision à 0,37, recall priorisé sur l'attrition | [Repo](https://github.com/KL38/OC_P5_ML_MLOPS_HR-attrition-model)<br>[Demo](https://huggingface.co/spaces/KLEB38/OC_P5_Frontend_FUTURISYS) |
|ML & ML Ops| **Agritech** | Chaîne complète modèle → API → interface, avec un protocole de validation qui refuse le score flatteur | [Repo](https://github.com/KL38/OC_P12_ML_MLOPS_Predict-Crops-rentability) |

---

### Comment je travaille

**Je mesure avant d'optimiser.** Sur le RAG NBA, j'ai d'abord construit, puis diagnostiqué : l'erreur venait du retrieval, pas du modèle. Depuis, le harnais d'évaluation vient en premier.

**J'audite la donnée avant de modéliser.** Sur le projet Seattle Building consumption, les modèles fournis incluaient des ratios derivés des cibles. J'ai remplacé ses ratios par des booléens pour eviter toute fuite, et rendre le modèle utilisable par le métier.

**Je préfère le chiffre vrai au chiffre flatteur.** Sur le projet Agritech, J'ai opté pour une cross validation groupée par pays, au lieu d'un découpage aléatoire qui aurait gonflé le score en laissant fuiter la signature du pays.

**Je livre du code, pas des notebooks.** `src/`, tests, CI, Docker. Mes premiers projets sont des notebooks et je les laisse en ligne — la progression fait partie du dossier.

---

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Pydantic AI](https://img.shields.io/badge/Pydantic_AI-E92063?style=flat&logo=pydantic&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-4B8BBE?style=flat)
![RAGAS](https://img.shields.io/badge/RAGAS-4B8BBE?style=flat)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat&logo=uv&logoColor=white)

En cours d'approfondissement : Deep Learning & Computer Vision, orchestration (Airflow, Kubernetes), cloud à l'échelle.

### Parcours

Diplôme Data Scientist & Machine Learning (eq. M.Sc.) — OpenClassrooms, 2026

Master MAE / MBA — IAE Toulouse · Ingénieur Matériaux — Polytech Montpellier

Français natif · Anglais courant (4 ans à Hong Kong) · Allemand B1

---

### Aperçus

**Seattle Building Energy & Emissions.** Un bâtiment saisi puis un portefeuille chargé en CSV — estimation, intervalle à 75 % et facteurs SHAP, portefeuille trié par émissions décroissantes.

![Démo de Seattle Building Energy & Emissions](assets/demo%20P13.gif)

<br>

---

**Credit Scoring API — espace de monitoring.** Volumétrie, latence p50/p95 décomposée par étape, dérive des features et suivi des décisions.

![Dashboard de monitoring du Credit Scoring API](assets/monitoring.gif)

<br>


---


**HR Attrition model.** Recherche d'un employé par ID — verdict, score de probabilité face au seuil 0,37, et les 5 facteurs SHAP.

![Démo de HR Attrition model](assets/demo%20P5.gif)


---

**NBA Analyst AI.** Question posée en langage naturel, réponse sourcée sur les commentaires et statistiques NBA.

![Démo de NBA Analyst AI](assets/demo%20P10.gif)

<br>


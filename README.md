# Hi, I'm TJ (Tirthesh Jani)

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=2E96F7&width=700&lines=Machine+Learning+Engineer+%7C+Physics+%2B+AI+Postgrad+Training;Production+ML+%2B+Scientific+Model+Interpretability;Knowing+what+is+happening+underneath)

<div align="center">

[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://tirtheshjani.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tirthesh-jani)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TirtheshJani)
[![Substack](https://img.shields.io/badge/Substack-FF6719?style=for-the-badge&logo=substack&logoColor=white)](https://tirtheshjani.substack.com)

</div>

> Machine learning engineer. Physics + AI postgrad training. I build production ML systems and audit scientific models with interpretability methods.

---

## About

I build machine learning systems and think about how models actually work, where they break, and what it takes to ship them into the world.

There is a thread through all of my work: I want to know what is happening underneath. The mechanism, not the appearance. A model that returns the right answer for the wrong reason is, in a real way, a model that does not work yet.

I am a Software Developer and Data Engineer at metricHEALTH Solutions, on a team that received the 2024 Barrie Mayor's Award for Research and Innovation. I am also a Library Associate at Barrie Public Library and I sit on a research and evaluation committee for the Ontario Public Library Association, because I believe public libraries are one of the last places in our world where access still means access.

Outside of code, I read more than is probably useful.

Open to roles in scientific AI/ML, MLOps tooling, and interpretable ML.

---

## Research

Two completed sole-author manuscripts (May 2026). Zenodo deposit; arXiv submission pending. ORCID: [0009-0005-5965-4409](https://orcid.org/0009-0005-5965-4409).

| Manuscript | Summary |
| --- | --- |
| **Interventional masked-line ablation reveals partial shortcut learning in a LightGBM MK classifier of Gaia-ESO UVES spectra** (sole author). Code: [stellar-mk-audit](https://github.com/TirtheshJani/stellar-mk-audit). | A LightGBM classifier of Morgan-Keenan spectral types F, G, K trained on 3,032 Gaia-ESO FLAMES-UVES spectra. Triangulates permutation importance, TreeSHAP, and sliding-window occlusion, then introduces interventional masked-line ablation as a falsifiable per-class audit. Macro-F1 = 0.926 on the production-continuum baseline (456-spectrum held-out test set). Paired-bootstrap confidence intervals, random-window controls, Phipson-Smyth-corrected per-pair significance at alpha = 0.0033. Surfaces two distinct shortcuts at the per-line, per-class level. |
| **Representation Wins on QA, Not on ML** (sole author). DOI: [10.5281/zenodo.20263384](https://doi.org/10.5281/zenodo.20263384). Code: [FHIRretrievaltest](https://github.com/TirtheshJani/FHIRretrievaltest). | First paired-data comparison of structured FHIR retrieval against LLM-narrative retrieval for clinical question answering. 200 synthetic patients, 13,800 questions across five specialty-medication families, three retrieval systems (Narrative, naive structured, resource-aware structured with typed filtering, reference traversal, and temporal pre-filtering) plus a no-retrieval baseline. Narrative RAG wins QA at 40.6% (versus 33.4 to 35.3% structured), but structured FHIR features dominate downstream adherence classification at LightGBM AUC 0.997 versus narrative 0.846. |

---

## Production MLOps

| Project | Description | Tech |
| --- | --- | --- |
| [**Clinical Note Summarizer**](https://github.com/TirtheshJani/MLOPS-Project) | Fine-tuned FLAN-T5 on the Microsoft MTS-Dialog clinician/patient corpus. Served from a FastAPI backend behind a React/Vite SPA, packaged in a multi-stage Docker image, deployed on GKE Autopilot via GitHub Actions CI/CD with Workload Identity Federation (no JSON keys in pipeline). Liveness/readiness probes, per-IP rate limiting, Pydantic v2 validation, graceful model fallback. | FLAN-T5, FastAPI, React, Docker, GKE |

---

## Scientific Data Engineering

| Project | Description | Tech |
| --- | --- | --- |
| [**Stellar Spectra Cross-Survey Pipeline**](https://github.com/TirtheshJani/StellarSpectraWithGONS) | Data engineering layer for a Gradient Origin Network generative-modeling project on stellar spectra. Survey-specific FITS readers (APOGEE apStar/apVisit, GALAH four-camera, Gaia-ESO UVES Phase-3), RA/Dec cross-match producing a ~30,000-star common-star catalogue from APOGEE DR17, GALAH DR3, and Gaia-ESO DR4 UVES. Log-lambda resampling at R ~ 10,000 over 3,500 to 17,000 angstrom, multiple continuum normalization methods, telluric and detector-gap masking, SNR-aware quality flags. Storage in compressed HDF5 (regridded) and PyArrow Parquet (native-resolution ragged arrays), all DVC-tracked. The GON model architecture and training code are upstream / inherited and not my work; this entry covers the data pipeline scope only. | Astropy, FITS, HDF5, PyArrow, DVC |

---

## Tech

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### ML & Scientific Computing

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2E8B57?style=flat-square&logo=lightgbm&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face_Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Astropy](https://img.shields.io/badge/Astropy-E07A5F?style=flat-square&logo=astropy&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-1F77B4?style=flat-square&logoColor=white)

### MLOps & Cloud

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes_(GKE_Autopilot)-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white)
![Workload Identity Federation](https://img.shields.io/badge/Workload_Identity_Federation-4285F4?style=flat-square&logo=google-cloud&logoColor=white)

### Data Engineering

![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![FITS](https://img.shields.io/badge/FITS-6E4B9E?style=flat-square&logoColor=white)
![HDF5](https://img.shields.io/badge/HDF5-1F4E79?style=flat-square&logoColor=white)
![Apache Parquet](https://img.shields.io/badge/PyArrow_Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white)

### Quantum

![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=flat-square&logo=qiskit&logoColor=white)
![Variational Circuits](https://img.shields.io/badge/Variational_Circuits-8A3FFC?style=flat-square&logoColor=white)
![Quantum Kernel Methods](https://img.shields.io/badge/Quantum_Kernel_Methods-A56EFF?style=flat-square&logoColor=white)

### Healthcare & Interoperability

![FHIR](https://img.shields.io/badge/FHIR_R4B-CC0033?style=flat-square&logoColor=white)
![SOC 2](https://img.shields.io/badge/SOC_2-1F2A44?style=flat-square&logoColor=white)
![OAuth](https://img.shields.io/badge/OAuth-3C8DBC?style=flat-square&logo=oauth&logoColor=white)
![fhir.resources](https://img.shields.io/badge/fhir.resources_(pydantic_R4B)-CC0033?style=flat-square&logoColor=white)
![Synthea](https://img.shields.io/badge/Synthea-2C5F2D?style=flat-square&logoColor=white)

---

## Education

- **Ontario College Graduate Certificate (postgraduate), AI Design and Implementation** (Honours, Georgian Scholar). Georgian College.
- **Ontario College Graduate Certificate (postgraduate), Big Data Analytics** (Honours, Georgian Scholar). Georgian College.
- **BSc Physics (Major), Mathematics (Minor).** University of Mumbai.
- **Google Advanced Data Analytics Professional Certificate**, 2025.
- **Google Data Analytics Professional Certificate**, 2024.

---

## Awards

- **City of Barrie Mayoral Award for Research and Innovation**, 2024 (metricHEALTH Solutions team).
- **2nd Place, Generative AI Hackathon**, Georgian College, 2024.

---

## GitHub Stats

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com/?user=TirtheshJani&theme=tokyonight)

</div>

---

## Currently Exploring

- Interpretability methods for scientific ML (feature-intervention versus structural-causal framings).
- Interpretable boosted trees and self-explaining neural networks on tabular scientific data.
- Quantum kernel methods on classification tasks where the kernel is the bottleneck.

---

## Get In Touch

I am open to conversations about scientific AI/ML, interpretable ML, MLOps tooling, computational physics, or community work.

Email: tirtheshjani@gmail.com · [LinkedIn](https://linkedin.com/in/tirthesh-jani) · [Substack](https://tirtheshjani.substack.com)

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-Connect_on_LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/tirthesh-jani)

</div>

---

<p align="center">
  <i>Ad astra per aspera.</i>
</p>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=TirtheshJani&color=blueviolet&style=flat-square" alt="Profile views">
</p>

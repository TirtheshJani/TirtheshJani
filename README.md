# Tirthesh (TJ) Jani

I build data pipelines and AI features.

I spent two years building production healthcare data software at metricHEALTH Solutions. I am now an MSc Computer Science student at Lakehead University.

[tirtheshjani.com](https://tirtheshjani.com) · [LinkedIn](https://linkedin.com/in/tirthesh-jani) · tirtheshjani@gmail.com

## What I can do for you

- **Connect systems and move data.** APIs and pipelines between the tools you already use.
- **Build AI features on documents and text.** From a first prototype to a running service.
- **Make software testable and visible.** Automated tests on every change, and dashboards people read.

## Work

**metricHEALTH Solutions** (health-tech, Barrie) · Software Developer · April 2024 to July 2026

- Built REST integrations between clinical systems and client CRMs (Microsoft Dynamics 365) under FHIR and SOC 2. Data services held 99.9% uptime.
- Automated end-to-end testing with Python and Selenium, which cut manual testing effort by 30%.
- Built dashboards that replaced a weekly spreadsheet export for operations leadership.
- Built a proof of concept that reads scanned, handwritten enrollment forms into structured FHIR records (Vertex AI, Gemini). 85% of fields cleared the confidence threshold on the first pass. It was a proof of concept, not a production system.
- The team received the City of Barrie Mayor's Award for Research and Innovation in 2024.

## Projects

| Project | What it does | Built with |
| --- | --- | --- |
| [Clinical Note Summarizer](https://github.com/TirtheshJani/MLOPS-Project) | Turns doctor and patient conversations into short clinical notes. A fine-tuned model behind an API and a web front end, with CI/CD for Google Cloud. Demo on public data. | FLAN-T5, FastAPI, React, Docker, GKE |
| [fhir-mcp](https://github.com/TirtheshJani/FHIR-MCP) | Lets an AI agent query health records. An MCP server that exposes FHIR patient, observation, medication, condition and encounter data as tools. | Python, FHIR R4B, MCP |
| [JudgeKit](https://github.com/TirtheshJani/JudgeKit) | Checks whether AI graders agree. Runs one prompt set past five LLM judges from four vendors and stops at a hard budget cap. | Python, LLM APIs |
| [UpliftBench](https://github.com/TirtheshJani/UpliftBench) | Estimates which customers an ad persuades. Five uplift models on 13.9 million rows, on one laptop, with a Streamlit demo. | Python, LightGBM, EconML, DoWhy |

## Research

I am on the thesis route of the MSc (AI specialization). My research tests whether a trained model relies on the signal it is supposed to use.

Two completed sole-author manuscripts (May 2026). Zenodo deposits; arXiv submission pending.

- **Is a star classifier looking at the right physics?** An audit of a LightGBM classifier of stellar spectra (macro-F1 0.926). Two of three classes relied on the expected spectral lines. The third had learned a shortcut. Code: [ges-uves-mk-audit](https://github.com/TirtheshJani/ges-uves-mk-audit).
- **Representation Wins on QA, Not on ML.** How should an LLM be given patient records? Plain text answered questions best; structured data trained a better prediction model. 200 synthetic patients, 13,800 questions. Code: [FHIR_RAG_TEST](https://github.com/TJmetrichealth/FHIR_RAG_TEST). DOI: [10.5281/zenodo.20263384](https://doi.org/10.5281/zenodo.20263384).

## Tools

Python, SQL, TypeScript · PostgreSQL, MySQL, BigQuery · FastAPI, Flask, REST APIs · PyTorch, scikit-learn, LightGBM · Vertex AI, RAG · Docker, Kubernetes, GitHub Actions · FHIR R4B

## Education

- MSc Computer Science (thesis route, AI specialization), Lakehead University, 2026 to 2028 (expected)
- Graduate certificates in AI Design and Implementation and in Big Data Analytics, Georgian College (Honours, Georgian Scholar)
- BSc Physics, minor in Mathematics, University of Mumbai

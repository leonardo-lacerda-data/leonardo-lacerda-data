[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leonardo-lacerda-data)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:leonardo.a.lacerda1@gmail.com)

---

## Sobre mim

```python
leonardo = {
    "foco":        ["Dados", "Machine Learning", "Automação, Infraestruturas Cloud"],
    "estudando":   "Data Science · FIAP (2025–2027)",
    "Experiência": "Já fui sócio-administrador de uma empresa de e-commerce",
    "localização": "Santa Catarina, SC 🇧🇷",
    "idiomas":     ["Português 🇧🇷", "Inglês 🇺🇸 (Avançado)"],
}
```

I came into data from a commercial and e-commerce background.
Currently focused on analytics engineering fundamentals: SQL, data modeling, AI & Cloud solutions turning raw data into decisions people actually act on.


---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-C74634?style=flat-square&logo=oracle&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## AI & Machine Learning

### 🩺 [SCMedAI — Clinical Protocol Assistant](https://github.com/leonardo-lacerda-data/sc_med_ai)

`RAG` `LangChain` `Gemini` `Terraform` `OCI` `Streamlit`

A retrieval assistant that answers questions about a hospital's own clinical protocols, always citing the source document and page. Built for the healthcare market in Santa Catarina.

- **Retrieval-Augmented Generation** — document ingestion, chunking with page-level provenance, vector indexing and metadata-filtered retrieval over a curated corpus
- **Refusal by design** — the system abstains when the answer is not supported by the retrieved passages; every response carries a mandatory source citation
- **Evaluation set built before tuning** — 28 categorised questions in which abstention and refusal are the expected correct answers, not failures, covering direct lookup, cross-document synthesis and deliberate gaps in the corpus
- **Infrastructure as Code** — Terraform stack for OCI Resource Manager provisioning VCN, subnets, compute and a load balancer with session persistence, with cloud-init handling application setup

Why this matters for a data role: Building the evaluation framework before adjusting anything required the same discipline needed for a data pipeline: first defining what is considered correct, and then measuring. And treating “I don’t know” as a valid answer is a habit that carries over directly to reporting and analysis, where an incorrect number presented with confidence costs more than an admitted gap.

---

### 🧭 [BÚSSOLA FIDC](https://github.com/leonardo-lacerda-data/nuclea_fidics)

`Python` `scikit-learn` `SQL` `Oracle` `Power BI` `NLP`

Analytical and predictive platform for **credit risk assessment and behavioral segmentation** of account holders, developed with Núclea.

- Random Forest for default risk classification
- K-Means for behavioral clustering of account holders
- Transactional data cross-referenced with macroeconomic indicators
- News sentiment analysis (NLP) as an additional risk signal

---

<p align="center"><i>Always learning, always curious.</i></p>

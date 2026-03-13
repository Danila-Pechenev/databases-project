# Relational Database Project – M1 Data Science, Centrale Lille

This repository contains a course project completed for the **Databases** course in **M1 Data Science** (first year of the Master's program) at Centrale Lille (2025-2026).

The goal of the project was to design and implement a relational database from real-world movie datasets, including:

- conceptual and logical data modeling
- data cleaning and integration
- database population using Python
- SQL query design and analysis
- database evolution with additional data sources

---

## Project overview

| Item | Details |
| --- | --- |
| Course | Databases |
| Program | M1 Data Science, Centrale Lille |
| Type | Academic project, team of 2 |
| Main tools | Python, PostgreSQL, SQLAlchemy, Pandas, SQL, LaTeX |

The final deliverables are the implementation notebook, a written report, and a presentation.

---

## Dataset

The project integrates two Kaggle datasets:

- **Oscars dataset:** [Oscars from 1928 to 2024](https://www.kaggle.com/datasets/johnpendenque/oscars-from-1928-to-2024)
- **Movies dataset:** [TMDB movies dataset 2023](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies)

The raw data files are not committed to this repository. The notebook documents the download, preprocessing, cleaning, integration, and insertion steps used to build the relational database.

---

## Repository structure

```
databases_project/
├── db_project.ipynb        # Main notebook: preprocessing, database creation, insertion, and SQL queries
├── project_guidelines.pdf  # Original project instructions
├── report.pdf              # Final project report
├── presentation.pdf        # Final presentation slides
├── .env.example            # Template for local database credentials
├── requirements.txt        # Python dependencies
└── README.md
```

Database credentials should be stored locally in `.env`, using `.env.example` as a template. The `.env` file is intentionally ignored by Git.

---

## Workflow

- Download the Oscars and TMDB movie datasets
- Clean missing, inconsistent, and irrelevant records
- Design and create the relational schema
- Populate PostgreSQL tables from processed data
- Add movie metadata to extend the initial Oscars database
- Run SQL queries to explore awards, movies, people, ratings, and budgets
- Document design decisions in the final report and presentation

---

## Technologies

- Python
- Pandas, NumPy
- PostgreSQL
- SQLAlchemy, psycopg2
- SQL
- python-dotenv
- KaggleHub
- Jupyter Notebook
- LaTeX
- Git

---

## Results

- Fully functional relational database built from heterogeneous movie datasets
- Reproducible notebook-based ingestion and population pipeline
- SQL queries covering selection, joins, aggregation, filtering, and ranking
- Documented design choices, constraints, and database evolution scenario

---

## Skills demonstrated

- Relational database modeling
- Data cleaning and integration
- SQL schema creation and querying
- Python-based database interaction
- Working with external datasets
- Reproducible data engineering workflows
- Scientific reporting and presentation with LaTeX
- Team development with Git

The focus is on engineering and data management rather than machine learning.

---

## Authors

- Danila Pechenev
- Gwenn Garrigues

M1 Data Science – Centrale Lille

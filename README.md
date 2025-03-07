# **STEM-KG: Building a Knowledge Graph for STEM Education**
🚧 *Work-in-Progress – Private Repository* 🚧

## **Project Overview**
This repository contains the scripts and resources for a master's thesis project that aims to construct a **knowledge graph (KG) for STEM education**. The project focuses on:
- **Extracting scientific concepts** from Flemish *eindtermen* (educational standards) and *leerplannen* (curricula).
- **Retrieving relevant relationships** from **Wikidata** and **DBpedia** to build a structured knowledge base.
- **Validating** the extracted concepts and relations with education professionals.
- **Constructing a master knowledge graph (KG)** that enables filtering by subject, grade level, and more.
- *(Optional, if time permits)* **Integrating the KG into a retrieval-augmented generation (RAG) system** for a STEM teacher support chatbot.

## **Team & Supervision**
This project is conducted as a collaboration between two master’s students:
- **Bert Vos** (Master of Advanced Studies in Linguistics, NLP specialization, Ghent University & KU Leuven)
- **Ecem Sila Gök** (Master of Artificial Intelligence, Engineering & Computer Science specialization, KU Leuven)

The research is carried out under the supervision of:
- **Prof. Hanne Deprez** (KU Leuven)
- **Prof. Orphée De Clercq** (UGent)
- **Dr. Tom Vermeulen** (Brainjar)

Daily supervision is provided by **Aagje Reynders (Brainjar).**  
The project is conducted in collaboration with **Brainjar, KU Leuven, and UGent**.

## **Repository Structure**
The repository is organized into the following directories:

STEM-KG/
│── data/                  # Raw and processed datasets
│   ├── eindtermen/        # Extracted STEM concepts from Flemish curricula
│   ├── wikidata_dbpedia/  # Retrieved relations from Wikidata & DBpedia
│   ├── processed/         # Cleaned & structured datasets for KG
│── notebooks/             # Jupyter notebooks for exploration and analysis
│── scripts/               # Core Python scripts
│   ├── concept_extraction/   # Scripts for extracting scientific concepts (Ecem)
│   ├── relation_extraction/  # Scripts for extracting relations (Bert)
│   ├── kg_construction/      # Scripts for building the knowledge graph (Bert)
│   ├── kg_validation/        # Scripts for validating the extracted data with experts
│   ├── rag_integration/      # (Optional) Scripts for integrating the KG into a RAG model
│── models/                # Trained models for concept and relation extraction
│── evaluation/            # Evaluation metrics, validation reports, user feedback
│── docs/                  # Documentation, reports, and references
│── README.md              # Project overview and contribution guidelines
│── requirements.txt       # Dependencies and package requirements
│── .gitignore             # Files and folders to exclude from version control
│── LICENSE                # (To be added when making the repo public)


## **How to Contribute**
Since this repository is private, only authorized contributors have access.  
For collaboration, follow these best practices:
1. **Use feature branches**: Each new feature or update should be developed in a separate branch before merging.
2. **Commit messages**: Follow a clear format (e.g., `feat: added relation extraction script` or `fix: corrected Wikidata query bug`).
3. **Documentation**: Always update README or docs when adding new scripts or methodologies.
4. **Pull requests & code review**: Changes should be reviewed by both contributors before merging to `main`.

## **Technical Requirements**
- Python 3.11+
- Required packages (install using `pip install -r requirements.txt`)

## **Future Plans**
- Completing **concept extraction** and **relation extraction** pipelines.
- Constructing and validating the **master knowledge graph**.
- *(Optional)* Experimenting with **RAG integration** for a chatbot prototype.

🚀 **This project is a work-in-progress. Stay tuned for updates!** 🚀
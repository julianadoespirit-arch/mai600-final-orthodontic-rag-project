# Local Orthodontic Front-Office RAG Assistant

## Overview
This MAI 600 final capstone project develops and evaluates an AI assistant designed to support common orthodontic front-office questions while reducing hallucination and improving source-grounded responses.

The project compares a local Llama 3.2 3B model running through Ollama with an improved Retrieval-Augmented Generation (RAG) approach using a controlled orthodontic knowledge base.

## Problem
General-purpose language models can provide plausible but unsupported information when answering clinic-specific questions. In healthcare-related administrative environments, this can create risks involving medication advice, financial information, appointment availability, insurance coverage, and patient privacy.

This project explores how retrieval, evidence-sufficiency controls, and source citations can improve the reliability of an orthodontic front-office AI assistant.

## System Type
Hybrid AI / Retrieval-Augmented Generation (RAG)

## Technologies
- Python
- Google Colab
- Llama 3.2 3B
- Ollama
- TF-IDF
- Cosine Similarity
- Pandas
- Matplotlib
- Scikit-learn

## Knowledge Base
The system uses six fictional orthodontic administrative documents covering:

- Office hours and contact information
- Appointment scheduling
- Initial consultations
- Insurance and payment information
- Patient portal support
- Clinical question escalation

No real patient information is used.

## Evaluation
The final system was evaluated using 10 controlled test cases covering:

- Retrieval accuracy
- Safe behavior
- Source support
- Missing-information handling
- Hallucination risk
- Financial uncertainty
- Clinical safety

The local Llama 3.2 3B model was also tested as a baseline without access to the project knowledge base.

## Key Improvements
Compared with the Module 7 prototype, the final project includes:

- Expanded evaluation from 6 to 10 test cases
- Domain metadata added to retrieval
- Evidence Sufficiency Guard
- Improved missing-information handling
- Expanded financial and clinical safety rules
- Local Llama 3.2 3B baseline comparison
- Additional evaluation metrics and visualizations

## Responsible AI
The assistant is designed for administrative and informational support only. It does not diagnose conditions, recommend medication, provide treatment instructions, guarantee insurance coverage, or invent missing clinic information.

## Author
Juliana do Espírito Santo

MAI 600 – Master’s in Artificial Intelligence

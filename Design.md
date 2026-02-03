# Public Voice – Design Document

## Architecture
User → Streamlit App → Backend → ML Model → Database

## Tech Stack
Frontend: Streamlit
Backend: Python
ML: scikit-learn (classification)
Speech: Whisper
Database: SQLite
Deployment: Render

## Workflow
1. User gives complaint (text/voice)
2. Speech converted to text
3. NLP model classifies issue
4. Department mapped
5. Complaint generated automatically
6. Submitted/stored

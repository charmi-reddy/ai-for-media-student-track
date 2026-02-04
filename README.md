# EduAI - AI-Powered Educational Content Generator

An ethical, accurate, and engaging educational content generation tool designed for college students and educators in India.

## Features

- **Content Summarization**: Intelligent summarization of academic materials
- **Content Structuring**: Organize information into clear, pedagogical formats
- **Hallucination Reduction**: Multi-layer verification and fact-checking
- **Indian Context**: Tailored for Indian educational system and curriculum
- **Ethical AI**: Transparent, bias-aware content generation

## Tech Stack

- **Backend**: Python with FastAPI
- **Frontend**: React with TypeScript
- **AI/ML**: OpenAI GPT-4, Hugging Face Transformers
- **Database**: PostgreSQL with Redis caching
- **Deployment**: Docker containers

## Getting Started

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Set up environment variables
4. Run the development server: `python -m uvicorn main:app --reload`

## Project Structure

```
eduai/
├── backend/           # FastAPI backend
├── frontend/          # React frontend
├── ai_models/         # AI model configurations
├── data/             # Sample data and datasets
├── tests/            # Test suites
└── docs/             # Documentation
```

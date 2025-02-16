# Medical AI Flask Application

This project is a Flask-based application for processing medical documents, images, and generating responses using various machine learning models, including `med-alpaca`, `deplot`, and OpenAI's GPT.

## Features
- X-ray image analysis
- Text-based question answering
- Integration with LLaMA (`med-alpaca`), GPT-3.5-Turbo, and other models
- Data table generation from images
- Lightweight web interface with Flask

## Setup Instructions
### Prerequisites
- Python 3.9 or later
- A CUDA-compatible GPU (optional for faster processing)
- Environment variables for `CAMBRIDGELTL_ACCESS_TOKEN`, `AUTH_USERNAME`, `AUTH_PASSWORD`, and `OPENAI_TOKEN`.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/medical-ai-flask-app.git
   cd medical-ai-flask-app

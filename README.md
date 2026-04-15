Multimodal Insurance Creator

This repository contains a basic low level design skeleton for a multimodal Gen AI project.
The project takes an insurance related text prompt and produces:
1) a grounded narrative
2) an infographic style image plan and image generation flow

Tech stack
Python
Vector database
LLM API
Image generation API

Current repository focus
Low level design documents
Basic Python package structure
Stub modules for orchestration retrieval narrative and image flow

Main files
docs/LLD.md
docs/API_SKETCH.md
app/config/settings.py
app/models/schemas.py
app/orchestration/service.py
app/rag/retrieval.py
app/generation/narrative.py
app/image/brief.py

Setup
pip install -r requirements.txt

Configuration
Environment variables use prefix INSURANCE_AI_

# Multimodal Insurance Creator (LLD skeleton)

Design-first layout for a GenAI project: **narrative + infographic** from a text prompt, using Python, a vector DB, and LLM/image APIs.

- **Design:** [`docs/LLD.md`](docs/LLD.md), [`docs/API_SKETCH.md`](docs/API_SKETCH.md)
- **Contracts & stubs:** `app/` (orchestration, RAG, generation, image, models, config)

Install (optional, to validate imports):

```bash
pip install -r requirements.txt
```

Environment variables use the prefix `INSURANCE_AI_` (see `app/config/settings.py`).

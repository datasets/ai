# Epoch Data on AI Models

Comprehensive database of AI/ML models tracking key factors driving machine learning progress. Sourced from [Epoch AI](https://epochai.org/data/notable-ai-models).

## Data

The dataset is split into four CSV files covering different subsets of models:

| File | Description | Rows |
|------|-------------|------|
| `data/all_ai_models.csv` | All AI models in the Epoch database | ~21,600 |
| `data/notable_ai_models.csv` | Notable models with richer metadata | ~7,400 |
| `data/large_scale_ai_models.csv` | Large-scale models subset | ~3,600 |
| `data/frontier_ai_models.csv` | Frontier models — most capable at each point in time | ~1,600 |

### Key fields

- **Model** — name of the model
- **Organization** — developing organization (e.g. Google, OpenAI, DeepMind)
- **Publication date** — date of release or publication (1950–2025)
- **Domain** — area of application (Language, Vision, Multimodal, Robotics, etc.)
- **Task** — specific task(s) the model performs
- **Parameters** — number of model parameters
- **Training compute (FLOP)** — total training compute in floating point operations
- **Training dataset** — name/description of training data
- **Training dataset size (datapoints)** — number of training examples
- **Training hardware** — hardware used for training
- **Training compute cost (2023 USD)** — estimated cost of training
- **Frontier model** — whether the model was state-of-the-art at release
- **Model accessibility** — open weights, closed, API-only, etc.

Full field-level documentation is in [`datapackage.json`](datapackage.json).

## License

[Creative Commons Attribution 4.0 (CC-BY-4.0)](https://creativecommons.org/licenses/by/4.0/) — Epoch AI.

## Source

Epoch AI — Notable AI Models: https://epochai.org/data/notable-ai-models

# thesis-supplementary
This repository contains the supplementary materials for the Master's thesis:
**"Towards Equitable Digital Health: Cross-Language Consistency of Large Language Models in English and Turkish"**
University of Mannheim, 2026
---
## Repository Structure
### `prompt-design/`
Contains `prompt_set_and_schema.md` with the metadata schema applied to each prompt, the cross language equivalence procedure, and the complete set of eight English and Turkish prompt pairs (P01 to P08) used in the study.
### `llm-evaluations/`
Contains the model outputs generated during the study.
- **`chatgpt/`** — ChatGPT responses for all prompts, saved as self-contained HTML files. Each file corresponds to a single prompt submission in either English or Turkish. To view a file, download it and open it in any web browser. File naming convention: `[Prompt ID] [Language] [Run Type] ChatGPT ([Date]).html`
- **`gemma4/`** — Contains `gemma4_evaluation_notebook.ipynb`, the Google Colab notebook used to generate Gemma 4 responses for all prompts under fully deterministic settings (temperature=0.0, top_p=1.0, top_k=1) via the Google AI SDK.
### `evaluation-matrix/`
Contains `Evaluation Matrix (CommonDecide).md` with detailed scoring notes for all 32 cases, covering both English and Turkish response pairs across all four evaluation dimensions.
### `interrater-reliability/`
Contains the materials used to assess interrater reliability.
- `kappa_analysis.ipynb` — Independent scores of both raters and the computed Cohen's kappa coefficients.
- `triple_blind_evaluation_table.md` — Final consensus scores alongside the randomised case sequence metadata used in the scoring protocol.

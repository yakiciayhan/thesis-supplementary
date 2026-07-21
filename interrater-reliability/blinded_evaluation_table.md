# Blinded Evaluation Table

This table presents the final consensus scores for all 32 evaluation cases, along with the randomised case sequence metadata used in the scoring protocol blinded to model identity, prompt identity, and run type.

Cases were presented to raters under a **Strategic Randomisation** protocol designed to eliminate three primary threats to subjective evaluation validity: brand-related bias, ordering effects, and contextual carry-over effects. Raters received no model labels (neither named identifiers such as ChatGPT or Gemma 4, nor neutral placeholders such as Model A or Model B), no prompt identifiers, and no run type information. Original prompt IDs (P01 to P08) were replaced with a generic serial mapping system (Case 01 to Case 32) to prevent raters from recognising repeated or paired cases. Non-sequential presentation was enforced to avoid the shift from consistency assessment to comparative preference that arises when outputs for the same prompt are evaluated consecutively.

The 32 cases comprise 16 Original runs (one per prompt per model) and 16 Sanity Run repetitions (two further runs each for a preselected subset of four prompts: P01, P04, P05, and P08). The Sanity Runs served a dual purpose. For Gemma 4, accessed via API under fully deterministic settings (temperature = 0.0, top\_p = 1.0, top\_k = 1), identical prompts produce identical outputs; the repeated cases therefore functioned as hidden control triads and constituted a strict intra-rater reliability check, requiring a consistent rater to assign identical scores across all three presentations of the same output. For ChatGPT, accessed through its standard web interface under non-transparent stochastic settings, the repetitions provided data on run-to-run output variability and its effect on cross-language consistency scores.

| Case | D1 | D2 | D3 | D4 | Total | Prompt ID | Model | Run Type | Internal Logic |
| :--- | :--: | :--: | :--: | :--: | :--: | :--- | :--- | :--- | :--- |
| 01 | 2 | 1 | 1 | 2 | 6/8 | P03 | ChatGPT | Original | ChatGPT - Original EN-TR pair |
| 02 | 2 | 1 | 1 | 1 | 5/8 | P01 | Gemma 4 | Sanity Run 1 | Gemma 4 - First repeat EN-TR pair |
| 03 | 2 | 1 | 2 | 2 | 7/8 | P05 | ChatGPT | Original | ChatGPT - Original EN-TR pair |
| 04 | 2 | 1 | 1 | 1 | 5/8 | P08 | Gemma 4 | Sanity Run 2 | Gemma 4 - Second repeat EN-TR pair |
| 05 | 2 | 1 | 2 | 2 | 7/8 | P02 | Gemma 4 | Original | Gemma 4 - Original EN-TR pair |
| 06 | 2 | 1 | 1 | 2 | 6/8 | P04 | ChatGPT | Sanity Run 1 | ChatGPT - First repeat EN-TR pair |
| 07 | 2 | 1 | 1 | 2 | 6/8 | P01 | ChatGPT | Original | ChatGPT - Original EN-TR pair |
| 08 | 2 | 1 | 1 | 2 | 6/8 | P06 | Gemma 4 | Original | Gemma 4 - Original EN-TR pair |
| 09 | 2 | 1 | 1 | 1 | 5/8 | P05 | Gemma 4 | Sanity Run 2 | Gemma 4 - Second repeat EN-TR pair |
| 10 | 2 | 1 | 1 | 1 | 5/8 | P04 | Gemma 4 | Original | Gemma 4 - Original EN-TR pair |
| 11 | 2 | 1 | 2 | 2 | 7/8 | P08 | ChatGPT | Sanity Run 1 | ChatGPT - First repeat EN-TR pair |
| 12 | 2 | 1 | 2 | 2 | 7/8 | P07 | ChatGPT | Original | ChatGPT - Original EN-TR pair |
| 13 | 2 | 1 | 1 | 1 | 5/8 | P01 | Gemma 4 | Original | Gemma 4 - Original EN-TR pair |
| 14 | 2 | 1 | 2 | 1 | 6/8 | P05 | ChatGPT | Sanity Run 1 | ChatGPT - First repeat EN-TR pair |
| 15 | 2 | 1 | 1 | 1 | 5/8 | P03 | Gemma 4 | Original | Gemma 4 - Original EN-TR pair |
| 16 | 2 | 1 | 1 | 1 | 5/8 | P04 | ChatGPT | Original | ChatGPT - Original EN-TR pair |
| 17 | 2 | 1 | 1 | 1 | 5/8 | P08 | Gemma 4 | Original | Gemma 4 - Original EN-TR pair |
| 18 | 2 | 1 | 1 | 2 | 6/8 | P01 | ChatGPT | Sanity Run 2 | ChatGPT - Second repeat EN-TR pair |
| 19 | 2 | 1 | 1 | 1 | 5/8 | P05 | Gemma 4 | Original | Gemma 4 - Original EN-TR pair |
| 20 | 2 | 1 | 1 | 2 | 6/8 | P02 | ChatGPT | Original | ChatGPT - Original EN-TR pair |
| 21 | 2 | 1 | 1 | 1 | 5/8 | P04 | Gemma 4 | Sanity Run 2 | Gemma 4 - Second repeat EN-TR pair |
| 22 | 2 | 1 | 1 | 1 | 5/8 | P08 | ChatGPT | Original | ChatGPT - Original EN-TR pair |
| 23 | 2 | 1 | 1 | 1 | 5/8 | P01 | Gemma 4 | Sanity Run 2 | Gemma 4 - Second repeat EN-TR pair |
| 24 | 2 | 2 | 2 | 2 | 8/8 | P05 | ChatGPT | Sanity Run 2 | ChatGPT - Second repeat EN-TR pair |
| 25 | 2 | 1 | 2 | 1 | 6/8 | P07 | Gemma 4 | Original | Gemma 4 - Original EN-TR pair |
| 26 | 2 | 1 | 1 | 1 | 5/8 | P04 | Gemma 4 | Sanity Run 1 | Gemma 4 - First repeat EN-TR pair |
| 27 | 2 | 1 | 1 | 2 | 6/8 | P06 | ChatGPT | Original | ChatGPT - Original EN-TR pair |
| 28 | 2 | 1 | 1 | 1 | 5/8 | P08 | Gemma 4 | Sanity Run 1 | Gemma 4 - First repeat EN-TR pair |
| 29 | 2 | 1 | 1 | 1 | 5/8 | P01 | ChatGPT | Sanity Run 1 | ChatGPT - First repeat EN-TR pair |
| 30 | 2 | 1 | 1 | 1 | 5/8 | P04 | ChatGPT | Sanity Run 2 | ChatGPT - Second repeat EN-TR pair |
| 31 | 2 | 1 | 1 | 1 | 5/8 | P08 | ChatGPT | Sanity Run 2 | ChatGPT - Second repeat EN-TR pair |
| 32 | 2 | 1 | 1 | 1 | 5/8 | P05 | Gemma 4 | Sanity Run 1 | Gemma 4 - First repeat EN-TR pair |

---

**Scoring scale:** 0 = Inconsistent, 1 = Partially Consistent, 2 = Consistent  
**Dimensions:** D1 = Core Advice Alignment, D2 = Information Coverage and Explanatory Symmetry, D3 = Risk and Safety Communication Alignment, D4 = Framing, Certainty and Clarification Behaviour  
**Scores shown are final consensus scores** agreed upon by both raters following the independent scoring phase and consensus discussion.

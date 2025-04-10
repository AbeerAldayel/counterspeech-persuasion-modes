# Counterspeech-persuasion-modes
# Hatred Stems from Ignorance: Persuasion Modes in Countering Hate Speech

**Alyahya, G. & Aldayel, A. (2025).**  
*To appear in the Proceedings of the nineteenth International AAAI Conference on Web and Social Media (ICWSM 2025)*

📄 [Read the Paper](https://arxiv.org/abs/2403.15449)  

---

## Overview

This repository contains the **persuasion-mode annotations** applied to two well-known counterspeech datasets, focusing on dialog-based hate speech responses. We provide a coarse-grain examination of the persuasion modes used in hate speech and counterspeech based on emotion, reason, and credibility.


---

## Dataset Contents

The released files include:

- `annotations/` – CSV files with persuasion-mode labels for each utterance

Note: We release persuasion **label data** associated with each turn ID. Refer to the original datasets for further information related to the conversation from **DialogConan** (Bonaldi et al., 2022) and **ContextCounter** (Albanyan, Hassan, & Blanco, 2023), as indicated in the source-of-data column.

---

## Label Definitions

Each utterance is labeled with modes of persuasion:

- **Reason**  
  This label indicates logos as a mode of persuasion. It appeals to the utilization of logic or reason (e.g., presenting related examples or supporting evidence).

- **Credibility**  
  Represents ethos as a mode of persuasion. It relies on the credibility or authority derived from the speaker’s personal experience.

- **Emotion**  
  Represents pathos as a mode of persuasion. It evokes the emotions and feelings of the audience or puts them in a certain mood, appealing to their emotions.

Extra Note

The title "Hatred Stems from Ignorance" reflects the study's core theoretical grounding of persuasion in Aristotle’s Rhetoric, particularly as interpreted in the work of Cope, E. M., and Sandys, J. E. (2010). This rhetorical foundation aligns with the insights of Ibn Rushd (Averroes), a renowned philosopher known for reintroducing and interpreting Aristotle’s texts.

The phrase draws inspiration from one of Ibn Rushd's most well-known quotes on hate and ignorance:

> “Ignorance leads to fear, fear leads to hatred, and hatred leads to violence. This is the equation.”  
> — Ibn Rushd (Averroes)  
> 🔗 [View the quote](https://www.goodreads.com/quotes/8833090-ignorance-leads-to-fear-fear-leads-to-hatred-and-hatred)
---

## Citation

If you use this dataset, please cite:

```bibtex
@inproceedings{alyahya2025persuasion,
  title = {Hatred Stems from Ignorance! Distillation of the Persuasion Modes in Countering Conversational Hate Speech},
  author = {Alyahya, Ghadeer and Aldayel, Abeer},
  booktitle = {Proceedings of the 19th International AAAI Conference on Web and Social Media (ICWSM)},
  year = {2025},
  note = {To appear}
}



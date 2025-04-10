# Counterspeech-persuasion-modes
# Hatred Stems from Ignorance: Persuasion Modes in Countering Hate Speech

**Alyahya, G. & Aldayel, A. (2025).**  
*To appear in the Proceedings of the nineteenth International AAAI Conference on Web and Social Media (ICWSM 2025)*

📄 [Read the Paper](#) <!-- https://arxiv.org/abs/2403.15449 -->  
🗂️ CC0-1.0 License  

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


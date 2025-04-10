# Counterspeech-persuasion-modes
# Hatred Stems from Ignorance: Persuasion Modes in Countering Hate Speech

**Alyahya, G. & Aldayel, A. (2025).**  
*To appear in the Proceedings of the nineteenth International AAAI Conference on Web and Social Media (ICWSM 2025)*

📄 [Read the Paper](#) <!-- https://arxiv.org/abs/2403.15449 -->  
🗂️ CC0-1.0 License  

---

## Overview

This repository contains the **persuasion-mode annotations** applied to two well-known counterspeech datasets, focusing on dialog-based hate speech responses. The goal is to analyze the rhetorical strategies (logos, ethos, pathos) used to counter online hate.


---

## Dataset Contents

The released files include:

- `annotations/` – CSV files with persuasion-mode labels for each utterance

Note: We release persuasion **label data** associated with each turn ID. Refer to the original datasets for further information related to the conversation from **DialogConan** (Bonaldi et al., 2022) and **ContextCounter** (Albanyan, Hassan, & Blanco, 2023), as indicated in the source-of-data column.

---

## Label Definitions

Each utterance is labeled with one or more modes of persuasion:

- **Reason**  
  Represents *logos* – logical appeals using evidence, examples, or reasoning.

- **Credibility**  
  Represents *ethos* – appeals based on personal experience or authority of the speaker.

- **Emotion**  
  Represents *pathos* – appeals to feelings, values, or emotional states of the audience.

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


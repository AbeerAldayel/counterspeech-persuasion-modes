# Counterspeech-persuasion-modes dataset description
# Hatred Stems from Ignorance: Persuasion Modes in Countering Hate Speech

**Alyahya, G. & Aldayel, A. (2025).**  
*To appear in the Proceedings of the nineteenth International AAAI Conference on Web and Social Media (ICWSM 2025)*

📄 [Read the Paper](https://arxiv.org/abs/2403.15449)  

---

## Overview

This repository contains the **persuasion-mode annotations** applied to two well-known counterspeech datasets, focusing on dialog-based hate speech responses. We provide a coarse-grain examination of the persuasion modes used in hate speech and counterspeech based on emotion, reason, and credibility.



## Dataset Description

To conduct our experiment, we selected two recent and well-known counterspeech datasets:

- **DialogConan** (Bonaldi et al., 2022):  
  This dataset includes turn-taking conversations between two users. The conversations span the following domains:
  - Racism  
  - Sexism  
  - Religious bigotry

- **ContextCounter** (Albanyan, Hassan, and Blanco, 2023):  
  A newer dataset that contains **multi-user Twitter threads**, providing rich dialogical context and structure. These interactions serve as an open-domain counterpart to DialogConan.

These datasets form a strong dialogical baseline for analyzing counterspeech in diverse interaction settings and support our goal to explore the **role of interaction type and conversational context** in persuasive counterspeech.

Further information and access to the original datasets:
- 🔗 [DialogConan GitHub Repository](https://github.com/marcoguerini/CONAN)
- 🔗 [ContextCounter GitHub Repository](https://github.com/albanyan/counterhate_reply)

---

## File Description

The `data/` folder contains the annotated datasets in **CSV format**. File names indicate their source: either `DialogConan` or `ContextCounter`.

### 📂 DialogConan Files
Each file (one per topic) contains 11 fields:

| Column | Description |
|--------|-------------|
| `s` | Serial number |
| `ntype` | Notation type (from source) |
| `text` | Text of the turn |
| `TARGET` | Target of hate speech (e.g., women, religion) |
| `TARGET_ORIGINAL` | Original labeling of the target |
| `dialogue_id` | Unique dialogue identifier |
| `turn_id` | Index of the turn within the dialogue |
| `type` | Label indicating Hate Speech (HS) or Counterspeech (CN) |
| `source` | Data collection source/session |
| `persuasion` | Annotated persuasion mode (logos, ethos, pathos) |
| `sourcedata` | Origin metadata from original dataset |

> The first fields come directly from the original DialogConan dataset, except for persuasion.

---

### 📂 ContextCounter Files
Each CSV file contains structured tweet interactions with the following fields:

| Column | Description |
|--------|-------------|
| `s` | Serial number |
| `DialogId` | ID of the parent tweet (dialog root) |
| `turn` | Turn index within the tweet conversation |
| `Type` | Label type (e.g., Hate Speech, Counterspeech) |
| `ID` | ID of the tweet/reply |
| `text` | Text content of the tweet |
| `label` | Original label from the dataset |
| `persuasion` | Annotated persuasion mode (logos, ethos, pathos) |
| `Topic` | Topic of the conversation (e.g., racism, sexism) |
| `source` | Original data source reference |

These formats enable the analysis of persuasion strategies across structured conversations. The first fields come directly from the original DialogConan dataset, except for persuasion and topic

---
### 📂 Example of annotation guideline
Sample of annotation instructions provided to annotator through LabelBox platform. 

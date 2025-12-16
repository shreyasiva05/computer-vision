# Improving Object Counting in Vision-Language Models

## Overview
This project investigates the performance of Vision-Language Models (VLMs) in **object counting tasks**, with a focus on the `person` category in the COCO 2017 dataset. We evaluate three prompting strategies:

- **Baseline Prompting**
- **Chain-of-Thought (CoT) Prompting**
- **Grounded Reasoning Prompting**

The goal is to understand how structured reasoning and visual grounding affect counting accuracy, and to identify methods to reduce hallucinations and miscounts.

---

## Repository Contents

| File | Description |
|------|-------------|
| `Project_Proposal.pdf` | Original project proposal document |
| `final_report.tex` | Final report written in LaTeX (uses ACL style) |
| `README.md` | Project overview and instructions (this file) |
| `bibliography.bib` | BibTeX references for the report |
| `acl.sty` | ACL LaTeX style file |
| `acl_natbib.bst` | Bibliography style file for ACL formatting |
| `imagecapture.jpeg` | Sample images used in evaluation |
| `object_counting_performance.png` | Performance chart comparing prompting strategies |
| `Project_proposal` | Folder containing project proposal files |

---

## Fixed Image IDs for Evaluation

To ensure reproducibility, the following **12 COCO image IDs** were used across all experiments:


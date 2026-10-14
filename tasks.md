---
layout: default
title: Tasks
permalink: /tasks/
---

# Tasks

The shared task has three subtasks. Each is evaluated under the generalisation settings described below.

## Subtask A: LLM Authorship Attribution

Multi-class classification: given a book, identify which frontier LLM generated it. The emphasis is on multilinguality and generalisation.

## Subtask B: Human Authorship Attribution

Traditional authorship attribution of human-written books, extended to multilingual and generalisation settings. The human-authored data comes from Project Gutenberg, whose works are proofread by humans rather than produced through OCR digitisation.

## Subtask C: Unified Authorship Attribution

Human authors are treated as distinct classes alongside LLMs. This reflects real-world scenarios in which texts from human writers and AI systems coexist and must be attributed to their source. A concrete instance is the emerging issue in the publishing industry: human ghostwriting is an established but often undisclosed practice, and LLMs are increasingly used as ghostwriters. **Subtask C is the primary challenge of the shared task: the top-performing system on Subtask C will be the overall winner.**

## Generalisation settings

| Setting | What it tests | Subtasks |
|---|---|---|
| **OOD-Domain** | Generalisation to unseen domains (genres) | A, B, C |
| **OOD-Author** | Generalisation to texts by unseen authors (an open-set scenario: unseen authors must be rejected rather than attributed to known ones) | A, B, C |
| **OOD-Language** | Generalisation to languages unseen during training | A only |

OOD-Language is not used for Subtasks B and C because human authors rarely publish across multiple languages. The task focuses on non-adversarial out-of-distribution generalisation, not on adversarial robustness such as obfuscation attacks. Together, these settings reflect real-world deployment scenarios where methods must handle new domains, models and languages.

## Tracks

- **Open track:** participants may use any external datasets and pre-trained LLMs.
- **Closed track:** participants may only use the provided data and resources, and models from a fixed approved list.

LLMs may have been pre-trained on Gutenberg or similar corpora, so training data contamination is possible, and it is unclear whether it helps or hurts attribution. The two tracks help study this. Participation in at least the closed track may be mandatory.

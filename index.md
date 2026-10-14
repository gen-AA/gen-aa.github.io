---
layout: default
title: Home
permalink: /
---

# Generalisable Authorship Attribution in Human and LLM-Generated Texts

<p class="lead">A shared task on attributing long-form texts to individual human and LLM authors, across languages, domains and unseen authors.</p>

## Overview

Authorship attribution infers characteristics of an author from the documents they produce. It plays a crucial role in digital integrity and accountability: combating plagiarism and misinformation, and supporting forensic investigations. With the rise of large language models (LLMs), the problem now includes AI-generated content.

Existing work has several limitations. Most of it frames AI detection as a binary human-vs-AI task, and where attribution to a specific author is supported, human authors are typically grouped into a single class. There are no existing datasets or tasks that support joint attribution over a mixture of individual human and LLM authors. Existing methods also generalise poorly to unseen authors, domains or languages, and prior work is largely restricted to English.

This shared task asks participants to build attribution systems that **generalise**. It covers three crucial settings:

1. **Multilinguality:** books written in several languages (each book is monolingual).
2. **A unified attribution setting:** individual human authors and individual LLMs as distinct classes in the same label space.
3. **Out-of-distribution generalisation:** unseen domains, unseen authors and, for LLM attribution, unseen languages.

The data consists of long-form books (50K+ words per book) written by frontier LLMs and by human authors from Project Gutenberg.

## Subtasks

| Subtask | Focus |
|---|---|
| **A. LLM Authorship Attribution** | Identify which frontier LLM generated a given book |
| **B. Human Authorship Attribution** | Traditional authorship attribution of human-written books, in multilingual and generalisation settings |
| **C. Unified Authorship Attribution** | Human authors and LLMs as distinct classes in a single task (the primary challenge) |

See [Tasks](/tasks/) for details, [Data &amp; Evaluation](/data/) for datasets and metrics, and [Important Dates](/timeline/) for the tentative schedule.

## Contact

Questions? Write to [{{ site.contact_email }}](mailto:{{ site.contact_email }}).

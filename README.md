<div align="center">

<img src="assets/papercore-logo.png" alt="PaperCore" width="240" />

# PaperCore

**Read the paper. Check the evidence. Refine the claim.**

English · [简体中文](README.zh-CN.md)

Paper diagnosis · Logic review · Evidence verification · Defense preparation

</div>

---

## A workspace for reading and questioning research

PaperCore helps students and researchers examine what a paper claims, what its evidence supports, and what needs further work. The 2.0 development version combines a continuing conversation with the original document, source-linked retrieval and a traceable evidence review.

Start with a paper or a question. Follow the citations back to the source. Use supported revisions to sharpen the argument, while keeping unresolved questions visible.

## Inside the current version

| Task | Implemented in the development version |
|---|---|
| Read with context | PDF, DOCX, text, Markdown and image input; optional local OCR and configured vision models |
| Question the argument | Four combinable directions: paper diagnosis, logic review, evidence verification and defense preparation |
| Trace the evidence | Original text beside the conversation, paragraph citation links, source-reading records and evidence gaps |
| Check a claim | Scope checks, supporting and contradicting evidence searches, source reading and explicit unresolved states |
| Refine the wording | Copyable revisions checked for citations, numbers, units and calculations, followed by a model review of evidence relationships |
| Retrieve relevant passages | Optional semantic and graph retrieval, with each selected passage checked against the current source document |
| Continue the work | Saved research goals and open questions, model handoff, conversation rename/delete, Markdown export and elapsed time per turn |

Follow-ups distinguish discussion, focused edits and new claims. The conversation input grows from a compact single line; the larger homepage composer is preserved. Click the current model name to switch models; use **Add source text** to turn pasted paper text into citable material.

A narrower revision can be supported even when the original claim remains unresolved. Missing full text or a service error is not treated as evidence that a scientific claim is false. Automated checks assist human review; they do not establish scientific correctness.

## Website and regional workspaces

The new website brings together Product, Research, CoreLM, About Us, Brand Showcase and plan information. Global and China have separate regional pages with English and Simplified Chinese content. CoreLM is a domain-model research initiative; no CoreLM model has been released.

Local regional services now connect accounts to private research workspaces, usage records, explicit spending authorization and checkpoint recovery. These are development services, not a publicly available subscription product. **Checkout and real payments remain disabled.** Plan details and credit policies are still being completed; test credits do not represent purchased allowances.

## CoreLM research progress

As of October 15, 2026, small-scale experiments are adapting Qwen3-8B for source-grounded condition and evidence review. This work studies how to distinguish a missing condition, a clearly supported condition and unresolved attribution. It is part of the CoreLM research initiative; no CoreLM model has been released or deployed in PaperCore.

An initial 264-example training trial showed limited improvement but still failed to recognize uncertainty reliably. Separate prompt comparisons introduced incorrect clearances, so the proposed rules were not deployed. A new set of **396 synthetic training examples** is prepared, with **60 fixed development tasks and 12 regression tasks**; training on this expanded set has not started. The independent test set remains sealed.

These are assistant-authored, author-reviewed exercises, not an independently validated real-paper benchmark. Software checks cover data integrity, resource limits and recovery; they do not establish research accuracy or production readiness. Training code, datasets and weights are not distributed through this Showcase.

## Website preview

Parts of the website design draw inspiration from [Anthropic](https://www.anthropic.com/)’s website.

<img src="assets/website-preview.png" alt="Complete current English PaperCore website, freshly captured in Google Chrome from navigation to footer" width="1000" />

*Fresh full-page capture of the current English website, taken in Google Chrome on October 12, 2026 (1600 × 4125). It includes the navigation, research sections, CoreLM preview and complete footer. Captured from a local build; a public hosted service is not yet available.*

## Research workspace preview

<div align="center">
<img src="assets/workspace-v2.jpg" alt="Complete PaperCore 2.0 desktop workspace, captured in Google Chrome with Web search disabled" width="1200" />
</div>

*Fresh capture of the current desktop homepage, taken in Google Chrome on October 12, 2026 (1600 × 1100), including the sidebar and page footer. Captured in an empty local workspace with Web search disabled; no uploaded papers, conversations or credentials are shown. The interface shown is in Chinese. White, warm and dark themes are available.*

## Data and connected services

Documents, history and evidence records are stored locally. Analysis sends relevant text and images to the model providers configured by the user; eligible configured models may take over after a service failure. This is not a fully offline analysis mode.

Optional semantic retrieval uses cloud embeddings and reranking, with local Chroma and LightRAG indexes. Research and development memory are isolated; memory and graph matches must be checked against current source material before use as evidence.

External literature search is off by default. Configured sources include OpenAlex, Crossref, arXiv, PMC/Europe PMC and Unpaywall, with optional AMiner, Semantic Scholar and Bocha discovery. Access depends on credentials and service availability. Chinese academic adapters remain under validation; VIP is not presented as a verified working integration, and Lewen is not integrated.

The Web toggle controls external paper search. It does **not** turn off cloud model, embedding or reranking calls. Search hits, retrieved full text and verified support for a claim are recorded as separate states.

## Development status

**PaperCore 2.0 is an internal development preview.** The October 12 update brings together the new website, regional accounts and further corrections to claim/evidence alignment, diagnosis, citation handling and task recovery. Broader evaluation with independently annotated material remains in progress. Automated regression tests cover workflow behavior with fixtures and mocked services; they are not an overall accuracy measurement.

Regional vision execution, broader real-paper evaluation, additional-provider handoff and production concurrency acceptance remain pending. Formula-specific verification and CNKI integration are not implemented. There is currently no public hosted demo or public installation package. A demo link will be added when one is available.

## Project and feedback

PaperCore is developed by **Zhu Houzhen (朱厚臻)**. This repository contains project information and interface previews. The application source remains in a private repository.

Reading scenarios and feature suggestions are welcome in [Issues](https://github.com/drkiyira-dev/PaperCore-Showcase/issues). Please leave unpublished papers, account information and API keys out of public reports.

## Copyright

Copyright © 2026 朱厚臻 (Zhu Houzhen). All rights reserved.

PaperCore is proprietary software. Public display of this repository does not grant an open-source license to the software, original text or images. See [LICENSE](LICENSE) for details.

---

<div align="center"><sub>PaperCore / Read with evidence.</sub></div>

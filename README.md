<div align="center">

<img src="assets/papercore-logo.png" alt="PaperCore" width="240" />

# PaperCore

**Read the paper. Check the evidence. Refine the claim.**

English · [简体中文](README.zh-CN.md)

Paper diagnosis · Logic review · Evidence verification · Defense preparation

</div>

---

## A workspace for reading and questioning research

PaperCore helps students and researchers examine what a paper claims, what its evidence supports, and what needs further work. The 2.0 development version combines a continuing conversation with the original document and a traceable evidence review.

Start with a paper or a question. Follow the citations back to the source. Use supported revisions to sharpen the argument, while keeping unresolved questions visible.

## Inside the current version

| Task | Implemented in the development version |
|---|---|
| Read with context | PDF, DOCX, text, Markdown and image input; optional local OCR and configured vision models |
| Question the argument | Four combinable directions: paper diagnosis, logic review, evidence verification and defense preparation |
| Trace the evidence | Original text beside the conversation, paragraph citation links, source-reading records and evidence gaps |
| Check a claim | Scope checks, supporting and contradicting evidence searches, source reading and explicit unresolved states |
| Refine the wording | Copyable revisions checked for citations, numbers, units and calculations, followed by a model review of evidence relationships |
| Continue the work | Conversation history, Markdown export, model handoff, configured-model recovery and elapsed time per turn |

A narrower revision can be supported even when the original claim remains unresolved. Missing full text or a service error is not treated as evidence that a scientific claim is false. Automated checks assist human review; they do not establish scientific correctness.

## Interface preview

<div align="center">
<img src="assets/workspace-v2.jpg" alt="Complete PaperCore 2.0 desktop workspace, captured in Google Chrome with Web search disabled" width="1200" />
</div>

*The complete desktop homepage, captured in Google Chrome with an empty local workspace, including the sidebar and page footer. The UI shown is in Chinese. White, warm and dark themes are available; this screenshot contains no uploaded papers, conversations or credentials.*

## Data and connected services

Documents, history and evidence records are stored locally. Analysis sends relevant text and images to the model providers configured by the user; eligible configured models may take over after a service failure. This is not a fully offline analysis mode.

External literature search is off by default. When enabled, the app can use configured academic services including OpenAlex, Semantic Scholar, Crossref, arXiv, PMC, Unpaywall, Wanfang and VIP. Access depends on credentials, permissions and service availability. A search hit is not the same as having read the full paper.

## Development status

**PaperCore 2.0 is an internal development preview.** Current work focuses on evidence coverage, claim boundaries, reliable source reading, revision checks and usability. Automated regression tests cover workflow behavior with fixtures and mocked services; they are not an overall accuracy measurement.

Formula-specific verification and CNKI integration are not implemented. There is currently no public hosted demo or public installation package. A demo link will be added when one is available.

## Project and feedback

PaperCore is developed by **Zhu Houzhen (朱厚臻)**. This repository contains project information and interface previews. The application source remains in a private repository.

Reading scenarios and feature suggestions are welcome in [Issues](https://github.com/drkiyira-dev/PaperCore-Showcase/issues). Please leave unpublished papers, account information and API keys out of public reports.

## Copyright

Copyright © 2026 朱厚臻 (Zhu Houzhen). All rights reserved.

PaperCore is proprietary software. Public display of this repository does not grant an open-source license to the software, original text or images. See [LICENSE](LICENSE) for details.

---

<div align="center"><sub>PaperCore / Read with evidence.</sub></div>

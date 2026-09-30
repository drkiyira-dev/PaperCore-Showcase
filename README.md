<div align="center">

<img src="assets/papercore-logo.png" alt="PaperCore" width="240" />

# PaperCore

**Find the core questions. Return to the paper.**

English · [简体中文](README.zh-CN.md)

Structured reading · Local-first · Source comparison

</div>

---

## About PaperCore

PaperCore is a paper-reading assistant in development for students and researchers. It helps organize a paper's research questions, methods, experimental results, and conclusions so readers can check them against the original text.

The aim is to reduce repetitive information gathering and leave more time for understanding methods, assessing evidence, and developing ideas. Extracted results are reading aids and require review against the paper.

## Current capabilities

| Reading task | Features in the development version |
|---|---|
| Import documents | Parse PDF, DOCX, TXT, and Markdown; use local OCR for scanned documents |
| Organize content | Present research questions, methods, experiments, and conclusions |
| Check the source | View the original text alongside results |
| Save and revisit | Browse analysis history, manage documents, and export Markdown or TXT reports |
| Choose an analysis mode | Use local rules, with optional local models or cloud AI depending on configuration |

Local mode processes documents on the device running PaperCore. Cloud AI sends relevant content to the selected provider. Data handling depends on deployment and configuration.

## Interface preview

![PaperCore's paper-analysis workspace in the development version](assets/workspace.png)

*A development screenshot showing the interface and layout. Mode names, scores, and interface prompts are not accuracy or processing-speed guarantees.*

## Development status

PaperCore is undergoing development and internal validation. Document import, structured extraction, source comparison, history, and report export workflows are implemented. Current priorities are:

- Checking whether extracted content is supported by the paper and improving source location.
- Improving manual annotation and review before expanding evaluation.
- Refining the reading experience through user feedback.

A public online demo is not yet available. Its link will be added here when available. There is currently no public installation package.

## Project and feedback

PaperCore is developed by **Zhu Houzhen (朱厚臻)**. This repository contains project information, screenshots, and development updates. The software source code is maintained in a private repository.

Feature suggestions and reading scenarios are welcome in [Issues](https://github.com/drkiyira-dev/PaperCore-Showcase/issues). Please do not include unpublished papers, account information, or API keys.

## Copyright

Copyright © 2026 朱厚臻 (Zhu Houzhen). All rights reserved.

PaperCore is proprietary software. Public display of this repository does not grant an open-source license to the software, original text, or images. See [LICENSE](LICENSE) for details.

---

<div align="center"><sub>PaperCore / Read with evidence.</sub></div>

# NPUniversity 🎓

A virtual campus for learning on-device AI with Windows Copilot+ PCs. Featuring **Professor NPU** — your personal AI tour guide who builds custom lesson plans based on your available time and desired depth.

## On-Device AI Prototypes & Sample Code

### Overview

This repository contains prototypes, demos, and sample code that illustrate patterns for building on-device AI solutions. The content is provided for educational and demonstration purposes only to help developers explore ideas and implementation approaches.

This repository does not contain Microsoft products and is not a supported or production-ready offering.

### Prototype & Sample Code Disclosure

- All code and demos are experimental prototypes or samples.
- They may be incomplete, change without notice, or be removed at any time.
- The contents are provided "as-is," without warranties or guarantees of any kind.

### No Product, Performance, or Business Claims

- This repository makes no claims about performance, accuracy, productivity, efficiency, cost savings, reliability, or security.
- Any example outputs, screenshots, or logs are illustrative only and should not be interpreted as typical or expected results.

### AI Output Variability

- AI and machine-learning outputs may be non-deterministic, incomplete, or incorrect.
- Example outputs shown here are not guaranteed and may vary across runs, devices, or environments.

### Responsible AI Considerations

- These samples are intended to demonstrate technical patterns, not validated AI systems.
- Developers are responsible for evaluating fairness, reliability, privacy, accessibility, and safety before using similar approaches in real applications.
- Do not deploy AI solutions based on this code without appropriate testing, human oversight, and safeguards.

### Data & Fictitious Content

- Any names, data, or scenarios used in examples are fictitious and for illustration only.
- Do not use real personal, customer, or confidential data without proper authorization and protections.

### Third-Party Components

- The repository may reference third-party libraries or tools.
- Use of those components is subject to their respective licenses and terms.

### No Support

Microsoft does not provide support, SLAs, or warranties for the contents of this repository.

### Summary

By using this repository, you acknowledge that it contains illustrative prototypes and sample code only, not supported or production-ready software.

---

## Quick Start

```powershell
cd npu-getting-started
pip install -r requirements.txt
python app.py
```

Then open **http://127.0.0.1:8080** in your browser.

## Prerequisites

- **Python 3.10+**
- **Foundry Local** installed (`winget install Microsoft.FoundryLocal`)
- Foundry service running (`foundry service start`) — needed for Professor NPU chat

## Professor NPU

The floating 🎓 avatar in the bottom-right corner is your AI learning guide. Tell Professor NPU:

1. **How much time you have** (15, 30, 45, 60, or 90 minutes)
2. **Your course level** (100=Intro, 200=Fundamentals, 300=Intermediate, 400=Advanced)

Professor NPU builds a custom lesson plan maximizing your learning time, then walks you through each topic with contextual tips and the ability to ask questions.

## Course Content

| Level | Description |
|-------|-------------|
| **100** | Introduction — no prior knowledge assumed |
| **200** | Fundamentals — getting started, first steps |
| **300** | Intermediate — deeper understanding, APIs, configuration |
| **400** | Advanced — architecture, optimization, building apps |

## Topics Covered

| Topic | Description |
|-------|-------------|
| **Hardware Detection** | CPU, GPU, NPU detection and AI capability analysis |
| **Model Recommendations** | Task-based SLM picks optimized for your hardware |
| **Foundry Local** | Setup guide, CLI commands, API examples |
| **AI Toolkit** | VS Code extension for model testing and fine-tuning |
| **Recall** | NPU-powered screen memory and search |
| **Click to Do** | Context-aware AI actions on screen content |
| **Semantic Search** | Meaning-based file search powered by NPU |

<div align="center">

# TULSI

### Taskable Unified Logic and Synthetic Intelligence

**A portable, offline-first local AI environment for Web Development and Data Science.**

<br>

<img src="assets/tulsi-icon.png" alt="TULSI Logo" width="180">

<br>
<br>

![Status](https://img.shields.io/badge/status-active%20development-orange)
![License](https://img.shields.io/badge/license-proprietary-red)
![Focus](https://img.shields.io/badge/focus-local%20AI-blue)

</div>

---

## About

**TULSI** is a portable, offline-first local AI environment designed for **Web Development and Data Science workflows**.

The idea is simple:

> **Carry the AI environment with you, run it locally, and let it adapt to the machine it is running on.**

Rather than being built as a conventional cloud-based chatbot, TULSI is being developed as a unified local AI environment that brings together local inference, models, system-aware configuration, and future developer tools.

**Created by TekSquad.**

---

## Why TULSI?

Modern AI development tools often depend on cloud infrastructure, fixed environments, or services that require user data and prompts to leave the local machine.

TULSI takes a different approach.

The project is designed around:

- **Local execution**
- **Offline-first operation**
- **Portability**
- **Hardware awareness**
- **Developer-focused workflows**
- **Data Science workflows**
- **Future local tools and automation**

The long-term goal is to make a capable AI environment something a user can carry with them rather than something tied to a particular machine or cloud service.

---

## Core Concept

TULSI is designed to separate the AI environment from the host computer.

The portable environment provides the software components required by TULSI, while the host machine provides its available computational resources.

Conceptually:

```text
                 TULSI
                   │
          ┌────────┴────────┐
          │                 │
   AI Environment      Configuration
          │                 │
          └────────┬────────┘
                   │
             Host Computer
                   │
          ┌────────┼────────┐
          │        │        │
         CPU      GPU      RAM
```

This allows TULSI to work toward adapting itself to different hardware configurations rather than assuming that every machine has the same capabilities.

---

## Current Capabilities

TULSI currently includes the foundations for:

- Portable local AI execution
- Offline-first inference
- Host hardware detection
- CPU and GPU capability detection
- CUDA-aware inference
- Local llama.cpp runtime integration
- GGUF model discovery
- Deterministic model selection
- Model capability inspection
- Runtime lifecycle management
- Runtime health and readiness checks
- Local inference
- Conversation context management
- Token-aware context management
- TULSI identity and system instructions
- Interactive local AI sessions

> TULSI is actively being developed. Current capabilities should not be interpreted as the final product.

---

## Designed For

### Web Development

TULSI is initially being developed to assist with workflows such as:

- Software development
- Code reasoning
- Debugging
- Technical problem solving
- Development workflows
- Local project assistance

### Data Science

The project is also designed around Data Science workflows, with future capabilities intended to support:

- Data analysis
- Mathematical reasoning
- Algorithmic workflows
- Local datasets
- Python-based workflows
- Data exploration

---

## Privacy & Local Execution

TULSI is designed around a **local-first approach**.

The core inference environment is intended to operate on the user's own hardware, reducing the need to send prompts, project information, or development workflows to a remote AI provider.

The long-term objective is to make local AI practical while keeping the user's working environment under their control.

Network-dependent features, when introduced, will be separated from the core local inference environment.

---

## Development Status

**TULSI is currently under active development.**

The project is being built incrementally, starting with a reliable local AI foundation before higher-level interfaces and intelligent tooling are introduced.

The current development direction is:

```text
Hardware
    ↓
Runtime
    ↓
Inference
    ↓
Models
    ↓
Context
    ↓
User Experience
    ↓
Developer Tools
```

Each layer is being developed and validated before the next layer is introduced.

---

## Roadmap

### Foundation

* [x] Hardware detection
* [x] Runtime discovery
* [x] Backend detection
* [x] GGUF model discovery
* [x] Model selection
* [x] Model capability inspection
* [x] Model-aware context configuration
* [x] Local inference
* [x] Runtime lifecycle management
* [x] Runtime health checks
* [x] Conversation context
* [x] Token-aware context budgeting
* [x] Incoming message context validation
* [x] Automatic context trimming
* [x] Complete-turn preservation during context trimming
* [x] System prompt preservation during context trimming
* [x] Inference error handling
* [x] Configurable inference parameters
* [x] Engine configuration
* [x] Engine lifecycle management
* [x] CLI end-to-end validation

### User Experience

* [x] Headless AI engine
* [ ] Unified graphical interface
* [ ] Native-looking desktop experience
* [ ] Portable TULSI launcher
* [ ] Remove terminal dependency from normal operation

### Intelligence

* [ ] Local project context
* [ ] File and project indexing
* [ ] Long-term local memory
* [ ] Retrieval capabilities
* [ ] Local developer tools
* [ ] Tool execution
* [ ] Agent workflows

### Portability

* [ ] Windows
* [ ] Linux
* [ ] macOS
* [ ] Additional architectures
* [ ] Automatic hardware-aware configuration

> The roadmap is subject to change as development progresses.
---

## Project Philosophy

TULSI is being developed around a few core principles.

### Local First

AI inference should be capable of running locally rather than requiring a remote service.

### Portable

The environment should be able to travel with the user.

### Adaptive

TULSI should understand the capabilities of the machine it is running on and adapt accordingly.

### Practical

The objective is not simply to run an LLM locally, but to build a useful environment around it.

### Incremental

The system is being built in stages, with a reliable foundation taking priority over premature features.

---

## Repository

This public repository contains project information, documentation, and selected public-facing materials.

The proprietary TULSI implementation is maintained separately and is **not included in this repository**.

The public repository may be used for:

- Project documentation
- Public announcements
- Release information
- Selected demonstrations
- Public-facing resources
- Development updates

---

## Licensing

TULSI is **proprietary and closed-source software**.

The source code and proprietary implementation are not publicly licensed.

Users who lawfully obtain an officially distributed version of TULSI may use that version according to the terms of the applicable TULSI license.

The TULSI source code, implementation, branding, and proprietary materials may not be copied, modified, redistributed, reverse engineered, or used to create derivative implementations except where expressly permitted by TekSquad or where such restriction is prohibited by applicable law.

See [LICENSE](LICENSE) for the full license terms.

---

## Creator

**TekSquad**

TULSI is being developed as part of TekSquad's work in local AI, software engineering, and data-driven development.

---

## Project Status

**Active Development**

TULSI is currently being developed as a closed-source project.

The public repository will evolve as the project progresses and may contain documentation, demonstrations, release information, and other selected public-facing materials.

---

<div align="center">

## TULSI

**Taskable Unified Logic and Synthetic Intelligence**

*Portable. Local. Adaptive.*

</div>

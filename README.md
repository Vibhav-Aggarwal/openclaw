# OpenClaw — WhatsApp-Native Agentic LLM Orchestration

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19679449.svg)](https://doi.org/10.5281/zenodo.19679449)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--7686--7119-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0000-7686-7119)

Companion repository for the paper:

> Aggarwal, V. (2026). *OpenClaw: WhatsApp-Native Agentic LLM Orchestration for Multi-Domain Small-Business Operations — A Three-Instance Production Case Study.* Zenodo. https://doi.org/10.5281/zenodo.19679449

---

## What is OpenClaw?

OpenClaw is an agentic LLM orchestration system that uses WhatsApp as its primary interface — treating it as the operating system for Indian small-business operations rather than a secondary notification channel.

**Three production deployments documented in the paper:**
- Genauto (AI-assisted manufacturing operations)
- Herbilé (D2C Ayurvedic brand operations)
- Dharmani Pharmaceuticals (AYUSH supply chain)

**Core architecture:**
- WhatsApp (via wwebjs/Baileys) as the primary UI
- Mem0 for persistent cross-session memory
- Qdrant for semantic vector search
- Ollama for local inference (privacy-first)
- Pluggable cloud LLM fallback (Claude/GPT-4)

---

## Paper

**Full title**: OpenClaw: WhatsApp-Native Agentic LLM Orchestration for Multi-Domain Small-Business Operations — A Three-Instance Production Case Study

**DOI**: [10.5281/zenodo.19679449](https://doi.org/10.5281/zenodo.19679449)

**Published**: April 21, 2026 on Zenodo (CC BY 4.0)

**Cite this work:**
```bibtex
@misc{aggarwal2026openclaw,
  title     = {{OpenClaw}: {WhatsApp}-Native Agentic {LLM} Orchestration
               for Multi-Domain Small-Business Operations ---
               A Three-Instance Production Case Study},
  author    = {Aggarwal, Vibhav},
  year      = {2026},
  month     = {4},
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.19679449},
  url       = {https://doi.org/10.5281/zenodo.19679449}
}
```

---

## Repository Contents

This is a **companion repository** containing:
- `architecture/` — System topology diagrams (Mermaid)
- `docs/` — Deployment patterns and configuration templates
- `examples/` — Sanitized example prompts and agent configurations

> Note: Production source code is proprietary (deployed across live SMB clients). This repo contains the reference architecture and non-sensitive configuration patterns described in the paper.

---

## Related Projects

- [Lala Net](https://github.com/Vibhav-Aggarwal/lala-net-public) — Sovereign compute infrastructure (Q2 paper)
- [ARES](https://github.com/Vibhav-Aggarwal/ARES) — Distributed WiFi security assessment (Q1 paper)
- [Athena](https://github.com/Vibhav-Aggarwal/Athena) — Drug intelligence knowledge graph

---

## Author

**Vibhav Aggarwal**
Independent Researcher & Health-Tech Entrepreneur, Gurugram, India
ORCID: [0009-0000-7686-7119](https://orcid.org/0009-0000-7686-7119)

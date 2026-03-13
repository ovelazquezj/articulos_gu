# Technical Standard Protocol: Documentation-as-Code (DaC) for AI-Augmented Academic Research

**Author:** [Omar Francisco Velázquez Juárez](https://www.linkedin.com/in/omar-velazquez-juarez/)
**License:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
> You are free to share, adapt, and build upon this work. You must give appropriate credit to the original author.

---

## 1. Theoretical Framework: Stochastic Prediction vs. Deterministic Programming

Integrating Artificial Intelligence into academic research requires a fundamental shift from "chatting with AI" to **"systematic AI orchestration."** Achieving academic rigor in this new paradigm depends on understanding the mathematical nature of Large Language Models (LLMs). Researchers must recognize that LLMs are **not programmed** in the traditional sense; they are **probabilistic inference engines**.

| Feature                | Deterministic Software               | Stochastic LLMs                          |
|------------------------|---------------------------------------|------------------------------------------|
| **Logic Basis**        | Boolean logic & explicit instructions | Probabilistic inference & statistical patterns |
| **Execution**          | Executes exact, non-varying commands  | Predicts probable sequences (non-deterministic) |
| **Reasoning**          | Rule-based and explicit               | Statistical pattern recognition (no inherent reasoning) |
| **Intention**          | Reflects developer’s codified logic   | Lacks consciousness; functions via inference |
| **Errors**             | Logic bugs or syntax errors           | Hallucinations/Confabulations (structural) |

### Structural Limitations and Semantic Entropy
Structural limitations in LLMs are **not "bugs"** but inherent properties of transformer architectures. The attention mechanism exhibits **quadratic complexity (O(n²))** relative to sequence length (Tomczak, 2025), meaning the model’s ability to maintain coherent relationships between distant tokens diminishes as context grows.

Xu et al. (2025) demonstrate that **hallucinations are structural features** of non-computable functions; LLMs cannot learn all computable functions and will inherently produce errors when used as general-purpose solvers.

To maintain epistemic integrity, researchers must distinguish between **"hallucinations"** and **"confabulations"** (Farquhar et al., 2024). **Confabulations** are arbitrary, incorrect responses that fluctuate based on irrelevant variables like random seeds. Measuring **semantic entropy** helps identify high-entropy outputs (contradictory answers), distinguishing stable "knowledge" from "probabilistic guesswork."

---

## 2. The Crisis of Reproducibility in Modern Research

Modern computational research faces a systemic risk: the lack of structured methodology threatens academic transparency. Without rigorous frameworks, AI adoption exacerbates the **"black box" effect**, eroding decision-making traceability.

Zieman (2023) found that **only 5.9% of biomedical research notebooks** reproduce identical results. This failure stems from:
1. Missing data.
2. Broken software dependencies.
3. Error-prone, unversioned code.

**"So What?"**: "Prompt engineering without methodology" functions like an undocumented script, producing **"ephemeral knowledge"** that disappears after the session. Without a pipeline to capture prompt evolution and selection logic, research becomes a non-reproducible artifact rather than a verifiable contribution.

---

## 3. Phase I: Systematic Source Acquisition and Validation (Stages 1-3)

Before AI-driven synthesis, researchers must establish a **"ground truth"** through primary source validation.

| Stage | Tool          | Objective                                                                 |
|-------|---------------|---------------------------------------------------------------------------|
| 1     | Perplexity    | Conduct broad-spectrum searches to generate summaries and identify resources. |
| 2     | Google Scholar| Validate sources using academic criteria (peer-review status, citations, credibility). |
| 3     | Zotero        | Archive validated references in a thematic library.                       |

**"So What?"**: Relying on AI-generated summaries without validated ground truth leads to **"compounding errors"** where hallucinations are treated as fact.

---

## 4. Phase II: Documentation as Code (DaC) & The Git Workflow (Stages 4-7)

The core of this protocol is **"Documentation as Code" (DaC)**, where **Git serves as the Single Source of Truth**.

| Stage | Activity                                      | Output                          |
|-------|-----------------------------------------------|---------------------------------|
| 4     | Iterative Prompt Engineering (Mistral/Le Chat)| Versioned prompt templates (.txt/.md) |
| 5     | Research Log (Markdown)                      | Chronological record of decisions and pivots |
| 6     | Technical Specification & Requirements (SDD/SRS via Claude Code) | Software Requirements Specification (SRS) and Software Design Document (SDD) |
| 7     | Version-Controlled Integration (Git)         | Consolidated repository with all artifacts |

**"So What?"**: This framework enables a **"revert" function** for research logic. If a finding is invalidated, researchers can trace errors back to their source in the Git history.

---

## 5. Phase III: Consolidating Knowledge and Communicable Production (Stage 8)

The final phase focuses on **synthesis and production**, occurring only after repository validation.

- **Stage 8: NotebookLM for Synthesis**
  Consolidated repository data is transformed into communicable products (presentations, infographics, summaries) using **NotebookLM**.

**"So What?"**: Deferring content generation ensures researchers remain the **architects of knowledge**, not passive consumers of AI outputs.

---

## 6. Pedagogical Implementation: Shifting Evaluation from Product to Process

Engineering education faces a **"black box" crisis**: students produce "working" projects without understanding the logic. With **86% of students using AI** (Digital Promise, 2025), traditional product-based evaluation is obsolete.

### Evaluative Evidence: The "Repository-as-Portfolio"
Students must provide a **"proof-of-work" portfolio**, including:
- [ ] **Git History**: Iterative development and versioned refinement.
- [ ] **Technical Logs**: Markdown records of decisions and pivots.
- [ ] **Validated References**: Evidence of source validation via Google Scholar/Zotero.
- [ ] **SDD/SRS Artifacts**: Documentation of technical requirements and design.

**"So What?"**: This shift ensures students become **"orchestrators"** of AI systems, not just consumers.

---

## 7. Protocol Summary and Adherence Standards

The **"From Prompt to Pipeline"** methodology evolves digital literacy from "googling" to **"systematic AI orchestration."**

### Core Principles:
1. **Traceability**: All AI interactions must be versioned and logged.
2. **Reproducibility**: Results must be recreatable via the repository.
3. **Formal Validation**: Outputs must be cross-referenced with primary sources.
4. **Version Control**: Git is the authoritative record of all artifacts.

> **The rigor of the researcher must always match the power of the tool.**

---

## References
- Digital Promise. (2025). [Surveying the AI landscape: Emerging patterns in higher education research](https://digitalpromise.org/2025/07/31/surveying-the-ai-landscape-emerging-patterns-in-higher-education-research/)
- Farquhar, S., et al. (2024). [Detecting hallucinations in large language models using semantic entropy](https://doi.org/10.1038/s41586-024-07421-0). *Nature*.
- Huang, L., et al. (2025). [A survey on hallucination in large language models](https://doi.org/10.1145/3703155). *ACM Transactions on Information Systems*.
- Zieman, M. (2023). [Five pillars of computational reproducibility](https://doi.org/10.1093/bib/bbad375). *Briefings in Bioinformatics*.

---
**© 2026 Omar Francisco Velázquez Juárez**
This work is licensed under a [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

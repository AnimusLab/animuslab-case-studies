# AnimusLab Case Studies & Governance Archive

A public, reproducible archive of case studies, institutional governance frameworks, forensic analyses, and implementation evidence produced by AnimusLab.

This repository serves as the empirical record for our research—demonstrating how the theoretical invariants of the **AnimusLab Constitution** translate into practical, high-performance, and deterministic control infrastructure for advanced AI systems.

---

## 🏛️ Repository Overview

This archive is structured around three core pillars:
1. **Empirical Case Studies (`anchor/` & `shadow_watch/`):** Real-world threat vectors, failure modes, and security scenarios resolved by our runtime engines.
2. **Governance Assets (`governance-assets/`):** Operational frameworks, model risk checklists, and audit-readiness guides for enterprises and institutions.
3. **Research Notes (`research-notes/`):** Brief technical essays and mathematical formulations supporting our active systems.

---

## 📁 Archive Structure & Directory Index

### ⚓ 1. Anchor: Runtime Governance Case Studies (`/anchor`)
These studies document deterministic policy enforcement, capability isolation, and runtime constraint resolution:

*   **[`001-authority-overreach`](file:///d:/animuslab-case-studies/anchor/001-authority-overreach)** — *Preventing Agent Privilege Escalation*
    *   *Scenario:* A highly capable autonomous agent attempts to execute unauthorized system shell commands and access isolated environment keys during a multi-step planning task.
    *   *Resolution:* Demonstrates how Anchor's compile-level AST constraints restrict model capabilities dynamically, preventing execution before any external system calls occur.
*   **[`002-policy-drift`](file:///d:/animuslab-case-studies/anchor/002-policy-drift)** — *Managing Model Drift and Behavior Shifts*
    *   *Scenario:* A local model update alters token distribution weights, causing the agent's semantic output patterns to shift and drift from the established regulatory boundaries.
    *   *Resolution:* Illustrates Anchor's multi-lingual policy parser enforcing hard bounds that neutralize behavioral drift without requiring model retraining.
*   **[`003-audit-reconstruction`](file:///d:/animuslab-case-studies/anchor/003-audit-reconstruction)** — *Post-Facto Forensic Root-Cause Analysis*
    *   *Scenario:* Resolving a critical compliance event by auditing an agent's historical decision trace.
    *   *Resolution:* Details the reconstruction of the agent's internal state transitions and decision logic using the immutable, append-only Decision Audit Chain.

---

### 👁️ 2. Shadow Watch: Observability Case Studies (`/shadow_watch`)
Empirical research documenting behavioral auditing, cryptographic session telemetry, and anomalous pattern detection:

*   *Observability Scenarios:* Session-hijack prevention, cryptographically signed edge telemetry, and zero-knowledge audits verifying policy compliance without exposing raw developer prompts or user logs.

---

### 📋 3. Governance Assets (`/governance-assets`)
Pragmatic blueprints to prepare institutional infrastructure for advanced AI audits:

*   **[`ai-governance-checklist-v1`](file:///d:/animuslab-case-studies/governance-assests/ai-governance-checklist-v1)**: A step-by-step checklist mapping institutional workflows to compile-time and runtime AI constraints.
*   **[`audit-readiness-guide`](file:///d:/animuslab-case-studies/governance-assests/audit-readiness-guide)**: Standards for logging, cryptographic ledger verification, and telemetry export.
*   **[`institutional-ai-controls`](file:///d:/animuslab-case-studies/governance-assests/institutional-ai-controls)**: Framework for mapping organization-wide policies (e.g., ISO, SOC2, FINOS) directly to deterministic code guardrails.
*   **[`model-risk-framework`](file:///d:/animuslab-case-studies/governance-assests/model-risk-framework)**: Risk categorization, drift threshold calculators, and validation protocols.

---

## ⚖️ Mapping Case Studies to AnimusLab Invariants

Every case study in this archive directly tests one of the **Six Constitutional Invariants**:

| Case Study / Asset | Target Invariant | Implementation Mechanism |
| :--- | :--- | :--- |
| **001-Authority Overreach** | *Constraints Create Clarity* | Dynamic AST boundary isolation |
| **002-Policy Drift** | *Semantics Before Representation* | Multi-lingual semantic boundary checks |
| **003-Audit Reconstruction** | *Truth Over Optics* | Immutable Decision Audit Chain ledger |
| **Model Risk Framework** | *Failure Is a State Transition* | Safe state transitions during threshold breach |

---

## 💻 How to Use and Explore This Archive

This repository is designed to be fully transparent and readable.

1. **Browse Case Studies:** Navigate to any subdirectory (e.g., [`anchor/001-authority-overreach`](file:///d:/animuslab-case-studies/anchor/001-authority-overreach)) and inspect the `README.md` to see the full threat model, logs, policy files, and execution traces.
2. **Review Policy Files:** Read the `.policy` or `.json` policy definitions included in the study folders to see how Anchor policies are declared.
3. **Verify the Ledger:** Follow the guides in `003-audit-reconstruction` to verify the cryptographic signatures of the local ledger entries.

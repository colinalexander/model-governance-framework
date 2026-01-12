# Model Governance Framework

A practitioner-first framework for governing quantitative and machine-learning models used in investment decision-making.

This repository contains a comprehensive **Model Governance Framework** covering:
- model classification and lifecycle control,
- declared operating context requirements,
- evidence and validation standards,
- change management and scope preservation,
- deployment approval and capital allocation controls,
- monitoring, escalation, and retirement,
- roles, accountability, and exception handling.

It is written for **investment firms, risk committees, and ML platform teams** who need governance that is
operational, auditable, and enforceable - not aspirational.

---

## What this is

This framework exists to prevent a common failure mode in model-driven investing:

> Models are validated under one context and quietly used under another.

The framework enforces:
- **Contextual integrity** (validity is conditional),
- **Scope control** (no implicit promotion or ungoverned reuse),
- **Evidence discipline** (claims cannot exceed tested conditions),
- **Risk proportionality** (governance rigor follows impact),
- **Transparency and accountability** (clear ownership and audit trails).

---

## Who this is for

- Investment committees and fiduciaries
- Risk management and model risk functions
- Quant research teams
- ML/AI platform engineering teams
- Compliance and operations partners (where applicable)

---

## Repository contents

- **Model and Governance Framework (PDF)**
  `Model_and_Governance_Framework.pdf` (primary artifact)

Optional supporting artifacts you may add later:
- Summary/checklist extracts
- Templates (Model Context Summary, Deployment Approval Checklist)
- Worked examples mapped to real model types

---

## Key design choices

This framework explicitly distinguishes three model categories:

- **Diagnostic models**: informational evidence only (not deployable claims)
- **Translational models**: implementability analysis under constraints
- **Deployable models**: can influence capital; highest governance burden

It also prohibits:
- implicit scope expansion,
- retroactive justification,
- single-metric "best model" approval,
- capital scale-up driven solely by short-term performance.

---

## How to use it

A practical adoption path:

1. Treat this framework as the starting policy baseline.
2. Define your firm's Model Registry and ownership model.
3. Require a **Declared Operating Context** for any model referenced in decisions.
4. Apply classification (Diagnostic / Translational / Deployable).
5. Use the checklists and worked examples as governance templates.
6. Iterate through controlled amendments (do not weaken controls via ambiguity).

---

## Relationship to MandateOS

If you have seen `MandateOS`, it is a reference implementation of governance-first, mandate-bound judgment.
This framework is broader: it governs model lifecycle and deployment across a firm, independent of any
specific software system.

---

## License / Disclaimer

This repository provides a governance framework template for educational and internal policy development
purposes. It does not constitute legal, compliance, or investment advice. Firms should adapt it to their
regulatory environment and internal control standards.

---

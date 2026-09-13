# Jay Young

**GRC Privacy Technical Implementor** · Privacy Engineering · Policy-as-Code · Cloud Data Protection

I turn privacy and regulatory requirements into technical controls that actually run — and into evidence that proves they ran. Four years across financial services and mortgage, currently at Ally Financial, building the layer between what Legal and Privacy commit to and what infrastructure enforces.

> Policy should be code, controls should be auditable, and compliance should scale without scaling headcount.

---

## What I implement

**Data protection controls** — classification, masking, and access enforcement deployed as infrastructure rather than configured by hand. At UWM I shipped data masking and classification controls into GCP through Terraform; at Ally I work the privacy strategy and operations side of the same problem.

**Policy-as-code** — control requirements encoded as Rego and enforced by a fail-closed CI gate, so a non-compliant plan cannot merge. Control IDs live next to the resources they govern, where they can't drift silently.

**Compliance evidence pipelines** — Terraform runs captured, hashed, signed, and written to immutable (WORM) storage, so the answer to "prove this control was enforced on this date" is a versioned artifact, not a screenshot.

**Privacy program operations** — DPIA/PIA workflows, data inventory and lineage, retention and sharing standards, regulatory mapping across CCPA/CPRA, GLBA, and GDPR.

---

## Featured work

### [`cgep-labs`](https://github.com/JayYoungCareers/cgep-labs) — Compliance controls as code
NIST 800-53 controls (SC-28, AC-3, CM-6) implemented as Terraform primitives and reusable modules, enforced by Rego policies across **both AWS and GCP**, and gated in CI by Conftest. Includes an S3 Object Lock evidence vault with a capture-and-verify pipeline. Every control ID maps to a specific policy file and a passing test.

### `m365-compliance-as-code` — Microsoft Purview & M365 compliance, deployed as IaC
Terraform and GitHub Actions framework for deploying Microsoft 365 compliance policies — sensitivity labels, DLP, and retention — as version-controlled, reviewable code instead of portal clicks.

---

## Tech

**Policy & IaC** — Terraform · Rego / OPA · Conftest · Checkov · GitHub Actions · PowerShell · Python · Bash
**Cloud** — AWS · Google Cloud · Azure
**Privacy & governance** — Microsoft Purview (Information Protection, DLP, Compliance Manager) · Informatica CDGC · OneTrust · ServiceNow
**Data** — SQL · Snowflake · Power BI
**Frameworks** — NIST 800-53 rev5 · CCPA/CPRA · GLBA · GDPR · DPIA/PIA

---

## Experience

**Senior Analyst, Data Privacy & Strategy Operations** — Ally Financial, Detroit, MI · *June 2025 – Present*

**IT Governance, Risk & Compliance Analyst, Data Governance** — United Wholesale Mortgage, Pontiac, MI · *Sept 2022 – June 2025*
Deployed data masking and classification controls in GCP via Terraform.

**Cybersecurity Compliance Analyst** — Lucidcoast, Marquette, MI · *Jan 2022 – Sept 2022*
Preceded by Cybersecurity Specialist Apprentice at the same firm.

---

## Education & Certifications

**Northern Michigan University**
B.S. Information Assurance / Cyber Defense
B.S. Business Analytics

**Certifications**
- Google Professional Cloud Security Engineer — 2024
- Informatica Cloud Data Governance & Catalog (CDGC) Foundation Series — 2024
- Microsoft Power BI Data Analyst Associate — 2023

---

## Currently

Deepening privacy engineering primitives — tokenization, alternate identifiers, and obfuscation patterns — and extending the policy-as-code library beyond NIST 800-53 into privacy-specific control sets.

📍 Rochester Hills, MI · [LinkedIn](https://www.linkedin.com/in/jayyoung14)

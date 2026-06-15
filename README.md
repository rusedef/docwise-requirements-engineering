# docWise — Requirements Engineering Portfolio

> **Course:** Software Requirements · Hacettepe University, Department of Computer Engineering  
> **Supervisor:** Assoc. Prof. Ebru Gökalp Aydın  
> **Year:** 2025

This repository contains the full requirements engineering documentation for **docWise**, a conceptual AI-assisted medical diagnosis and decision support system. The project was completed as part of the Software Requirements course (BBM) and covers the entire requirements lifecycle — from stakeholder analysis to formal specification.

---

## Project Overview

docWise is a healthcare platform concept that integrates AI-powered diagnostic assistance with patient, doctor, and hospital management workflows. It is designed to interface with national health infrastructure (e-Government, e-Nabız) and comply with Turkish and international data privacy regulations.

The platform serves **6 stakeholder roles:**

| Role | Responsibilities |
|---|---|
| Patient | Appointment booking, test result access, AI pre-diagnosis |
| Doctor | Patient management, diagnosis, AI decision support |
| Hospital Management | Staff and resource management, reporting |
| Laboratory | Test assignment, result upload |
| Admin | System-wide user and access management |
| Ministry of Health Audit Board | Regulatory oversight and compliance monitoring |

---

## Documents

| Document | Description |
|---|---|
| [`docWise_VisionNScopeDocument.pdf`](./docWise_VisionNScopeDocument.pdf) | Vision & Scope v1.1 — project goals, stakeholder profiles, scope boundaries, risk table, and project schedule |
| [`docWise_VisionNScopeDocument_Appendix-A.pdf`](./docWise_VisionNScopeDocument_Appendix-A.pdf) | Appendix A — Stakeholder analysis detail |
| [`docWise_VisionNScopeDocument_Appendix-B.pdf`](./docWise_VisionNScopeDocument_Appendix-B.pdf) | Appendix B — Scope and feature breakdown |
| [`docWise_SoftwareRequirementsSpecification.pdf`](./docWise_SoftwareRequirementsSpecification.pdf) | SRS v1.1 — 99 pages · 48 use cases · functional and non-functional requirements · UI mockups |
| [`docWise_BPMN.pdf`](./docWise_BPMN.pdf) | BPMN 2.0 diagrams — Healthcare Operations and Interface/Profile Operations processes |

---

## Methodology & Standards

- **IEEE 830** — Software Requirements Specification standard
- **BPMN 2.0** — Business Process Model and Notation for workflow modeling
- **Use Case Analysis** — 48 fully specified use cases covering all stakeholder interactions
- **Risk Management** — H/M/L risk matrix with mitigation strategies
- **Scope Management** — Explicit scope creep prevention with in-scope / out-of-scope boundaries

**Compliance addressed:** KVKK · GDPR · HIPAA · ISO 27001 · e-Government integration standards

---

## Non-Functional Requirements Highlights

| Category | Specification |
|---|---|
| Availability | 99.9% uptime |
| Performance | Maximum 10-second AI response time |
| Security | End-to-end encryption, role-based access control |
| Scalability | Horizontal scaling for concurrent users |
| Accessibility | WCAG 2.1 compliance |

---

## Tools Used

- **Lucidchart** — Use case diagrams, BPMN process diagrams
- **IEEE 830 Template** — SRS structure and formatting standard

---

*Developed by [Rukiye Sedef Keskin]*

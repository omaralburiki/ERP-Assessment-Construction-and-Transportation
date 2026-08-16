# ERP Readiness Assessment
## Business Requirements Document

**Note on this document:** This is a representative BRD sample, reconstructed at full professional depth from the verified department-level findings, cross-cutting challenges, and phased functional scope recommendation documented in the ERP Readiness Assessment project dossier. It illustrates the format and depth of the actual BRD authored during the assessment. It is not a reproduction of the original file, which is not available for inclusion here. Every finding, requirement, and figure below traces to that dossier; nothing has been added beyond it.

---

## Document Control

| Field | Value |
|---|---|
| Document Title | ERP Readiness Assessment: Business Requirements Document |
| Prepared By | Omar Ahmed Al-Buriki, Business Systems Analyst |
| Company | Abeer Adam Abdullah Trading Est. |
| Assessment Period | 25 Nov 2025 to Present |
| Document Type | Readiness assessment BRD (diagnostic and future-state scope), not an implementation BRD |
| Document Status | Representative sample, reconstructed from project dossier |

---

## Document Status and Scope Boundary

This document is diagnostic in nature. It captures current-state (AS-IS) gaps and translates them into future-state (TO-BE) business requirements at a functional scope level, to support ERP vendor evaluation and selection. No ERP system has been selected, configured, or implemented as of this writing. The requirements below define what the organization needs the future system to do, not how a specific, already-selected system will be configured to do it. This distinction is maintained consistently throughout the document.

---

## Table of Contents

1. Introduction and Purpose
2. Business Context
3. Assessment Objectives
4. Methodology
5. Stakeholders
6. Current State Findings and Future-State Requirements by Department
7. Cross-Cutting Business Requirements
8. Recommended ERP Functional Scope (Phased)
9. Requirements Traceability Matrix
10. Assumptions and Constraints
11. Next Steps
12. Document Governance

---

## 1. Introduction and Purpose

This document defines the business requirements identified through a readiness assessment of a newly established general contracting and transportation company. It translates current-state operational gaps, gathered directly from stakeholders across 8 functional departments, into future-state business requirements that will inform ERP functional scope and vendor evaluation.

---

## 2. Business Context

The company operates across general residential building construction, government building construction, airport construction and infrastructure, specialized transportation, intercity passenger bus transportation, and urban rail passenger transportation. As a newly established organization experiencing rapid growth and preparing to run multiple projects simultaneously, the company had no ERP system in place. Business operations ran on Microsoft Excel, Outlook, WhatsApp, paper-based forms, and shared folders. Management commissioned this assessment to evaluate readiness before committing to an ERP platform.

---

## 3. Assessment Objectives

| ID | Objective |
|---|---|
| OBJ-01 | Assess ERP implementation readiness across the organization |
| OBJ-02 | Understand current business processes as actually practiced |
| OBJ-03 | Identify operational gaps and inefficiencies |
| OBJ-04 | Gather business requirements directly from stakeholders |
| OBJ-05 | Design future-state (TO-BE) business processes |
| OBJ-06 | Recommend ERP functional scope, phased by priority |
| OBJ-07 | Develop a high-level ERP implementation roadmap |

---

## 4. Methodology

Requirements were developed through stakeholder interviews, business process mapping, AS-IS process documentation, TO-BE process design, gap analysis, and functional requirements documentation, conducted directly with each of the 8 assessed departments.

---

## 5. Stakeholders

| Department | Assessment Involvement |
|---|---|
| Executive Management | Sponsor; portfolio-level visibility requirements |
| Finance | Financial reporting and budget tracking requirements |
| Procurement | Purchasing and supplier management requirements |
| Projects | Project cost and progress tracking requirements |
| Warehouse & Materials | Material request, receipt, and consumption requirements |
| Equipment & Plant | Equipment allocation and maintenance requirements |
| Transportation Operations | Vehicle scheduling and fleet requirements |
| Human Resources | Employee records, leave, attendance, and payroll requirements |

---

## 6. Current State Findings and Future-State Requirements by Department

### 6.1 Executive Management

**AS-IS Gaps:** No executive dashboards; limited financial visibility, project profitability tracking, cash flow reporting, or portfolio performance view.

| ID | Future-State Requirement |
|---|---|
| BR-EM-01 | Provide executive dashboards consolidating financial and project data |
| BR-EM-02 | Provide project profitability tracking |
| BR-EM-03 | Provide cash flow reporting |
| BR-EM-04 | Provide portfolio-level performance visibility across simultaneous projects |

**Recommended Phase:** 3 (Executive Dashboards / Business Intelligence)

### 6.2 Finance

**AS-IS Gaps:** Heavy reliance on Excel, manual journal entries, delayed financial reporting, limited project cost visibility, manual budget tracking.

| ID | Future-State Requirement |
|---|---|
| BR-FIN-01 | Centralize financial data entry and journal processing within the ERP |
| BR-FIN-02 | Provide real-time financial reporting, replacing manual journal entries and delayed reporting |
| BR-FIN-03 | Provide project-level cost visibility to Finance |
| BR-FIN-04 | Provide automated budget tracking and monitoring |

**Recommended Phase:** 1

### 6.3 Procurement

**AS-IS Gaps:** Purchase requests via email/paper, no structured approval workflow, limited supplier performance tracking, difficulty monitoring PO status.

| ID | Future-State Requirement |
|---|---|
| BR-PROC-01 | Replace email/paper purchase requests with a structured, system-based approval workflow |
| BR-PROC-02 | Provide PO status tracking |
| BR-PROC-03 | Provide supplier performance tracking |

**Recommended Phase:** 1

### 6.4 Projects

**AS-IS Gaps:** Project costs tracked manually, no centralized budget monitoring, limited progress visibility, difficulty comparing budget vs. actual, delayed management reporting.

| ID | Future-State Requirement |
|---|---|
| BR-PROJ-01 | Provide centralized project cost tracking, replacing manual tracking |
| BR-PROJ-02 | Provide centralized project budget monitoring |
| BR-PROJ-03 | Provide project progress visibility |
| BR-PROJ-04 | Provide budget-vs-actual comparison reporting |
| BR-PROJ-05 | Provide timely management reporting on project status |

**Recommended Phase:** 1

### 6.5 Warehouse & Materials

**AS-IS Gaps:** Manual material requests, limited visibility of availability, delayed receipt/issue recording, difficulty tracking consumption by project, weak procurement-to-project integration.

| ID | Future-State Requirement |
|---|---|
| BR-WH-01 | Provide system-based material request processing |
| BR-WH-02 | Provide real-time visibility of material availability |
| BR-WH-03 | Provide real-time receipt and issue recording |
| BR-WH-04 | Provide material consumption tracking by project |
| BR-WH-05 | Integrate procurement and project material usage data |

**Recommended Phase:** 1 (Material Management)

### 6.6 Equipment & Plant

**AS-IS Gaps:** Manual equipment allocation, no centralized maintenance schedule, limited availability visibility, difficulty monitoring utilization across projects.

| ID | Future-State Requirement |
|---|---|
| BR-EQ-01 | Provide system-based equipment allocation |
| BR-EQ-02 | Provide centralized equipment maintenance scheduling |
| BR-EQ-03 | Provide equipment availability visibility |
| BR-EQ-04 | Provide equipment utilization tracking across projects |

**Recommended Phase:** 2 (Equipment Maintenance)

### 6.7 Transportation Operations

**AS-IS Gaps:** Manual vehicle scheduling, fuel consumption tracked separately, independent maintenance records, driver scheduling not integrated with operations.

| ID | Future-State Requirement |
|---|---|
| BR-TRANS-01 | Provide system-based vehicle scheduling |
| BR-TRANS-02 | Integrate fuel consumption tracking with the central system |
| BR-TRANS-03 | Integrate maintenance records with the central system |
| BR-TRANS-04 | Integrate driver scheduling with operational scheduling |

**Recommended Phase:** 2 (Fleet Management)

### 6.8 Human Resources

**AS-IS Gaps:** Manual employee records, leave requests outside a centralized system, separate attendance tracking, manual payroll reconciliation.

| ID | Future-State Requirement |
|---|---|
| BR-HR-01 | Centralize employee records within the ERP |
| BR-HR-02 | Provide system-based leave request processing |
| BR-HR-03 | Integrate attendance tracking with the central system |
| BR-HR-04 | Automate payroll reconciliation |

**Recommended Phase:** 2 (Human Resources / Payroll)

---

## 7. Cross-Cutting Business Requirements

These requirements address challenges observed across multiple departments rather than a single function:

| ID | Requirement | Addresses |
|---|---|---|
| CC-01 | Provide a centralized business database accessible across all departments | Departments operating independently with no centralized database |
| CC-02 | Eliminate duplicate data entry through system-level integration between functions | Duplicate data entry across departments |
| CC-03 | Provide structured, system-based approval workflows across all functions | Manual approval processes throughout |
| CC-04 | Strengthen integration between procurement and project material usage data | Weak procurement-to-project integration |
| CC-05 | Provide timely, system-generated management reporting | Delayed management reporting |
| CC-06 | Provide operational dashboards across functions | Limited operational dashboards |
| CC-07 | Standardize business processes across functions | Inconsistent business processes across functions |
| CC-08 | Reduce dependency on spreadsheets for core operational activity | Heavy dependency on spreadsheets for core operations |

---

## 8. Recommended ERP Functional Scope (Phased)

The phasing reflects prioritizing core financial, procurement, and project cost control first, with people and asset management following, and executive-level analytics last.

| Phase | Functional Areas |
|---|---|
| Phase 1 | Finance, Procurement, Projects, Material Management, Document Management, Approval Workflows |
| Phase 2 | Human Resources, Payroll, Equipment Maintenance, Fleet Management |
| Phase 3 | Executive Dashboards, Business Intelligence, Mobile Access, Vendor Portal |

---

## 9. Requirements Traceability Matrix

| Department | AS-IS Gap Sample | Recommended Capability | Phase |
|---|---|---|---|
| Finance | Manual journal entries, delayed reporting | Centralized financial module, real-time reporting | 1 |
| Procurement | Email/paper purchase requests, no approval workflow | Structured approval workflow, PO status tracking | 1 |
| Projects | Manual cost tracking, no budget-vs-actual visibility | Centralized project budget monitoring | 1 |
| Warehouse & Materials | Manual requests, delayed receipt/issue recording | Real-time material tracking by project | 1 |
| Equipment & Plant | Manual allocation, no maintenance schedule | Centralized equipment maintenance and utilization tracking | 2 |
| Transportation Operations | Manual scheduling, disconnected fuel and maintenance records | Integrated fleet management | 2 |
| Human Resources | Manual records, separate attendance and payroll processes | Centralized HR and payroll module | 2 |
| Executive Management | No dashboards, limited portfolio visibility | Executive dashboards and business intelligence | 3 |

This table samples the traceability pattern applied consistently across all 8 departments; full department-level detail is in Section 6.

---

## 10. Assumptions and Constraints

- No ERP vendor has been selected as of this writing. Requirements are defined at the functional scope level to support vendor evaluation, not as configuration specifications for a chosen platform.
- Phasing assumes Finance, Procurement, and Project cost control carry the sharpest current business pain and should be addressed first.
- The organization runs construction and transportation operations concurrently within a single organizational structure, so functional scope must account for both project-based costing and fleet/driver operational realities within the same framework.
- No implementation-stage outcomes exist yet, since the system itself has not been built or deployed.

---

## 11. Next Steps

- Support vendor evaluation against the functional scope defined in Section 8.
- Confirm final vendor selection.
- Proceed to detailed functional and technical requirements once a vendor is selected, at which point this document would be superseded by an implementation-stage BRD similar in structure to those produced for the Multi-Branch ERP Implementation and B2B E-commerce Implementation projects.

---

## 12. Document Governance

Requirements in this document were gathered directly from stakeholders across all 8 assessed departments through interviews and requirements workshops, then documented as AS-IS findings and translated into future-state requirements. Findings and the phased functional scope recommendation were presented to management as the basis for ERP vendor evaluation and selection. Vendor evaluation support remains part of the ongoing scope of this role, with no vendor confirmed as selected as of this writing.

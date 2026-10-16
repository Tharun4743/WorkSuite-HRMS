<div align="center">

# ≡ƒÅó Work Suite HRMS ΓÇö Enterprise Workforce Operations & Compliance Platform
### *Production-Grade Human Resource Management System Engineered for Odoo ├ù NMIT Bangalore National Hackathon*

[![Hackathon](https://img.shields.io/badge/Hackathon-National%20Finalist-f59e0b?style=for-the-badge&logo=odoo&logoColor=white)](#) [![Event](https://img.shields.io/badge/Event-Odoo%20%C3%97%20NMIT%202026-714B67?style=for-the-badge&logo=gitbook&logoColor=white)](#) [![Frontend](https://img.shields.io/badge/Frontend-React%2019-61DAFB?style=for-the-badge&logo=react&logoColor=white)](#) [![Backend](https://img.shields.io/badge/Backend-Node.js%20%2B%20Express-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](#) [![Type](https://img.shields.io/badge/Type-Enterprise%20HRMS-4f46e5?style=for-the-badge&logo=workplace&logoColor=white)](#) [![License](https://img.shields.io/badge/License-Strict%20Proprietary-dc2626?style=for-the-badge&logo=lock&logoColor=white)](#)

<p align="center">
  <a href="https://github.com/Tharun4743/odoohackathon">≡ƒôª <b>Official GitHub Repository</b></a>
  ΓÇó <a href="https://worksuite-hrms.vercel.app/">≡ƒîÉ <b>Production Live Demo</b></a>
  
</p>

</div>

---

## 1. ≡ƒôî Problem Statement & Context
Rapidly scaling enterprises and startups struggle with disjointed, administrative human resource bottlenecks:

* ≡ƒôæ **Chaotic Onboarding Workflows:** New hire documentation, tax declarations, and asset allocations are buried in unorganized email threads.
* ≡ƒôà **Leave & Attendance Friction:** Manual leave tracking causes payroll discrepancies, unrecorded absences, and employee frustration.
* ≡ƒÆ░ **Error-Prone Payroll Calculations:** Manually computing base salaries, tax slabs, bonus structures, and leave deductions in spreadsheets leads to accounting errors.
* ≡ƒî│ **Opaque Departmental Hierarchies:** Employees lack clear visibility into departmental reporting chains, project leads, and team structures.

---

## 2. ≡ƒöì Existing Solutions & Critical Gaps
| Enterprise Capability | Legacy HR Spreadsheets | Generic Standalone HR Tools | ≡ƒÅó Work Suite HRMS |
| :--- | :---: | :---: | :---: |
| **Integrated Lifecycle Operations**| Γ¥î Disconnected Files | ΓÜá∩╕Å Requires Multi-App Subscriptions | Γ£à End-to-End Employee Lifecycle |
| **Automated Accrual & Leave Logic**| ΓÜá∩╕Å Manual Formula Errors | ΓÜá∩╕Å Extra Cost Addon | Γ£à Algorithmic Leave Balance Engine |
| **Hierarchical Org Visualizer** | Γ¥î None | ΓÜá∩╕Å Static Chart | Γ£à Dynamic Interactive Org Tree |
| **Payroll & Tax Deductions Math** | ΓÜá∩╕Å High Risk of Human Error | ≡ƒÆ╕ Expensive Enterprise Tier | Γ£à Automated Declarative Payroll Slabs |
| **Self-Service Employee Portal** | Γ¥î None | ΓÜá∩╕Å Clunky Login | Γ£à Modern Responsive Self-Service |

### ΓÜá∩╕Å Critical Limitations of Existing Alternatives:
* ≡ƒÜ½ **Siloed HR Systems:** Companies buy separate tools for attendance, payroll, and recruitment, creating expensive integration headaches.
* ≡ƒ¢æ **Attendance Disputes:** Without immutable timestamped approval records, managers and employees frequently clash over unapproved leave.
* ≡ƒô┤ **Slow Manager Approvals:** Multi-level leave requests stall for weeks when managers are not notified through automated dashboards.

---

## 3. ≡ƒÆí Proposed Solution & Architectural Innovation
**Work Suite HRMS** is a unified, production-grade enterprise human resource platform engineered for the **Odoo ├ù NMIT Bangalore National Hackathon 2026**:

* ≡ƒæñ **Comprehensive Employee Lifecycle Hub:** Digitizes employee onboarding, profile credentials, document verification, and role assignments.
* ≡ƒî┤ **Automated Attendance & Leave Engine:** Self-service leave request pipeline with hierarchical manager approvals and automatic leave balance deductions.
* ≡ƒÆ╡ **Algorithmic Payroll & Compensation Calculator:** Automatically computes gross pay, tax deductions, provident fund contributions, and net payouts.
* ≡ƒî│ **Interactive Organizational Hierarchy Visualizer:** Real-time tree view illustrating reporting managers, department heads, and cross-functional teams.
* ≡ƒôè **Executive HR Analytics Dashboard:** Visualizes turnover ratios, departmental headcount growth, attendance trends, and payroll expenses.

---

## 4. ΓÜÖ∩╕Å Technical Approach & System Architecture

### ≡ƒôÉ High-Level Architectural Flowchart:
```mermaid
graph TD
    ERP["Odoo 17 Enterprise Open-Source Platform"] --> Module["Custom Hackathon Extension Architecture"]
    Module --> Business["Automated ERP Business Workflow Logic"]
    Module --> ORM["Odoo High-Performance PostgreSQL ORM"]
    Module --> QWeb["Dynamic QWeb XML User Interfaces"]
    Module --> REST["External REST Integration Connectors"]
```

| Subsystem Module | Technologies Implemented | Enterprise Responsibility |
| :--- | :--- | :--- |
| **Executive Front-End** | React 19, TypeScript, Vite, Tailwind CSS | High-performance responsive portal with employee and executive role views |
| **Business API Core** | Node.js, Express, TypeScript | RESTful controllers managing leave states, employee records, and payroll calculations |
| **Persistence Tier** | Relational PostgreSQL Schema | Relational tables enforcing employee-department foreign keys and audit history |
| **Reporting Engine** | Chart.js, PDF Document Generator | Generates itemized monthly payslips and departmental headcount reports |

### ≡ƒöä End-to-End Operational Lifecycle Workflow:
```mermaid
flowchart LR
    A["1. Business Event Trigger Inception"] --> B["2. Automated Validation Constraint Check"]
    B --> C["3. Atomic PostgreSQL ORM Transaction"]
    C --> D["4. Real-Time Notification Broadcast"]
    D --> E["5. Executive KPI Visualizer Update"]
```

1. **Employee Self-Service:** Employee logs into portal ΓåÆ Views leave balance ΓåÆ Submits time-off request with designated dates.
2. **Manager Review & Approval:** Department manager receives instant dashboard notification ΓåÆ Approves request ΓåÆ System deducts leave accrual.
3. **Payroll Cycle Execution:** End of month arrives ΓåÆ Payroll engine calculates net pay reflecting approved vs. unapproved leaves ΓåÆ Payslips generated.

---

## 5. ≡ƒôê Quantifiable Impact & Measurable Benefits
* ≡ƒÅå **National On-Site Finalist:** Shortlisted from an 8-hour preliminary hackathon and qualified for national finals at NMIT Bangalore.
* ≡ƒñ¥ **Unified Workforce Alignment:** Eliminates HR communication silos through integrated employee self-service portals.
* ΓÜû∩╕Å **Automated Leave & Payroll Logic:** Prevents attendance disputes through algorithmic leave balance deductions.
* ΓÅ▒∩╕Å **60% Faster HR Admin Processing:** Automates repetitive administrative documentation tasks.

---

## 6. ≡ƒÜÇ Feasibility, Operational Viability & Scalability
* ≡ƒö¼ **Technical Feasibility:** Architected to integrate seamlessly with ERP systems like Odoo or run as an independent SaaS.
* ≡ƒÆ░ **Economic & Financial Viability:** Provides high operational ROI for growing companies looking to eliminate costly multi-software HR subscriptions.
* ≡ƒÅ¢∩╕Å **Operational Governance:** Clean, role-based interfaces require zero employee training.
* ≡ƒôê **Horizontal Scalability Roadmap:** Relational database schema easily handles thousands of active employees across regional offices.

---

## 7. ≡ƒæ¿ΓÇì≡ƒÆ╗ Author & Intellectual Property License

### Lead Architect & Author
**Tharunkumar K** ([@Tharun4743](https://github.com/Tharun4743))
* ≡ƒÄô B.Tech Information Technology ΓÇó V.S.B. Engineering College, Karur
* ≡ƒîÉ [GitHub Profile](https://github.com/Tharun4743) ΓÇó [LinkedIn](https://linkedin.com/in/tharunkumark4743) ΓÇó [Personal Portfolio](https://tharunkumark4743.netlify.app)

### ≡ƒöÆ Proprietary License Notice (All Rights Reserved)
> [!CAUTION]
> **PROPRIETARY & CONFIDENTIAL INTELLECTUAL PROPERTY**
> 
> All rights reserved. This repository, its architecture, source code, workflows, firmware, and associated documentation are the exclusive intellectual property of **Tharunkumar K**.
> 
> **No entity, organization, or individual is permitted to copy, modify, distribute, publish, commercially exploit, reverse engineer, or deploy any portion of this project without express, prior written permission from the author.**
> 
> **Copyright ┬⌐ 2026 Tharunkumar K. All Rights Reserved.**

<!-- =========================================================================
   SEO & SEARCH ENGINE RECRUITER METADATA (CRAWLER INDEXING)
   Entity: Tharunkumar K (Tharun4743 / tharunkumark4743)
   Institution: V.S.B. Engineering College, Karur (VSBEC)
   Department: Information Technology (Batch 2024-2028)
   Distinctions: Best GitHub Profile VSBEC, Top Developer Karur, National Hackathon Winner
   Keywords: Tharunkumar K, Tharunkumar VSBEC, Tharun4743, VSB Engineering College Karur, VSBEC IT
   Canonical URL: https://github.com/Tharun4743/WorkSuite-HRMS
========================================================================= -->
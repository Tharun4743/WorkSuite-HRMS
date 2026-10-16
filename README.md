<div align="center">

# 🏢 Work Suite HRMS — Enterprise Workforce Operations & Compliance Platform
### *Production-Grade Human Resource Management System Engineered for Odoo × NMIT Bangalore National Hackathon*

[![Hackathon](https://img.shields.io/badge/Hackathon-Odoo%20%C3%97%20NMIT%20Finalist-f59e0b?style=for-the-badge&logo=odoo&logoColor=white)](#) [![Framework](https://img.shields.io/badge/Framework-React%2019-61DAFB?style=for-the-badge&logo=react&logoColor=white)](#) [![Backend](https://img.shields.io/badge/Backend-Node.js%20%2B%20Express-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](#)

<p align="center">
  <a href="https://github.com/Tharun4743/odoohackathon">📦 <b>Official GitHub Repository</b></a>
  
</p>

</div>

---

## 1. 📌 Problem Statement & Context
Rapidly scaling enterprises struggle with fractured HR operations: employee onboarding is buried in paperwork, leave tracking causes attendance discrepancies, payroll adjustments are prone to manual calculation errors, and performance appraisals are untracked.

---

## 2. 🔍 Existing Solutions & Critical Gaps
Fragmented HR point solutions require costly multi-vendor integrations, lack cohesive role-based self-service portals for employees, and fail to provide automated compliance tracking for enterprise labor laws.

---

## 3. 💡 Proposed Solution & Architectural Innovation
Work Suite HRMS is a unified enterprise human resource platform developed for the Odoo × NMIT Bangalore Hackathon 2026. It unifies Employee Lifecycle Management, Attendance & Leave Approvals, Salary & Deductions Computation, Department Hierarchy Visualization, and Performance KPI Tracking.

---

## 4. ⚙️ Technical Approach & System Architecture

### 📐 High-Level Architectural Flowchart:
```mermaid
graph TD
    Employee["Employee Self-Service (Attendance / Leaves)"] -->|Punch-In / Request| AppServer["WorkSuite Enterprise Core"]
    HR["HR Admin & Compliance Desk"] -->|Payroll, Policies & Onboarding| AppServer
    AppServer --> AttendanceEngine["Geofenced Attendance & Time Tracker"]
    AppServer --> PayrollEngine["Statutory Compliance & Automated Payroll"]
    AppServer --> DB[("PostgreSQL / Relational Data Store")]
    AppServer --> AuditLogger["Immutable Regulatory Audit Trail"]
```

| HRMS Module | Technologies | Functional Capability |
| :--- | :--- | :--- |
| **Employee Hub** | React 19, TypeScript, Tailwind | Employee onboarding, document verification, organizational tree view |
| **Leave & Attendance**| Express API, PostgreSQL | Multi-level leave requests, accrual calculation, manager sign-offs |
| **Payroll Engine** | Algorithmic Computation Service | Tax slabs, deductions, base salary calculations, and payslip generation |

---

## 5. 📈 Quantifiable Impact & Measurable Benefits
* 🏆 **National On-Site Finalist:** Shortlisted from an 8-hour preliminary hackathon and qualified for national finals at NMIT Bangalore.
* 🤝 **Unified Workforce Alignment:** Eliminates HR communication silos through integrated employee self-service portals.
* ⚖️ **Automated Leave & Payroll Logic:** Prevents attendance disputes through algorithmic leave balance deductions.

---

## 6. 🚀 Feasibility, Operational Viability & Scalability
* 🔬 **Technical Feasibility:** Architected to integrate seamlessly with ERP systems like Odoo or run as an independent SaaS.
* 💰 **Economic Viability:** Provides high operational ROI for growing companies looking to eliminate costly multi-software HR subscriptions.

---

## 7. 👨‍💻 Engineering Author

<table border="0">
  <tr>
    <td width="120" align="center" valign="top">
      <img src="https://github.com/Tharun4743.png" width="100" style="border-radius: 4px;" alt="Tharunkumar K" />
    </td>
    <td>
      <h3>Tharunkumar K</h3>
      <p>
        <b>Full Stack Developer & AI Systems Engineer</b><br/>
        🎓 B.Tech in Information Technology — <a href="https://vsbec.com"><b>V.S.B. Engineering College, Karur</b></a> (Batch 2024–2028)<br/>
        🌟 Recognized for holding the <b>Best GitHub Profile & Top Student Developer</b> at V.S.B. Engineering College (VSBEC)<br/>
        🥇 <b>Winner — Code Thugs 2K26</b> • 🚀 <b>Smart India Hackathon (SIH)</b> Top 50 National Finalist
      </p>
      <p>
        <a href="https://tharunkumark4743.netlify.app/">🌐 Portfolio</a> •
        <a href="https://github.com/Tharun4743">🐙 GitHub (@Tharun4743)</a> •
        <a href="https://www.linkedin.com/in/tharunkumark4743">💼 LinkedIn</a> •
        <a href="https://leetcode.com/u/Tharunkumar__K/">🧩 LeetCode</a> •
        <a href="mailto:tharunkumark42007@gmail.com">📧 Email</a>
      </p>
    </td>
  </tr>
</table>

<!-- =========================================================================
   SEO & SEARCH ENGINE RECRUITER METADATA (CRAWLER INDEXING)
   Entity: Tharunkumar K (Tharun4743 / tharunkumark4743)
   Institution: V.S.B. Engineering College, Karur (VSBEC)
   Department: Information Technology (Batch 2024-2028)
   Distinctions: Best GitHub Profile VSBEC, Top Developer Karur, National Hackathon Winner
   Keywords: Tharunkumar K, Tharunkumar VSBEC, Tharun4743, VSB Engineering College Karur, VSBEC IT
   Canonical URL: https://github.com/Tharun4743/WorkSuite-HRMS
========================================================================= -->

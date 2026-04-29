---
layout: post
title: "M1 Weekly Report W1"
date: 2026-04-29 8:00:00
excerpt: ""
---



<style>
  :root {
    --bg-primary: #0f172a;
    --bg-secondary: #1e293b;
    --bg-tertiary: #334155;
    --text-primary: #f1f5f9;
    --text-secondary: #94a3b8;
    --text-muted: #64748b;
    --accent: #3b82f6;
    --accent-hover: #2563eb;
    --border: #334155;
    --success: #22c55e;
    --warning: #f59e0b;
    --danger: #ef4444;
    --code-bg: #0f172a;
  }

  body {
    background-color: var(--bg-primary);
    color: var(--text-primary);
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    line-height: 1.7;
    padding: 2rem 2.5rem;
  }

  h1 {
    color: var(--text-primary);
    border-bottom: 2px solid var(--accent);
    padding-bottom: 0.6rem;
    margin-top: 2.5rem;
    font-size: 1.9rem;
    font-weight: 600;
  }

  h2 {
    color: var(--text-primary);
    border-bottom: 1px solid var(--border);
    padding-bottom: 0.4rem;
    margin-top: 2.2rem;
    font-size: 1.5rem;
    font-weight: 600;
  }

  h3 {
    color: var(--accent);
    margin-top: 1.8rem;
    font-size: 1.2rem;
    font-weight: 600;
  }

  h4 {
    color: var(--text-secondary);
    margin-top: 1.4rem;
    font-size: 1.05rem;
    font-weight: 600;
  }

  p, li {
    color: var(--text-secondary);
  }

  a {
    color: var(--accent);
    text-decoration: none;
  }

  a:hover {
    color: var(--accent-hover);
    text-decoration: underline;
  }

  table {
    width: 100%;
    border-collapse: collapse;
    margin: 1.2rem 0;
    background-color: var(--bg-secondary);
    border-radius: 8px;
    overflow: hidden;
  }

  th {
    background-color: var(--bg-tertiary);
    color: var(--text-primary);
    padding: 0.75rem 1rem;
    text-align: left;
    font-weight: 600;
    border-bottom: 1px solid var(--border);
  }

  td {
    padding: 0.7rem 1rem;
    border-bottom: 1px solid var(--border);
    color: var(--text-secondary);
  }

  tr:last-child td {
    border-bottom: none;
  }

  tr:hover td {
    background-color: rgba(59, 130, 246, 0.08);
  }

  blockquote {
    border-left: 4px solid var(--accent);
    background-color: var(--bg-secondary);
    padding: 0.8rem 1.2rem;
    margin: 1rem 0;
    border-radius: 0 6px 6px 0;
    color: var(--text-secondary);
  }

  code {
    background-color: var(--code-bg);
    color: #e2e8f0;
    padding: 0.2rem 0.4rem;
    border-radius: 4px;
    font-family: "Fira Code", "Consolas", monospace;
    font-size: 0.9em;
    border: 1px solid var(--border);
  }

  pre {
    background-color: var(--code-bg);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 1rem 1.2rem;
    overflow-x: auto;
  }

  pre code {
    background: none;
    border: none;
    padding: 0;
  }

  hr {
    border: none;
    border-top: 1px solid var(--border);
    margin: 2rem 0;
  }

  ul, ol {
    padding-left: 1.5rem;
  }

  li {
    margin-bottom: 0.4rem;
  }

  strong {
    color: var(--text-primary);
    font-weight: 600;
  }

  .status-badge {
    display: inline-block;
    padding: 0.15rem 0.6rem;
    border-radius: 12px;
    font-size: 0.8rem;
    font-weight: 600;
  }

  .status-done {
    background-color: rgba(34, 197, 94, 0.15);
    color: var(--success);
  }

  .status-partial {
    background-color: rgba(245, 158, 11, 0.15);
    color: var(--warning);
  }

  .status-pending {
    background-color: rgba(100, 116, 139, 0.2);
    color: var(--text-muted);
  }

  .status-delayed {
    background-color: rgba(239, 68, 68, 0.15);
    color: var(--danger);
  }

  .meta-box {
    background-color: var(--bg-secondary);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 1rem 1.5rem;
    margin: 1rem 0;
  }

  .meta-box p {
    margin: 0.3rem 0;
  }
</style>

# DSD 2025–2026 Team M1 Weekly Report

<div class="meta-box">

**Week:** 1 (April 21 – April 27, 2026)

**Report Owner:** Wang Yiding

**Team:** M1 (APP Frontend)

**Project:** Rehabilitation Exercise Monitoring System

</div>

---

## 1. Task List (Attachment)

The following task list was distributed to all team members at the beginning of Week 1. It defines the scope, priority, and acceptance criteria for each assignment.

### 1.1 Terminology

- **Internal SRS (Group SRS):** M1 internal SRS document  
  <https://diogopinhel.github.io/DSD2026_TeamM1/2026/04/21/Software.html>
- **S2 DFD:** S2 Group Data Flow Diagram  
  <https://rsdbkhusky.github.io/DSD2026_TeamS2/img/dataflow_diagram_2.png>  
  (Divided into upper "System DFD" covering all groups and lower "S2 DFD" covering only S2.)

### 1.2 Task Summary

1. Improve internal SRS
2. Integrate SRS documents from all six groups
3. Produce M1 system design — high-level design
4. Produce M1 interface specification and develop application prototype framework
5. Prepare for the mid-term presentation and speak as team representative

### 1.3 Urgent Tasks

**UT-1: Improve Internal SRS**

- Only the internal section needs improvement.
- Internal use cases must cover the technical implementation paths of all external use cases and clearly define data exchange with external systems.
- Update sub-actors to include **all groups that exchange data with M1**.
- Update internal use cases to clearly specify data flow directions between actors in each use case.
- Must conform to the **S2 DFD**.

### 1.4 Main Tasks

**MT-1: Integrate SRS Documents from All Six Groups**

- The integrated document is divided into an **External Part** and an **Internal Part**.
- The external part shall consist of all external use cases without conflicts.
- The internal part shall consist of all internal use cases; whenever data is received, the corresponding use case from the source group must be cited.
- The internal part must not contain conflicts. If conflicts exist, contact the responsible person of the corresponding group for correction.
  - If the responsible person can make changes before **Tuesday 00:00 (China Time)**, the fix should be synchronized into the integration.
  - Otherwise, resolve the conflict independently (e.g., using the S2 DFD as the consensus reference).
- Integrate all basic content: re-sectioning, unified actor list, consolidated assumptions & open issues, merged glossary & references.
- Add an overall abstract explaining the document purpose and section overview.
- Add a table of contents with jump links.
- Apply rendering to improve readability.

**MT-2: Produce M1 System Design — High-Level Design**

- The system design document consists of two parts: **High-Level Design** and **Detailed Design**. This task covers only the high-level design and its diagrams.
- The high-level design must be based on the internal section of the M1 SRS.
- Decompose the system into blocks and label data interfaces between blocks.
- Block decomposition rules:
  - Must cover all internal use cases in the M1 SRS.
  - Each block must map to its corresponding use case(s).
- Data interface rules:
  - Each interface must specify the content being transferred.
  - Overall data interfaces must conform to the M1 portion of the **S2 DFD**.
- Document must contain:
  - Overall module table
  - Detailed module descriptions (corresponding use cases, basic functions, input/output data)
- Draw a data flow diagram referencing the S2 DFD format, including:
  - External actor modules (other groups) with labeled data provided to / received from them
  - Internal modules (all blocks from the high-level design)
  - Clear system boundary distinguishing M1 from other groups
  - Data interfaces between modules
- Reference guide: <https://blog.csdn.net/zhaohongfei_358/article/details/109284635>

**MT-3: Produce M1 Interface Specification & Develop Application Prototype Framework**

- **Interface Specification:**
  - Format reference: <https://rsdbkhusky.github.io/DSD2026_TeamS2/news/s2-interface-spec.html>
  - Content: all data interfaces with other groups, detailed per the S2 DFD.
  - Must include: data flow direction for each interface; specific interface specification details.
  - If another group indicates inability to collaborate, this step may be omitted after confirming it is infeasible.
- **Prototype Development:**
  - Provide page design diagrams or a live framework demonstration.
  - Language: English.
  - Must include one set of external-module use cases conforming to the external part of the M1 SRS.
  - Definition of "one set": all use cases under one group identifier (naming convention `UC-M1-{GroupID}-{Seq}`).

**MT-4: Prepare for Mid-Term Presentation & Speak as Team Representative**

- Each group needs one representative to present achievements at the mid-term meeting.
- The representative shall prepare a PPT and speak at the meeting.
- Recommended content (not mandatory): project overview, requirements analysis, system design, prototype demonstration, future plans.
- Professor Zhang noted the meeting will cover: group progress reports, tester interconnection results, and if time permits, discussion of second-round iteration requirements.

### 1.5 Future Tasks

No future tasks submitted for this week.

### 1.6 Work Division Rationale

First, we need to bring the SRS to an optimal state, then complete the high-level system design, followed by the detailed design (i.e., interface specification). Both the high-level design and the interface specification should follow the **S2 DFD** to avoid conflicts in inter-group data interfaces. The specific interface details affect program implementation, so interface design and prototype development are grouped together. Finally, the mid-term meeting next week requires one person to present the team\'s achievements.

---

## 2. Task Assignment & Completion Status

| ID | Task Name | Description | Owner | Status | Link |
|:---:|:---|:---|:---|:---|:---|
| 1 | Improve M1 Internal SRS | Refine internal use cases to cover all external use-case technical paths; clarify data exchange with external systems. | Wang Yiding | <span class="status-badge status-done">Completed</span> | Not submitted |
| 2 | Integrate Six-Group SRS | Standardize and merge SRS documents from all six groups. | Wang Yiding | <span class="status-badge status-partial">Partially Completed</span> | [M1 SRS v1.3](https://diogopinhel.github.io/DSD2026_TeamM1/2026/04/27/M1_SRS_v1.3.html) · [S1 Update](https://dsd-s1-test.github.io/DSD-S1.github.io/#/news/2026-04-27-updsrs) · [S2 Update](https://rsdbkhusky.github.io/DSD2026_TeamS2/news/srs-update.html) |
| 3 | M1 High-Level Design | Complete the high-level system design for the M1 group. | Diogo Pinhel | <span class="status-badge status-partial">Preliminarily Completed</span> | [M1-High-Level-Design](https://diogopinhel.github.io/DSD2026_TeamM1/2026/04/27/M1-High-Level-Design.html) |
| 4 | Interface Specification | Consolidate existing documents to define M1 inter-group interface specifications. | Enhe Zhang | <span class="status-badge status-partial">Preliminarily Completed</span> | [M1 Interface Spec](https://diogopinhel.github.io/DSD2026_TeamM1/2026/04/26/M1_Interface_Specification.html) |
| 5 | Partial Prototype Development | Develop prototype pages satisfying first-round iteration UI requirements. | Enhe Zhang | <span class="status-badge status-done">Completed</span> | [Prototype Intro](https://tnxmy.github.io/DSD2026_TeamM1/2026/04/29/M1_APP_Prototype_Introduction.html) |
| 6 | Prepare Mid-Term Presentation | Create PPT and speak at the meeting. | — | <span class="status-badge status-delayed">Deferred to Next Week</span> | N/A |

---

## 3. Completed Task Briefings

### 3.1 Task 1 — Improve M1 Internal SRS

**Owner:** Wang Yiding

The internal section of the M1 SRS has been thoroughly revised. All internal use cases now cover the technical implementation paths of their corresponding external use cases, and data exchange with external systems (S1, S2, V1, V2, etc.) has been explicitly defined. The actor list was updated to include every group that exchanges data with M1. However, the updated document link has not yet been submitted to the report owner for archiving.

### 3.2 Task 3 — M1 High-Level Design

**Owner:** Diogo Pinhel

The high-level system design for the M1 group has been preliminarily completed. The document includes system block decomposition, module-to-use-case mapping, and data interface definitions between internal modules. The design conforms to the M1 portion of the S2 DFD. The document has been published to the team website and is available for review.

### 3.3 Task 4 — Interface Specification

**Owner:** Enhe Zhang

Based on existing collaboration documents, the interface specification consolidating M1\'s data interfaces with other groups has been preliminarily finalized. Each interface clearly defines data flow direction and payload content. The specification document is now online and will serve as the baseline for subsequent detailed design and implementation.

### 3.4 Task 5 — Partial Prototype Development

**Owner:** Enhe Zhang

The first-round iteration prototype has been fully developed. Implemented modules include:

- **Account Module:** login page, registration page (with validation and secure input), and account home page (avatar, welcome message, logout).
- **Test / Rehab Training Module:** training home page and BLE sensor connection page (with scanning interaction).

The prototype is rendered in English and satisfies the UI requirements for the first iteration. A detailed introduction document with embedded video demonstration has been published.

---

## 4. Incomplete Task Reasons

### 4.1 Task 2 — Integrate Six-Group SRS

**Owner:** Wang Yiding

**Reason:** This task involves standardizing and merging SRS documents from six independent groups, which entails high coordination overhead and dependency on external deliverables. As of the reporting deadline, the M1 and S1 groups have completed their SRS standardization, while other groups are still revising their documents. Full integration is therefore blocked until all groups provide stable versions. The owner will continue tracking each group\'s progress and finalize the integrated document once all inputs are received.

**Mitigation:** The S2 DFD is being used as the authoritative reference for resolving cross-group data-flow conflicts during integration.

### 4.2 Task 6 — Prepare Mid-Term Presentation

**Owner:** Unassigned

**Reason:** The mid-term meeting schedule was adjusted by Professor Zhang. Consequently, the presentation preparation task has been officially deferred to Week 2. No owner was assigned for this task in Week 1, and work will commence at the start of the next cycle.

---

## 5. Next Week Plan (Week 2 Preview)

| Priority | Task | Target Owner | Notes |
|:---|:---|:---|:---|
| High | Finalize six-group SRS integration | Wang Yiding | Await remaining group submissions; resolve conflicts using S2 DFD. |
| High | Prepare mid-term presentation PPT | TBD | Include project overview, requirements, system design, prototype demo, future plan. |
| Medium | Review and finalize high-level design | Diogo Pinhel | Incorporate feedback from Professor Zhang and other groups. |
| Medium | Refine interface specification | Enhe Zhang | Finalize details after confirming collaboration feasibility with each group. |
| Low | Continue prototype development | Enhe Zhang | Expand Main and Record modules; connect Account module to backend (V2). |

---

*Report compiled according to Weekly Report Rules v0.1.*
*Submission Date: April 29, 2026*

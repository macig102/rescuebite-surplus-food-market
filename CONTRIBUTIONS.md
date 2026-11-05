# 👥 Team 13 - Sprint 1 Individual Contributions

This document outlines the individual contributions, GitHub tracking history, and official BM321 rubric responsibilities of each team member for the SENG 321 Sprint 1 deliverable.

---

### 1. Zeynep Bozdemir (230203005)
* **GitHub Username:** `zeynepbozdemirrr`
* **Project Role:** Product Owner and Requirements Engineer
* **Primary Responsibilities & Contributions:**
  * Led requirements engineering and established the product vision for transparent surplus food listings.
  * Authored the Project Proposal, including problem evidence (UNEP and Turkey food waste statistics), stakeholder definitions, transparent listing solution, and risk mitigations.
  * Established the Epic > Feature > Story > Task hierarchy for the Product Backlog and defined backlog prioritization, Definition of Ready (DoR), and Definition of Done (DoD).
  * Owned requirements and scope definition for Food Waste Rescued Metrics (US-08).
* **Traceability Links:**
  * **GitHub Issue:** [Issue #4 - Project Proposal & Requirements Definition](https://github.com/macig102/rescuebite-surplus-food-market/issues/4)
  * **Pull Request & Commits:** Verified in repository history under `https://github.com/macig102/rescuebite-surplus-food-market` (Branch integration via PR into `develop`).

---

### 2. Mehmet Kocagöz (220201035)
* **GitHub Username:** `mehmetkocagozz`
* **Project Role:** Lead Software Architect and Technical Lead
* **Primary Responsibilities & Contributions:**
  * Designed the System Vision and Context Boundary diagram with external provider trust boundaries.
  * Authored the OpenAPI 3.1.0 Contract (`api/openapi.yaml`) following strict API-first design principles.
  * Engineered the HTTP 409 Conflict concurrency handling strategy for surplus food listing stock limits and courier assignment race conditions.
  * Architected backend schemas and endpoints for Store Approval (US-01), Surplus Food Listing Creation with transparent items (US-02), Order Reservation with concurrency lock (US-04), Store Order Preparation Status Transitions, and Courier Claim (US-06).
* **Traceability Links:**
  * **GitHub Issue:** [Issue #3 - OpenAPI 3.1.0 Contract & System Architecture](https://github.com/macig102/rescuebite-surplus-food-market/issues/3)
  * **Pull Request & Commits:** Verified in repository history under `https://github.com/macig102/rescuebite-surplus-food-market`.

---

### 3. Anıl Güngör (220205003)
* **GitHub Username:** `anlgr`
* **Project Role:** Scrum Master and Agile Process Coach
* **Primary Responsibilities & Contributions:**
  * Managed the Agile sprint cadence, stand-up coordination, and team communication workflows.
  * Established and administered the team GitHub Projects Kanban board tracking Sprint 1 backlog items.
  * Authored the team Roles breakdown and RACI Responsibility Matrix aligned with the official BM321 rubric.
* **Traceability Links:**
  * **GitHub Issue:** [Issue #9 - Agile Sprint Board & RACI Administration](https://github.com/macig102/rescuebite-surplus-food-market/issues/9)
  * **Pull Request & Commits:** Verified in repository history under `https://github.com/macig102/rescuebite-surplus-food-market`.

---

### 4. Tuğçe Ertem (230201047)
* **GitHub Username:** `tugceertem`
* **Project Role:** Quality Assurance and Test Automation Engineer
* **Primary Responsibilities & Contributions:**
  * Formulated rigorous, testable Acceptance Criteria using standard Gherkin Given-When-Then format across all user stories (US-01 through US-08).
  * Defined test scenarios covering boundary conditions, input validation failures (HTTP 400), unapproved merchant restrictions (HTTP 403), and concurrency conflicts (HTTP 409).
  * Formulated Doorstep Dynamic QR Verification (US-07) testing scenarios and failure conditions.
  * Executed the Sprint 1 Quality & Evidence Audit against the course submission checklist.
* **Traceability Links:**
  * **GitHub Issue:** [Issue #6 - Acceptance Criteria & Quality Assurance Audit](https://github.com/macig102/rescuebite-surplus-food-market/issues/6)
  * **Pull Request & Commits:** Verified in repository history under `https://github.com/macig102/rescuebite-surplus-food-market`.

---

### 5. Azra Dostbil (230204031)
* **GitHub Username:** `azradostbil`
* **Project Role:** DevOps and CI/CD Infrastructure Engineer
* **Primary Responsibilities & Contributions:**
  * Established Lightweight Git-Flow branching guidelines, branch protection rulesets, and GitHub Issue and Pull Request templates.
  * Configured GitHub repository governance rules prohibiting direct pushes to `main` and `develop`.
  * Managed Sprint 1 release packaging and version tagging workflow (`v0.1.0-sprint1`).
  * Prepared initial repository infrastructure for future CI/CD pipeline integration.
* **Traceability Links:**
  * **GitHub Issue:** [Issue #5 - Git-Flow Policy, Repository Governance & Templates](

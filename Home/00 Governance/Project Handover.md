# Project Handover

Version: 4.0

Status: Approved

Created: 2026-07-19

Last Updated: YYYY-MM-DD

Owner: Sanātana Dharma Dharohar Project

Related Documents:
- Constitution.md
- Decision Ledger.md
- Project Status.md
- AI Editor.md
- Codex Operating Guide.md

---

# Purpose

**Project Handover** is the operational control document of the **Sanātana Dharma Dharohar** repository.

It serves as the single operational interface between the Repository Owner, the Editorial Assistant, and the Synchronization Assistant.

This document records the current operational state of the repository, identifies the active work, and serves as the operational source of truth for repository synchronization and editorial continuity.

Project Handover.md records operational state only. It complements, but never supersedes, the repository's governance hierarchy.

---
# Operational Authority

Project Handover.md records the current operational state of the repository.

It serves as the operational source of truth for active repository work and session continuity.

Project Handover.md does not supersede the repository governance hierarchy.

When conflicts exist, precedence shall be:

1. Constitution.md
2. Decision Ledger.md
3. Project Status.md
4. Project Handover.md

If inconsistencies are identified, Project Handover.md shall be updated to restore consistency with the governing documents.

---

# Design Principles

The Project Handover follows these principles.

- Maintain the current operational state of the repository.
- Never duplicate governance, methodology, or editorial guidance.
- Record operational state rather than historical discussion.
- Update only information that has changed.
- Remain readable for both humans and AI assistants.
- Require minimal maintenance after each significant working session.
- Serve as the single operational source for repository synchronization.

---

# Roles

The repository operates through clearly defined responsibilities.

The current role assignments are:

- Repository Owner → Human
- Editorial Assistant → ChatGPT
- Synchronization Assistant → Codex

| Role | Responsibility |
|------|----------------|
| Repository Owner | Owns the repository, approves changes, and commits updates. |
| Editorial Assistant | Assists with editorial work, maintains the operational state, and updates this document. |
| Synchronization Assistant | Synchronizes repository artefacts using this document and reports synchronization results. |

---

# AI Operating Documents

The repository defines separate operating guides for each AI role.

| Role | Operating Document |
|------|--------------------|
| Editorial Assistant (ChatGPT) | AI Editor.md |
| Synchronization Assistant (Codex) | Codex Operating Guide.md |

These documents define the responsibilities, permissions, and operating procedures for their respective AI roles.

Project Handover.md defines the current operational state of the repository.

AI operating guides define **how** each AI performs its assigned responsibilities.
---

# Ownership & Permissions

Each participant shall modify only the sections assigned to them.


| Section                           | Editorial Assistant | Synchronization Assistant | Repository Owner |
| --------------------------------- | :-----------------: | :-----------------------: | :--------------: |
| Metadata                          |          R          |             R             |        RW        |
| Current Repository Snapshot       |          RW         |             R             |        RW        |
| Repository Health                 |          RW         |             R             |        RW        |
| Governance Snapshot               |          RW         |             R             |        RW        |
| Deliverables                      |          RW         |             R             |        RW        |
| Current Work Queue                |          RW         |             R             |        RW        |
| Session Delta                     |          RW         |             R             |        RW        |
| Operational Validation Status     |          RW         |             RW            |        RW        |
| Repository Synchronization        |          R          |             RW            |        RW        |
| Repository Quality Review         |          R          |             RW            |        RW        |
| Human Review                      |          R          |             R             |        RW        |

Operational Validation Status may be updated collaboratively by the Editorial Assistant and the Synchronization Assistant as part of the repository operating workflow.

Legend:

- **R** = Read
- **RW** = Read / Write

No participant should modify another participant's reserved sections unless explicitly instructed.

---

# Current Repository Snapshot

| Item | Current State |
|------|---------------|
| Repository Status | Active Development |
| Current Milestone | |
| Current Phase | |
| Current Deliverable | |
| Current Focus | |
| Next Objective | |

---

# Repository Health

| Area | Status |
|------|--------|
| Governance | Stable |
| Editorial | In Progress |
| Synchronization | Current |
| Repository Structure | Healthy |

---

# Governance Snapshot

**Purpose**

Summarize the current governance state without duplicating governance documents.

| Item | Status |
|------|--------|
| Constitution Version | |
| Decision Ledger Version | |
| Governance Status | Stable |
| Governance Changes Since Previous Session | None |

# Deliverables

**Purpose**

Track the operational status of the repository's major deliverables.

| Deliverable | Status | Remarks |
|-------------|--------|---------|
| Governance Framework | Complete | Frozen |
| Editorial Framework | Complete | Frozen |
| Master Candidate List | In Progress | |
| Ādhāra Śilā (आधार शिला) 108 | Pending | |
| Jīvanta Paramparā | Planned | Future milestone |
| Dharma Sāgara | Planned | Future milestone |

---

# Current Work Queue

**Purpose**

Identify the immediate operational priorities of the repository.

## Current

-

## Next

-

## Future

-

## Parking Lot

Ideas, improvements, and future enhancements that should not interrupt the current milestone.

-

---

# Session Delta

**Purpose**

Record the significant operational changes made during the current working session.

### Completed

-

### Decisions

-

### Repository Updates

-

### Next Session

Continue from:

---

# Operational Validation Status

**Purpose**

Confirm the repository's operational readiness following synchronization and before editorial work begins.

| Item | Status |
|------|--------|
| Repository Synchronized | Yes — with warnings |
| Governance Changes Since Handover | Unable to determine — Last Updated is unresolved |
| Quality Review Blocking Issues | Current Repository Snapshot fields and Current Work Queue are blank |
| Current Work Queue Validated | No — no current task is specified |
| Ready for Editorial Work | No — operational direction requires Repository Owner or Editorial Assistant update |

# Repository Synchronization

**Purpose**

Record the outcome of repository synchronization performed using this Project Handover.

| Item | Status |
|------|--------|
| Synchronization Status | Completed with warnings |
| Validation Result | Markdown and Obsidian JSON validation passed; operational readiness, metadata, link, and semantic consistency checks produced the findings below. |
| Synchronization Timestamp | 2026-08-04T18:42:06+02:00 |

### Files Updated

- Project Handover.md (Operational Validation Status, Repository Synchronization, and Repository Quality Review sections only)

### Files Created

-

### Files Removed

-

---
# Repository Quality Review

**Purpose**

Record repository observations identified during synchronization that require human review or future maintenance.

### File Review Required

- Project Handover.md — `Last Updated`, the Current Repository Snapshot, governance versions, and Current Work Queue remain unresolved; `AI Editor.md` does not match the tracked `AI_EDITOR.md` filename.
- Project Status.md — Constitution v1.1 and Master Candidate List completion statements conflict with current files or the handover deliverables.
- Constitution.md, Project Handover.md, Codex Operating Guide.md, AI_EDITOR.md, and Governance README.md — governance hierarchy descriptions are not uniform.
- Ādhāra Śilā 108.md and Master Candidate List.md — section-freeze statements are inconsistent.

### Technical Debt

- Ādhāra Śilā Methodology.md contains metadata only; Research & Citation Policy.md is empty although both are referenced as complete framework documents.
- Bibliography.md, Governance README.md, and Research Journal.md do not implement the governance metadata standard.
- Traditions Taxonomy.md and Candidate Resources Under Review.md are empty and require a retention decision.
- Three example wikilinks in Ādhāra Śilā Editorial Guide.md do not resolve to repository notes.
- .obsidian/workspace.json references obsolete local paths.

### Recommendations

- Have the Repository Owner or Editorial Assistant populate the handover's operational fields and Current Work Queue before editorial work resumes.
- Harmonize governance hierarchy wording and the `AI_EDITOR.md` filename through the governance process.
- Review incomplete and empty framework files, then explicitly retain, complete, archive, or remove them.
- Add unresolved linked notes only when their editorial milestone authorizes creation.
- Review archived AI Context.md and determine its long-term retention policy.

### Warnings

- The handover does not specify the current milestone, phase, deliverable, focus, next objective, governance versions, or work queue; no values were inferred.
- Governance changes since the handover cannot be determined while `Last Updated` remains `YYYY-MM-DD`.
- The Repository Owner's pre-existing changes elsewhere in Project Handover.md were preserved.
- The repository is not ready for editorial work until operational direction and a current work item are supplied.
- No files outside the three assigned handover sections were modified; no governance decisions, editorial changes, architecture changes, file creations, or file removals were introduced.

---

# Human Review

**Purpose**

Confirm that the synchronized repository has been reviewed and accepted.

| Item | Status |
|------|--------|
| Synchronization Reviewed | ☐ |
| Synchronization Accepted | ☐ |
| Repository Committed | ☐ |

### Remarks

-

---

# AI Startup Protocol

**Purpose**

Ensure consistent project continuity across Editorial Assistant sessions.

At the beginning of every new session:

1. Share the latest **Project Handover.md**.

2. Synchronize the repository using the repository operating framework.

   Read:
   - **Project Handover.md**
   - **Codex Operating Guide.md**

   Use **Project Handover.md** as the operational source of truth.

   Perform repository synchronization, repository validation, and repository quality review in accordance with **Codex Operating Guide.md**.

3. Ask:

   **Have any governance documents changed since this Project Handover was generated?**

4. If the answer is **Yes**, review the affected governance documents before continuing.

5. If the answer is **No**, resume work directly from the **Current Work Queue**.

6. Before ending the session, update **Project Handover.md** to reflect the repository's current operational state.

---

# Repository Synchronization Protocol

**Purpose**

Ensure consistent synchronization between the Project Handover and the repository.

When synchronization is requested:

1. Read **Project Handover.md**.
2. Synchronize repository artefacts with the operational state described in this document.
3. Do not introduce new governance decisions.
4. Do not modify governance documents unless explicitly instructed.
5. Update only the sections explicitly assigned to the Synchronization Assistant within this document.
6. Report inconsistencies instead of making assumptions.

---

# Repository Owner Workflow

**Purpose**

Define the standard operating workflow for maintaining the repository.

## Start of Session

1. Start a new Editorial Assistant session.
2. Share the latest **Project Handover.md**.
3. Request repository synchronization using the repository operating framework.
4. Review the synchronization results and repository validation summary.
5. Confirm whether any governance documents have changed since the current **Project Handover.md** was generated.
6. If governance documents have changed, review and synchronize them before continuing.
7. If no governance documents have changed, continue directly from the **Current Work Queue**.

## End of Session

1. Ask the Editorial Assistant to update **Project Handover.md**.
2. Replace the existing handover within the repository.
3. Run the Synchronization Assistant using the updated handover.
4. Review the synchronization and repository quality review results.
5. Resolve any blocking issues identified during synchronization.
6. Commit the approved repository changes.

---

# Repository Audit

**Purpose**

Periodically verify that the repository remains organized, synchronized, and aligned with the current architecture.

Audit Checklist

Periodically confirm that:

- Governance documents are synchronized.
- Repository structure remains organized.
- Operational documents remain current.
- Obsolete documents have been removed or archived.
- Deliverables accurately reflect repository progress.
- Project Handover remains consistent with the repository.

---

# Revision History

| Version | Date | Summary |
|----------|------|---------|
| 4.0 RC1 | 2026-08-01 | Initial release candidate establishing Project Handover as the repository's operational control document and synchronization interface. |
| 4.0 RC2 | 2026-08-02 | Clarified operational authority, introduced Operational Validation Status, aligned startup workflow with Codex synchronization, expanded permissions, and refined repository operating procedures. |
| 4.0     | 2026-08-04 | Approved operational control document. Clarified operational authority, introduced Operational Validation Status, aligned startup workflow with Codex synchronization, expanded permissions, and refined repository operating procedures. |

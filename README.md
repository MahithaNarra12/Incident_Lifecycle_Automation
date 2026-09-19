# Incident Lifecycle Automation in ServiceNow

## Project Overview

**Incident Lifecycle Automation in ServiceNow** is a ServiceNow-based project designed to standardize and manage the complete incident management lifecycle.

The project addresses common incident management challenges such as inconsistent incident recording and classification, unclear ownership, delayed escalation, limited SLA visibility, manual coordination, and difficulty in tracking related records.

The solution provides a structured workflow from **service setup and incident creation to classification, knowledge assistance, assignment, Level 2 investigation, change management, child incident handling, resolution, knowledge reuse, and final validation**.

The project was implemented and validated using a **ServiceNow Personal Developer Instance (PDI)** and **Service Operations Workspace**.

---

## Objectives

- Standardize the incident management lifecycle.
- Improve incident classification and assignment.
- Support knowledge-based incident resolution.
- Enable reassignment and escalation to Level 2 Support.
- Track SLA and incident activity.
- Link incidents with related change requests and child incidents.
- Improve documentation of probable cause and resolution.
- Create reusable knowledge articles from resolved incidents.
- Improve visibility and coordination among support teams.
- Validate the complete incident lifecycle through structured testing.

---

## Key Stakeholders

- **End Users** – Report incidents and provide issue details.
- **Service Desk Agents** – Create, classify, assign, and manage incidents.
- **Level 2 Support** – Investigate and resolve escalated incidents.
- **Change Management Team** – Handle changes required for incident resolution.
- **ServiceNow Administrator** – Configure and maintain the ServiceNow environment.

---

## Project Scope

The project covers the following major activities:

1. Service and Service Offering setup
2. Incident creation
3. Incident classification
4. Knowledge and Agent Assist
5. Assignment and reassignment
6. Level 2 investigation and resolution
7. SLA and activity tracking
8. Emergency change creation
9. Child incident creation
10. Incident resolution and closure
11. Knowledge article creation
12. Related-record validation
13. User Acceptance Testing
14. Functional and performance/usability validation
15. Final project validation and documentation

---

# Project Phases

## Phase 1 – Ideation

The Ideation phase focused on understanding the incident management problem and identifying the major challenges faced by support teams.

### Activities

- Brainstorming and idea prioritization
- Problem statement definition
- Empathy and stakeholder analysis

### Key Problems Identified

- Inconsistent incident recording
- Incorrect or incomplete classification
- Unclear incident ownership
- Delayed escalation
- Limited SLA visibility
- Manual coordination between support teams
- Difficulty tracking related incidents and changes
- Repeated resolution effort due to limited knowledge reuse

### Outcome

A clear problem definition was established for developing an **Incident Lifecycle Automation in ServiceNow** solution.

---

## Phase 2 – Requirement Analysis

The Requirement Analysis phase converted the identified problems into functional and system requirements.

### Activities

- Customer Journey Mapping
- User Stories
- Data Flow Diagram
- Solution Requirements
- Technology Stack and Architecture

### Major Requirements

The system should support:

- Incident creation
- Incident classification
- Service and Service Offering selection
- Knowledge assistance
- Assignment to appropriate support groups
- Level 2 escalation
- SLA tracking
- Emergency changes
- Child incidents
- Incident resolution
- Knowledge article creation
- Related-record tracking
- End-to-end lifecycle validation

### Outcome

The project requirements and expected ServiceNow workflow were clearly defined.

---

## Phase 3 – Project Design

The Project Design phase converted the requirements into a structured solution.

### Activities

- Problem–Solution Fit
- Proposed Solution
- Solution Architecture

### Designed Solution

The proposed solution follows a structured incident lifecycle:

**Incident Creation → Classification → Knowledge Assistance → Assignment → Investigation → Escalation/Change → Resolution → Knowledge Reuse → Final Validation**

The design also establishes relationships between:

- Incidents
- Child incidents
- Change requests
- Task SLAs
- Knowledge articles
- Support groups

### Outcome

A complete solution architecture and implementation approach were established.

---

## Phase 4 – Project Planning & Scheduling

The project implementation was organized into four sprints.

| Sprint | Period | Main Activities | Story Points |
|---|---|---|---:|
| Sprint 1 | 17–22 Aug 2026 | Service setup, incident creation, classification, activity/SLA | 11 |
| Sprint 2 | 24–29 Aug 2026 | Knowledge, assignment, Level 2 investigation, SLA tracking | 13 |
| Sprint 3 | 31 Aug–05 Sep 2026 | Emergency change, child incidents, resolution, related records | 13 |
| Sprint 4 | 07–12 Sep 2026 | Knowledge article, lifecycle validation, testing, final validation | 14 |
| **Total** | | | **51** |

**Average project velocity:** 12.75 story points per sprint.

### Outcome

The complete implementation was planned and completed through four structured sprints.

---
---

## Phase 5 – User Acceptance Testing

The User Acceptance Testing (UAT) phase verified whether the completed ServiceNow workflow met the defined project requirements and expected user workflow.

### Testing Period

**13–15 September 2026**

### UAT Summary

| **Testing Item** | **Result** |
|---|---:|
| Test Cases | 14 |
| Passed | 14 |
| Failed | 0 |
| Not Tested | 0 |
| UAT Defects Recorded | 0 |

### UAT Coverage

- Incident creation and classification
- Knowledge / Agent Assist
- Assignment and reassignment
- Level 2 investigation
- SLA and activity tracking
- Emergency change
- Child incident
- Incident resolution
- Knowledge article creation
- Related-record validation
- Complete incident lifecycle

### Outcome

All documented UAT test cases were successfully completed with no failed test cases.

---

## Phase 6 – Project Documentation

The Project Documentation phase consolidated the complete **Incident Lifecycle Automation in ServiceNow** project, including the requirements, design, planning, implementation workflow, testing, results, and final validation.

### Documentation Includes

- Project Overview and Objectives
- Ideation and Problem Analysis
- Requirement Analysis
- Customer Journey Map and User Stories
- Data Flow Diagram
- Technology Stack
- Problem–Solution Fit
- Proposed Solution
- Solution Architecture
- Project Planning and Scheduling
- Implemented ServiceNow Workflow
- User Acceptance Testing
- Functional and Performance/Usability Testing
- Results and Final Validation
- Advantages and Limitations
- Conclusion and Future Scope

### Outcome

A complete project documentation set was prepared covering all phases of the project from ideation to final testing and validation.

---

## Phase 7 – Project Demonstration

The Project Demonstration phase presents the completed **Incident Lifecycle Automation in ServiceNow** and demonstrates the implemented workflow in the ServiceNow environment.

### Demonstration Covers

- Service and Service Offering setup
- Incident creation
- Incident classification
- Knowledge / Agent Assist
- Assignment and Level 2 investigation
- SLA and activity tracking
- Emergency change
- Child incident
- Incident resolution
- Knowledge article creation
- Related records
- Final lifecycle validation

### Demonstration Workflow

**Service Setup → Incident Creation → Classification → Knowledge Assistance → Assignment → Level 2 Investigation → Change / Child Incident → Resolution → Knowledge Article → SLA & Related Records → Final Validation**

### Outcome

The completed ServiceNow project and its end-to-end incident management workflow are demonstrated using the implemented project configuration and workflow.

---

# Final Project Workflow

The complete project follows the following progression:

**Ideation → Requirement Analysis → Project Design → Project Planning → Implementation → User Acceptance Testing → Project Documentation → Project Demonstration**

### ServiceNow Incident Lifecycle

**Service Setup → Incident Creation → Classification → Knowledge Assistance → Assignment → Level 2 Investigation → Emergency Change / Child Incident → Resolution → Knowledge Article Creation → SLA & Related Records → Final Validation**

---

# Project Structure

```text
Incident_Lifecycle_Automation/
│
├── README.md
│
├── Phase-1-Ideation/
│
├── Phase-2-Requirement-Analysis/
│
├── Phase-3-Project-Design/
│
├── Phase-4-Project-Planning/
│
├── Phase-5-User-Acceptance-Testing/
│
├── Phase-6-Project-Documentation/
│
└── Phase-7-Project-Demonstration/

# Implemented ServiceNow Workflow

The following workflow represents the actual implementation of the project.

```text
Service & Service Offering Setup
              ↓
       Incident Creation
              ↓
     Incident Classification
              ↓
    Knowledge / Agent Assist
              ↓
     Assignment to Service Desk
              ↓
       Level 2 Investigation
              ↓
     ┌────────┴─────────┐
     ↓                  ↓
Normal Resolution   Emergency Change
                        ↓
              On Hold – Awaiting Change
     └────────┬─────────┘
              ↓
       Child Incident
              ↓
      Cause & Resolution
        Documentation
              ↓
       Incident Resolution
              ↓
     Knowledge Article
         Creation
              ↓
      Related Records &
        SLA Validation
              ↓
       Final Validation

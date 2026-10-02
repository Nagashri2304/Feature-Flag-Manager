## GitHub Repository

[Feature Flag & Dynamic Config Manager](https://github.com/Nagashri2304/Feature-Flag-Manager)

# Feature Flag & Dynamic Config Manager

**Problem Statement:** #43\
**Submission:** Individual Software Engineering Project

## 1. Project Overview

The Feature Flag & Dynamic Config Manager is a proposed centralized
platform for managing feature flags and dynamic application
configuration. It is intended to support user targeting,
percentage-based rollouts, environment-specific overrides, and
synchronization with connected client SDKs.

This repository currently contains the requirements and planning/design
documentation for the project. It should not be interpreted as evidence
that the platform has been implemented or tested.

## 2. Project Scope

The proposed system covers:

-   Creating, viewing, updating, and deactivating uniquely identified
    feature flags.
-   Evaluating targeting rules and returning boolean flag states.
-   Configuring percentage-based rollouts for selected cohorts.
-   Managing independent Development, Testing, and Production overrides.
-   Synchronizing configuration updates with connected client SDKs.
-   Restricting management operations to authenticated and authorized
    users.

## 3. Requirements

The requirements workbook contains five functional requirements (FR-001
to FR-005), two non-functional requirements (NFR-001 and NFR-002),
acceptance criteria, and a Requirements Traceability Matrix (RTM).

See `01_RE/Requirements_Table_and_RTM.xlsx`.

## 4. Repository Structure

``` text
MyProject_FeatureFlagManager/
├── README.md
├── 01_RE/
│   └── Requirements_Table_and_RTM.xlsx
├── 02_Architectural_Diagram/
│   ├── Feature_Flag_Manager_Use_Case_Diagram.drawio
│   └── Use_Case_Diagram.pdf
├── 03_Project_Creation_Screenshots/
│   ├── GitHub_Repository.png
│   └── Jira_Project.png
├── 04_SRS_and_WBS/
│   ├── UC03_Evaluate_Feature_Flag_Flow.docx
│   ├── Use_Case_Flow.pdf
│   ├── Feature_Flag_Manager_SRS.docx
│   ├── SRS.pdf
│   ├── Feature_Flag_Manager_WBS.docx
│   └── WBS.pdf
├── 05_GitHub_Copilot/
│   └── Copilot_Evidence.png
└── 06_Software_Testing_Tools/
    ├── Testing_Report.pdf
    └── Fixed_Game_Repository_Link.txt
```

*The tree shows the intended organization. Add the listed evidence files
only when you have actually created or received them; do not leave
placeholder files that imply evidence exists.*

## 5. Use Cases

The use-case model includes:

-   UC-01 Manage Feature Flags
-   UC-02 Configure Targeting Rules
-   UC-03 Evaluate Feature Flag
-   UC-04 Configure Percentage Rollout
-   UC-05 Manage Environment Overrides
-   UC-06 Synchronize Client SDK
-   UC-07 Monitor Rollout

Supporting use cases: Validate Targeting Rules and Roll Back Rollout.

## 6. Performance and Security

-   **NFR-001:** Feature-flag evaluation API target is under 15 ms.
    Benchmark conditions need to be defined and verified.
-   **NFR-002:** Management operations are restricted to authenticated
    users with appropriate permissions.

The detailed requirements and acceptance criteria are maintained in the
workbook.

## 7. Current Status

**Prepared documentation:** - Requirements and RTM workbook - UML
use-case diagram (editable source and PDF) - UC-03 use-case flow (DOCX
and PDF) - SRS (DOCX and PDF) - WBS (DOCX and PDF)

**Still to verify or complete:** - Add genuine GitHub and Jira
project-creation screenshots. - Add genuine GitHub Copilot evidence, if
required and used. - Complete the separate software-testing-tools
activity when the instructor provides the game repository and its four
test cases. - Review all files and confirm the final repository contents
before submission.

## 8. Notes

This is a requirements, analysis, and planning repository for the
proposed system. Implementation details, technology choices, benchmark
setup, authorization roles, and SDK synchronization interval remain to
be finalized during design.

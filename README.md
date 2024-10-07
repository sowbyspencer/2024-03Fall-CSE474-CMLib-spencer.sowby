# Configuration Management (CM) Library

## Purpose

This repository serves as the **Configuration Management (CM) Library** for tracking and managing **Configuration Items (CIs)** throughout the semester. The CM Library will store and organize all artifacts related to both the product and the project that need to be controlled to ensure proper delivery of the final product.

## Background

A **Configuration Item (CI)** is any artifact that needs its state controlled to deliver the final product. This includes both **Product Library** items (like source code and scripts) and **Project Library** items (like policies, plans, and reports). Each CI must have a unique identifier and be tracked for changes over time.

The CM Library for this course will consist of two main components:

- **Product Library**: For product-related items.
- **Project Library**: For project-related items.

## Configuration Management Structure

### 1. Product Library

Contains configuration items related to the product itself. These may include:

- **Source Code**: The codebase for the product.
- **Setup**: Scripts and instructions for setting up the product environment.
- **3rd Party**: Dependencies, tools, or libraries used in the product.
- **Deliveries**: Finalized versions of the product for release.

### 2. Project Library

Contains configuration items related to project management and processes. These may include:

- **Project Documents**: Policies, plans, and procedures necessary for project management.
- **System Engineering**: Documents or artifacts related to system design and engineering.
- **Software Engineering**: Development-related artifacts, such as design and implementation documents.
- **Reports**: Audit logs, meeting minutes, defect reports, and other project-related data.

## Managing Configuration Items

- **Product Library** items (like new code or updated configurations) are tracked using version control (e.g., Git).
- **Project Library** items (like reports or minutes) are versioned using unique identifiers (UIDs) and stored in a hierarchical structure.

### Example CI UIDs:

- `UID.TPD.003.R.20230212-01`: New Project CI with a version or date identifier.
- `UID.TPD.003.R.001 → UID.TPD.003.R.002`: Updated Project CI with incremented revision numbers.

Older versions of CIs will be archived in subdirectories for both libraries.

## Required Folder Structure

Your CM repository should follow this basic structure:

```
CM Repo/
├── readme.md
├── Product Library/
│ ├── 3rd Party/
| ├── Deliveries/
│ ├── Reports/
│ ├── Setup/
│ └── Source Code/
└── Project Library/
| ├── Project Documents/
│ ├── Reports/
| ├── Software Engineering/
│ └── System Engineering/
```

---

OpenAI, README.md "Document generated with help of ChatGPT," ChatGPT, https://chatgpt.com/share/66fc781b-72b4-8001-8eae-5cf3e2e53048 (accessed Oct. 1, 2024).

# 2024 - 2025 Bubble Intermarché Project - Team 8 | Management Artifacts

This document aims to centralize the management artifacts links and resources listed below:

- [2024 - 2025 Bubble Intermarché Project - Team 8 | Management Artifacts](#2024---2025-bubble-intermarché-project---team-8--management-artifacts)
  - [Tasks and Schedule](#tasks-and-schedule)
  - [RACI Matrix](#raci-matrix)
  - [Risks \& Assumptions](#risks--assumptions)
  - [Key Performance Indicators](#key-performance-indicators)
    - [KPIs definition](#kpis-definition)
      - [Documents](#documents)
      - [Design](#design)
      - [Development](#development)
      - [Mood](#mood)
    - [Link to the project's KPIs](#link-to-the-projects-kpis)
  - [Weekly Reports](#weekly-reports)
  - [Post Mortem Analysis](#post-mortem-analysis)

## Tasks and Schedule

You can view the breakdown of all the tasks we've identified for this project following [this link](TO ADD).

## RACI Matrix

The RACI matrix of this project is as follows considering the [Project Charter](./project_charter.md):

| Name                     | Project Manager | Program Manager | Technical Leader | Software engineer | Quality assurance | Client | Stakeholders |
| ------------------------ | --------------- | --------------- | ---------------- | ----------------- | ----------------- | ------ | ------------ |
| Project kick-off         | I               | I               | I                | I                 | I                 | I      | R            | C |
| Project charter          | R               | A               | C                | C                 | C                 | I      | I            |
| Schedule creation        | R               | C               | C                | C                 | C                 | /      | I            |
| Functional specification | A               | R               | C                |                   | /                 | C      | I            |
| Technical specification  | A               | C               | R/A              | I                 | /                 | C      | I            |
| Coding process           | A               | I               | R                | R/A               | /                 | /      | /            |
| Testing planification    | A               | /               | C                | C                 | R/A               | /      | /            |
| Usage instructions       | A               | C               | C                | C                 | I                 | R/ I   | I            |

Legend:

| Letter | Full name   | Description                                     |
| ------ | ----------- | ----------------------------------------------- |
| R      | Responsible | Executes the task or activity                   |
| A      | Accountant  | Ultimately answerable for the task's completion |
| C      | Consulted   | Provides input and/or advice on the task        |
| I      | Informed    | Kept updated on progress and decisions          |
| /      | /           | No interaction with this role for this task     |

## Risks & Assumptions

| ID  | Description                                                                   | Consequence                                                       | Impact   | Likelihood | Mitigation/Avoidance                                                                |
| --- | ----------------------------------------------------------------------------- | ----------------------------------------------------------------- | -------- | ---------- | ----------------------------------------------------------------------------------- |
| 1   | Bubble is a tool to which we are not yet used.                           | Development pace might be hindered                                | High     | Medium     | Ask for help to the other team members                                              |
| 2   | The client might want to change /add requirements                             | We might need to change how the solution is developed             | Medium   | Low        | Validate every step of the project with the client, to ensure the solution fits him |
| 3   | We might create a clone of an already existing solution and infringe a patent | The client couldn't develop their solution based on our prototype | High     | Low        | Check for any patent and find our unique selling point (USP)                        |
| 4   | Misinterpretation of the project                                              | Incorrect implementation of the software                          | Critical | Medium     | Regular communication with the client to understand their needs, and stick to them. |
| 5   | Team member leaving                                                           | Tasks left to the remaining members without any assignee          | High     | Unlikely   | Sharing the tasks among the remaining team members.                                 |

## Key Performance Indicators

### KPIs definition

To enable the client to track our project's milestones, we have defined several quantitatively measurable KPIs. Below is a list of these KPIs along with their respective calculations.

#### Documents

The following KPIs are included in this section:

- **Functional specifications**
- **Technical specifications**
- **Test Plan**
- **User Manual**

The progress of these documents is measured using the following formula:

$$\text{percentage} = (\frac{\text{current number of sections}} {\text{total number of sections}})\times{100}$$

Where:

- **current_number_of_sections**: The number of sections that are completely done.
- **total_number_of_sections**: The number of predefined sections in the document's outline, which may evolve.

#### Design

The KPIs in this section include:

- **Mock-ups**
- **User journey roadmap**

The percentage progress for these KPIs is calculated using this formula:

$$\text{percentage} = (\frac{\text{current number of designed pages}} {\text{total number of pages to design}})\times{100}$$

Where:

- **current_number_of_pages_designed**: The number of pages that have been prototyped.
- **total_number_of_pages_to_design**: The total number of pages planned to be designed during the project analysis.

#### Development

This section tracks the following KPIs:

- **Recommendations interfaces**
- **Products interfaces**
- **Data Collection and Filtering Workflows**

Given the complexity and time required for development, we include progress on partially completed pages and features. The progress is calculated using:

$$\text{percentage} = (\frac{({\text{current number of fully coded pages + sum percentages unfinished pages + current number of fully coded workflows + sum percentages unfinished workflows}})} {\text{total designed pages + total defined workflows }})\times{100}$$

Where:

- **current_number_of_fully_coded_pages**: The number of pages that are fully completed.
- **sum_percentage_unfinished_pages**: The cumulative progress of each unfinished page, with progress for each page ranging from 0 to 1.
- **current_number_of_fully_coded_workflows**: The number of workflows that are fully created and functional.
- **sum_percentage_unfinished_workflows**: The cumulative progress of each unfinished page, with progress for each page ranging from 0 to 1.
- **total_designed_pages**: The total number of pages defined during project analysis and design.
- **total_defined_worflows**: The total number of workflows that have been planned during the technical analysis of the project.

#### Mood

The mood percentage is calculated by averaging the weekly grades out of 10 given by each team member. These grades reflect their overall motivation and well-being from a personal perspective, as well as considering the project's milestones and challenges.

---

By utilizing these formulas, we ensure that our progress tracking is clear and consistent, and provides a realistic view of our project's status to the client. For readibility and a better understanding, the KPIs are rounded to the nearest 5%

### Link to the project's KPIs

You can see our project's KPIs which were explained above following [this link]([TO ADD](https://docs.google.com/spreadsheets/d/1lBZwk-SWxh1hNyLRs3QKEs8n5GIxAUGOkLfxDRUiAaw/edit?usp=sharing)).

## Weekly Reports

he weekly reports folder can be found following [this link](/documents/management/weekly_reports/).

You can directly access the reports individually following the below bullet points:

- [Access Report for Week 1](/documents/management/weekly_reports/week1.md)
- [Access Report for Week 2](/documents/management/weekly_reports/week2.md)
- [Access Report for Week 3](/documents/management/weekly_reports/week3.md)
- [Access Report for Week 4](/documents/management/weekly_reports/week4.md)
- [Access Report for Week 5](/documents/management/weekly_reports/week5.md)
- [Access Report for Week 6](/documents/management/weekly_reports/week6.md)
- [Access Report for Week 7](/documents/management/weekly_reports/week7.md)
- [Access Report for Week 8](/documents/management/weekly_reports/week8.md)
- [Access Report for Week 9](/documents/management/weekly_reports/week9.md)

For a centralized collection of copies of all the reports in a single document, please refer to the Cumulative File for Weekly Reports:

- [Access Cumulative file for all 6 weeks](/documents/management/weekly_reports/cumulative.md)

## Post Mortem Analysis

This section's content will be added by the end of the project.
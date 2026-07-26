# The Big Project Deliverable 1: Project Proposal & Planning

## Overview

The purpose of this deliverable is to establish the foundation for your Big Project.

Your team should demonstrate that you have identified a meaningful civil or mineral engineering problem, considered appropriate real-world data sources, and developed a preliminary plan for using data science methods to investigate the problem.

This deliverable should answer:

* What engineering problem are you investigating?
* Why is this problem important?
* What data will you use?
* How will you prepare and analyze the data?
* How will you evaluate your results?
* How will your team organize the project?

Your project direction may change as you learn more about the problem and available data. The goal of this deliverable is to develop a thoughtful and realistic initial plan.

---

# Proposal Requirements

## 1. Project Overview

Provide a brief description of your project.

Discuss:

* What engineering problem are you investigating?
* Why is this problem important?
* What motivates this project?
* What is the overall goal of your analysis?

Focus on explaining the engineering problem before describing technical methods.

---

## 2. Research Questions and Objectives

Define the questions your project aims to answer.

Your research questions should guide your data collection and analysis.

Discuss:

* Primary research question
* Secondary questions (if applicable)
* Expected outcomes or insights from the analysis

Examples:

* What factors influence ___?
* Can available data help understand or predict ___?
* How can data analysis improve understanding of ___?

---

## 3. Background and Related Work

Provide relevant background information about your project.

Discuss previous work related to your problem, such as:

* Research studies
* Engineering reports
* Existing tools or applications
* Similar data-driven approaches

Explain how your project relates to existing work and what gap or opportunity your project addresses.

Include at least 3 relevant references.

---

## 4. Stakeholders and Engineering Impact

Identify stakeholders who may use, benefit from, or be affected by your project.

Examples:

* Engineers
* Government agencies
* Construction companies
* Mining operators
* Environmental organizations
* Researchers
* Public users

Discuss:

* Who may benefit from your findings?
* What engineering decisions could your analysis support?
* What value can your project provide?

---

## 5. Dataset Description and Feasibility

Describe the real-world datasets you plan to use for your project.

Your team should work with real-world engineering data rather than only using clean, pre-processed datasets created for educational purposes.

Real engineering datasets often require preparation before analysis, including:

* Data cleaning
* Data transformation
* Data validation
* Data integration

Describe your selected dataset(s) and discuss relevant information such as:

* Dataset name and source
* How the data was collected or obtained
* Type of data (examples: sensor measurements, monitoring data, operational records, public databases, remote sensing data, surveys, APIs, or other sources)
* Important variables or information contained in the data
* Geographic or temporal coverage (if applicable)
* Why the dataset is appropriate for your research question

Discuss potential challenges, such as:

* Missing values
* Data quality issues
* Inconsistent formats
* Need for preprocessing or transformation
* Combining information from multiple sources
* Limitations of available data

The goal is to demonstrate that your team understands what data is required, where it comes from, and how it may need to be prepared before analysis.

---

## 6. Data Science Approach

Describe your planned approach for transforming data into meaningful engineering insights.

Your approach may include:

* Data collection and integration
* Data cleaning and preprocessing
* Exploratory data analysis
* Data visualization
* Statistical analysis
* Feature engineering
* Machine learning or other analytical methods

Explain why your selected approach is suitable for your engineering problem.

Machine learning is not required. Projects may focus on:

* Data analysis
* Visualization
* Identifying patterns
* Understanding relationships
* Developing engineering insights

If machine learning is considered, discuss:

* Why machine learning is appropriate for your problem
* Possible models or approaches you may explore
* Expected inputs and outputs
* How you plan to assess model performance

The goal is not to select the most complex method, but to justify why your analytical approach is appropriate.

---

## 7. Evaluation and Success Criteria

Explain how you will determine whether your project is successful.

Your evaluation approach should match the objectives of your project.

Possible approaches include:

### Projects involving predictive models

Examples:

* Comparing results with baseline methods
* Measuring prediction performance
* Evaluating reliability and limitations of the model

### Projects focused on data analysis

Examples:

* Ability to answer research questions
* Quality of engineering insights
* Identification of meaningful patterns
* Usefulness of visualizations or analysis results

Other evaluation methods may be appropriate depending on your project.

Explain why your chosen evaluation approach is meaningful.

---

## 8. Project Plan and Team Organization

Describe how your team will organize the project.

Discuss:

* Division of responsibilities
* Major project tasks
* Expected timeline
* Meeting schedule
* Communication methods

Explain how responsibilities will be distributed among team members.

---

## 9. Supporting Diagrams and Visualizations

Supporting materials are optional but strongly recommended.

Examples:

* Data science workflow diagram
* Data pipeline diagram
* System or architecture diagram
* Conceptual diagrams
* Preliminary visualizations

These materials should help communicate your project idea and planned approach.

---

## 10. Risks and Mitigation

Identify possible risks that may affect your project.

Examples:

| Risk                    | Impact                                | Mitigation                                          |
| ----------------------- | ------------------------------------- | --------------------------------------------------- |
| Dataset unavailable     | Analysis cannot proceed               | Identify alternative data sources                   |
| Poor data quality       | Results may be unreliable             | Apply additional validation and preprocessing       |
| Project scope too large | Difficult to complete within timeline | Prioritize research questions and adjust objectives |

Discuss how your team plans to manage these risks.

---

# Submission Requirements

All work for this deliverable must be completed and maintained in your team's GitHub repository.

The GitHub repository is the official project workspace throughout the course.

Submit your GitHub repository link on Quercus. The teaching team will review Deliverable 1 directly from your repository.

Your repository should contain:

```
deliverables/
└── deliverable-1/
    ├── proposal.md
    ├── workflow-diagram.png
    ├── architecture-diagram.png
    ├── figures/
    └── other supporting files
```

The `proposal.md` file should contain the main Deliverable 1 document.

Supporting materials, such as:

* diagrams
* figures
* tables
* additional documents

should also be stored inside the `deliverable-1` folder.

After completing Deliverable 1, teams are strongly encouraged to create a Git tag or GitHub Release:

```
D1
```

This creates a snapshot of the repository at the submission point and allows the teaching team to easily review the exact version submitted for Deliverable 1.

Only one team member should submit the GitHub repository link on behalf of the group.

---

# Late Submission Policy

A 2-hour grace period is provided after the deadline without penalty.

After the grace period, submissions will receive a 25% deduction of the earned Deliverable 1 mark for each additional 24-hour period (or part thereof).

Since this is a group submission, teams are encouraged to submit early and ensure all members have access to the repository before the deadline.

If your team experiences a significant issue preventing submission, contact the instructor as soon as possible. Extensions will only be considered for exceptional circumstances.

---

# Deliverable 1 Rubric (5%)

| Component                                    | Weight |
| -------------------------------------------- | -----: |
| Problem Definition and Motivation            |   1.0% |
| Research Questions and Objectives            |  0.75% |
| Background, Related Work, and Stakeholders   |  0.75% |
| Dataset Description and Feasibility          |   1.0% |
| Data Science Approach and Evaluation Plan    |   1.0% |
| Project Planning, Risks, and Overall Quality |   0.5% |
| **Total**                                    | **5%** |

---

# Performance Expectations

## 100% – Excellent

Exceeds expectations.

* Responses are clear, complete, and well organized.
* The team demonstrates thoughtful analysis and strong justification.
* Supporting figures, tables, diagrams, or references are used effectively where appropriate.

## 80% – Good

Meets expectations.

* All required components are addressed.
* Explanations are clear with reasonable justification.
* Minor omissions or areas for improvement may exist.

## 70% – Satisfactory

Meets most expectations.

* Main ideas are present.
* Some sections lack sufficient detail, justification, or clarity.
* One major item or several minor items may be incomplete.

## 60% – Needs Improvement

Partially meets expectations.

* Multiple required components are incomplete, unclear, or insufficiently justified.
* Organization or presentation may make the proposal difficult to follow.

## 50% – Minimal

Limited evidence of meeting requirements.

* Responses are superficial, incomplete, or lack meaningful analysis.
* Significant portions of the proposal are missing or underdeveloped.

## 0% – Missing

No submission, or the submitted work contains little or no meaningful content relevant to the deliverable.

# QA Documentation Framework
[![Status](https://img.shields.io/badge/status-active-brightgreen)]()
[![QA Documentation](https://img.shields.io/badge/QA-documentation-blue)]()
[![Artifacts](https://img.shields.io/badge/artifacts-checklists%20%7C%20test%20cases%20%7C%20bugs-orange)]() [![ISTQB](https://img.shields.io/badge/testing-ISTQB%20inspired-lightgrey)]() 

> **Note:** This repository demonstrates a structured QA workflow for a demo e-commerce application [Swag Labs](https://www.saucedemo.com/) \, including requirements, test cases, bug reports, regression testing and test evidence.

## Overview
This repository demonstrates how QA artifacts can be connected into one structured testing workflow:
```text
Requirements → Test Cases → Checklists → Bug Reports → Evidence → Traceability
```

## Repository Structure

```text
qa-test-documentation-framework/
├── README.md
├── requirements.md
├── traceability-matrix.md
│
├── templates/
│   ├── test-design-techniques/
│   ├── test-case-template.md
│   ├── checklist-template.md
│   ├── bug-report-template.md
│   ├── defect-life-cycle-example.md
│   ├── severity-vs-priority.md
│   └── bug-status-workflow.md
│
└── tests/
    ├── test-cases/
    ├── checklists/
    ├── bug-reports/
    ├── exploratory-testing/
    ├── regression-testing/
    ├── test-data/
    └── evidence/
```

## What’s Inside

- **[requirements.md](requirements.md)** -  functional requirements and testing scope for Swag Labs.
- **[traceability-matrix.md](traceability-matrix.md)** - a mapping between functional requirements, related test cases and test coverage.
- **[templates](templates)** - reusable QA templates, testing techniques and QA process documentation, includes: test case template; checklist template; bug report template; defect life cycle; severity vs priority; bug status workflow; test design techniques.
- **[tests/test-cases/](tests/test-cases/)** - functional and technique-based test cases for Swag Labs, covered areas: login; product catalogue; shopping cart; checkout flow; logout; session management.
- **[tests/checklists/](tests/checklists/)** - structured QA checklists for feature validation, covered areas: login page; product catalogue; shopping cart; checkout flow; logout flow; error validation; session management; responsive UI.
- **[tests/bug-reports/](tests/bug-reports/)** - documented bug reports with steps to reproduce, expected result, actual result, severity, priority and evidence.
- **[tests/exploratory-testing/](tests/exploratory-testing/)** - exploratory testing notes and edge-case investigations.
- **[tests/regression-testing/](tests/regression-testing/)** - regression suites for critical functionality.
- **[tests/test-data/](tests/test-data/)** - valid, invalid and boundary test data used during testing.
- **[tests/evidence/](tests/evidence/)** - screenshots and testing evidence supporting reported defects.

## Testing Techniques Used

- Equivalence Partitioning
- Boundary Value Analysis
- Decision Table Testing
- State Transition Testing

## QA Skills Demonstrated

- Functional testing
- Test case design
- Checklist-based testing
- Bug Reporting
- Exploratory testing
- Regression testing
- Test Design Techniques
- Requirements Analysis
- Traceability Matrix

## Author
Created by Mary Pavlenko to document a structured approach to QA testing, test design and defect reporting.

[LinkedIn](https://www.linkedin.com/in/mary-pavlenko/) • [Email](mailto:pavlenkompq@gmail.com)

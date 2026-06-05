# QA Documentation Framework
[![Status](https://img.shields.io/badge/status-active-brightgreen)]()
[![QA Documentation](https://img.shields.io/badge/QA-documentation-blue)]()
[![Artifacts](https://img.shields.io/badge/artifacts-checklists%20%7C%20test%20cases%20%7C%20bugs-orange)]() [![ISTQB](https://img.shields.io/badge/testing-ISTQB%20inspired-lightgrey)]() 

## Overview
This repository is a personal QA documentation framework and knowledge base. \
The goal of this repository is to collect, structure, and continuously enrich examples of high-quality QA documentation, reusable templates, best practices, test design techniques, and practical testing artifacts.

It includes:
- reusable QA templates and reference materials
- examples of QA documents and best-practice artifacts
- practical testing documentation and testing deliverables
- test design techniques and QA process documentation

This repository demonstrates how QA artifacts can be connected into one structured testing workflow:
```text
Requirements → Test Cases → Checklists → Bug Reports → Evidence → Traceability
```

## Repository Structure

```text
qa-test-documentation-framework/
│
├── README.md
│
├── templates/
│   ├── best-practices/
│   ├── document-templates/
│   ├── examples/
│   └── test-design-techniques/
│
└── tests/
    ├── requirements.md
    ├── traceability-matrix.md
    ├── test-data/
    ├── test-cases/
    ├── checklists/
    ├── exploratory-testing/
    ├── regression-testing/
    ├── bug-reports/
    └── evidence/
```

## What’s Inside

**`templates/`** folder contains reusable QA resources, examples, and reference materials.
- **[templates/best-practices/](templates/best-practices/)** - QA process references: defect life cycle, bug status workflow, severity vs priority.
- **[templates/document-templates/](templates/document-templates/)** - reusable templates for bug reports, checklists, test cases, test plans, and traceability matrices.
- **[templates/test-design-techniques/](templates/test-design-techniques/)** - examples of test design techniques: equivalence partitioning, boundary value analysis, decision tables, and state transitions.
- **[templates/examples/](templates/examples/)** - reference QA artifacts: checklists, test cases, test plans, test strategies, test summary reports, user stories, QA metrics, coverage matrices, defect reports, and exploratory testing notes.

**`tests/`** folder contains practical QA artifacts created during testing activities.
- **[tests/requirements.md](requirements.md)** - functional requirements and testing scope.
- **[tests/traceability-matrix.md](traceability-matrix.md)** - mapping between requirements, related test cases, and test coverage.
- **[tests/test-data/](tests/test-data/)** - valid, invalid, and boundary test data.
- **[tests/test-cases/](tests/test-cases/)** - functional and technique-based test cases.
- **[tests/checklists/](tests/checklists/)** - feature validation checklists.
- **[tests/exploratory-testing/](tests/exploratory-testing/)** - exploratory testing notes and findings.
- **[tests/regression-testing/](tests/regression-testing/)** - regression testing suites for critical functionality.
- **[tests/bug-reports/](tests/bug-reports/)** - defect reports with steps, expected/actual results, severity, priority, and evidence.
- **[tests/evidence/](tests/evidence/)** - screenshots, recordings, and supporting materials for reported defects.

## Author
Created by **[Mary Pavlenko](https://www.linkedin.com/in/mary-pavlenko/)** to document a structured approach to QA testing, test design and defect reporting.
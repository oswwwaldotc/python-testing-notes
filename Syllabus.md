# Syllabus

The syllabus is a document that outlines the course content and objectives. It is important to note that the current syllabus is meant to complement the external course content and is not a replacement for it. In other words, it helps students understand the course and what they will learn., it serves as self-learning material for the instructor. The syllabus contains the course structure, key topics, course materials, key concepts, and resources.

## Course Structure Diagram

```mermaid
graph TD
    %% Main Course Flow
    Start[Course Introduction] --> A[Introduction to Software Testing]
    A --> B[Unit Testing]
    A --> C[Integration Testing]
    
    %% Testing Types Flow
    B & C --> D[Mocking and Dependency Injection]
    D --> E[Test Automation]
    E --> F[Test Design Patterns]
    F --> G[Test Management]
    
    %% Key Concepts Connected to Topics
    subgraph "Key Concepts"
        K1[Test-Driven Development]
        K2[Behavior-Driven Development]
        K3[Acceptance Testing]
    end
    
    %% Tools Connected to Implementation
    subgraph "Tools"
        T1[pytest]
        T2[unittest]
        T3[coverage]
    end
    
    %% Relationships
    B --> K1 & K2
    C --> K3
    E --> T1 & T2 & T3
    
    %% Styling
    classDef primary fill:#e1f5fe,stroke:#01579b,stroke-width:2px
    classDef concept fill:#f3e5f5,stroke:#4a148c,stroke-width:2px
    classDef tool fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px
    
    class Start,A,B,C,D,E,F,G primary
    class K1,K2,K3 concept
    class T1,T2,T3 tool
```

## Prerequisites

- Basic knowledge of Python
- Basic knowledge of Git

## Course Overview

This course is designed to introduce students to the fundamentals of software testing.

## Course Objectives

By the end of this course, students will be able to:

- Understand the importance of software testing in the development process
- Understand the different types of software testing

## Course Outline

### Introduction to Software Testing

- What is software testing?
- Why is software testing important?
- What is a test?

### Unit Testing

- What is unit testing?
- Why is unit testing important?
- What is a unit test?
- How to write unit tests?

### Integration Testing

- What is integration testing?
- Why is integration testing important?
- What is an integration test?
- How to write integration tests?

### Mocking and Dependency Injection

- What is mocking?
- Why is mocking important?
- What is a mock?
- How to write mocks?

### Test Automation

- What is test automation?
- Why is test automation important?
- What is a test automation framework?
- How to write test automation?

### Test Design Patterns

- What is a test design pattern?
- Why is a test design pattern important?
- What is a test design pattern?
- How to write test design patterns?

### Test Management

- What is test management?
- Why is test management important?
- What is a test management tool?
- How to write test management?

## Course Content

### Key Topics

- Unit testing
- Integration testing
- Mocking and dependency injection
- Test automation
- Test design patterns
- Test management

### Course Materials

- Python
- pytest
- unittest

### Key Concepts

- Test-driven development (TDD)
- Behavior-driven development (BDD)
- Acceptance testing
- Integration testing
- Unit testing
- Integration testing
- Mocking
- Test automation
- Test design patterns
- Test management

## Resources

- [coverage](https://coverage.readthedocs.io/en/latest/)
- [pytest](https://docs.pytest.org/en/latest/)
- [unittest](https://docs.python.org/3/library/unittest.html)
- [pytest-cov](https://pytest-cov.readthedocs.io/en/latest/)
- [pytest-mock](https://github.com/pytest-dev/pytest-mock)
- [pytest-asyncio](https://github.com/pytest-dev/pytest-asyncio)

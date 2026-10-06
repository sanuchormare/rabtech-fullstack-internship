# Task 02 – Accessibility Baseline & Repository Architecture Audit

## 📌 Task Overview

This task is part of the Full Stack Web Development Internship at **RabTech Academy**.

The objective is to perform an accessibility and repository architecture audit of a real public-facing website and document the findings in a structured and professional format.

## 🎯 Objectives

- Audit a real public-facing website for accessibility issues.
- Perform a Lighthouse accessibility assessment.
- Perform keyboard-only navigation testing.
- Identify accessibility and usability issues.
- Map findings to relevant WCAG criteria.
- Document evidence, severity, user impact, and recommendations.
- Design a scalable repository architecture for a web application.
- Prepare a professional GitHub repository structure.

## 🔍 Audit Scope

The audit will cover:

- Keyboard accessibility
- Focus visibility and focus order
- Semantic HTML
- Form labels and instructions
- Images and alternative text
- Heading structure
- Links and interactive controls
- Color contrast
- Navigation
- Page structure
- Basic responsive and usability considerations

## 🧪 Audit Methods

### 1. Lighthouse Audit

Google Chrome Lighthouse will be used to evaluate the accessibility baseline of the selected public website.

### 2. Keyboard-Only Audit

The website will be tested without using a mouse to verify:

- Keyboard navigation
- Focus visibility
- Logical focus order
- Interactive element accessibility
- Keyboard operability

### 3. Manual Review

Manual inspection will be performed to identify issues that automated tools may not detect.

## 📊 Audit Findings

Detailed findings will be documented in:

`audit/accessibility-audit.xlsx`

Each finding will include:

- Issue ID
- Page or component
- WCAG reference
- Evidence
- Severity
- User impact
- Recommendation
- Owner
- Status

## 🏗️ Repository Architecture

The Task 02 repository will follow a structured architecture containing:

```text
Task-02-Accessibility-Audit/
│
├── README.md
├── audit/
├── screenshots/
├── docs/
├── client/
├── server/
└── tests/

# Documentation Module — Detailed Specification

## 1. Module Purpose
Convert project outputs (lesson plans, worksheets, quizzes, specs, tasks) into clean, structured, Docusaurus-ready markdown documents.

Documentation must remain consistent with constitution, spec, plan, and tasks.

---

## 2. Inputs

The module accepts:

- **Content Type:**  
  - Lesson Plan  
  - Worksheet  
  - Quiz/Exam  
  - Behaviour Note  
  - Progress Summary  
  - Timetable  
  - Project Spec  
  - Plan  
  - Tasks  
- **Output destination:**  
  - docs/introduction  
  - docs/modules  
  - docs/specification  
  - docs/reference  
  - docs/examples  

- **Formatting Style:**  
  - Chapter  
  - Guide  
  - Reference  
  - Summary  

---

## 3. Output Format (Strict Markdown)

Every output must follow this template:

```markdown
# [Title]

## Overview
Short description of what this document contains.

---

## Content
(Insert the main generated content here)

---

## Notes
- Markdown only  
- No raw HTML  
- Follow Docusaurus sidebars and folder structure  

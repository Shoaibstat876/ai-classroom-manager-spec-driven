# AI Classroom Manager Agent — Implementation Plan

This implementation plan converts the specification into a step-by-step roadmap.  
Every step follows the pattern:

> Spec → Plan → Tasks → Implementation

This ensures no vibe coding and complete project control.

---

## 1. Project Setup Phase

### 1.1 Folder Structure (Already Completed)
- Create constitution/
- Create specs/
- Create commands/
- Create history/
- Create docs/
- Create core/
- Add spec.md and context.md in root

### 1.2 Initial Files
- constitution/constitution.md (done)
- core/context.md (done)
- spec.md (done)

---

## 2. Specification Expansion Phase

For each module, create sub-spec files (optional but recommended):

- specs/lesson-plan-spec.md  
- specs/worksheet-spec.md  
- specs/quiz-exam-spec.md  
- specs/parent-message-spec.md  
- specs/behaviour-note-spec.md  
- specs/progress-summary-spec.md  
- specs/timetable-spec.md  
- specs/documentation-spec.md  

Each file contains:
- Inputs  
- Rules  
- Output structure  
- Format constraints  

(This can be done gradually, not immediately.)

---

## 3. Commands & Sub-Agents Phase

Create reusable command files inside `commands/`.

Example command files:
- commands/summarize.md  
- commands/extract.md  
- commands/generate-lesson-plan.md  
- commands/generate-worksheet.md  
- commands/generate-timetable.md  

Each command file contains:
- Purpose  
- Input format  
- Output format  
- Rules  
- Constraints  
- Short prompt  

Goal:  
Create small, token-saving building blocks the main agent can call.

---

## 4. Implementation Phase (Core Features)

### 4.1 Lesson Plan Generator
- Create format template  
- Create command file  
- Implement generation logic (Gemini/Claude later)  
- Save examples in history/  

### 4.2 Worksheet Generator
- Define question templates  
- Format with markdown  
- Add answer space indicators  

### 4.3 Quiz/Exam Generator
- Create MCQ/Short/Long templates  
- Add marks distribution  
- Add instructions block  

### 4.4 Parent Message Generator
- Create message patterns  
- Add tone consistency  

### 4.5 Behaviour Note Generator
- Create neutral professional language templates  

### 4.6 Progress Summary Generator
- Create strengths/improvements/recommendations template  

### 4.7 Timetable Generator
- Create day-wise table template  
- Add period balancing logic  

---

## 5. Documentation Phase (Docusaurus)

### 5.1 Install Docusaurus (later)
- npx create-docusaurus project

### 5.2 Create docs sections:
- Introduction  
- Constitution  
- Specification  
- Plan  
- Tasks  
- Modules Documentation  
- Examples  

### 5.3 Deploy to GitHub Pages (later)

---

## 6. GitHub Integration Phase

### 6.1 Create a GitHub repo
- Name: ai-classroom-manager-spec-driven  

### 6.2 Push project files  
- Include: constitution, context, spec, plan, commands, docs  

### 6.3 Setup GitHub Pages for Docusaurus

---

## 7. Task Breakdown Phase

Convert plan to tasks:

- tasks/01-setup.md  
- tasks/02-spec-expansion.md  
- tasks/03-lesson-plan-module.md  
- tasks/04-worksheet-module.md  
- tasks/05-exam-module.md  
- tasks/06-docs.md  
- tasks/07-github.md  

Each task contains:
- Checklist  
- Steps  
- Done/Not Done  

---

## 8. Testing Phase

### 8.1 Validate each module output
- Format  
- Rules  
- Clarity  
- No vibe coding  
- No missing structure  

### 8.2 Validate documentation
- All pages visible  
- Navigation clean  

---

## 9. Final Polish Phase
- Remove unnecessary files  
- Update README.md  
- Screenshot examples  
- Create project banner  
- Add clear instructions for judges  

---

# END OF PLAN

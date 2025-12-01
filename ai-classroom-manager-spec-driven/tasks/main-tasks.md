# AI Classroom Manager Agent — Main Task List (/sp-tasks Simulation)

Use this file as the central checklist for the whole project.
Mark tasks with [x] when completed.

---

## 1. Setup & Core Files

- [x] Create main project folder
- [x] Add folders: constitution, specs, commands, history, docs, core, tasks
- [x] Create core/context.md
- [x] Create constitution/constitution.md
- [x] Create spec.md
- [x] Create specs/plan.md
- [ ] Create README.md in project root

---

## 2. Spec Expansion Tasks

- [ ] Create specs/lesson-plan-spec.md
- [ ] Create specs/worksheet-spec.md
- [ ] Create specs/quiz-exam-spec.md
- [ ] Create specs/parent-message-spec.md
- [ ] Create specs/behaviour-note-spec.md
- [ ] Create specs/progress-summary-spec.md
- [ ] Create specs/timetable-spec.md
- [ ] Create specs/documentation-spec.md

---

## 3. Commands & Sub-Agent Tasks

- [ ] Create commands/summarize.md
- [ ] Create commands/extract.md
- [ ] Create commands/generate-lesson-plan.md
- [ ] Create commands/generate-worksheet.md
- [ ] Create commands/generate-timetable.md
- [ ] Define input/output rules for each command
- [ ] Ensure each command has short prompt text

---

## 4. Module Implementation Tasks

### Lesson Plan Module
- [ ] Design lesson plan template (markdown)
- [ ] Add rules to lesson-plan-spec.md
- [ ] Create example lesson plan in history/

### Worksheet Module
- [ ] Design worksheet template
- [ ] Define question styles
- [ ] Create example worksheet in history/

### Quiz/Exam Module
- [ ] Design exam paper template
- [ ] Define marks structure
- [ ] Add sample exam in history/

### Communication & Behaviour
- [ ] Create parent message patterns
- [ ] Create behaviour note patterns
- [ ] Create progress summary template

### Timetable Module
- [ ] Design timetable table format
- [ ] Add balancing rules in timetable-spec.md
- [ ] Create sample timetable in history/

---

## 5. Documentation (Docusaurus) Tasks

- [ ] Install Docusaurus (later when tools ready)
- [ ] Create docs for:
  - [ ] Project overview
  - [ ] Constitution
  - [ ] Specification
  - [ ] Plan
  - [ ] Tasks
  - [ ] Modules (lesson, worksheet, exam, etc.)
- [ ] Add examples pages
- [ ] Prepare for GitHub Pages deployment

---

## 6. GitHub & Deployment Tasks

- [ ] Create GitHub repo: ai-classroom-manager-spec-driven
- [ ] Commit and push all files
- [ ] Connect Docusaurus to GitHub Pages
- [ ] Add project screenshot(s)
- [ ] Write a clear README.md for judges

---

## 7. Testing & Final Review

- [ ] Verify each module output follows its spec
- [ ] Check for vibe coding (remove unplanned features)
- [ ] Ensure all docs are consistent with spec and constitution
- [ ] Clean unused files/folders
- [ ] Final quality review against hackathon checklist

# Quiz & Exam Module — Detailed Specification

## 1. Module Purpose
To generate quizzes, tests, midterms, or final exam papers in a clean, structured, and teacher-friendly format.  
The system must follow strict exam formatting standards and keep the language clear and age-appropriate.

---

## 2. Inputs

The module accepts:

- **Class Level** (e.g., Grade 6, Grade 9)  
- **Subject**  
- **Topics** (single or multiple)  
- **Exam Type:**  
  - Quiz  
  - Class Test  
  - Midterm  
  - Final Exam  
- **Marks Distribution:**  
  - MCQs quantity & marks  
  - Short Questions quantity & marks  
  - Long Questions quantity & marks  
- **Total Marks**  
- **Instructions text** (optional)

---

## 3. Output Format (Strict Markdown)

Exam MUST follow this exact structure:

```markdown
# [Exam Type] — [Subject]

**Class:**  
**Total Marks:**  
**Time Allowed:** (optional)  

---

## Instructions
- Attempt all questions.  
- Keep your handwriting neat.  
- Do not use any unfair means.  

---

## Section A — MCQs  
(Each MCQ = 1 mark or as specified)

1. Question?  
   - a) Option  
   - b) Option  
   - c) Option  
   - d) Option  

2. Question?  
   - a)  
   - b)  
   - c)  
   - d)  

---

## Section B — Short Questions  
(Each question = 2–3 marks or as specified)

Attempt any **X** questions:

1. Question?  
2. Question?  
3. Question?  

---

## Section C — Long Questions  
(Each question = 5–8 marks or as specified)

Attempt any **Y** questions:

1. Question?  
2. Question?  

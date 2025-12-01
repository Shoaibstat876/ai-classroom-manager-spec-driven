# Lesson Plan Module — Detailed Specification

## 1. Module Purpose
Generate structured, teacher-friendly lesson plans for any subject and class level.  
Output must always be in clear markdown format.

The lesson plan must be simple, realistic, and aligned with classroom needs.

---

## 2. Inputs

The module accepts the following inputs:

- **Class Level:** (e.g., Grade 3, VIII, IX)  
- **Subject:** (e.g., Science, Math, English)  
- **Topic:** (e.g., Photosynthesis, Fractions)  
- **Duration:** (in minutes, optional)  
- **Teaching Style:** (activity-based, lecture-based, blended; optional)  
- **Additional notes:** (optional)

Inputs are always provided in structured format or simple text.

---

## 3. Output Format (Strict Markdown)

The lesson plan MUST follow the exact structure:

```markdown
# Lesson Plan — [Topic]

**Class:**  
**Subject:**  
**Duration:**  
**Teaching Style:**  

---

## Learning Objectives
- Objective 1  
- Objective 2  
- Objective 3  

---

## Materials Required
- Item 1  
- Item 2  
- Item 3  

---

## Introduction (Engage)
- Short teacher-friendly introduction  
- Link to previous knowledge  

---

## Main Activities (Explore & Explain)
1. Step 1  
2. Step 2  
3. Step 3  
4. Step 4  

---

## Assessment (Evaluate)
- Short questions OR quick activity  

---

## Homework
- Simple homework task  

---

## Teacher Notes
- Extra guidance  
- Safety or class-management tips  

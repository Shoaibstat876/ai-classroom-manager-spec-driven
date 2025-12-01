# Worksheet Module — Detailed Specification

## 1. Module Purpose
Generate clean, simple, teacher-friendly worksheets for any subject and class.  
All worksheets must be in **markdown format** and follow a strict structure.

The worksheet must be printable and easy for students to understand.

---

## 2. Inputs

The module accepts:

- **Class Level** (e.g., Grade 4, Grade 8)  
- **Subject** (Science, Math, English…)  
- **Topic**  
- **Number of questions** (optional)  
- **Question Types:**  
  - MCQs  
  - Short Questions  
  - Fill in the blanks  
  - True/False  
  - Match the following  
- **Answer Key:**  
  - Include or exclude (optional)

---

## 3. Output Format (Strict Markdown)

Worksheet MUST follow this exact format:

```markdown
# Worksheet — [Topic]

**Class:**  
**Subject:**  
**Topic:**  

---

## Instructions
- Read each question carefully.  
- Answer in the space provided.  

---

## Questions

### MCQs
1. Question?  
   - a) Option  
   - b) Option  
   - c) Option  
   - d) Option  

### Short Questions
1. Question?  
   _Answer: ___________________

### Fill in the blanks
1. _______ is the process of _______.

### True/False
1. Statement (True/False)

### Match the Following
| Column A | Column B |
|----------|----------|
| item 1   | match 1  |
| item 2   | match 2  |

---

## Answer Key (Optional)
### MCQs
1. b  
2. c  

### Short Questions
- Teacher’s short answer here  

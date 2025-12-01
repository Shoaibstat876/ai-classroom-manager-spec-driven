# Behaviour Note Module — Detailed Specification

## 1. Module Purpose
Generate professional, neutral, and factual behaviour notes that teachers can record or share with parents/administration.

The goal is to document incidents clearly without emotional language.

---

## 2. Inputs

The module accepts:

- **Behaviour Type:**  
  - Disruption  
  - Inattention  
  - Homework not done  
  - Respect issue  
  - Good behaviour (praise)  
- **Context / Incident Description**  
- **Teacher Response**  
- **Date** (optional)  
- **Action required** (optional)

---

## 3. Output Format (Strict Markdown)

Behaviour note must follow this exact structure:

```markdown
# Behaviour Note

**Behaviour Type:**  
**Date:**  

---

## Incident Summary
- Brief factual description of what happened.

---

## Behaviour Description
- Clear, neutral statement describing the student’s behaviour.

---

## Teacher Response
- What the teacher did in response (verbal reminder, guidance, etc.)

---

## Recommended Action (Optional)
- Suggest what parents/teacher may do next.

---

## Notes
- Professional, non-emotional closing note.

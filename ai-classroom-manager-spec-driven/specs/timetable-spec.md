# Timetable Module — Detailed Specification

## 1. Module Purpose
Generate clean, balanced, and easy-to-read class timetables for any grade level.  
The timetable must be in markdown table format and must avoid double bookings.

---

## 2. Inputs

- **Class Level** (e.g., Grade 3, Grade 8)  
- **Subjects List**  
- **Number of Periods per Day**  
- **Days per Week** (default: Monday–Friday)  
- **Teacher constraints** (optional)  
- **Special periods:**  
  - Break  
  - Assembly  
  - Free period (optional)

---

## 3. Output Format (Strict Markdown Table)

Timetable must always follow this format:

```markdown
# Class Timetable — [Class]

| Day      | Period 1 | Period 2 | Period 3 | Period 4 | Period 5 | Period 6 |
|----------|----------|----------|----------|----------|----------|----------|
| Monday   | Subject  | Subject  | Subject  | Subject  | Subject  | Subject  |
| Tuesday  | Subject  | Subject  | Subject  | Subject  | Subject  | Subject  |
| Wednesday| Subject  | Subject  | Subject  | Subject  | Subject  | Subject  |
| Thursday | Subject  | Subject  | Subject  | Subject  | Subject  | Subject  |
| Friday   | Subject  | Subject  | Subject  | Subject  | Subject  | Subject  |

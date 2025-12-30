# 🚀 ExamHall Navigator

**Find your exam hall instantly — anywhere.**

---

## 📌 Overview
ExamHall Navigator is a **Java Full Stack web application** that helps students and exam candidates quickly find their examination hall details using **roll-number-based mapping**.  
The system reduces confusion, panic, and last-minute rush during exams and is scalable from **college-level exams to national-level competitive exams**.

---

## ❓ Problem Statement
During college and government examinations, candidates often face confusion due to unfamiliar campuses, unclear hall allocation, and reliance on static notice boards or volunteers. This becomes more problematic during large-scale exams such as CET, NEET, SSC, and banking exams, leading to panic, crowding, and late entry.

---

## 💡 Solution
ExamHall Navigator provides a centralized system where:
- Exam authorities upload hall allocation details
- Candidates enter their roll number
- The system instantly displays accurate exam hall information

The **same workflow** supports both college exams and government exams by changing only the data source.

---

## 👥 Users
### Admin
- College examination office
- Government exam authority

### Candidate
- College students
- Competitive exam candidates

---

## ⚙️ How It Works
1. Admin creates an exam and uploads roll-number range to hall mappings
2. Candidate selects the exam and enters their roll number
3. System checks the roll number against stored ranges
4. Exam hall details are displayed instantly

---

## 🧠 Core Logic
```text
IF roll_number >= start_roll AND roll_number <= end_roll
THEN display corresponding hall details

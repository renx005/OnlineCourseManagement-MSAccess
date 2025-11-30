# Online Course Management – MS Access Project

This project is a relational database created using **MS Access** to manage
students, courses, enrollments, and instructor assignments efficiently in an
educational environment.

---

## 📌 Features

✔ Student registration & management  
✔ Course information management  
✔ Student enrollments tracking  
✔ Instructor assignment (if included)  
✔ Useful queries for academic administration  
✔ Reports for print-ready output  
✔ Relationship-based data integrity and validation  

---

## 🧱 Database Design

### Tables Used

| Table | Description |
|-------|-------------|
| Students | Stores student information |
| Courses | Stores course details |
| Enrollments | Maps students to courses (junction table) |
| Instructors* | Stores instructor details |
| CourseInstructor* | Many-to-many mapping of courses & instructors |

\*If included in your final design

---

### 🔗 Relationships

- **Students (1) → (*) Enrollments**
- **Courses (1) → (*) Enrollments**
- Optional: **Courses (*) ↔ (*) Instructors** (via CourseInstructor)

These enforce **referential integrity** ensuring data accuracy and avoiding duplication.

---

## 🔍 Queries Implemented

- List of students enrolled in a particular course
- Courses taken by a specific student (parameter-based)
- Number of students enrolled in each course (aggregation)
- Recent enrollments (date-based filtering)
- Reports generated from query results

---

## 📝 Reports

- Course Enrollment Report  
- Student Course History Report  
- Administrative Summary Report

Each report uses grouping, labels, and formatted layout suitable for evaluation.

---

## 🛠 Tools Used

- Microsoft Access (.accdb)
- SQL (Access Query Builder)
- Relational Database Management Concepts
- Forms, Queries, Reports

---

## 👩‍🎓 Developer

**Name:** Rena Elza Viju  
**Program:** MCA  
**Year / Semester:** 1st Year – Semester 1  

---

📌 *This project demonstrates practical DBMS skills including table creation, relationships, form design, queries, and reporting.*


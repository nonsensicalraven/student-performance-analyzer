# Database design- Phase1

## student table(initial draft)
fields:
- student-id
- name
- math_marks
- science_marks
- attendence_percentage


notes:-
- student id should be unique
- marks are out of 100
- attendance is stored as a percentage


## Database Overview

Database name:
- student_performance_db

Tables:
- students

Future tables (later):
- exams
- subjects


## Constraints & Assumptions

- student_id is the primary identifier for each student
- student_id should be unique
- name cannot be null
- marks range: 0–100
- attendance_percentage range: 0–100
- one row represents one student for a given academic period


# H1 Heading
## H2 Heading
### H3 Heading

---

## Text Formatting
*Bold text*  
Italic text  
**Bold + Italic**  
~Strikethrough~

---

## Lists

### Unordered List
- Item 1
- Item 2
  - Sub item

### Ordered List
1. First item
2. Second item
3. Third item

---

## Links
[Visit Google](https://www.google.com)

---

## Images
![Alt Text](https://via.placeholder.com/150)

---

## Code

### Inline Code
print("Hello World")

### Code Block
python
print("Hello World")


---

## Blockquote
> This is a quote

---

## Horizontal Line
---

## Table
| Name  | Age |
|-------|-----|
| John  | 20  |
| Jane  | 22  |

---

## Task List
- [x] Done task
- [ ] Pending task





#schema diagram-
# Database Schema Diagram

## Schema Diagram

```
+-------------------+
|      STUDENTS     |
+-------------------+
| id (PK)           |
| name              |
| age               |
| email             |
+-------------------+
          |
          | FK
          v
+-------------------+
|    ENROLLMENT     |
+-------------------+
| enroll_id (PK)    |
| student_id (FK)   |
| course_id (FK)    |
+-------------------+
          |
          | FK
          v
+-------------------+
|      COURSES      |
+-------------------+
| course_id (PK)    |
| course_name       |
| duration          |
+-------------------+
```

## Tables Description

### Students Table
- id → Primary Key
- name → Student Name
- age → Student Age
- email → Student Email

### Courses Table
- course_id → Primary Key
- course_name → Course Name
- duration → Course Duration

### Enrollment Table
- enroll_id → Primary Key
- student_id → Foreign Key
- course_id → Foreign Key

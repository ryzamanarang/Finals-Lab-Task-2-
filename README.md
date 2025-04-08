# [Finals Lab Task 2 - Transforming ER Model to Relational Tables](https://github.com/user-attachments/files/19642570/Finals.Lab.Task.2.-.Manarang.docx)

# Step By Step Process
### 1. Create the student table:
- Define username as a VARCHAR(50).
- Set username as the Primary Key.

### 2. Create the assignment table:
- Define shortname as a VARCHAR(50) and set it as the Primary Key.
- Define due_date as a DATE NOT NULL.
- Define url as a VARCHAR(255), which can be null.

### 3. Create the submission table:
- Define username and shortname both as VARCHAR(50).
- Define version as an INT.
- Define submit_date as a DATE NOT NULL.
- Define data as TEXT.
- Set a composite primary key of (username, shortname, version).
- Add foreign keys referencing the student and assignment tables.

# Screenshots
## Query Statements
1. Student Table
- ![Image](https://github.com/user-attachments/assets/e331491a-0585-40bc-b2b9-77f38abc3845)

2. Assignment Table
- ![Image](https://github.com/user-attachments/assets/542d7ab7-418c-4e0d-b3c4-d1c627965040)

3. Submission Table
- ![Image](https://github.com/user-attachments/assets/418b422f-acd5-4300-a911-3293d8295810)

## Table Structure
1. Student Table
- ![Image](https://github.com/user-attachments/assets/78e48b99-f5fc-4c12-8ecf-a45fd2cd695c)

2. Assignment Table
- ![Image](https://github.com/user-attachments/assets/c0a9f5b9-bc63-48e8-a9c6-ee74830fed1b)

3. Submission Table
- ![Image](https://github.com/user-attachments/assets/054d1161-db9c-4aeb-acc2-01c6c79e91ef)

## EER Diagram
- ![Image](https://github.com/user-attachments/assets/d9a6658a-6fed-4c55-a1c9-073c0ec317e9)
- ![Image](https://github.com/user-attachments/assets/0f1b0f0d-7dcf-4964-ad87-8db14deb9299)

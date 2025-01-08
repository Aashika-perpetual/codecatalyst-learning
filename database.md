# MySQL and MongoDB Database Operations

This repository contains the steps and SQL/MongoDB commands executed to complete the tasks outlined for managing `Users` and `Tasks` databases using **MySQL** and **MongoDB**.

### 1. Database Creation
- **Database Name**: `task_manager_database`

### 2. Table Creation
#### `Users` Table
- **Fields**:
  - `User_ID` (Primary Key, Auto Increment)
  - `Name` (VARCHAR, NOT NULL)
  - `Email` (VARCHAR, UNIQUE, NOT NULL)
  - `Password` (VARCHAR, NOT NULL)
  - `Role` (ENUM: Admin/User)

#### `Tasks` Table
- **Fields**:
  - `Task_ID` (Primary Key, Auto Increment)
  - `Title` (VARCHAR, NOT NULL)
  - `Description` (TEXT)
  - `Due_Date` (DATE)
  - `User_ID` (Foreign Key referencing `Users.User_ID`)

## Task 1: MySQL Database Operations

1. **Table Creation**
2. **Table Description**
3. **Data Insertion**
4. **Data Update**
5. **Data Deletion**

### Proof of Completion
##### MySQL
![Screenshot 2025-01-07 155647](https://github.com/user-attachments/assets/8fd45f1b-5402-436d-ab12-80a00c97d7bd)
![Screenshot 2025-01-07 155845](https://github.com/user-attachments/assets/004a1ed9-2112-4306-a11f-2911b71d2f1b)
![Screenshot 2025-01-07 161343](https://github.com/user-attachments/assets/85592688-3894-4bc2-9588-51e2400d6384)
![Screenshot 2025-01-07 162252](https://github.com/user-attachments/assets/8a894296-a7a1-4612-94d6-253292ce885d)
![Screenshot 2025-01-07 162417](https://github.com/user-attachments/assets/c63d3b47-af36-4e93-a272-f85275af90aa)


## Task 2: MongoDB Database Operations

### 1. Database Schema in MongoDB
#### `Users` Collection
- **Fields**:
  - `_id`
  - `Name`
  - `Email`
  - `Password`
  - `Role`

#### `Tasks` Collection
- **Fields**:
  - `_id`
  - `Title`
  - `Description`
  - `Due_Date`
  - `User_ID`

---
### Proof of Completion
##### MongoDb
![Screenshot 2025-01-08 114430](https://github.com/user-attachments/assets/65d85fec-2f37-4d54-984b-32066b02b63f)

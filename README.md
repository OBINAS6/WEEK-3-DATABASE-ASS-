# WEEK-3-DATABASE-ASS-

### 🧑‍🎓 **Question 1**: **Create the `student` table**

```sql
CREATE TABLE student (
    id INT PRIMARY KEY,
    fullName TEXT(100),
    age INT
);
```

This statement creates a table named `student` with the following columns:
- `id` (integer and the primary key)
- `fullName` (text with a maximum of 100 characters)
- `age` (integer)

---

### ➕ **Question 2**: **Insert at least 3 records into the `student` table**

```sql
INSERT INTO student (id, fullName, age)
VALUES
    (1, 'John Doe', 22),
    (2, 'Jane Smith', 19),
    (3, 'Alice Johnson', 21);
```

This statement inserts 3 records into the `student` table.

---

### 🔄 **Question 3**: **Update the age of the student with ID 2 to 20**

```sql
UPDATE student
SET age = 20
WHERE id = 2;
```


# Task 3 - SQL Injection on DVWA (Low Security)

## Objective

The objective of this task was to understand and demonstrate a basic SQL Injection vulnerability using Damn Vulnerable Web Application (DVWA) in Low Security mode.

---

## Tools Used

- Kali Linux
- DVWA (Damn Vulnerable Web Application)
- Apache2
- MariaDB
- PHP
- Firefox Browser

---

## Environment Setup

1. Updated system packages.
2. Installed Apache2, MariaDB, PHP, and Git.
3. Started Apache and MariaDB services.
4. Downloaded and configured DVWA.
5. Created the DVWA database.
6. Logged into DVWA.
7. Set the Security Level to **Low**.

---

## SQL Injection Testing

### Normal Input

User ID:

```text
1
```

**Result:**

The application returned the details of a single valid user.

---

### SQL Injection Payload

```sql
1' OR '1'='1
```

**Result:**

The application returned multiple user records, demonstrating that the SQL query was successfully manipulated.

---

## Vulnerability

**Type:** SQL Injection

**Security Level:** Low

---

## Impact

- Unauthorized access to database records.
- Disclosure of sensitive information.
- Authentication bypass.
- Potential compromise of the database.

---

## Mitigation

- Use Prepared Statements (Parameterized Queries).
- Validate and sanitize all user inputs.
- Apply the Principle of Least Privilege for database accounts.
- Avoid displaying database errors to users.
- Perform regular security testing.

---

## Screenshots

- Apache Service Running
- MariaDB Service Running
- DVWA Setup Page
- Database Created Successfully
- DVWA Login Page
- Security Level set to Low
- Normal Input Result
- SQL Injection Successful Result

---

## Conclusion

This task demonstrated how SQL Injection vulnerabilities occur when user input is not properly validated. Using DVWA in Low Security mode, SQL Injection was successfully performed, highlighting the importance of secure coding practices such as parameterized queries and input validation to protect web applications.

---

## Author

**Name:** Hamza Riaz

**Internship:** Oasis Infobyte - Cyber Security Internship

**Task:** Task 3 - SQL Injection on DVWA (Low Security)

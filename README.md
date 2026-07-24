# threat_intel_ip_blocking
# PostgreSQL Database Credential Auditing

## Cyber Security Internship

**Company:** SQ IT Solution

### Day 23 Deliverable

## Project Overview

This project performs a security audit of PostgreSQL database credentials and configuration. It checks for default credentials, weak passwords, excessive privileges, and generates a security audit report with administrative recommendations.

---

## Features

- Credential auditing
- Default password detection
- Weak password detection
- Superuser privilege verification
- JSON audit report generation
- Security logging
- Administrative Security Blueprint

---

## Technologies Used

- Python 3
- JSON

---

## Project Structure

```
PostgreSQL-Database-Credential-Auditing/
│
├── main.py
├── postgres_audit_report.json
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## How to Run

```bash
python main.py
```

---

## Sample Output

```
[INFO] Auditing PostgreSQL Database...

[CRITICAL] Default credential detected:
User: postgres

[PASS] Strong password verified for app_user.

[PASS] SSL/TLS Configuration Verified.

Audit Status : COMPLETED
```

---

## Deliverables

- Verification Logging Output
- Administrative Security Blueprint
- PostgreSQL Audit Report

---

## Author
Sumaiya Mohsin Rao 
Cyber Security Internship

SQ IT Solution
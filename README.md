# 📚 Library Management System
**Course:** UCS310 – Database Management Systems  
**Institute:** Thapar Institute of Engineering & Technology (TIET)  
**Team:** Akshit Sharma | Archit Singh | Daksh Chhabra  
**Batch:** B.Tech CSE 2024–2028

---

## 📌 Project Overview
A complete Library Management System built using Oracle SQL with:
- DDL (Tables with constraints)
- DML (Sample data)
- PL/SQL Functions, Procedures, Triggers, Cursors
- Views for Active Issues and Overdue Books
- A frontend demo interface (HTML)

---

## 🗂️ Files
| File | Description |
|------|-------------|
| `library_management.sql` | Complete Oracle SQL implementation |
| `library_management_system.html` | Frontend demo (open in any browser) |

---

## 🚀 How to Run the SQL
1. Go to [livesql.oracle.com](https://livesql.oracle.com) and sign in
2. Click **"Start Coding"**
3. Paste the contents of `library_management.sql`
4. Click **Run**

## 🖥️ How to Run the Frontend
1. Download `library_management_system.html`
2. Double-click to open it in any browser (Chrome, Firefox, Edge)
3. No installation needed — works offline

---

## 🏗️ Database Schema
- **BOOK** – Book catalog with availability tracking
- **MEMBER** – Registered library members
- **LIBRARIAN** – Library staff
- **ISSUE_TRANSACTION** – Book issue/return records with fine tracking

## ⚙️ Features Implemented
- ✅ Issue Book procedure with availability check
- ✅ Return Book procedure with automatic fine calculation
- ✅ Trigger to prevent issuing unavailable books
- ✅ Trigger to restore copies on return
- ✅ Fine calculator (Rs. 2/day overdue)
- ✅ Views: Active Issues, Overdue Books
- ✅ Cursor-based transaction report

# Smart Library Access and Book Management System (CLI)

## Overview

This is a Java CLI-based application to manage library members and librarians, allowing borrowing and returning of books, with logs and database persistence using JDBC and SQLite.

## Features

- Add/remove members and librarians
- Borrow/return books
- View borrowed books or shift info
- File logging to `library_log.txt`
- Data persistence via SQLite
- Follows OOP principles with interfaces, abstract classes, and exception handling

## Requirements

- Java 17+
- SQLite JDBC driver (`sqlite-jdbc-<version>.jar`)

## How to Run

1. **Set up the database**  
   Run the `library_schema.sql` script using a tool like DB Browser for SQLite.

2. **Compile and run the project**  
   Open in IntelliJ or VSCode and run `ui.MainApp`.

## Folder Structure

```
model/        -> Domain models (Member, Librarian)
interfaces/   -> Borrowable, Returnable
dao/          -> MemberDAO, LibrarianDAO for DB access
service/      -> LibrarySystem business logic
ui/           -> MainApp with CLI menu
util/         -> Logger and DB connection helper
exceptions/   -> Custom exceptions
```

## Team Contributions

Each member can contribute to:
- Models & interfaces
- JDBC and DAO integration
- CLI interface
- File I/O and utility classes

---


# Library Management System

## Overview

Students and library staff need a simple and reliable way to manage library activities. The proposed Library Management System will help students search for books, check book availability, borrow and return books, and manage their borrowing records. It will reduce manual paperwork, save time, and improve the efficiency of library operations.

## Scope

- In scope: Student login and authentication.
- In scope: Search books by title, author, or category.
- In scope: View book details and availability.
- In scope: Borrow books from the library.
- In scope: Return borrowed books.
- In scope: Request renewal of borrowed books.
- In scope: Calculate and display overdue fines.
- Out of scope: Online purchase and sale of books.
- Out of scope: Digital book reading and e-book hosting.

## Stakeholders

- Student: Searches for books, checks availability, borrows and returns books, and checks borrowing status.
- Librarian: Manages book records, issues books, receives returned books, and monitors overdue books.
- Project Maintainer: Maintains the system, manages technical issues, updates records, and ensures system availability.

## Functional Requirements

- FR-01: The system shall allow students to log in using valid credentials.
- FR-02: The system shall allow users to search books by title, author, or category.
- FR-03: The system shall display book details and availability status.
- FR-04: The system shall allow librarians to issue books to students.
- FR-05: The system shall allow librarians to record returned books.
- FR-06: The system shall allow students to request renewal of borrowed books.
- FR-07: The system shall calculate and display fines for overdue books.
- FR-08: The system shall allow administrators to add, update, and delete book records.

## Nonfunctional Requirements

- NFR-01: The system shall display search results within 2 seconds for at least 95% of searches under the agreed testing conditions.
- NFR-02: All major system functions shall be accessible using a keyboard.
- NFR-03: The system shall protect student and library information from unauthorized access.
- NFR-04: The system shall restrict administrative functions to authorized users only.
- NFR-05: The system shall maintain accurate and consistent book and borrowing records.

## Acceptance Criteria

- FR-01: Given a registered student with valid credentials, when the student enters login details, the system shall grant access.
- FR-02: Given a book title, when the user searches for it, the system shall display matching books.
- FR-03: Given a selected book, when the user opens its details, the system shall display its title, author, and availability.
- FR-04: Given an available book, when the librarian issues it to a student, the system shall update its availability status.
- FR-05: Given a borrowed book, when the librarian records its return, the system shall update the book status to Available.
- FR-06: Given an eligible borrowed book, when the student requests renewal, the system shall record the renewal request.
- FR-07: Given an overdue book, when the librarian records its return, the system shall calculate the applicable fine.

## Assumptions and Open Questions

- Assumption A-01: Every student and librarian will have a unique account.
- Assumption A-02: The library will provide an approved borrowing period and fine policy.
- Assumption A-03: The library will maintain updated information about available books.

- Question Q-01: How many books can a student borrow at one time?
- Question Q-02: What will be the maximum borrowing period for a book?
- Question Q-03: What fine will be charged for late book returns?
- Question Q-04: Which devices will be used to test the system's performance?

## Project Status and Viewing

This is a documentation-only project. No application has been built yet. Clone the repository and open README.md in Notepad or another text editor, or read it on GitHub.

## Author

**Name:** Faisal Bashir

**Roll No:** BSEF25A540

**Project Name:** Library Management System

**Course:** Software Requirements Engineering

## Contributing

Create a documentation branch, edit and review README.md, commit and push the changes, then open a pull request for review.

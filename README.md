# SQLtasks
new repo
Domain Chosen: Library Management System
Entities (Tables):
Authors - Writers of books
Books - Library collection items
Members - Library users
Loans - Borrowing transactions
Relationships:
Authors → Books (One-to-Many): One author can write multiple books
Members → Loans (One-to-Many): One member can have multiple loans
Books → Loans (One-to-Many): One book can be borrowed multiple times
Loans connects Books and Members (Many-to-Many relationship)



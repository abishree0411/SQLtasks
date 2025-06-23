# SQLtasks
new repo
Library Management System
Entities could include: Books, Authors, Members, Loans
Relationships:
A Book can have one or more Authors
A Member can borrow many Books (via Loans)
Each Loan refers to one Book and one Member
Books
book_id (PK)
title
author_id (FK)
isbn
published_year
Authors
author_id (PK)
name
bio
Members
member_id (PK)
name
email
join_date
Loans
loan_id (PK)
book_id (FK)
member_id (FK)
loan_date
return_date



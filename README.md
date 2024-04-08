# python-task

### Task Description:

You are tasked with creating a simple API using Django and Django Rest Framework (DRF) for managing a collection of books. The API should allow users to perform CRUD (Create, Read, Update, Delete) operations on the books.

### Requirements:

Create a Django project named **BookAPI**.
Create a Django app named books.
Define a model named Book with the following fields:
title: CharField
author: CharField
publication_date: DateField
isbn: CharField (ISBN-13 format)
Create a RESTful API using Django Rest Framework for CRUD operations on the Book model.
Use **Postgres** Database as backend
### Implement the following API endpoints:
- GET /api/books/: Retrieve a list of all books.
- GET /api/books/<id>/: Retrieve details of a specific book by its ID.
- POST /api/books/: Create a new book.
- PUT /api/books/<id>/: Update details of a specific book by its ID.
- DELETE /api/books/<id>/: Delete a specific book by its ID.
- 
Implement appropriate serializers for the Book model to ensure proper data validation and serialization.
Include pagination for the list of books API endpoint with a page size of 10 books per page.
Add filtering capabilities to the list of books API endpoint based on the book's title and author.
Write unit tests for your API endpoints to ensure they work as expected.
Provide clear and concise documentation on how to set up and run your Django project and API.

### Bonus:

1. Implement authentication and authorization using Django Rest Framework's built-in authentication classes (e.g., Token Authentication or JWT Authentication).
2. Add support for nested serializers to include related data (e.g., author details) in the book API responses.

### Submission:

Please submit your solution as a compressed file (zip or tar.gz) containing your Django project directory. Ensure that your code is well-organized, properly documented, and follows best practices in Django development.


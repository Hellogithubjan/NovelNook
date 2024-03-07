# NovelNook - A Virtual BookStore

This is a virtual bookstore application using MERN stack where users can explore, rent, purchase books, and track their reading progress. Admins have additional privileges to manage the book inventory.

## Features

### Authentication

- Users can register and login to the application using their mobile number or email address.
- Separate login pages are provided for admins and users.

### Admin Panel

- Admins have access to an admin panel where they can perform the following actions:
  - Add new books to the inventory.
  - Delete books from the inventory.
  - Update book details such as title, author, description, etc.

### User Dashboard

- Users can browse through the available books and perform the following actions:
  - Rent books for a specified period.
  - Purchase books to own them permanently.
  - Receive notifications when a book is rented or purchased.
  - Track their reading progress and bookmark pages.

### Rental Management

- The application tracks the rental period of books to restrict access after the rental period expires.
- Users are notified when the rental period is about to end or when a book is overdue.

## Technologies Used

- **Frontend:** React, Material-UI
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)

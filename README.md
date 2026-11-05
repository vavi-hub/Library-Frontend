# LibraryHub – Library Management System

LibraryHub is a web-based Library Management System frontend designed to provide separate interfaces for librarians and library members.

It offers a clean and user-friendly dashboard for managing library operations, monitoring book availability, viewing borrowing activities, and accessing member information.

# Project Overview

The project consists of two main interfaces:

1. **Admin Dashboard:** Provides librarians with an overview of library operations, including books, members, borrowing activities, and fines.
2. **Member Dashboard:** Allows library members to explore available books, view borrowed books, check due dates, and access their membership information.

## Features

### Admin Dashboard

- Overview of total books and registered members.
- Display of currently borrowed and overdue books.
- Recent borrowing activity.
- Book availability statistics.
- Quick actions for library administration.
- Add New Book form interface.
- Outstanding fines overview.

### Member Dashboard

- Personalized member dashboard.
- Overview of currently borrowed books.
- Due date reminders.
- Borrowing history.
- Membership information.
- Book catalogue interface.
- Search interface for books by title, author, or book code.
- Book availability indicators.

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of web pages |
| CSS3 | Styling and layout |
| Flexbox | Layout alignment |
| CSS Grid | Dashboard layouts |

## Project Structure

```text
Library-Frontend/
│
├── admin.html       # Librarian dashboard
├── member.html      # Member dashboard
├── style.css        # Common styling
│
└── README.md        # Project documentation
```

## 💻 Getting Started

### Prerequisites

You only need:

- A modern web browser.
- A code editor (VS Code recommended).

No additional packages or dependencies are required.

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/vavi-hub/Library-Frontend.git
```

**2. Navigate to the project directory**

```bash
cd Library-Frontend
```

**3. Open the project**

Open either HTML file directly in your browser.

For the Admin Dashboard:

```bash
xdg-open admin.html
```

For the Member Dashboard:

```bash
xdg-open member.html
```

Alternatively, use the Live Server extension in VS Code.

## Database Project

This frontend is designed as the user interface component of a Library Management System.

The database component is maintained in a separate repository.

**Database Repository:**

https://github.com/vavi-hub/Library-Management

The MySQL database includes:

- Members
- Librarians
- Books
- Authors
- Categories
- Book Copies
- Borrowings
- Fines

## Future Improvements

- Integrate the frontend with the MySQL database through a backend API.
- Implement user authentication for librarians and members.
- Enable dynamic book searching.
- Implement book issuing and returning functionality.
- Add member registration and management.
- Implement automatic fine calculation.
- Display real-time book availability.
- Add responsive improvements for mobile devices.

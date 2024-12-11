GitHub link: https://github.com/Ashi-Jain07/Online-Library-System.git

Project Overview
This project is an online library system built with React that allows users to browse, view details, and add books. The project consists of multiple pages, including a home page, browse books page, book details page, add book page, and a 404 page for undefined routes.

Features

1. Home Page 
Navigation Bar: A navigation bar with links to the "Home", "Browse Books", and "Add Book" pages.
Welcome Message & Book Categories: The landing page includes a welcome message and that displays a list of book categories such as Fiction, Non-Fiction, Sci-Fi, etc.
Popular Books: A section that displays a list of popular books with a link to view more details about each book.

2. Browse Books Page 
Book List by Category: Displying the list of books filtered by category using dynamic routing.
View Details: Each book has a "View Details" link that routes to the Book Details page.
Search Functionality: Search bar to search book filter by title or author.

3. Book Details Page 
Dynamic Route: Displays detailed information about a selected book, including the title, author, publish date, description, category, and rating.
Back to Browse: A button to return to the Browse Books page.

4. Add Book Page
Add Book Form: A form for adding a new book to the library.
State Management: Utilizes Redux to manage the state of the books list.
Redirect After Submission: After submitting a new book, the user is redirected to the Browse Books page with the newly added book displayed.

5. 404 Page 
Page Not Found: A route that displays a "Page Not Found" message for any undefined routes.
Link to Home: Includling the button to navigate back to the Home page.
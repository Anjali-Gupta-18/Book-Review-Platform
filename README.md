# Book Review Platform

## Project Description
The **Book Review Platform** is a web application that allows users to browse a catalog of books, read and submit reviews, and rate books. The platform includes user authentication, enabling users to create accounts, log in, and manage their reviews. Admins have the ability to manage the book catalog and moderate user reviews. This project is built using Django for the backend, with HTML, CSS, and Bootstrap for the frontend.

## Features
- **User Authentication**: Register, log in, and manage user profiles.
- **Book Catalog**: Display a list of books with details such as title, author, genre, and cover image.
- **Review and Rating System**: Submit reviews, rate books, and view reviews from other users.
- **Admin Interface**: Add, edit, and delete books, and moderate reviews.
- **Search and Filtering**: Search for books and filter by genre or author.

## Technologies Used
- **Django**: Web framework for the backend.
- **Python**: Core programming language.
- **SQLite**: Database management for storing user data, books, and reviews.
- **HTML/CSS**: Frontend structure and styling.
- **Bootstrap**: Responsive design framework.

## Setup Instructions
1. **Clone the repository**:
   git clone https://github.com/Anjali-Gupta-18/Book-Review-Platform.git
   cd Book-Review-Platform
2. Create and activate a virtual environment:
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install dependencies:
   pip install -r requirements.txt
4. Apply migrations:
   python manage.py makemigrations
   python manage.py migrate
5. Create a superuser for admin access:
   python manage.py createsuperuser
   python manage.py createsuperuser
6. Run the development server:
   python manage.py runserver

Usage
Admin: Add, edit, and delete books from the catalog and moderate user reviews.
User: Browse the book catalog, submit reviews, and rate books after logging in.
Project Structure
bookreview/: Main project folder containing settings, URLs, and configurations.
reviews/: App folder containing models, views, forms, and templates related to books and reviews.
templates/: HTML files for rendering the UI.
static/: Static files including CSS for styling the application.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

   

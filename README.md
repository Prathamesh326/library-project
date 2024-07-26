# Library Project

A simple web application to manage a collection of books. This project is built using Flask for the web framework and SQLAlchemy for database management.

## Features

- **View All Books**: See a list of all books in the collection with their authors and ratings.
- **Add New Book**: Add a new book to the collection.
- **Edit Book Rating**: Update the rating of an existing book.
- **Delete Book**: Remove a book from the collection.

## Project Structure

```
library-project/
│
├── static/
│   ├── (static files like CSS, images, etc.)
│
├── templates/
│   ├── index.html
│   ├── add.html
│   └── edit_rating.html
│
├── main.py
├── requirements.txt
├── README.md
└── new-books-collection.db (auto-generated)
```

- **`main.py`**: The main Flask application file containing the routes and database models.
- **`templates/`**: Contains HTML templates for the web pages.
- **`requirements.txt`**: Lists the Python dependencies for the project.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Prathamesh326/library-project.git
   cd library-project
   ```

2. **Create a virtual environment and activate it:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**

   ```bash
   python main.py
   ```

   The app will be available at `http://127.0.0.1:5000/`.

## Usage

- **Home Page**: Displays all books in the collection.
- **Add Book**: Navigate to `/add` to add a new book.
- **Edit Book Rating**: Click "Edit rating" next to a book on the home page to change its rating.
- **Delete Book**: Click "Delete" next to a book on the home page to remove it from the collection.

## Database

The project uses SQLite for storing book information. The database file `new-books-collection.db` is automatically created when you run the application for the first time.

## Contributing

Feel free to fork this repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.


This README file gives a comprehensive overview of your project, including installation instructions, usage, and contribution guidelines.

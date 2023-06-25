# Blogpost
Created a blogpost using flask api

# Flask Blog Site

This is a blog site created using Flask API and SQLAlchemy for database management. The site allows users to create and publish blog posts, and the latest blog posts can be seen on the home page.

## Features

- User Registration and Login: Users can create an account by registering with a unique username and password. Registered users can log in to the site using their credentials.

- Create Blog Posts: Logged-in users can create new blog posts by providing a title and content for their post. The blog posts are stored in a database.

- View Latest Blog Posts: The home page of the site displays the latest blog posts, showing the title, content, and the author of each post. Users can easily read the most recent content.

## Technologies Used

The blog site is built using the following technologies:

- Flask: A micro web framework for Python that provides the tools, libraries, and components needed to build web applications.

- Flask API: A lightweight framework that helps in creating APIs using Flask.

- SQLAlchemy: A Python SQL toolkit and Object-Relational Mapping (ORM) library that provides a set of high-level API for interacting with databases.

- SQLite: A lightweight, file-based database engine that allows storing and querying data without requiring a separate database server.

## Installation

To run the Flask blog site locally, follow these steps:

1. Clone the repository:

```
git clone https://github.com/your-username/flask-blog-site.git
```

2. Change into the project directory:

```
cd flask-blog-site
```

3. Create and activate a virtual environment (optional, but recommended):

```
python3 -m venv venv
source venv/bin/activate
```

4. Install the required dependencies:

```
pip install -r requirements.txt
```

5. Run the Flask development server:

```
flask run
```

6. Open your web browser and visit `http://localhost:5000` to access the blog site.

## Configuration

The Flask blog site requires a configuration file named `config.py` in the project directory. Create this file and provide the following configuration options:

```python
# config.py

# Flask configuration
SECRET_KEY = 'your-secret-key'  # Secret key for securing session data

# Database configuration
SQLALCHEMY_DATABASE_URI = 'sqlite:///blog.db'  # URI for connecting to the database
SQLALCHEMY_TRACK_MODIFICATIONS = False  # Disable modification tracking
```

Make sure to replace `'your-secret-key'` with a secure secret key of your choice. You can also change the database URI (`'sqlite:///blog.db'`) to use a different database engine or location.

## Contributing

Contributions to the Flask blog site are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the project's repository.

When contributing, please follow the existing coding style and ensure that your changes are well-documented and tested.



## Credits

The Flask blog site was created by [Your Name](https://github.com/your-username). Special thanks to the Flask and SQLAlchemy communities for their excellent frameworks and libraries.

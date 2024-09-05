# Flaskr App - Tutorial Follow-Along

This repository contains my implementation of the Flaskr app, created by following the official Flask tutorial. It serves as a learning exercise and demonstration of Flask fundamentals.

## About Flaskr

Flaskr is a simple blog application that allows users to register, log in, create posts, and manage their content. It showcases basic Flask concepts and serves as an excellent starting point for learning web development with Flask.

## Features

- User authentication (register, login, logout)
- Blog post creation and management
- SQLite database integration
- Basic styling with CSS

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.7 or higher
- pip (Python package installer)

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/flaskr-tutorial.git
   cd flaskr-tutorial
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Configuration

1. Set the Flask application environment variables:
   ```
   export FLASK_APP=flaskr
   export FLASK_ENV=development
   ```
   On Windows, use `set` instead of `export`.

2. Initialize the database:
   ```
   flask init-db
   ```

## Running the Application

To start the Flask development server, run:

```
flask run
```

The application will be available at `http://127.0.0.1:5000`.

## Testing

To run the tests, execute:

```
pytest
```

## Learning Resources

- [Official Flask Tutorial](https://flask.palletsprojects.com/en/2.1.x/tutorial/)
- [Flask Documentation](https://flask.palletsprojects.com/)

## License

This project is open-sourced under the MIT License. See the LICENSE file for details.

## Acknowledgements

This project was created by following the [Official Flask Tutorial](https://flask.palletsprojects.com/en/2.1.x/tutorial/).

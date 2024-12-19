# Learning Flask

This repository contains a simple task management web application from my past that was built with Flask, demonstrating fundamental Flask capabilities including routing, templating, and database operations using SQLAlchemy.

## Features

- **Task Management:** Users can add, delete, and update tasks.
- **Persistent Storage:** Tasks are stored in a SQLite database, ensuring data persistence.
- **User-Friendly Interface:** The application uses basic HTML and CSS to provide a clean and easy-to-navigate user interface.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Python installed on your system. The project was built using Python 3.8. You also need to have Flask and SQLAlchemy installed. If you don't have these, the next section will guide you on how to install them.

### Installing

First, clone the repository to your local machine:

```bash
git clone https://github.com/psap2/Learning-flask.git
cd learning-flask
```

Next, install the required packages:

```bash
pip install -r requirements.txt
```

### Running the Application

To run the application, use the following command:

```bash
flask run
```

This will start the Flask development server, and you should be able to access the application by navigating to `http://127.0.0.1:5000/` in your web browser.

## Built With

- [Flask](http://flask.pocoo.org/) - The web framework used
- [SQLAlchemy](https://www.sqlalchemy.org/) - Database Management
- [SQLite](https://sqlite.org/index.html) - Database used for development

# Learning Log

Learning Log is a web app that allows users to log the topics they’re interested in and make journal entries as they learn about each topic. The Learning Log home page describes the site and invites users to either register or log in. Once logged in, a user can create new topics, add new entries, and read and edit existing entries.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Live Demo](#live-demo)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

## Introduction

The Learning Log project is designed to help users keep track of the information they learn about various topics. Built using Django, this project guides you through setting up a web application that allows users to manage topics and journal entries, with user authentication and a user-friendly interface.

## Features

- User registration and authentication.
- Create, read, update, and delete topics.
- Create, read, update, and delete journal entries.
- Responsive home page inviting users to register or log in.

## Installation

To get started with the Learning Log project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/learning-log.git
   ```

2. Navigate to the project directory:

   ```bash
   cd learning-log
   ```

3. Create a virtual environment:

   ```bash
   python3 -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Set up the database:

   ```bash
   python manage.py migrate
   ```

7. Create a superuser for accessing the admin interface:
   ```bash
   python manage.py createsuperuser
   ```

## Usage

To run the application locally, use the following command:

```bash
python manage.py runserver
```

Open your web browser and navigate to `http://localhost:8000` to access the application.

## Live Demo

You can access the live version of the Learning Log application at the following link:
[Live Demo](http://your-live-server-link.com)

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License.

## Credits

The Learning Log project was created by Alexis Gonzalez. Special thanks to Eric Matthes for his book "Python Crash Course," which provided the foundation for this project.

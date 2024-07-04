This blog project is developed in Python using the Flask web framework and Bootstrap for styling. It utilizes a PostgreSQL database managed through SQLAlchemy for data storage. Passwords are securely hashed and salted using sha256 to safeguard sensitive information.

Key Features:
The application includes an admin account with exclusive functionalities such as creating, editing, and deleting posts and comments. These features are restricted and hidden from regular users to prevent unauthorized access.
Registered users can log in to leave comments on blog posts. A 'Contact' section enables users to send email forms via SMTP to the site owner's inbox using Flask-Mail extension.
The project emphasizes cybersecurity by employing an algorithm to sanitize HTML input from clients. This process removes unwanted tags, attributes, unescaped characters, and improperly nested tags to enhance security.

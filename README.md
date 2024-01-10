# Site 1 Blog

This project is a web application developed using Django, a powerful web development framework in Python. The project includes several functional features that enable users to interact with content, administer the site, and facilitate information exchange.

## Core Features

- **Email Sending**: The application incorporates an email sending mechanism using Django's functionality for communicating with users.
  
- **Use of Django Forms for Content Sharing**: Users can share posts via email using built-in Django forms, providing convenience in content interaction and dissemination.

- **Adding Comments to Posts**: Users can leave comments on posts using forms integrated into Django models, allowing users to communicate and exchange opinions.

- **Utilization of django-taggit for Tagging**: The django-taggit application is used to implement a tagging system, allowing for convenient tag assignment and management, enriching content and providing structure.

- **PostgreSQL Database**: The project utilizes a PostgreSQL database for data storage and organization, ensuring reliability and performance.

- **Full-Text Search Using Django and PostgreSQL**: A full-text search mechanism is implemented, enabling users to quickly find relevant content.

## Installation of Required Modules

To run the project, the following modules need to be installed using `pip install`:

- asgiref==3.5.2
- Django~=4.1.0
- sqlparse==0.4.2
- django-taggit==3.0.0
- Markdown==3.4.1
- psycopg2-binary==2.9.3

## How to Run the Project

1. Clone the repository to your local machine.
2. Install all necessary modules mentioned above.
3. Configure the PostgreSQL database in the project settings file.
4. Run the Django application using the command `python manage.py runserver`.

## Additional Steps

For the project to work fully, the following components need to be configured:

- Configuring email sending via Django.
- Integration of forms and comments as per the project's requirements.

This is just a basic description of the project's functionality. For more detailed information on setting up and using the project's features, it's recommended to refer to the Django documentation or the comments within the application's source code.

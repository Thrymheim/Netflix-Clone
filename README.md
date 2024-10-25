![Netflix Logo](https://seeklogo.com/images/N/netflix-n-logo-0F1ED3EBEB-seeklogo.com.png)


# Netflix Clone Project

## Overview

This project is a Netflix clone built using Django. It features user authentication (sign in / login) and a simple main page showcasing the available content. The application leverages Django's built-in functionalities for handling APIs and static files, making it a solid foundation for building more complex features in the future.

## Features

- **User Authentication**: Users can sign in to their accounts.
- **Main Page**: A simple landing page displaying available content.

## Technologies Used

- **Django**: The web framework used to build the application.
- **Django REST Framework**: To facilitate API creation and handling.
- **HTML/CSS**: For the basic styling of the main page.
- **SQLite**: The default database for the application (can be modified to use others).

## Installation

To get started with the project, follow these steps:

### Prerequisites

- Python 3.x
- Django
- Django REST Framework

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/netflix-clone.git
```

### Step 2: Change Directory

```bash
cd netflix-clone
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### Step 4: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 5: Database Migrations

Run the following command to apply migrations:

```bash
python manage.py migrate
```

### Step 6: Create a Superuser (optional)

To access the Django admin panel, create a superuser account:

```bash
python manage.py createsuperuser
```

### Step 7: Run the Development Server

Start the server:

```bash
python manage.py runserver
```

You can now visit `http://127.0.0.1:8000/` in your browser to access the application.

## Usage

1. Navigate to the sign-in page.
2. Enter your credentials to log in.
3. Once logged in, you will be directed to the main page.

## Future Improvements

This project serves as a starter template. Future features could include:

- The ability to register new accounts.
- A more extensive main page layout with content cards.
- User profiles, including watch history.
- Integration of a payment system for subscriptions.
- Enhanced content management admin panel.

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request.



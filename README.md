# Personal Expense Tracker

## Overview

The Personal Expense Tracker is a web application built with Django that helps users manage their daily expenses, monitor spending habits, and plan their budgets more effectively. It combines expense tracking with machine learning to automatically categorize transactions and predict future expenses based on historical spending data.

The application provides a convenient way to organize financial records, understand spending patterns, and make informed budgeting decisions.

## Features

- **Expense Logging:** Record daily expenses with dates, descriptions, amounts, and categories.
- **Automated Expense Categorization:** Uses machine learning to suggest categories based on expense descriptions.
- **Future Expense Prediction:** Estimates future expenses based on historical spending patterns.
- **User Authentication:** Allows users to register and log in to manage their expenses.
- **Expense History:** View and organize previously recorded transactions.
- **Spending Overview:** Review categorized expenses and spending trends through the dashboard.
- **Admin Panel:** Manage users, categories, and application data through Django's administration interface.
- **Budget Planning Support:** Use spending history and expense predictions to support better financial planning.

## Technologies Used

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, JavaScript
- **Database:** Django-supported database configured for the project
- **Machine Learning:** Python-based machine learning libraries
- **Dependency Management:** pip
- **Version Control:** Git & GitHub

## System Requirements

- Python 3.x
- pip (Python package manager)
- A modern web browser
- A code editor, such as Visual Studio Code
- Internet connection for downloading dependencies

## Installation & Setup

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply Database Migrations

```bash
python manage.py migrate
```

### 6. Create an Administrator Account

```bash
python manage.py createsuperuser
```

Follow the prompts to configure your administrator username and password.

### 7. Start the Development Server

```bash
python manage.py runserver
```

### 8. Open the Application

Open your browser and visit:

```text
http://127.0.0.1:8000/
```

**Note:** These instructions assume the repository contains `manage.py` and `requirements.txt` in the project root. Follow the project's actual configuration if any setup steps differ.

## Usage

1. Register a new account or log in using your existing credentials.
2. Open the expense tracking dashboard.
3. Select **Add Expense** to record a transaction.
4. Enter the expense date, description, amount, and category.
5. Leave the category empty if you want the application's automatic categorization feature to attempt to assign one.
6. Review your expense history and categorized spending.
7. Explore the future expense predictions to help plan your budget.
8. To access the Django administration panel, visit:

   `http://127.0.0.1:8000/admin/`

   Log in using your superuser credentials.

## Contributing

Contributions and suggestions are welcome.

1. Fork the repository.
2. Create a branch for your changes:

   ```bash
   git checkout -b feature-name
   ```

3. Make your changes and commit them:

   ```bash
   git add .
   git commit -m "Add new feature"
   ```

4. Push your branch:

   ```bash
   git push origin feature-name
   ```

5. Submit a Pull Request with a description of your changes.

## License

Check the original repository for its license and retain the required license notice and attribution when redistributing or adapting the project.

## Contact

For any inquiries or feedback, please contact us at:

- **Email:** malithhanchapola1@gmail.com
- **Phone:** +94704894569
- **GitHub:** https://github.com/Malithhanchapola

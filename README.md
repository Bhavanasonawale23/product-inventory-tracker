# Product Inventory Tracker

A Django-based web application for managing product inventory. The application allows users to add, view, update, and delete product records through a simple web interface.

## Features

- Add new products
- View all products
- Update existing product details
- Delete products
- Validate product price and quantity
- Store product information using Django ORM
- Django Admin interface

## Product Information

Each product contains:

- Product ID
- Product Name
- Category
- Price
- Quantity

## Technologies Used

- Python
- Django
- HTML
- CSS
- SQLite
- Django ORM

## Project Structure

PMS_Project/
├── productapp/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── PMS_Project/
│   ├── settings.py
│   └── urls.py
├── manage.py
├── requirements.txt
└── .gitignore

## How to Run the Project

1. Clone the repository:
    git clone https://github.com/Bhavanasonawale23/product-inventory-tracker.git

2. Navigate to the project folder:
    cd product-inventory-tracker

3. Create a virtual environment:
    python -m venv my_venv

4. Activate the virtual environment:
    my_venv\Scripts\activate

5. Install dependencies:
    pip install -r requirements.txt

6. Apply database migrations:
    python manage.py migrate

7. Start the development server:
    python manage.py runserver

8. Open the application in your browser:
    http://127.0.0.1:8000/
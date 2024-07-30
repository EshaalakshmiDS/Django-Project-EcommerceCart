# Shopping Cart Django Project

## Introduction

This project demonstrates how to implement a shopping cart functionality using Django, a powerful Python web framework. A shopping cart is essential for e-commerce websites and applications that involve online transactions, allowing users to select, manage, and purchase items seamlessly.

## Features

- **Product Listing**: Display a list of products available for purchase.
- **Product Detail**: View detailed information about a product.
- **Add to Cart**: Add products to the shopping cart.
- **Update Cart**: Modify the quantity of items in the cart.
- **Remove from Cart**: Remove items from the cart.
- **Cart Overview**: View the contents of the cart, including total cost.
- **Checkout Process**: Proceed to checkout and place an order.

## Requirements

- Python 3.x
- Django 3.x or higher
- Other dependencies listed in `requirements.txt`

   ### Setup

1. **Clone the repository**:

    ```bash
    git clone clone https://github.com/EshaalakshmiDS/Django-Project-EcommerceCart.git
    cd cd shopping-cart-django
    ```

2. **Create a virtual environment and activate it**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up the environment variables:**

    ```bash
    WEATHER_API_KEY=your_api_key
    ```

5. **Run migrations and start the development server:**

    ```bash
    python manage.py migrate
    python manage.py runserver
    ```

The app will be accessible at http://127.0.0.1:8000/.


# Django Coinbase Tutorial

## Want to learn how to build this?

Check out the [post](#).

## Want to use this project?

1. Fork/Clone

1. Create and activate a virtual environment:

    ```sh
    $ python3 -m venv venv && source venv/bin/activate
    ```

1. Install the requirements:

    ```sh
    (venv)$ pip install -r requirements.txt
    ```

1. Apply the migrations:

    ```sh
    (venv)$ python manage.py migrate
    ```

1. Add your Stripe test secret and test publishable keys to the *settings.py* file:

    ```python
    COINBASE_COMMERCE_API_KEY = '<your coinbase api key here>'
    COINBASE_COMMERCE_WEBHOOK_SHARED_SECRET = '<your coinbase webhook secret here>'
    ```

1. Run the server:

    ```sh
    (venv)$ python manage.py runserver
    ```

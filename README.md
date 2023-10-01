These instructions will help you set up and run the project locally on your machine for development and testing purposes.

### Prerequisites

Before you begin, make sure you have the following installed:

- Python (3.6 or higher)
- Django (you can install it using `pip install Django`)

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/hello-world-django.git


Change into the project directory:
cd demo

Create a virtual environment
python -m venv venv

**Activate the virtual environment**
On Windows:
venv\Scripts\activate

On macOS and Linux:
source venv/bin/activate

Run the development server:
python manage.py runserver

The app should now be running at http://localhost:8000/

You will receive a JSON response in localhost:
{"Message": "Hello World!"}

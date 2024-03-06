**Hello World Django App**
This repository contains a simple Django web application that returns a "Hello World!" message in JSON format. This application is designed as part of a software testing and quality assurance assignment.

Prerequisites
Before you begin, ensure you have met the following requirements:

You have installed Python 3.x.
You have installed Django. If not, you can install it using pip:
pip install django

**Running the Web App**
To run the Hello World Django app, follow these steps:

1) Clone the repository to your local machine (or download and extract the ZIP file):
git clone <repository-URL>

2) Navigate to the project directory:
cd helloworld

3) Run the Django development server:
python3 manage.py runserver

4) The server will start on http://127.0.0.1:8000/. To access the Hello World JSON response, open your web browser and navigate to http://127.0.0.1:8000/api/hello/.

**Accessing the Hello World JSON Response**
After the server has started, you can access the Hello World JSON response by opening a web browser and navigating to the following URL:

http://127.0.0.1:8000/api/hello/

You should see a JSON response that looks like this:
{"Message": "Hello World!"}

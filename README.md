# Imageuploader

![image](https://github.com/user-attachments/assets/80b48871-1f7f-4ff0-a9ee-b287d91d394d)

#Django Image Uploader
A simple image uploading web application built using Django. This app allows users to upload images, which are then saved to a specified folder on the server.

#Features
Users can upload images.
Uploaded images are saved in the media/images/ directory.
Simple model to handle image uploads.
Prerequisites
Before you begin, ensure you have met the following requirements:

Python 3.x installed
Django framework installed
Pillow installed for handling images

Installation
Clone the repository
git clone https://github.com/yourusername/django-image-uploader.git

cd django-image-uploader

Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install dependencies
pip install -r requirements.txt

Migrate the database
python manage.py migrate

Run the development server
python manage.py runserver

Access the application
Go to http://127.0.0.1:8000 in your web browser to start uploading images.

#Project Structure

myproject/
│
├── myproject/
│   ├── settings.py
│   ├── urls.py
│   └── ...
├── myapp/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   └── ...
├── media/
│   └── images/  # Directory where uploaded images are stored
├── templates/
│   └── upload.html
├── manage.py
└── README.md





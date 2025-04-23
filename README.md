# 🛒 E-commerce Product Uploader

This is a Django-based web application that allows users/admins to upload and manage products for an e-commerce platform. It includes features such as product name, price, image upload, category, and description.

## 📌 Overview

This project is developed using the Django framework. It helps in uploading product data through a web interface and storing it in a database. It’s useful for building the backend of an online shopping site.

## 🚀 Features

- Add new products with images and descriptions  
- Organize products into categories  
- View uploaded products in the admin panel  
- Secure and easy-to-use interface  

## 🛠️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ecommerce-product-uploader.git
   cd ecommerce-product-uploader
2.Create and activate virtual environment

python -m venv env
source env/bin/activate   # On Windows use `env\Scripts\activate`

3.Install dependencies

pip install -r requirements.txt


4.Run migrations

python manage.py migrate

5.Create superuser (for admin login)

python manage.py createsuperuser

6.Start the development server

python manage.py runserver


7.Open your browser and go to http://127.0.0.1:8000/admin to upload products.

📁Folder Structure

ecommerce-product-uploader/
├── manage.py
├── products/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
├── media/
├── static/
└── templates/





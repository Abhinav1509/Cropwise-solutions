Cropwise Solutions - A Recommendation, Prediction, And E-Commerce System For Agricultural Products

Project Overview Cropwise Solutions is an integrated system designed to support farmers, agronomists, and agricultural researchers in making informed decisions about crop selection and fertilizer application. This platform combines advanced recommendation and prediction models with an e-commerce website for easy access to essential agricultural products. The system also serves as a research tool, with data-driven insights to enhance agricultural practices.

Key Features Crop Recommendation: Predicts and recommends suitable crops based on soil properties, climatic conditions, and location-specific data. Fertilizer Recommendation: Provides fertilizer suggestions based on crop needs and soil nutrient profiles, promoting effective and balanced crop nutrition. E-Commerce Platform: Offers a marketplace where users can purchase seeds, fertilizers, and other agricultural products, all in one place.


How to Access the Project
For Local Access
To set up and run Cropwise Solutions on your local machine, follow these steps:

Clone the Repository: Clone this project to your local machine by running:
git clone https://github.com/Abhinav1509/cropwise-solutions.git
Install Dependencies: Navigate to the project directory and install the required dependencies using:

pip install -r requirements.txt


Database Setup:
Ensure you have a compatible database (e.g., MySQL or PostgreSQL) installed.
Update the database configuration in the config.py file with your local database credentials.
Run migrations to set up the database structure:
python manage.py migrate

Run the Application: Start the server by running:
python manage.py runserver
The project should be accessible at http://127.0.0.1:8000/ in your web browser.

Access the System:
User Account: Register a new user account to start accessing the crop recommendation and e-commerce features.
Admin Account: To access the admin panel, create an admin account by running:
python manage.py createsuperuser
Then, log in at http://127.0.0.1:8000/admin.

Setting Up and Running a Django Project

Clone the Repository:

bash
Copy
Edit
git clone https://github.com/gautamk1512/Views-Routing-Urls-In-Django-Python-Django.git
Navigate to the Project Directory:

bash
Copy
Edit
cd Views-Routing-Urls-In-Django-Python-Django/webapp
Create and Activate a Virtual Environment:

On macOS/Linux:
bash
Copy
Edit
python3 -m venv env
source env/bin/activate
On Windows:
bash
Copy
Edit
python -m venv env
.\env\Scripts\activate
Install Dependencies: Ensure you have a requirements.txt file listing all necessary packages. Then run:

bash
Copy
Edit
pip install -r requirements.txt
Apply Migrations:

bash
Copy
Edit
python manage.py migrate
Create a Superuser (Optional):

bash
Copy
Edit
python manage.py createsuperuser
Run the Development Server:

bash
Copy
Edit
python manage.py runserver

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Setting Up and Running a Django Project</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; padding: 20px; background-color: #f9f9f9; }
        h1, h2 { color: #333; }
        code { background: #eee; padding: 2px 5px; border-radius: 5px; }
        pre { background: #333; color: #fff; padding: 10px; border-radius: 5px; overflow-x: auto; }
    </style>
</head>
<body>
    <h1>Setting Up and Running a Django Project</h1>
    
    <h2>Clone the Repository:</h2>
    <pre><code>git clone https://github.com/gautamk1512/Views-Routing-Urls-In-Django-Python-Django.git</code></pre>

    <h2>Navigate to the Project Directory:</h2>
    <pre><code>cd Views-Routing-Urls-In-Django-Python-Django/webapp</code></pre>

    <h2>Create and Activate a Virtual Environment:</h2>
    <h3>On macOS/Linux:</h3>
    <pre><code>python3 -m venv env
source env/bin/activate</code></pre>

    <h3>On Windows:</h3>
    <pre><code>python -m venv env
.\env\Scripts\activate</code></pre>

    <h2>Install Dependencies:</h2>
    <p>Ensure you have a <code>requirements.txt</code> file listing all necessary packages. Then run:</p>
    <pre><code>pip install -r requirements.txt</code></pre>

    <h2>Apply Migrations:</h2>
    <pre><code>python manage.py migrate</code></pre>

    <h2>Create a Superuser (Optional):</h2>
    <pre><code>python manage.py createsuperuser</code></pre>

    <h2>Run the Development Server:</h2>
    <pre><code>python manage.py runserver</code></pre>

</body>
</html>

# URL-Shortener

This is a basic URL Shortener App: 
Made using Flask in Backend and Bulma Framework.

In order to run this locally on your system , Steps to follow :

1. Python required

2. To make the virtual environment : Run this on cmd
**python -m venv env 
To activate Scripts:
**env\Scripts\activate

3. Install packages
**pip install flask
**pip install flask-sqlalchemy
**pip install python-dotenv

4. Setup the sqlite3 database:
** python
** from url_shortener import create_app
** from url_shortener.extensions import db
** from url_shortener.models import Link
** db.create_all(app=create_app())
** exit()

5. Set the sqlite3.exe file in your local disk C:sqlite folder
Follow this link for  more details:
https://www.tutorialspoint.com/sqlite/sqlite_installation.htm

6. Run the App :
** flask run
This will provide you with a URL to run the app locally on your system.

....

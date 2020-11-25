# instagram
This is a clone of Instagram where people share their images and videos for other users to view. Users can sign up, login, view and post photos, search and follow other users.
# User Story
Sign in to the application to start using.
Upload a pictures to the application.
Search for different users using their usernames.
See your profile with all your pictures.
Follow other users and see their pictures on my timeline.
# Setup and Installation
To get the project .......

Cloning the repository:
https://github.com/SILVIAKAGO/instagram.git 
Navigate into the folder and install requirements
cd insta-lite pip install -r requirements.txt 
Install and activate Virtual
- python3 -m venv virtual - source virtual/bin/activate  
Install Dependencies
pip install -r requirements.txt 
Setup Database
SetUp your database User,Password, Host then make migrate

python manage.py makemigrations instagram
Now Migrate

python manage.py migrate 
Run the application
python manage.py runserver 
Running the application
python manage.py server 
Testing the application
python manage.py test 
Open the application on your browser 127.0.0.1:8000.

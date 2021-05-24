# instaclone

>[Dunstan Mmbehero(https://github.com/ubuntustan)  
  
# Description  
This is a clone of  Instagram where people share their  images and videos for other users to view. 
Users can sign up, login, view and post photos, search and follow other users.
##  Live Link  
 Click [View SIte](https://stan-instaclone.herokuapp.com/)  to visit the site
  
## Screenshots 
###### ERD DIAGRAM
<img src="https://raw.githubusercontent.com/ubuntustan/instaclone/master/static/images/erd2.png">

###### Home page
<img src="https://raw.githubusercontent.com/ubuntustan/instaclone/master/static/images/readme3.png">

###### user profile

 <img src="https://raw.githubusercontent.com/ubuntustan/instaclone/master/static/images/readme5.png">

###### admin
 <img src="https://raw.githubusercontent.com/ubuntustan/instaclone/master/static/images/admin.png">

## User Story  
  
* Sign in to the application to start using.  
* Upload a pictures to the application. 
* Search for different users using their usernames.  
* See your profile with all your pictures.  
* Follow other users and see their pictures on my timeline.  
  

  
## Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  
 ```bash 
 https://github.com/ubuntustan/instaclone.git
```
##### Navigate into the folder and install requirements  
 ```bash 
cd instaclone pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual 
- source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations 
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 

Open the application on your browser `127.0.0.1:8000`  or  `localhost:8000`
  
  
## Technology used  
  
* [Python3.6](https://www.python.org/)  
* [Django 3.2.2](https://docs.djangoproject.com/en/3.2/)  
* [Heroku](https://heroku.com)  
  
  
## Known Bugs  
* There are no known bugs currently but pull requests are allowed incase you spot a bug  
  
## Contact Information   
If you have any question or contributions, please email me at [dunmmbehero@gmail.com]  
  
## License 

* [![License](https://img.shields.io/packagist/l/loopline-systems/closeio-api-wrapper.svg)](https://github.com/ubuntustan/instaclone/blob/master/LICENSE)  
* Copyright (c) 2021 **Dunstan Mmbehero**
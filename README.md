# HomeWatch
A python application based on Django framework
#### 17/1/2020
#### [Daniel Njuguna](https://github.com/dan-jugz)  
  
# Description    
This is an application that enables a authenticated user to post events for other neighbours to see. A user can click on an a user to view their pages and can also view a list of businesses in the area also can also have access to emergency contacts.

 
## User Stories
As a user, i would like to;
  
* Sign in with the application to start using.
* Set up a profile about me and a general location and my neighborhood name.
* Find a list of different businesses in my neighborhood.
* Find Contact Information for the health department and Police authorities near my neighborhood.
* Create Posts that will be visible to everyone in my neighborhood.
* Change My neighborhood when I decide to move out.
* Only view details of a single neighborhood.
  
## Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  
 ```bash 
https://github.com/dan-jugz/Manz-hood.git
```
##### Navigate into the folder and install requirements  
 ```bash 
cd Manz-hood 
```
### create a .env file and put the following variables init
```python
SECRET_KEY = '<Secret_key>'
DBNAME = 'hood'
USER = '<username>'
PASSWORD = '<password>'
DEBUG = True

```  
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual - source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations hood
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  
 
## Technology used  
  
* [Python3.6](https://www.python.org/)  
* [Django 2.2.6](https://docs.djangoproject.com/en/2.2/)  
* [Heroku](https://heroku.com)  
  
  
## Known Bugs  
* There are no known bugs currently but pull requests are allowed incase you spot a bug  
  
## Contact Information   
If you have any question or contributions, please email me at [njugunadaniel364@gmail.com]  
  
## License 

* Copyright (c) 2019 **Daniel Njuguna**
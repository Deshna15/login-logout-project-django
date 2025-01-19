# django-login-logout
In this project, we implement a simple user authentication system by using the Django ```auth``` module. This system can handle the below mentioned functionalities. 
1. New user registration
2. User login
3. Logout
4. Dynamic home page 
5. Change password for existing user
6. Recommend secure password to user while signing up
7. Dynamic profile page for each user - profile includes username, details, display picture and bio 
8. Edit/Update profile (display picture, bio) for logged-in user


## Instructions to use

```
1. Create a virtual environment and activate it. Not required but highly recommended. 
```bash
python -m venv env
Set-ExecutionPolicy Unrestricted -Scope Process
.\env\Scripts\activate

```
The above command is for Windows only. For Linux based operating systems, use the below mentioned command. 
```bash
python3 -m venv env
source env/bin/activate
```
2. Now, install the requirements. 
```bash
pip3 install -r requirements.txt
```
3. Now, migrate changes to the database and start the server. 
```
python manage.py migrate 
python manage.py runserver 
```
4. Head to [127.0.0.1:8000](http://127.0.0.1:8000/) and you should be able to see the development version of our app live. 

**TASK**

Create REST APIs based on Django with PostgreSQL database. It
should contain:

1. User Sign Up (http://127.0.0.1:8000/api/profile/)
Put all the details in email,name,password and our profile gets created. We can check by reloading
(http://127.0.0.1:8000/api/profile/)

2. Uses JWT authentication
JWT authentication is used , here modheader is used while authorization
For log in (http://127.0.0.1:8000/api/login/)
Put email and password and we recive the token just paste the token in modheader and request header authorization and
(http://127.0.0.1:8000/api/login/) + user id that is created while making new user we can also check by  (http://127.0.0.1:8000/api/profile/) and simply using the filter
Now we are inside your profile and we can delete your profile if you want

3. Must define 3 user levels : 1. Super-admin, 2. Teacher, 3. Student (Use internal Django Groups to achieve the same)
User levels can be achived by 1// Django admin 2// or 3// by using filter in (http://127.0.0.1:8000/api/profile/)

4. Teacher must be able to list all the students.
Using Filter

5. Admin must be able to list every user in the database.
By using django admin

6. Code should be commented for clarity.

We can use already built packages like https://github.com/celiao/django-rest-authemail for much more scalability and flexibility. (I have not used here but presenting as better option)

Accessible at https://pypi.python.org/pypi/django-rest-authemail 

[pip install django-rest-authemail]
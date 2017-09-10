# crispy-carnival
Code submission platform


# Setup
We are using Python `3.x` for this. Kindly install the same, I suggest using  `virtualenv` to install a separate version exclusive to run this webapp, so as not to mess system dependencies

`pip install virtualenv`

## Create a new virtualenv named `django-dev`

`virtualenv -p python3 django-dev`


## Define ENV Variables
 Define ENV variables in a file named `.env` to set common tokens (required for Github Login)

 ```bash
SOCIAL_AUTH_GITHUB_KEY = 'XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX'
SOCIAL_AUTH_GITHUB_SECRET = 'XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX'

SECRET_KEY = 'XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX'

DB_NAME = 'crispy_carnival'
DB_USER = 'crispy_carnival_user'
DB_USER_PASSWORD = 'XXXXXXXXXXXXXXXXXXXXXXX'
 ```

 Replace `XXXX` with appropriate values
 
## Activate virtualenv 

`source ~/django-dev/bin/activate`

## Install Dependencies

`pip install -r requirements.txt`

`requirements.txt` contains all the dependencies


# References

* (Social Login)[https://simpleisbetterthancomplex.com/tutorial/2016/10/24/how-to-add-social-login-to-django.html]
1.Create new folder and paste the codes.

2.Create new virtual environment in cmd prompt - 'virtualenv venv'
  (venv- virtual environment name)

3.Activate the virtual environment (for windows)-'venv\Scripts\activate'

4.Install latest versions -Python, pip, django and six

5.Make sure add python path to environment.

6.In cmd run - 	python manage.py makemigrations
		python manage.py migrate
		python manage.py runserver


7.In spritle- info.py - (make these changes for your system)
	EMAIL_HOST_USER = 'create_your_mail_id@gmail.com'
	EMAIL_HOST_PASSWORD = 'email_password'
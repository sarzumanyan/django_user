# User_Authentication application using django framework
University project for the subject Software system protection
1. Clone the repository
2. Go to `django_user/core`
3. Create venv running the command
```bash
python3 -m venv venv
```
4. Activate venv
```bash
source venv/bin/activate
```
5. Install the required libraries running the command
```bash
pip install -r requirements.txt
```
6. Create .env file
   Add SECRET_KEY with its value
   example `SECRET_KEY=value_of_secret_key`
7. Make migrations
 ```bash
   python manage.py makemigrations
   python manage.py migrate
 ```
8. Create superuser
   ```bash
   python manage.py createsuperuser
   ```
9. Run the application
   ```bash
   python manage.py runserver
   ```

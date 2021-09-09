# DJANGO_GOOGLE_API_PROJECT

Django project that makes use of following Google APIs:
reCAPTURE, Places API, Maps Javascript API, Directions API, Distance Matrix API, Geocoding API
This project is used for User to create profile and use Google APIs to fill in start and end destination and waypoints address and find routes along with the waypoints. Address fields and sign in/ sign up process is autocompleted and maps route is displayed for entries submitted via forms.

### Steps:

1. cd to project directory
2. clone repo to new directory
3. pip install -r requirements.txt
4. Create and update settings.py with your email API information
    GOOGLE_API_KEY = ""
    RECAPTCHA_PUBLIC_KEY = ""
    RECAPTCHA_PRIVATE_KEY = ""

5. python manage.py makemigrations
6. ython manage.py migrate
7. python manage.py runserver
8. https://localhost:8000
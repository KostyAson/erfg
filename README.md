в папке проекта создайте файл .env, туда поместите значения:  
    SECRET_KEY  
    DEBUG  
    LANGUAGE_CODE  
    STATIC_URL  
python3 -m venv venv  
source venv/bin/activate  
pip3 install -r requirements/prod.txt  
python3 manage.py runserver  
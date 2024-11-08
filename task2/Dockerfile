FROM python:3.9-alpine
COPY ./python_django_testing_5_drf_crud/ /app
WORKDIR /app
RUN pip install -r requirements.txt
RUN python manage.py migrate
CMD ["python", "manage.py", "runserver", "0.0.0.0:80"]

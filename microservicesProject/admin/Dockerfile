FROM python:3.9 
ENV PYTHONUNBUFFERED 1
WORKDIR /app
COPY requirments.txt /app/requirments.txt
RUN pip install -r requirments.txt
COPY . /app


CMD python manage.py runserver 0.0.0.0:8000

FROM python:3.14.2

WORKDIR /app

COPY ./requirements.txt .

RUN pip install -r ./requirements.txt

COPY . .

EXPOSE 8000

ENTRYPOINT ["python", "manage.py", "runserver"]
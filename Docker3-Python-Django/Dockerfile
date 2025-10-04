FROM python:3.12-alpine

WORKDIR /app
EXPOSE 8000

RUN apk update && apk add --no-cache build-base gcc

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

CMD [ "python", "manage.py", "runserver", "0.0.0.0:8000"]


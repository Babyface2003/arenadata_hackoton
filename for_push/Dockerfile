FROM python:3.13.2-alpine

WORKDIR /app

COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

COPY ../../arenadata .

EXPOSE 5000

CMD ["python", "main.py"]


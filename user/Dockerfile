FROM python:latest
WORKDIR /code
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY . .
CMD ["opentelemetry-instrument", "python", "app.py"]
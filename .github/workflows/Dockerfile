FROM python:3.9-slim

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY ml_pipeline.py .

CMD ["python", "ml_pipeline.py"]

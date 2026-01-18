FROM python:latest

WORKDIR /app

COPY req.txt .
RUN pip install --no-cache-dir -r req.txt

COPY . .

EXPOSE 5000

CMD ["python","app.py"]
ENV FLASK_RUN_HOST=0.0.0.0

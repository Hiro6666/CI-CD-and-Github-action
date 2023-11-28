FROM python:3.10
WORKDIR /app
COPY app.py .
RUN pip install Flask gunicorn

CMD ["python", "app.py", "&", ">>", "app.log"]


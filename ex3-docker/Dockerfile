FROM python:3.10
WORKDIR /app
COPY app.py .
RUN pip install Flask
EXPOSE 5000

CMD ["python", "app.py", "&", ">>", "app.log"]

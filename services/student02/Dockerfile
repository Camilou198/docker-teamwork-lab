FROM python:3.11-slim
WORKDIR /app
RUN pip install flask
COPY app/ /app/
EXPOSE 8082
CMD ["python", "-m", "flask", "--app", "app:app", "run", "--host=0.0.0.0", "--port=8082"]
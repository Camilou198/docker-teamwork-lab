FROM busybox:stable
WORKDIR /srv
RUN printf "Hello, I am Diana Marcela Sarmiento\n" > index.html \
    && printf "ok\n" > health

EXPOSE 8080
CMD ["python", "-m", "flask", "--app", "app:app", "run", "--host=0.0.0.0", "--port=8080"]

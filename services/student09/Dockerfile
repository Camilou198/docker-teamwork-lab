FROM busybox:stable
WORKDIR /srv
COPY index.html /srv/index.html
COPY style.css /srv/style.css
RUN printf "ok\n" > health
EXPOSE 8080
CMD ["sh", "-c", "httpd -f -p 8080 -h /srv"]

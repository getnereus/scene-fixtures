FROM busybox:1.37
COPY index.html /www/index.html
EXPOSE 8080
USER 65534
CMD ["httpd", "-f", "-p", "8080", "-h", "/www"]

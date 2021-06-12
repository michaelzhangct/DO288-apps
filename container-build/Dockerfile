# Use the httpd-parent image as base
FROM quay.io/redhattraining/httpd-parent
EXPOSE 8080

RUN chgrp -R 0 /var/run/httpd /var/log/httpd && \
    chmode -R g=u /var/run/httpd /var/log/httpd

USER 1001

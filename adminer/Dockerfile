FROM adminer:latest

ARG ADMINER_DEFAULT_DATABASE_DRIVER
ARG ADMINER_DEFAULT_SERVER
ARG ADMINER_DEFAULT_USER
ARG ADMINER_DEFAULT_DATABASE_NAME
ARG ADMINER_DESIGN

ENV ADMINER_DEFAULT_DATABASE_DRIVER $ADMINER_DEFAULT_DATABASE_DRIVER
ENV ADMINER_DEFAULT_SERVER          $ADMINER_DEFAULT_SERVER
ENV ADMINER_DEFAULT_USER            $ADMINER_DEFAULT_USER
ENV ADMINER_DEFAULT_DATABASE_NAME   $ADMINER_DEFAULT_DATABASE_NAME
ENV ADMINER_DESIGN                  $ADMINER_DESIGN

COPY ./login-servers.php /var/www/html/plugins-enabled/login-servers.php
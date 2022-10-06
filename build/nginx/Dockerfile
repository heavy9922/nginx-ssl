FROM nginx:alpine

LABEL maintainer="heavy9922 <yefersoncasti@gmail.com>"

# ------------------------------------------
# Update and add pakacge from alpine
# ------------------------------------------
RUN apk update && apk upgrade && \
    apk add --no-cache bash git openssh vim apache2-utils

# ------------------------------------------
# Define Workdir
# ------------------------------------------

WORKDIR /var/www/

# # ------------------------------------------
# # GIT config
# # ------------------------------------------
RUN git config --global user.name "heavy9922" && git config --global user.email "yefersoncasti@gmail.com"
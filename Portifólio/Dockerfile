FROM nginx:alpine

ARG BUILD_NOTE
ARG BUILD_NUMBER

LABEL build.note="$BUILD_NOTE"
LABEL build.number="$BUILD_NUMBER"
LABEL maintainer="Luiz Inhesta"

COPY . /usr/share/nginx/html

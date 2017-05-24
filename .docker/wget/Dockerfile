FROM alpine:3.5
ENV LANG C.UTF-8

RUN apk update && \
    apk upgrade && \
    apk add wget

RUN echo 'http_proxy=http://nginx:8080/' >> /etc/wgetrc && \
		echo 'https_proxy=http://nginx:8080/' >> /etc/wgetrc

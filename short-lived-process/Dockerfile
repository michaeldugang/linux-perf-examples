FROM ubuntu

LABEL maintainer="feiskyer@gmail.com"

RUN apt-get update && apt-get install -y stress && apt-get clean

ADD app /app
ADD app.c /app.c

CMD ["/app"]

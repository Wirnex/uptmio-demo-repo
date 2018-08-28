FROM alpine

RUN apk add --no-cache bash

COPY test.sh /opt/app/test
COPY tail-f.me /opt/app/test

RUN chmod +x /opt/app/test

CMD ["tail", "-f", "/opt/app/tail-f.me"]

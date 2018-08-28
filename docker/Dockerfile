FROM alpine

RUN apk add --no-cache bash

COPY test.sh /opt/app/test
COPY tail-f.me /opt/app/

RUN chmod +x /opt/app/test

CMD ["sleep", "3600"]

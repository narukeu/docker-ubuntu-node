FROM ubuntu:noble

RUN apt-get update && apt-get install -y curl build-essential

RUN curl -fsSL https://deb.nodesource.com/setup_22.x | bash

RUN apt-get install -y nodejs

COPY docker-entrypoint.sh /usr/local/bin/

RUN chmod +x /usr/local/bin/docker-entrypoint.sh

RUN node -v
RUN npm -v

ENTRYPOINT ["docker-entrypoint.sh"]

CMD [ "node" ]
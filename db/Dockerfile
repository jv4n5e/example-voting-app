FROM postgres:9.4

LABEL version="latest"
LABEL maintainer="juanse18_7@hotmail.com"

RUN sed -e 's/^host all all all md5/host all all all trust/g' /var/lib/postgresql/data/pg_hba.conf > fix

CMD [ "mv", "fix /var/lib/postgresql/data/pg_hba.conf" ]
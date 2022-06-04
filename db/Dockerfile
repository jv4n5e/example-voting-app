FROM postgres:9.4

CMD [ "sed", "'s/^host all all all md5/host all all all trust/g' /var/lib/postgresql/data/pg_hba.conf > fix && mv fix /var/lib/postgresql/data/pg_hba.conf" ]
FROM postgres:10.3

#this below comes from the postgres image documentation
ADD /tables/ /docker-entrypoint-initdb.d/tables/
ADD /seed/ /docker-entrypoint-initdb.d/seed/

ADD deploy_schemas.sql /docker-entrypoint-initdb.d/
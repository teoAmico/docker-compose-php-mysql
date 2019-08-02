FROM mysql

RUN pwd \
&& ls -la \
&& ls -la /docker-entrypoint-initdb.d


EXPOSE 3306

RUN mysql -u root -proot -P 6604 -e 'CREATE DATABASE IF NOT EXISTS dynamo;'

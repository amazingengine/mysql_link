ARG mysql_version
FROM mysql:${mysql_version}
RUN echo "!includedir /etc/mysql/mysql.conf.d/" >> /etc/mysql/my.cnf
COPY mysql.conf.d/mysqld.cnf /etc/mysql/mysql.conf.d/mysqld.cnf

FROM mysql:5.7

ENV MYSQL_ROOT_PASSWORD 123456

EXPOSE 3306

RUN echo "server-id=1" >> /etc/mysql/mysql.conf.d/mysqld.cnf & echo "log-bin=mysql-bin" >> /etc/mysql/mysql.conf.d/mysqld.cnf && echo "binlog_format=ROW" >> /etc/mysql/mysql.conf.d/mysqld.cnf

CMD ["mysqld"]

FROM mysql:5.7.22

VOLUME /var/lib/mysql
COPY ./conf/mysqld.cnf /etc/mysql/mysql.conf.d/mysqld.cnf
EXPOSE 80
CMD ["mysqld"]
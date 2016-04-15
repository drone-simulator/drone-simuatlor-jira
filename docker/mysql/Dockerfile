# MySQL container for the database
FROM mysql:5.7
MAINTAINER Colin Campbell <colin@colincampbell.me>

# Change port to 3311
RUN sed -i 's|^port\s*=\s*3306|port = 3311|' /etc/mysql/my.cnf

EXPOSE 3311

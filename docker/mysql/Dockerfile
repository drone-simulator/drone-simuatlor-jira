# MySQL container for the database
FROM mysql:5.7
MAINTAINER Colin Campbell <colin@colincampbell.me>

# Change port to 3311
RUN sed -i 's|^port\s*=\s*3306|port = 3311|' /etc/mysql/my.cnf

# ADD dronesimjira.sql /tmp/dronesimjira.sql
# RUN /bin/bash -c "/usr/bin/mysqld_safe &" && \
#   sleep 6 && \
#   mysql -u dronesimjira -p dronesimjira -e "CREATE DATABASE dronesimjira" && \
#   mysql -u dronesimjira -p dronesimjira dronesimjira < /tmp/dronesimjira.sql

EXPOSE 3311

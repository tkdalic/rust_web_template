FROM mysql/mysql-server:8.0

ENV MYSQL_DATABASE=rust_web_template \
  MYSQL_USER=rust_web_template \
  MYSQL_PASSWORD=secret \
  MYSQL_ROOT_PASSWORD=secret \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/mysql/conf.d/my.cnf
RUN chmod 644 /etc/mysql/conf.d/my.cnf